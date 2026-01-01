<template>
  <div>
    <transition name="fade">
      <LoadingComponent v-if="isLoading" :is-loading="isLoading" />
    </transition>
    <div 
      v-show="!isLoading" 
      class="bg-white"
      :class="{ 'content-loaded': !isLoading }"
    >
      <HomeComponent />
      <AboutComponent />
      <TechComponent />
      <ProjectsComponent />
      <OtherProjectsComponent />
      <ExperienceComponent />
      <ContentComponent />
      <FooterComponent />
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import LoadingComponent from './components/LoadingComponent.vue'
import HomeComponent from './components/HomeComponent.vue'
import AboutComponent from './components/AboutComponent.vue'
import TechComponent from './components/TechComponent.vue'
import ExperienceComponent from './components/ExperienceComponent.vue'
import ProjectsComponent from './components/ProjectsComponent.vue'
import OtherProjectsComponent from './components/OtherProjectsComponent.vue'
import ContentComponent from './components/ContentComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

const isLoading = ref(true)

// Function to preload key images
const preloadImages = () => {
  // List of key images to preload
  const imagesToPreload = [
    '/3D_Medical_Reconstruction_project.png',
    '/bg_image_artorias961.png',
    '/bg_image_chris.png',
    '/bg_image_christopher.png',
    '/chris-image-2.jpg',
    '/chris-image-3.jpg',
    '/chris-image.jpg',
    '/dqn_snake_model.png',
    '/escalation.png',
    '/fading_bar.png',
    '/favicon.ico',
    '/heart.png',
    '/Heated_Sonicator.png',
    '/homelab.png',
    '/landing-bg.png',
    '/mechanical_keyboard.png',
    '/mips32.png',
    '/Multiserver.png',
    '/network-visualizer.png',
    '/opencv_retro_filter.png',
    '/portfolio_finale.png',
    '/portfolio_one.png',
    '/portfolio_two.png',
    '/purple-wave.png',
    '/second-wave.png',
    '/sidebg.png',
    '/small icon 2.jpg',
    '/smart_program_VR_AR_XR_tech.png',
    '/sobel_1.png',
    '/speech_to_text.png',
    '/spin.png',
    '/spinner.png',
    '/third wave.png',
    '/watch_dogs.png',
    '/Websocket-REST-API-using-Python.png',
    '/white_unified.png'
  ];
  
  let loadedCount = 0
  const totalImages = imagesToPreload.length
  
  return new Promise((resolve) => {
    // If there are no images, resolve immediately
    if (totalImages === 0) {
      resolve()
      return
    }
    
    // Load each image
    imagesToPreload.forEach(src => {
      const img = new Image()
      
      img.onload = img.onerror = () => {
        loadedCount++
        if (loadedCount === totalImages) {
          resolve()
        }
      }
      
      img.src = src
    })
  })
}

onMounted(async () => {
  // Wait for images to load
  await preloadImages()
  
  // Add a slight delay to ensure smooth transition
  setTimeout(() => {
    isLoading.value = false
  }, 800)
})
</script>

<style scoped>
/* Fade transition for loading screen */
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}

/* Content appear animation */
.content-loaded {
  animation: fadeIn 0.8s ease-in-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
