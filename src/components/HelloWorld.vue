<template>
  <h1>{{ msg }}</h1>
  
  <p v-bind:style="{ textAlign: 'center', marginLeft: '50px' }">
    郭哥和蘇老爺曾經是好朋友，他們在一起工作、玩樂，並且彼此關係非常親密。<br> 
    但是，最近發生了一些事情，使得他們之間的關係降溫。 <br>
    對郭哥來說，蘇老爺原本是他的恩師，對他的成長和發展有莫大的貢獻。<br>
    但是，在最近的一次合作中，蘇老爺的行為讓郭哥感到很失望。<br>
    蘇老爺沒有履行他的承諾，也沒有對郭哥表示歉意。對郭哥來說，這是一個很大的打擊，他無法接受蘇老爺這樣的行為。<br>
    於是，郭哥決定與蘇老爺分道揚鑣。<br>
    他告訴蘇老爺，他無法再和他繼續保持友誼，因為他對蘇老爺的信任已經毀損。<br>
    蘇老爺聽了郭哥的話，感到非常傷心。他向郭哥道歉，並告訴他自己的想法。<br>
    但是，對郭哥來說，這已經太遲了。<br>
    他已經決定與蘇老爺斷絕關係，並且決定走自己的路。<br>
    雖然郭哥和蘇老爺之間的友誼已經結束，但是他們之間的回憶仍然深刻。
  </p>
  
  <button type="button" @click="count++">Like: {{ count }}</button>

</template>

<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
