<script setup>
import { Timeline, TimelineItem, TimelinePoint, TimelineTime, TimelineContent, TimelineTitle } from 'flowbite-vue'
</script>
<template>
    <center>
    <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"><i><u>My Hobby</u></i></h2><br>
    </center>

  <Timeline horizontal="">
    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
        </timeline-time>
        <timeline-title>
          Menyanyi
        </timeline-title>
        <timeline-body>membersihkan dan mencegah perkembangbiakan bakteri yang bisa mengganggu sistem pernapasan.</timeline-body>
      </timeline-content>
    </timeline-item>
    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
        </timeline-time>
        <timeline-title>
          Mendengarkan Musik
        </timeline-title>
        <timeline-body>Selain bermanfaat untuk kesehatan mental, musik juga bisa memperbaiki suasana hati.</timeline-body>
      </timeline-content>
    </timeline-item>
    <timeline-item>
      <timeline-point>
      </timeline-point>
      <timeline-content>
        <timeline-time>
        </timeline-time>
        <timeline-title>
           Bersepeda
        </timeline-title>
        <timeline-body>meningkatkan kekuatan otot, bersepeda secara rutin juga bisa melatih keseimbangan dan koordinasi tubuh.</timeline-body>
      </timeline-content>
    </timeline-item>

  </Timeline>
</template>

