<template>
  <BraveTabs
    ref="bravetabref"
    class="overflow-hidden"
    tabsWrapperClass="flex mx-auto max-w-min bg-slate-800 p-1 rounded-xl"
    tab-button-class="rounded-xl px-10 py-2 dark:text-slate-400 whitespace-nowrap cursor-pointer text-center duration-200"
    tab-button-active-class="rounded-xl bg-slate-900 dark:text-white whitespace-nowrap px-10 py-2 cursor-pointer text-center duration-200 shadow-md"
    tabs-content-class="mt-7 rounded-lg grid grid-cols-4 grid-flow-row gap-6"
    v-bind:tabs="['a', 'b', 'c', 'd', 'e']"
    initialTab="a"
  >
    <!-- ================================================================ -->
    <!-- Board-A PANEL  -->
    <!-- ================================================================ -->
    <template #tab-head-a>
      <span class="uppercase">Festive Sale</span>
    </template>
    <template #tab-panel-a>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
          h-[550px]
          2xl:h-[750px]
          row-span-2
          col-span-2
        "
        style="background-image: url('src/assets/15903.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="
          background-image: url('src/assets/attractive-asian-woman-showing-smartphone-app-shopping-bags-buying-online-via-application-standi.jpg');
        "
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="
          background-image: url('src/assets/tv-cabinet-modern-living-room-with-lamp-table-flower-plant-yellow-wall-background.jpg  ');
        "
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/appliance\ realistic.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="
          background-image: url('src/assets/young-african-american-girl-teen-student-denim-clothes-backpack-hold-pc-fan-cash-money-isolated-blue-wall.jpg');
        "
      ></div>
    </template>

    <!-- ================================================================ -->
    <!-- Board-B PANEL  -->
    <!-- ================================================================ -->
    <template #tab-head-b>
      <span class="uppercase">Mobile</span>
    </template>
    <template #tab-panel-b>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
          h-[550px]
          2xl:h-[750px]
          row-span-2
          col-span-2
        "
        style="background-image: url('src/assets/mobile-1.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/mobile-2.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/mobile-3.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/mobile-4.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/mobile-5.jpg')"
      ></div>
    </template>

    <!-- ================================================================ -->
    <!-- Board-C PANEL  -->
    <!-- ================================================================ -->
    <template #tab-head-c>
      <span class="uppercase">Tv</span>
    </template>
    <template #tab-panel-c>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
          h-[550px]
          2xl:h-[750px]
          row-span-2
          col-span-2
        "
        style="background-image: url('src/assets/tv-1.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tv-2.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tv-3.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tv-4.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tv-5.jpg')"
      ></div>
    </template>

    <!-- ================================================================ -->
    <!-- Board-D PANEL  -->
    <!-- ================================================================ -->
    <template #tab-head-d>
      <span class="uppercase">Appliance</span>
    </template>
    <template #tab-panel-d>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
          h-[550px]
          2xl:h-[750px]
          row-span-2
          col-span-2
        "
        style="background-image: url('src/assets/ap-1.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/ap-2.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/ap-3.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/ap-4.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/ap-5.jpg')"
      ></div>
    </template>

    <!-- ================================================================ -->
    <!-- Board-E PANEL  -->
    <!-- ================================================================ -->
    <template #tab-head-e>
      <span class="uppercase">Tabs & Computing</span>
    </template>
    <template #tab-panel-e>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
          h-[550px]
          2xl:h-[750px]
          row-span-2
          col-span-2
        "
        style="background-image: url('src/assets/tc-1.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tc-2.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tc-3.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tc-4.jpg')"
      ></div>
      <div
        class="
          bg-slate-900
          rounded-lg
          p-5
          bg-cover bg-no-repeat bg-center
          shadow
        "
        style="background-image: url('src/assets/tc-5.jpg')"
      ></div>
    </template>
  </BraveTabs>
</template>

<script>
import { BraveTabs } from 'bravevue';
export default {
  components: {
    BraveTabs,
  },
};
</script>
