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
    <div class="flex gap-5 w-full p-5">
            <!-- <i class="pi pi-arrow-right-arrow-left"></i>
            <p>ben.dev</p>
            <p>Home</p>
            <p>LinkedIn</p>
            <p>Resume</p> -->
        
            <Menubar class="w-1/2 mx-auto flex items-center justify-between">
                <MenubarMenu>
                    <MenubarTrigger class="data-[state=open]:bg-transparent hover:bg-transparent focus:bg-transparent"><i class="pi pi-arrow-up-right-and-arrow-down-left-from-center px-5"></i>ben.dev</MenubarTrigger>
                    <MenubarContent>
                        <MenubarItem><i class="pi pi-id-card px-5"></i>Introduction</MenubarItem>
                        <MenubarItem><i class="pi pi-info-circle px-5"></i>About</MenubarItem>
                        <MenubarItem><i class="pi pi-briefcase px-5"></i>Projects</MenubarItem>
                        <MenubarItem><i class="pi pi-cog px-5"></i>Skill</MenubarItem>
                        <MenubarItem><i class="pi pi-calendar px-5"></i>Experience</MenubarItem>
                        <MenubarItem><i class="pi pi-envelope px-5"></i>Contact</MenubarItem>
                    </MenubarContent>

                </MenubarMenu>
                <MenubarMenu>
                    <MenubarTrigger class="data-[state=open]:bg-transparent hover:bg-transparent focus:bg-transparent"><i class="pi pi-hashtag px-5"></i>SNS</MenubarTrigger>
                    <MenubarContent>
                        <MenubarItem><i class="pi pi-linkedin px-5"></i>LinkedIn</MenubarItem>
                        <MenubarSeparator/>
                        <MenubarItem><i class="pi pi-github px-5"></i>GitHub</MenubarItem>
                        <MenubarSeparator/>
                        <MenubarItem><i class="pi pi-bookmark-fill px-5"></i>Medium</MenubarItem>
                    </MenubarContent>
                </MenubarMenu>
                <MenubarMenu>
                    <MenubarTrigger class="data-[state=open]:bg-transparent hover:bg-transparent focus:bg-transparent"><i class="pi pi-download px-5"></i>Resume</MenubarTrigger>
                </MenubarMenu>
            </Menubar>
    </div>
</template>