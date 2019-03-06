<template>
  <div class="body-container">
      <div class="box-container " >
        <div class="box-detail">
          <div class="work-box "><span>今日计划开工20项</span> <span>今日计划完工20项</span></div>
         
          <table>
            <tr>
              <td>一级风险</td>
              <td>二级风险</td>
              <td>三级风险</td>
            </tr>
            <tr>
              <td>4项</td>
              <td>6项</td>
              <td>8项</td>
            </tr>
          </table>

          <div class="work-box"><span>今日准点开工率96</span> <span>今日准点完工率96</span></div>
          <div class="work-box"><span>今日临时计划率96</span> <span>今日计划取消率96</span></div>
          <div class="line"></div>
          <div class="work-box"><span>累计实际开工96</span> <span>累计实际完工96</span></div>
          <div class="work-box"><span>整体开工率96</span> <span>整体完工率96</span></div>
        </div>
        

        <div class="date">
          <span>11月2日</span>
        </div>
        <div class="sanjiao"></div> 
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
* {
    box-sizing: border-box;
}
.body-container{
    height:100%;
    width:100%;
   
}
.box-container{
  height:200px;
  width:350px;
  color:red;
  
  /* border:1px solid red; */
  position: relative;
  /* overflow: hidden; */
}
.box-detail{
    background-color: blanchedalmond;
    border-radius: 5px 5px 0 0;
      padding-left:12px;  
      padding-top:8px; 
    height:85%; 
     width:100%; 
     /* overflow: hidden; */
    
} 
.work-box{
    width:100%;
   
}
.work-box span{
    display: block;
    width:50%;
    float:left;
}


table{
    border-collapse: collapse;
    margin-left: 4px;
    text-align: center;
    /* margin-right:2px; */
     width:90%;
}
td{
    border:1px solid #ccc;
    /* width:30%; */
}
.line{
    height:2px;
    width:95%;
    background: #ccc;
     overflow: hidden; 
}
.date{
    height:15%;
    width:100%;
    background: gray;
    overflow: hidden;
    text-align: center;
    
   
}
.sanjiao{
    width: 0;
    height: 0;
    border-left: 10px solid transparent;
    border-right: 10px solid transparent;
    border-top: 10px solid gray;
     position: absolute;
    left:50%; 
  }
   /* 问题：span设置的浮动，日期区域清除浮动后，用p标签，11月2日在下方显示？，用span标签，在略上方显示呢？ */
</style>
  
 

  

