<script setup vapor lang="ts">
import Label from '@/components/ui/label/Label.vue'

interface Props {
  company: string
  role: string
  date: string
  points: string[]
}

const props = defineProps<Props>()
</script>

<template>
  <div class="relative">
    <div class="absolute -left-8 top-2 w-4 h-4 rounded-full bg-primary"></div>

    <!-- Company -->
    <Label class="text-xl font-semibold text-foreground">
      {{ props.company }}
    </Label>

    <!-- Role -->
    <Label class="text-base font-semibold text-muted-foreground">
      {{ props.role }}
    </Label>

    <!-- Date -->
    <p class="text-sm text-muted-foreground mb-3">{{ props.date }}</p>

    <!-- Bullets -->
    <ul class="list-disc px-5">
      <li
        v-for="(item, i) in points"
        :key="i"
        class="text-muted-foreground leading-relaxed"
      >
        {{ item }}
      </li>
    </ul>
  </div>
</template>
