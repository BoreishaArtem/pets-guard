<template>
  <div class="antialiased text-gray-900 bg-blue-600">


    <div class="mx-4 card bg-white max-w-md p-10 md:rounded-lg my-8 mx-auto">
      <div class="title">
        <h1 class="font-bold text-center">Report a bug or request a feature</h1>
      </div>

      <div class="options md:flex md:space-x-6 text-sm items-center text-gray-700 mt-4">
        <p class="w-1/2 mb-2 md:mb-0">I would like to </p>
        <select class="w-full border border-gray-200 p-2 focus:outline-none focus:border-gray-500">
          <option value="select" selected>Select an option</option>
          <option value="bug">report a bug</option>
          <option value="feature">Request a feature</option>
          <option value="feedback">Feedback</option>
        </select>
      </div>

      <div class="form mt-4">
        <div class="flex flex-col text-sm">
          <label for="title" class="font-bold mb-2">Title</label>
          <input class=" appearance-none border border-gray-200 p-2 focus:outline-none focus:border-gray-500" type="text" placeholder="Enter a title">
        </div>

        <div class="text-sm flex flex-col">
          <label for="description" class="font-bold mt-4 mb-2">Description</label>
          <textarea class=" appearance-none w-full border border-gray-200 p-2 h-40 focus:outline-none focus:border-gray-500"  placeholder="Enter your description"></textarea>
        </div>
      </div>

      <div class="submit">
        <button type="submit" class=" w-full bg-blue-600 shadow-lg text-white px-4 py-2 hover:bg-blue-700 mt-8 text-center font-semibold focus:outline-none ">Submit</button>
      </div>
    </div>


  </div>
</template>

<script>
export default {
  name: "GForm"
}
</script>

<style scoped>

</style>
