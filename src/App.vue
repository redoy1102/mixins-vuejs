<template>
<div>
  <compProduct></compProduct>
  <compProducts></compProducts>
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