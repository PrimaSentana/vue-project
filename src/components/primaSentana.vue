<script lang="js">

export default {
    data(){
        return {
            clicked : 0
        }
    },
    methods : {
        increment: function() {
            this.clicked++;
        }
    }
}

</script>

<template>
    <p>Value = {{clicked}} !</p>
    <button @click="increment" class="text-white bg-gray-800 hover:bg-gray-900 focus:outline-none focus:ring-4 focus:ring-gray-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-gray-800 dark:hover:bg-gray-700 dark:focus:ring-gray-700 dark:border-gray-700">Click Here !</button>
  <a href="https://steamcommunity.com/id/iyaitudah/">My Steam Account</a>
</template>

<style>

</style>

