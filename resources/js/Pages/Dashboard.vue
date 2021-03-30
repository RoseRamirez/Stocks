<template>
  <breeze-authenticated-layout>
    <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">
        Dashboard
      </h2>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
          <div class="p-6 bg-white border-b border-gray-200">
            <table class="rounded-t-lg m-5 w-5/6 mx-auto bg-gray-200 text-gray-800">
  <tr class="text-left border-b-2 border-gray-300">
    <th class="px-4 py-3">Firstname</th>
    <th class="px-4 py-3">Lastname</th>
    <th class="px-4 py-3">Age</th>
    <th class="px-4 py-3">Sex</th>
  </tr>
  
  <tr class="bg-gray-100 border-b border-gray-200">
    <td class="px-4 py-3">Jill</td>
    <td class="px-4 py-3">Smith</td>
    <td class="px-4 py-3">50</td>
    <td class="px-4 py-3">Male</td>
  </tr> 
<!-- each row -->
  <tr class="bg-gray-100 border-b border-gray-200">
    <td class="px-4 py-3">Jill</td>
    <td class="px-4 py-3">Smith</td>
    <td class="px-4 py-3">50</td>
    <td class="px-4 py-3">Male</td>
  </tr> 
<!-- each row -->
  <tr class="bg-gray-100 border-b border-gray-200">
    <td class="px-4 py-3">Jill</td>
    <td class="px-4 py-3">Smith</td>
    <td class="px-4 py-3">50</td>
    <td class="px-4 py-3">Male</td>
  </tr> 
<!-- each row -->

</table>
          </div>
        </div>
      </div>
    </div>
  </breeze-authenticated-layout>
</template>

<script>
import BreezeAuthenticatedLayout from "@/Layouts/Authenticated.vue";

export default {
  components: {
    BreezeAuthenticatedLayout,
  },
};
</script>
