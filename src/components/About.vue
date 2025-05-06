<template>
    <div class="about">
        <h1>{{msg}}</h1>
        <p>
            Reference site about Lorem Ipsum, giving information on 
            its origins, as well as a random Reference site about Lorem Ipsum, giving information
             on its origins, as well as a random
            Reference site about Lorem Ipsum, giving information on its origins, as well as a random
        </p>
    </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'Welcome to Your About Us Page'
    }
  }
}
</script>

<style scoped>
    .about {
        padding:10px;
        margin:10px;
        background-color: #f3f3f3;
        color:#384141;
    }
</style>