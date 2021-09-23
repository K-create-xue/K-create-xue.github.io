# 薛展鹏-C++后台研发-151-2950-5070 
# [简历-(实习).pdf](https://github.com/K-create-xue/K-create-xue.github.io/files/7217252/review_.-.-._20210923193709.pdf)

[](https://user-images.githubusercontent.com/76169472/134500001-9af9dfc0-acd9-453b-ae14-5206cd1104aa.jpg)



<!DOCTYPE html>
<html lang="zh-CN">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>背景</title>
 <style>
 *{
 margin: 0;
 padding: 0;
 box-sizing: border-box;
 }
 li {
 list-style: none;
 }
 img{
 border: 0px;
 vertical-align: middle;
 width: 192px;
 }
 div{
 width: 768px;
 height: 120px;
 }
 div ul {
 overflow: hidden;
 background-color: pink ;
 margin: 100px auto;
 }
 div ul li {
 float: left;
 width: 192px;
 height: 120px;
 cursor: pointer;
 }
 body{
 background: url(images/1.jpg) no-repeat center top;
 }
 </style>
</head>
<body>
 <div>
 <ul>
 <li><img src=images/1.jpg> </li>
 <li><img src=images/2.jpg></li>
 <li><img src=images/3.jpg></li>
 <li><img src=images/4.jpg></li>
 </ul>
 </div>
 <script>
 var img = document.querySelector('ul').querySelectorAll('img')
 for(var i = 0 ;i < img.length;i++){
 img[i].onclick = function(){
 document.body.style.backgroundImage='url('+this.src+')';
 }
 }
 </script>
</body>
</html>
