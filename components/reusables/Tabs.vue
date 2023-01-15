<template>
  <div class="w-full max-w-5xl py-10 px-24 sm:px-0 mx-auto">
    <TabGroup>
      <TabList class="flex space-x-1 rounded-xl p-1 bg-white">
        <Tab as="template" v-slot="{ selected }">
          <button
            :class="[
              'w-full rounded-lg py-2.5 text-sm font-bold tracking-wider uppercase leading-5 text-gray-600',
              'focus:outline-none ',
              selected ? 'text-green-600 shadow' : ' hover:bg-green-100',
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
              selected ? 'text-green-600 shadow' : ' hover:bg-green-100',
            ]"
          >
            Conversion-Events
          </button>
        </Tab>
      </TabList>

      <TabPanels class="h-[800px] px-10 py-1 mt-5 shadow-md bg-white">
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
                <th class="table-cell">Product-Level</th>
                <th class="table-cell">Order-Level</th>
                <th class="table-cell">User-Level</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border">
                <td class="table-cell">Product Name</td>
                <td class="table-cell">Order ID</td>
                <td class="table-cell">User ID</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Category</td>
                <td class="table-cell">Order Total Price</td>
                <td class="table-cell">User Type</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product SKU/ID</td>
                <td class="table-cell">Order Shipping Price</td>
                <td class="table-cell">User Recency</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Google Feed ID</td>
                <td class="table-cell">Order Tax</td>
                <td class="table-cell">User Frequency</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Type</td>
                <td class="table-cell">Order Coupon Code</td>
                <td class="table-cell">User Monetary (Total Spent)</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Brand</td>
                <td class="table-cell">Payment Currency</td>
                <td class="table-cell">User Email (hased)</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Total Price</td>
                <td class="table-cell"></td>
                <td class="table-cell">User First Name</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Shipping Price</td>
                <td class="table-cell"></td>
                <td class="table-cell">User Last Name</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Quantity</td>
                <td class="table-cell"></td>
                <td class="table-cell">User Phone</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Tax</td>
                <td class="table-cell"></td>
                <td class="table-cell">User Address</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Category/Collection Name</td>
                <td class="table-cell"></td>
                <td class="table-cell">User Zip Code</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Category/Collection ID</td>
                <td class="table-cell"></td>
                <td class="table-cell">User City/Province/Country</td>
              </tr>
            </tbody>
          </table>
        </TabPanel>
        <TabPanel>
          <table class="w-full mt-20">
            <thead>
              <tr class="border">
                <th class="table-cell">Event Name</th>
                <th class="table-cell">Trigger</th>
                <th class="table-cell">Data</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border">
                <td class="table-cell">Global</td>
                <td class="table-cell">All Pages</td>
                <td class="table-cell">Page-level,user-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Impression</td>
                <td class="table-cell">Collection/Category Pages</td>
                <td class="table-cell">
                  Product-level data of all products impressed
                </td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Click</td>
                <td class="table-cell">Product Click in any listing</td>
                <td class="table-cell">Product-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Product Detail</td>
                <td class="table-cell">Single product page</td>
                <td class="table-cell">Product-level</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Add to cart</td>
                <td class="table-cell">A product added to the cart</td>
                <td class="table-cell">Cart details (including products))</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Initiate Checkout</td>
                <td class="table-cell">Started checkout steps</td>
                <td class="table-cell">Cart details (including products)</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Checkout Steps</td>
                <td class="table-cell">All checkout steps</td>
                <td class="table-cell">Cart details (including products)</td>
              </tr>
              <tr class="border">
                <td class="table-cell">Purchase</td>
                <td class="table-cell">Thank you page</td>
                <td class="table-cell">
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
