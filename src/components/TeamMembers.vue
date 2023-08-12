<script setup>
import team from '../data/team'
import TeamMember from './TeamMember.vue'

</script>
<template>
    <TeamMember  
        v-for="(member, index) in team" 
        :key="index"
        :member="member"
    />
</template>