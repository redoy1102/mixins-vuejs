<template>
<div>
  <CompProduct></CompProduct>
  <comp-products></comp-products>
</div>
</template>


<script>

import compProduct from './components/Product'
import compProducts from './components/Products'
export default {
  data(){
    return{

    }
  },
  components:{
    compProduct,
    compProducts
  }
}
</script>