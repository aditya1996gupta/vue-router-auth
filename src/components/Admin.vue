<template>
    <div class="hello">
        <router-link to='/logout'>Log out</router-link>
        <h1>Welcome to administrator page</h1>
        <h2>{{msg}}</h2>
    </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'The superheros'
    }
  }
}
</script>
<style scoped>
    h1, h2 {
        font-weight: normal;
    }
    ul {
        list-style-type: none;
        padding: 0;
    }
    li {
        display: inline-block;
        margin: 0 10px;
        text-decoration: none;
    }
    a {
        color: #;
        text-decoration: none;
    }
</style>
