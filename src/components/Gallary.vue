<template>
  <v-carousel  mandatory
 circle height="800px">
    <v-carousel-item
    
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      
      reverse-transition="fade-transition"
    >
    
    </v-carousel-item>
    
  </v-carousel>
  
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: "./image/wealth.jpg",
        },
        {
          src: "./image/payment.jpg",
        },
        {
          src: "./image/stock.jpg",
        },
      ],
    };
  },
};
</script>