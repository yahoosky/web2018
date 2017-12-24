<template>
  <div>
    <ul>
        <li v-for="leftnav in navs">
            <p>{{leftnav.title}}</p>
            <ul class="navs-2">
                <li v-for="s in leftnav.navs" >{{s}}</li>
            </ul>
        </li>
    </ul>
  </div>
</template>
<script>
export default {
  data () {
    return {
      navs: [{
        title: 'a',
        navs: {
          a: 'a',
          b: 'b'
        }
      }]
    }
  }
}
</script>
<style lang="scss" scoped>
    ul{
        list-style: none;
        padding:0;
        margin:0;
        li{
            list-style: none;
            p{
                border-bottom:1px solid #ccc;
                &:hover{
                    .navs-2{
                        display: bloc
                    }
                }
            }
            .navs-2{
                display: none;
            }
        }
    }
</style>
