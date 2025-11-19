<script setup vapor lang="ts">
    import { Separator } from "@/components/ui/separator"
    import { Badge } from "./ui/badge";
</script>

<template>
  <section class="min-h-screen flex items-center w-full justify-around py-16">
    <div class="max-w-4xl px-6">
      <h1 class="text-4xl font-extrabold tracking-tight text-foreground">
        Benedict Ell Nino
      </h1>

      <div class="space-x-4 py-2">
        <Badge class="bg-[#61dbfa]">React</Badge>
        <Badge
          class="
            border-none
            relative 
            bg-gradient-to-br from-[#8c76db] to-[#5432cf]
            text-white
            border border-transparent
            before:absolute before:inset-0 before:rounded-[inherit]
            before:p-[1px] before:bg-gradient-to-br before:from-[#9e86e7] before:to-[#4a2bb8]
            before:-z-10
          "
        >
          C#
        </Badge>
        <Badge
          class="
            border-none
            relative 
            bg-gradient-to-br from-[#6cc24a] to-[#3d7a2b]
            text-white
            border border-transparent
            before:absolute before:inset-0 before:rounded-[inherit]
            before:p-[1px] before:bg-gradient-to-br before:from-[#8ddf67] before:to-[#2d5e21]
            before:-z-10
          "
        >
          Node.js
        </Badge>
      </div>

      <p class="text-xl mt-2 text-muted-foreground font-bold">
        Software Engineer · Fullstack Developer
      </p>

      <Separator class="my-4"/>

      <p class="mt-6 text-lg leading-relaxed text-muted-foreground">
        Fullstack Developer delivering <span class="font-medium text-foreground">end-to-end solutions</span> from frontend experience to backend reliability
      </p>
    </div>
    <div class="px-6">
      
    </div>
  </section>
</template>

