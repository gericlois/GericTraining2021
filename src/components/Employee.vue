<template>
<div class="flex flex-wrap justify-center h-screen">
    <div class="px-6 flex flex-col w-1/2 ">
        <div class="p6">
        <label class="font-mono text-blue-900 text-xl w-full md:text-3xl text-left ">Organization  </label>
        <label class="font-mono text-black-900 text-xl w-full md:text-3xl text-left "> / Murazik PLC Toy-O'Kon </label>
        </div>
        <div class="flex flex-col bg-red-300">
        <div class="flex flex-wrap bg-white-900">
            <div class="p-3 flex flex-col w-full md:w-1/2 lg:w-1/4 ">
                <label class="font-mono text-left md:text-xs" for="department" > First Name </label>
                <input class="p-1 border-collapse border border-black-800" type="text"/>
            </div>
            <div class="p-3 flex flex-col w-full md:w-1/2 lg:w-1/4">
                <label class="font-mono text-left  md:text-xs" for="department"> Last Name </label>
                <input class="p-1 border-collapse border border-black-800" type="text"/>
            </div>
            <div class="p-3 flex flex-col w-full md:w-1/2 lg:w-1/4">
                <label class="font-mono text-left md:w-1/2 ld:text-lg" for="department"> Email </label>
                <input class="p-1 border-collapse border border-black-800" type="email"/>
            </div>
            <div class="p-3 flex flex-col w-full md:w-1/2 lg:w-1/4">
                <label class="font-mono text-left md:text-xs" for="department"> Department </label>  
                <select class="" name="cars" id="cars">
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="opel">Opel</option>
                    <option value="audi">Audi</option>
                </select>
            </div>
        </div>
        </div>
        <div class="p-2 px-3 flex flex-col items-end bg-gray-100">
          <button class="p-2 my-2 font-mono bg-blue-900 text-white rounded-md focus:outline-none focus:ring-2 ring-blue-200 ring-offset-2" >
            Update
          </button>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: "Employee",
  props: {
    msg: String,
  },
};
</script>

<style>
</style>