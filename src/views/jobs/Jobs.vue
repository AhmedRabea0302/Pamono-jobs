<template>
  <h1>Jobs:</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{job.title}}</h2>
  </div>

</template>

<script>
export default {
    data() {
        return {
            jobs: [
                {id: 1, title: 'Full-Stack Developer (MERN)', details: 'Lorema'},
                {id: 2, title: 'Front-End Developer', details: 'Lorema'},
                {id: 3, title: 'React Native Developer', details: 'Lorema'},
            ]
        }
    }
}
</script>

<style>

</style>