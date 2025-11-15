<script setup vapor lang="ts">
import Label from './ui/label/Label.vue';


</script>

<template>
    <section class="w-full py-20">
        <div class="max-w-3xl mx-auto px-6">
            <h2 class="text-3xl font-bold tracking-tight mb-10">Experience</h2>

            <div class="relative border-l border-border pl-6 space-y-12">
                <div class="relative">
                    <div class="absolute -left-8 top-2 w-4 h-4 rounded-full bg-primary"></div>
                    <Label class="text-xl font-semibold text-foreground">
                        Sistem Aksesindo Perdana
                    </Label>
                    <Label class="text-base font-semibold text-muted-foreground ">
                        Research and Development
                    </Label>
                    <p class="text-sm text-muted-foreground mb-3">11/2023 — Present</p>
                    <ul class="list-disc px-5">
                        <li class="text-muted-foreground leading-relaxed">
                            Built the entire Parking Lock ecosystem end-to-end, including the service API, web dashboard, and desktop controller app. Worked on real-time device communication, system reliability, and production deployment.
                        </li>
                        <li class="text-muted-foreground leading-relaxed">
                            Developed CI/CD pipeline with GitHub Actions and Docker for reducing deployment process time and automate release process
                        </li>
                        <li class="text-muted-foreground leading-relaxed">
                            Designed, developed, and maintained Admin Dashboard Resident Management System with NextJS.
                        </li>
                        <li class="text-muted-foreground leading-relaxed">
                            Developed, and maintained Kiosk web app with .NET Core and MVC.
                        </li>
                        <li class="text-muted-foreground leading-relaxed">
                            Developed transaction sorter app with React.
                        </li>
                        <li class="text-muted-foreground leading-relaxed">
                            Developed multistage build on Docker image for optimize Docker images and reduced footprints in VPS.
                        </li>
                    </ul>
                </div>

                <div class="relative">
                    <div class="absolute -left-8 top-2 w-4 h-4 rounded-full bg-primary"></div>
                    <Label class="text-xl font-semibold text-foreground">
                        PT United Tractors
                    </Label>
                    <Label class="text-base font-semibold text-muted-foreground ">
                        Software Engineer
                    </Label>
                    <p class="text-sm text-muted-foreground mb-3">11/2022 - 02/2023</p>
                    <ul class="list-disc px-5">
                        <li class="text-muted-foreground leading-relaxed">
                        Improved internal workflow by developing an automated Ticketing Dashboard
                        that streamlined issue handling and reduced response time across teams.
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>