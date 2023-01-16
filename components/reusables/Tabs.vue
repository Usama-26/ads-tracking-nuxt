<template>
  <div class="w-full max-w-7xl py-10 px-24 sm:px-0 mx-auto">
    <TabGroup>
      <TabList class="flex space-x-1 rounded-xl p-1 bg-white">
        <Tab as="template" v-slot="{ selected }">
          <button
            :class="[
              'w-full rounded-lg py-2.5 text-sm font-bold tracking-wider uppercase leading-5 text-gray-600',
              'focus:outline-none ',
              selected
                ? 'text-white bg-[#34cc81] shadow'
                : ' hover:bg-green-100',
            ]"
          >
            Datenschichtvariablen
          </button>
        </Tab>
        <Tab as="template" v-slot="{ selected }">
          <button
            :class="[
              'w-full rounded-lg py-2.5 text-sm font-bold tracking-wider uppercase leading-5 text-gray-600',
              'focus:outline-none ',
              selected
                ? 'text-white bg-[#34cc81] shadow'
                : ' hover:bg-green-100',
            ]"
          >
            Conversion-Events
          </button>
        </Tab>
      </TabList>

      <TabPanels class="h-[700px] px-10 py-1 mt-5 shadow-md bg-white">
        <TabPanel>
          <h1 class="my-8">
            All diese Variablen sind den korrelierten Ereignissen zugeordnet.
            Die Datenschichten sind perfekt strukturiert und als
            benutzerdefinierte Trigger und Variablen mit dem Google Tag Manager
            verbunden.
          </h1>
          <table class="w-full">
            <thead>
              <tr class="border">
                <th class="table-cell py-2">Product-Level</th>
                <th class="table-cell py-2">Order-Level</th>
                <th class="table-cell py-2">User-Level</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border">
                <td class="table-cell py-2">Product Name</td>
                <td class="table-cell py-2">Order ID</td>
                <td class="table-cell py-2">User ID</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Category</td>
                <td class="table-cell py-2">Order Total Price</td>
                <td class="table-cell py-2">User Type</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product SKU/ID</td>
                <td class="table-cell py-2">Order Shipping Price</td>
                <td class="table-cell py-2">User Recency</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Google Feed ID</td>
                <td class="table-cell py-2">Order Tax</td>
                <td class="table-cell py-2">User Frequency</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Type</td>
                <td class="table-cell py-2">Order Coupon Code</td>
                <td class="table-cell py-2">User Monetary (Total Spent)</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Brand</td>
                <td class="table-cell py-2">Payment Currency</td>
                <td class="table-cell py-2">User Email (hased)</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Total Price</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User First Name</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Shipping Price</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User Last Name</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Quantity</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User Phone</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Product Tax</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User Address</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Category/Collection Name</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User Zip Code</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-2">Category/Collection ID</td>
                <td class="table-cell py-2"></td>
                <td class="table-cell py-2">User City/Province/Country</td>
              </tr>
            </tbody>
          </table>
        </TabPanel>
        <TabPanel>
          <table class="w-full mt-8">
            <thead>
              <tr class="border">
                <th class="table-cell py-4">Event Name</th>
                <th class="table-cell py-4">Trigger</th>
                <th class="table-cell py-4">Data</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border">
                <td class="table-cell py-4">Global</td>
                <td class="table-cell py-4">All Pages</td>
                <td class="table-cell py-4">Page-level,user-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Product Impression</td>
                <td class="table-cell py-4">Collection/Category Pages</td>
                <td class="table-cell py-4">
                  Product-level data of all products impressed
                </td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Product Click</td>
                <td class="table-cell py-4">Product Click in any listing</td>
                <td class="table-cell py-4">Product-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Product Detail</td>
                <td class="table-cell py-4">Single product page</td>
                <td class="table-cell py-4">Product-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Add to cart</td>
                <td class="table-cell py-4">A product added to the cart</td>
                <td class="table-cell py-4">
                  Cart details (including products))
                </td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Initiate Checkout</td>
                <td class="table-cell py-4">Started checkout steps</td>
                <td class="table-cell py-4">
                  Cart details (including products)
                </td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Checkout Steps</td>
                <td class="table-cell py-4">All checkout steps</td>
                <td class="table-cell py-4">
                  Cart details (including products)
                </td>
              </tr>
              <tr class="border">
                <td class="table-cell py-4">Purchase</td>
                <td class="table-cell py-4">Thank you page</td>
                <td class="table-cell py-4">
                  Order details, user-level data, products
                </td>
              </tr>
            </tbody>
          </table>
        </TabPanel>
      </TabPanels>
    </TabGroup>
  </div>
</template>

<script setup>
import { TabGroup, TabList, Tab, TabPanels, TabPanel } from "@headlessui/vue";
</script>
