<script setup vapor lang="ts">
    import { Separator } from "@/components/ui/separator"
</script>

<template>
  <section class="w-full flex justify-around items-center py-16">
    <div class="max-w-4xl px-6">
      <h1 class="text-4xl font-extrabold tracking-tight text-foreground">
        Benedict Ell Nino
      </h1>

      <p class="text-xl mt-2 text-muted-foreground font-bold">
        Software Engineer · Fullstack Developer
      </p>

      <Separator class="my-4"/>

        <p class="mt-6 text-lg leading-relaxed text-muted-foreground">
            Fullstack Developer with strong end-to-end ownership in building
            complete systems and
            enhanced internal software efficiency at
            <span class="font-medium text-foreground">Sistem Aksesindo Perdana</span>. I developed a full Parking Lock ecosystem —
            including the <span class="font-medium text-foreground">backend service API</span>,
            <span class="font-medium text-foreground">web management dashboard</span>,
            and <span class="font-medium text-foreground">desktop controller app</span>.
            I also previously create a prototype app for ticketing at
            <span class="font-medium text-foreground">PT United Tractors</span>.
        </p>
    </div>
    <div class="px-6">
      
    </div>
  </section>
</template>
