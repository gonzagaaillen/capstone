\<template>
    <div class="bg-white rounded-lg p-5 flex justify-between items-center w-full">
        <div class="flex flex-col items-start">
        <p class="text-4xl font-medium text-custom-orange">{{ totalPetowners }}</p>
        <h3 class="mt-1">Total Pet Owners</h3>
      </div>
      <font-awesome-icon icon="user" size="3x" class="text-custom-yellow" />
    </div>
  </template>
  
  <script>
  export default {
    name: 'totalPetowners',
    props: {
      totalPetowners: {
        type: Number,
        required: true
      }
    }
  }
  </script>
  