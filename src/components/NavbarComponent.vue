<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://www.vhv.rs/dpng/d/512-5121842_portfolio-png-png-download-portflio-logo-transparent-png.png">
          Linda Setiawati
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>About</NavbarLink>
          <NavbarLink>Hobby</NavbarLink>
          <NavbarLink>Skill</NavbarLink>
          <NavbarLink>Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
