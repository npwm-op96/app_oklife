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
        {
          src:"https://i.pinimg.com/originals/c5/3c/9c/c53c9c31952bad45bca4146ac1e91f97.png"
        }
      ],
    };
  },
};
</script>