<script setup vapor lang="ts">
    import ExperienceItem from '@/templates/ExperienceItem.vue';
</script>

<template>
  <section class="w-full min-h-screen">
    <div class="max-w-3xl mx-auto px-6">
      <h2 class="text-3xl font-bold tracking-tight mb-10">Experience</h2>

      <div class="relative border-l border-border pl-6 space-y-12">

        <ExperienceItem
          company="Sistem Aksesindo Perdana"
          role="Research and Development"
          date="11/2023 — Present"
          :points="[
            'Built the entire Parking Lock ecosystem end-to-end, including the service API, web dashboard, and desktop controller app.',
            'Developed CI/CD pipeline with GitHub Actions and Docker to automate release processes.',
            'Designed and maintained the Admin Dashboard Resident Management System with NextJS.',
            'Developed and maintained kiosk web app using .NET Core and MVC.',
            'Developed transaction sorter app with React.',
            'Implemented multistage Docker builds to reduce image size for VPS deployment.'
          ]"
        />

        <ExperienceItem
          company="PT United Tractors"
          role="Software Engineer"
          date="11/2022 — 02/2023"
          :points="[
            'Improved internal workflow by developing an automated Ticketing Dashboard that streamlined issue handling and reduced response time across teams.'
          ]"
        />

      </div>
    </div>
  </section>
</template>
