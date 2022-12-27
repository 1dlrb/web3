# web
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>

img {
  max-width: 100%;
  height: auto;
}
video {
  max-width: 100%;
  height: auto;
}
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}

/* 页眉/Blog 标题 */
.header {
  padding: 30px;
  text-align: center;
  background: white;
}

.header h1 {
  font-size: 50px;
}

/* 设置上导航栏的样式 */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* 设置 topnav 链接的样式 */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* 改变鼠标悬停时的颜色 */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* 创建两个不相等的彼此并排的浮动列 */
/* 左列 */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* 右列 */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/* 伪图像 */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* 为文章添加卡片效果 */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

/* 清除列之后的浮动 */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* 页脚 */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* 响应式布局 - 当屏幕的宽度小于 800 像素时，使两列堆叠而不是并排 */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* 响应式布局 - 当屏幕的宽度小于 400 像素时，使导航链接堆叠而不是并排 */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>My Website</h1>
  <p>个人信息介绍</p>
</div>
<div class="topnav">
  <a href="">关于我</a>

  <a href="#">大事记</a>

  <a href="#">生活集</a>

  <a href="#">近期计划</a>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>大事记</h2>
      <h5> Nov 14, 2020</h5>
      <div class="fakeimg" style="height:300px;"><video width="400" controls>
  <source src="/Users/apple/Desktop/266.MP4 " type="video/mp4">
</video></div>
      <p>电气与信息工程学院迎新晚会演出</p>
    </div>
    <div class="card">
      <h2>生活集</h2>
      <h5>Dec 25, 2022</h5>
      <div class="fakeimg" style="height:250px;"><video width="150" controls>
  <source src="/Users/apple/Desktop/11.mp4 " type="video/mp4">
</video></div>
      <p>圣诞快乐</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>关于我</h2>
      <div class="fakeimg" style="height:50px;">姓名：侯慕昭</div>
      <div class="fakeimg" style="height:50px;">生日：6月16</div>
      <div class="fakeimg" style="height:50px;">爱好：运动</div>
      <div class="fakeimg" style="height:50px;">身高：168cm</div>
      <div class="fakeimg" style="height:50px;">体重：55kg</div>
      <p>联系电话：15901008825</p>
    </div>
    <div class="card">
      <h3>近期计划</h3>
      <ul>
        <li class="fakeimg" style="height:50px;">健身</li>
        <li class="fakeimg" style="height:50px;">读书</li>
        <li class="fakeimg" style="height:50px;">准备考研</li>
        <li class="fakeimg" style="height:50px;">练球</li>
      </ul>
    </div>
  </div>
</div>

<div class="footer">
	<div id="fenye">
    	<a href="">&lt;&lt;上一页</a>
        <a href="file:///Users/apple/Desktop/web.html">1</a>
        <a href="file:///Users/apple/Desktop/2.html">2</a>
        <a href="file:///Users/apple/Desktop/3.html">3</a>
        <a href="file:///Users/apple/Desktop/2.html">下一页&gt;&gt;</a>
</div>

</body>
</html>
