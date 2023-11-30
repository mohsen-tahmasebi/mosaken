<template>
  <main class="grid grid-cols-[minmax(10rem,15rem)_1fr] grid-rows-1 min-h-screen">
    <aside
      class="gap-2 bg-primary border-l border-secondary flex flex-col text-white text-2xl p-6"
    >
      <a href="#">آیتم</a>
      <a href="#">آیتم</a>
      <a href="#">آیتم</a>
      <a href="#">آیتم</a>
    </aside>
    <div class="mx-12 my-6">
      <Bar :data="data" :options="{responsive:true,}" class="text-2xl"/>
    </div>
  </main>
</template>

<script setup>
import {
  Chart as ChartJS,
  Title,
  Tooltip,
  Legend,
  BarElement,
  CategoryScale,
  LinearScale,
} from 'chart.js'
import { Bar } from 'vue-chartjs'

ChartJS.register(CategoryScale, LinearScale, BarElement, Title, Tooltip, Legend)


const data = reactive({  
        labels: ['فروردین', 'اردیبهشت', 'خرداد', 'تیر', 'مرداد', 'شهریور', 'مهر', 'آبان', 'آذر', 'دی', 'بهمن', 'اسفند'],
        datasets: [{
      backgroundColor: 'rgb(9 218 102)', data: Array.from({ length: 12 }, () => Math.floor(Math.random() * 12) + 1) }]
      })

</script>
