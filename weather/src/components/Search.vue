<template>
 <div class="search"> <input v-model="search" type="text" placeholder="Search a City"/> <button> Search </button> </div>
    
</template>

<script>
export default {
  name: 'Search',

  data:{
      search,
      }
}
</script>