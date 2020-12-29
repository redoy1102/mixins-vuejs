<template>
  <div>
    <p>{{text}}</p>
    <ul>
      <li v-for="car in cars" :key="car">
        {{car}}
      </li>
    </ul>
  </div>
</template>

<script>

import {carMixin} from './mixin'
export default {
  data(){
    return{
      text: "Md Fuadul Islam Redoy",
    }
  },
  mixins: [carMixin]
}
</script>