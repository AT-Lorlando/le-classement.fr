<script lang="ts" setup>
const battleLink = useRuntimeConfig().public.classement.battle.registrationLink
</script>

<template>
  <ClassementLink part="classement" :button-link="battleLink" button-text="S'inscrire à la Battle" target="_blank" />
</template>
