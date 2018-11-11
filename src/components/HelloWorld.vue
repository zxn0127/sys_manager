<template>
  <div class="hello">
  <div class="wraper">
    <h1>{{ msg }}</h1>
  
    
    <h2>业余了解</h2>
    <ul>
      <li>
        <a
          href="https://baike.baidu.com/item/%E6%B0%B4%E6%9E%9C%E4%B8%93%E5%AE%B6/3973653"
          target="_blank"
        >
          水果
        </a>
      </li>
      <li>
        <a
          href="http://www.aiyanghua.com/"
          target="_blank"
        >
          养花
        </a>
      </li>
      <li>
        <a
          href="http://www.aiyanghua.com/"
          target="_blank"
        >
          热点新闻
        </a>
      </li>
      
      <br>
      <li>
       
      </li>
    </ul>
    <h2>体育</h2>
    <ul>
      <li>
         <a
          href="https://baike.baidu.com/item/%E5%9B%BD%E9%99%85%E7%91%9C%E4%BC%BD%E6%97%A5"
          target="_blank"
        >
         瑜伽
        </a>
         <li>
         <a
          href="https://baike.baidu.com/item/%E5%9B%BD%E9%99%85%E7%91%9C%E4%BC%BD%E6%97%A5"
          target="_blank"
        >
         双杠
        </a>
      </li>
      <li>
         <a
          href="https://baike.baidu.com/item/%E8%B7%91%E6%AD%A5/4510250"
          target="_blank"
        >
         跑步
        </a>
      </li>
    </ul>
    </div>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎来到我的博客乐园',
      form:{

        }
    }
  },
  methods:{

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wraper{
  width: 500px;
  height: 100%;
  border: 1px solid #f0f0f0;
  box-shadow: 0 0 10px #0CC; 
  margin: 0 auto;
  vertical-align: center;
  padding:20px 50px;
}
h1, h2 {
  font-weight: normal;
  text-align: center;
}
ul {
  list-style-type: none;
  padding: 0;
  width: 500px;
  margin: 0 auto;
}
li {
  display: inline-block;
  margin: 0 auto;
  text-align: center;
  font-size: 18px;
}
a {
  color: #42b983;
  text-align: center;
  margin: 0 15px;
}
</style>
