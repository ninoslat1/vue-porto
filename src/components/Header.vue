<script setup lang="ts">
import {
  Menubar,
  MenubarContent,
  MenubarItem,
  MenubarMenu,
  MenubarSeparator,
  MenubarShortcut,
  MenubarTrigger,
} from '@/components/ui/menubar'
</script>

<template>
    <div class="flex gap-5 w-full">
        <div class="flex gap-5 items-center justify-around w-1/4">
            <!-- <i class="pi pi-arrow-right-arrow-left"></i>
            <p>ben.dev</p>
            <p>Home</p>
            <p>LinkedIn</p>
            <p>Resume</p> -->
            <Menubar>
                <MenubarMenu>
                    <MenubarTrigger>ben.dev</MenubarTrigger>
                    <MenubarTrigger>File</MenubarTrigger>
                    <MenubarTrigger>Home</MenubarTrigger>
                    <MenubarTrigger>LinkedIn</MenubarTrigger>
                    <MenubarTrigger>Resume</MenubarTrigger>
                </MenubarMenu>
            </Menubar>
        </div>
        <div>

        </div>
    </div>
</template>