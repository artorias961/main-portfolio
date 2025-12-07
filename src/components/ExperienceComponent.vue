<template>
  <section id="experience" class="bg-[#ebebeb] relative pt-0 mt-0 pb-16" ref="experienceSection">
    <div class="relative">
      <div class="px-6 mx-auto max-w-6xl lg:px-8">
        <div class="flex flex-col md:flex-row md:items-start py-10">
          <!-- Heading on the left -->
          <div class="md:w-1/3 mb-8 md:mb-0">
            <p
              class="font-inter text-[25px] md:text-[45px] font-semibold text-[#030303] md:sticky md:top-8"
            >
              my experience
            </p>
          </div>

          <!-- Experience timeline on the right -->
          <div class="md:w-2/3 mt-16">
            <!-- Experience 1 -->
            <div class="mb-10 experience-item" ref="expItem1">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">Northrop Grumman | Electrical Engineer</h3>
                <span class="text-sm text-[#030303] font-light">Woodland Hills, CA | Aug 2025 - Present</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                    <li>
                      Designed and developed multiple connectors and adapters to ensure seamless system compatibility. 
                      Performed power output testing, noise analysis, and detailed documentation using oscilloscopes, 
                      DMMs, and technical datasheets
                    </li>

                    <li>
                      Developed and implemented a Python GUI-based executable script to convert .xls files into .csv 
                      format, enabling data integration and improving compatibility across systems
                    </li>

                    <li>
                      Reduced processing time by 30% through the development and implementation of a C++ computer vision 
                      multithreading solution, using OpenCV and Windows threading
                    </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 2 -->
            <div class="mb-10 experience-item" ref="expItem1">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  Northrop Grumman | Electronics Engineer
                </h3>
                <span class="text-sm text-[#030303] font-light">Baltimore, MD | Aug 2024 - Aug 2025 </span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Technical lead in the lab environment, coordinating test activities, delegating tasks, and ensuring 
                        engineering processes are followed across multiple high-visibility programs.
                      </li>

                      <li>
                        Executed ATP testing using oscilloscopes, DMMs, and programmable power supplies, identifying faults 
                        and validating system performance against specifications.
                      </li>

                      <li>
                        Collaborated with multidisciplinary teams to meet product schedules and deliverables.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 3 -->
            <div class="mb-10 experience-item" ref="expItem1">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">Smart Program VR Tech for Virtual Learning Space | Team Lead</h3>
                <span class="text-sm text-[#030303] font-light"> Los Angeles, CA | Jan 2024 - Aug 2024</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Led a team of 23 interns to create a cost-effective AR system integrating generative AI, Unity, and 
                        LucidVR gloves.
                      </li>

                      <li>
                        Developed hardware measurement tools and trained interns to design and validate components used 
                        within the ESP32-driven AR system.
                      </li>

                      <li>
                        Utilized Docker containers to host the Meta Llama 3 70B model, where input from an ESP32 board was 
                        used to detect user interactions, enhancing LLM assistance in an AR environment.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 4 -->
            <div class="mb-10 experience-item" ref="expItem2">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  NSF CREST Center for Advancement toward Sustainable Urban System | Fellow Research
                </h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | Oct 2023 - Aug 2024</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Developed a BLE-based system to track occupancy patterns, improving energy efficiency by 20%.
                      </li>

                      <li>
                        Taught foundational concepts of Zephyr RTOS and BLE to over 50 students using the nRF52DK.
                      </li>

                      <li>
                        Educated students on how modern IoT systems learn host behavior—using examples such as smart 
                        appliances and sensors—to design solutions tailored for elderly and accessibility-focused use cases.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 5 -->
            <div class="mb-10 experience-item" ref="expItem3">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  Dept. of Electrical and Computer Engineering, CSULA | Teacher Associate
                </h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | Aug 2022 - Aug 2024</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Introduced students to the fundamentals of embedded systems using the Nucleo F401RE development board,
                        covering microcontroller architecture, GPIO programming, and sensor interfacing through practical
                        hands-on exercises.
                      </li>

                      <li>
                        Guided students in analyzing linear and rotational systems to determine their dynamic characteristics,
                        and taught techniques for calculating and tuning proportional, integral, and derivative gains for
                        optimal system performance.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 6 -->
            <div class="mb-10 experience-item" ref="expItem4">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  Dept. of Electrical and Computer Engineering, CSULA | Makerspace Assistant
                </h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | Aug 2021 - Aug 2024</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Designed and led a workshop on computer vision, focusing on object detection and tracking techniques 
                        using OpenCV and implementing algorithms such as YOLO.
                      </li>

                      <li>
                        Created a workshop for transfer students on PCB design, guiding participants through building a circuit 
                        using a 555 timer to blink an LED and demonstrating the end-to-end PCB creation process.
                      </li>

                      <li>
                        Developed and delivered a series of foundational workshops covering Vim navigation, Miniforge installation, 
                        virtual machine setup, and Linux fundamentals, with fully documented materials published for continued 
                        student use.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 7 -->
            <div class="mb-10 experience-item" ref="expItem5">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">Office of Special Service Math Tutor | Math Tutor</h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | Sep 2020 - Aug 2022</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Developed and implemented strategies to meet student needs using appropriate instructional methods 
                        and learning delivery in the least restrictive environment.
                      </li>

                      <li>
                        Differentiated activities and goals to meet each student's individual needs and ability.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 8 -->
            <div class="mb-10 experience-item" ref="expItem6">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  NSF Southeastern Coalition for Engagement and Exchange in Nanotechnology Education | Undergraduate Fellow Research
                </h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | July 2021</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Designed a diagnostic neural electrode using AutoCAD, integrating principles from semiconductor 
                        processing, lithography, and nanomaterial applications.
                      </li>

                      <li>
                        Conducted electrochemical impedance spectroscopy (EIS) experiments to evaluate how varying pH levels 
                        influence electrode impedance characteristics.
                      </li>

                      <li>
                        Synthesized findings on neural electrode design and EIS results into a research poster, presenting 
                        outcomes grounded in vacuum technologies, nanoparticle behavior, and cleanroom methodologies.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 9 -->
            <div class="mb-10 experience-item" ref="expItem6">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                    CSU Fullerton Statistical and Data Science Research | Undergraduate Research</h3>
                <span class="text-sm text-[#030303] font-light">Fullerton, CA | Jun 2019 - Aug 2019</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Collected and validated international datasets on average puberty onset for males and females, ensuring 
                        accurate cross-country comparisons.
                      </li>

                      <li>
                        Collaborated with a partner to perform multiple logistic regression analyses, using RStudio to program, 
                        visualize, and interpret statistical outcomes.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 10 -->
            <div class="mb-10 experience-item" ref="expItem6">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">
                  NASA/CaSGC Microcomputer & and Robotics Internship 
                </h3>
                <span class="text-sm text-[#030303] font-light">Los Angeles, CA | May 2019 - Aug 2019</span>
              </div>

              <ul class="text-[#030303] mb-6 list-disc pl-6">
                      <li>
                        Implemented core control functionality for the hot-wire CNC machine using an Arduino Uno, enabling 
                        automated wire heating and motion control.
                      </li>

                      <li>
                        Collaborated with a team to design the overall hot-wire cutting system, integrating mechanical, 
                        electrical, and firmware components.
                      </li>

                      <li>
                        Built the machine frame using plywood, utilizing electrical and hand tools to assemble a stable 
                        structure for precision cutting.
                      </li>
              </ul>


              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>

            <!-- Experience 11 -->
            <div class="mb-10 experience-item" ref="expItem6">
              <div class="flex justify-between items-start mb-4">
                <h3 class="text-xl font-semibold text-[#030303]">Web Developer at Flipbill</h3>
                <span class="text-sm text-[#030303] font-light">Mar 2021 - Apr 2022</span>
              </div>

              <p class="text-[#030303] mb-6">
                Designed and developed the company website in 2 weeks.
              </p>

              <div
                class="h-[2px] bg-gradient-to-r from-transparent via-[#FF0000] to-transparent w-full mt-6"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref, onMounted } from 'vue'

// Create refs for all experience items
const experienceSection = ref(null)
const expItem1 = ref(null)
const expItem2 = ref(null)
const expItem3 = ref(null)
const expItem4 = ref(null)
const expItem5 = ref(null)
const expItem6 = ref(null)

onMounted(() => {
  // Get all experience items as an array
  const expItems = [
    expItem1.value,
    expItem2.value,
    expItem3.value,
    expItem4.value,
    expItem5.value,
    expItem6.value,
  ]

  // Apply initial styles
  expItems.forEach((item) => {
    if (item) {
      item.style.opacity = '0'
      item.style.transform = 'translateY(30px)'
      item.style.transition = 'opacity 0.6s ease-out, transform 0.6s ease-out'
    }
  })

  // Set up Intersection Observer for each item
  const observerOptions = {
    root: null, // viewport is the root
    rootMargin: '0px',
    threshold: 0.1, // 10% of the item needs to be visible
  }

  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        // When the item comes into view, make it visible
        entry.target.style.opacity = '1'
        entry.target.style.transform = 'translateY(0)'

        // Stop observing after animation is triggered
        observer.unobserve(entry.target)
      }
    })
  }, observerOptions)

  // Start observing each item
  expItems.forEach((item) => {
    if (item) {
      observer.observe(item)
    }
  })
})
</script>

<style scoped>
.experience-item {
  /* Add a small delay to each subsequent item for cascade effect */
  &:nth-child(1) {
    transition-delay: 0s;
  }
  &:nth-child(2) {
    transition-delay: 0.2s;
  }
  &:nth-child(3) {
    transition-delay: 0.4s;
  }
  &:nth-child(4) {
    transition-delay: 0.6s;
  }
  &:nth-child(5) {
    transition-delay: 0.8s;
  }
  &:nth-child(6) {
    transition-delay: 1s;
  }
}
</style>
