<script setup>

</script>

<template>
    <div class="py-4">
      <header>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <h1 class="text-lg leading-6 font-semibold text-gray-900">
            Payment Dashboard
          </h1>
          <p>Check status and make payments</p>
        </div>
      </header>

      <main>
        <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
          <!-- Replace with your content -->
          <div class="px-4 py-8 sm:px-0">
            <div class="flex flex-col">
                <div class="-my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
                  <div class="py-2 align-middle inline-block min-w-full sm:px-6 lg:px-8">
                    <div class="shadow overflow-hidden border-b border-gray-200 sm:rounded-lg">
                      <table class="min-w-full divide-y divide-gray-200">
                        <thead class="bg-gray-50">
                          <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                              Invoice Number
                            </th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                              Issue Date
                            </th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                              Invoice Amount
                            </th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                              Status
                            </th>
                            <th scope="col" class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">
                              Action
                            </th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                              J12368
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              01/15/2022
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              $127.45
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-blue-100 text-blue-800">
                                New Invoice
                              </span>
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right">
                              <div class="ml-1 mt-1 flex-shrink-0">
                                <button type="button" class="relative inline-flex items-center px-4 py-1 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-green-300 hover:bg-green-600 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
                                  Pay Now
                                </button>
                              </div>
                            </td>
                          </tr>
                          <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                              G2389
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              12/05/2021
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              $150.57
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                Invoice is Paid
                              </span>
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right">
                              <div class="ml-1 mt-1 flex-shrink-0">
                                <button type="button" class="relative inline-flex items-center px-4 py-1 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-gray-300 hover:bg-gray-600 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500">
                                  Edit
                                </button>
                              </div>
                            </td>
                          </tr>
                          <tr>
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                              G1148
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              11/06/2021
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              $136.25
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                              <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                Invoice is Paid
                              </span>
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right">
                              <div class="ml-1 mt-1 flex-shrink-0">
                                <button type="button" class="relative inline-flex items-center px-4 py-1 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-gray-300 hover:bg-gray-600 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500">
                                  Edit
                                </button>
                              </div>
                            </td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
          </div>
          <!-- /End replace -->
        </div>
      </main>
    </div>
</template>