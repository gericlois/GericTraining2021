<template>
   <div class="flex justify-center h-screen">
    <div class="flex justify-col">
      <div class="p-3 flex justify-center flex-col">
        <div class="p-3 px-3 flex flex-col items-start border-collapse border border-black-80">
          <label class="font-mono" for="department"> Department </label>
          <input class="p-1 border-collapse border border-black-800" type="text"/>
        </div>
        <div class="p-2 px-3 flex flex-col items-end bg-gray-100">
          <button class="p-1 my-2 font-mono bg-blue-900 text-white rounded-md focus:outline-none focus:ring-2 ring-blue-200 ring-offset-2" >
            Create Department
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Department',
  props: {
    msg: String
  }
}
</script>

<style>

</style>