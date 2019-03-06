<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <link rel="stylesheet" href="./base.css" />
    <link rel="stylesheet" href="./index.css" />

  </head>
  <body>
    <div class="body-container">
      <div class="box-container " v-for="(item,index) in list":key="index">
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
  </body>
  <!-- 问题：span设置的浮动，日期区域清除浮动后，用p标签，11月2日在下方显示？，用span标签，在略上方显示呢？ -->
  <script>
    
  
  </script>

  <script src="./index.js"></script>
  <!-- <script src="./jquery-1.12.4.js"></script> -->
  <script src="https://cdn.bootcss.com/jquery/3.1.1/jquery.min.js"></script>
</html>
