<script>
  import photo1 from '$lib/assets/photo1.jpg';
  import photo2 from '$lib/assets/photo2.jpg';
</script>


<div class="max-w-5xl mx-auto">

    <div class="flex justify-between items-center pb-5">
      <div>
        <h2 class="text-xl font-semibold">User Accounts</h2>
        <p class="text-gray-500 text-sm">View accounts of registered users</p>
      </div>
      <button class="bg-blue-600 text-white px-4 py-2 rounded-lg">CSV</button>
    </div>

    <div class="bg-white rounded-xl shadow overflow-hidden">

      <table class="w-full border-collapse">

        <thead class="bg-blue-600 text-white text-sm">
          <tr>
            <th class="p-3 text-left">ID</th>
            <th class="p-3 text-left">FULL NAME</th>
            <th class="p-3 text-left">USER ROLE</th>
            <th class="p-3 text-left">CREATED AT</th>
            <th class="p-3 text-left">STATUS</th>
          </tr>
        </thead>

        <tbody class="text-sm divide-y divide-gray-200">

          <tr>
            <td class="p-3">3</td>
            <td class="p-3 flex items-center gap-3">
              <img src="{photo1}" class="w-8 h-8 rounded-full">
              Regis Balla
            </td>
            <td class="p-3">Administrator</td>
            <td class="p-3">Sep 28, 2022</td>
            <td class="p-3">
              <span class="bg-green-100 text-green-700 px-2 py-1 rounded-full text-10">Active</span>
            </td>
          </tr>

          <tr>
            <td class="p-3">7</td>
            <td class="p-3 flex items-center gap-3">
              <img src="{photo2}" class="w-8 h-8 rounded-full">
              Ron Volaj
            </td>
            <td class="p-3">Author</td>
            <td class="p-3">Sep 28, 2022</td>
            <td class="p-3">
              <span class="bg-green-100 text-green-700 px-2 py-1 rounded-full text-10">Active</span>
            </td>
          </tr>
        </tbody>
      </table>

    </div>

  </div>