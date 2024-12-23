<!DOCTYPE html>
<html lang="en" ondragstart="return false">
 
<head>
      <meta charset="UTF-8">
      <meta name="Keywords" content="">
      <meta name="Description" content="">
      <title>3D旋转照片墙</title>
      <style type="text/css">
            /* 去掉默认效果 */
            * {
                  margin: 0;
                  padding: 0;
            }
 
            body {
                  background: #222;
                  overflow: hidden;
                  /* 取消选中 */
                  user-select: none;
 
            }
 
            @keyframes rotate {
                  100% {
                        transform: rotateY(360deg);
                  }
            }
 
            .perspective {
                  /*子元素透视 场景深度*/
                  perspective: 600px;
            }
 
            .wrap {
                  /* 3d */
                  width: 135px;
                  height: 240px;
                  margin: 100px auto;
                  position: relative;
                  /* border: 1px solid red; */
                  transform: rotateX(-20deg) rotateY(0deg);
                  transform-style: preserve-3d;
 
            }
 
            .wrap img {
                  display: block;
                  /* 绝对定位 */
                  position: absolute;
                  width: 100%;
                  height: 100%;
                  transform: rotateY(0deg) translateZ(0px);
                  background: transparent;
                  box-shadow: 0 0 4px #fff;
                  border-radius: 5px;
 
                  /* webkit */
            }
 
            /* 照片底座 */
            .wrap p {
                  width: 1200px;
                  height: 1200px;
                  background: -webkit-radial-gradient(center center, 600px 600px, rgba(122, 122, 122, .5), rgba(0, 0, 0, 0));
                  position: absolute;
                  border-radius: 50%;
                  left: 50%;
                  top: 100%;
                  margin-left: -600px;
                  margin-top: -600px;
                  /* 沿着x轴按倒 */
                  transform: rotateX(90deg);
 
            }
      </style>
</head>
 
<body>
      <!-- 盒子容器 -->
      <div class="perspective">
            <div class="wrap" id="imgwrap">
                  <!-- 引入图片值页面 -->
                  <img class="f1" src="img/e (1).jpg" />
                  <img class="f1" src="img/e (2).jpg" />
                  <img class="f1" src="img/e (3).jpg" />
                  <img class="f1" src="img/e (4).jpg" />
                  <img class="f1" src="img/e (5).jpg" />
                  <img class="f1" src="img/e (6).jpg" />
                  <img class="f1" src="img/e (7).jpg" />
                  <img class="f1" src="img/e (8).jpg" />
                  <img class="f1" src="img/e (9).jpg" />
                  <img class="f1" src="img/e (10).jpg" />
                  <img class="f1" src="img/e (11).jpg" />
                  <img class="f1" src="img/e (12).jpg" />
                  <img class="f1" src="img/e (13).jpg" />
                  <img class="f1" src="img/e (14).jpg" />
                  <img class="f1" src="img/e (15).jpg" />
                  <img class="f1" src="img/e (16).jpg" />
                  <img class="f1" src="img/e (17).jpg" />
                  <img class="f1" src="img/e (18).jpg" />
                  <img class="f1" src="img/e (19).jpg" />
                  <img class="f1" src="img/e (20).jpg" />
                  <img class="f1" src="img/e (21).jpg" />
                  <img class="f1" src="img/e (22).jpg" />
                  <img class="f1" src="img/e (23).jpg" />
                  <img class="f1" src="img/e (24).jpg" />
                  <img class="f1" src="img/e (25).jpg" />
                  <img class="f1" src="img/e (26).jpg" />
                  <img class="f1" src="img/e (27).jpg" />
                  <img class="f1" src="img/e (28).jpg" />
                  <img class="f1" src="img/e (29).jpg" />
                  <img class="f1" src="img/e (30).jpg" />
                  <img class="f1" src="img/e (31).jpg" />
                  <img class="f1" src="img/e (32).jpg" />
                  <img class="f1" src="img/e (33).jpg" />
                  <img class="f1" src="img/e (34).jpg" />
                  





                  <!-- 引入图片值页面 -->
                  <img class="f2" src="img/e (34).jpg" />
                  <img class="f2" src="img/e (35).jpg" />
                  <img class="f2" src="img/e (36).jpg" />
                  <img class="f2" src="img/e (37).jpg" />
                  <img class="f2" src="img/e (38).jpg" />
                  <img class="f2" src="img/e (39).jpg" />
                  <img class="f2" src="img/e (40).jpg" />
                  <img class="f2" src="img/e (41).jpg" />
                  <img class="f2" src="img/e (42).jpg" />
                  <img class="f2" src="img/e (43).jpg" />
                  <img class="f2" src="img/e (44).jpg" />
                  <img class="f2" src="img/e (45).jpg" />
                  <img class="f2" src="img/e (46).jpg" />
                  <img class="f2" src="img/e (47).jpg" />
                  <img class="f2" src="img/e (48).jpg" />
                  <img class="f2" src="img/e (49).jpg" />
                  <img class="f2" src="img/e (50).jpg" />
                  <img class="f2" src="img/e (51).jpg" />
                  <img class="f2" src="img/e (52).jpg" />
                  <img class="f2" src="img/e (53).jpg" />
                  <img class="f2" src="img/e (54).jpg" />
                  <img class="f2" src="img/e (55).jpg" />
                  <img class="f2" src="img/e (56).jpg" />
                  <img class="f2" src="img/e (57).jpg" />
                  <img class="f2" src="img/e (58).jpg" />
                  <img class="f2" src="img/e (59).jpg" />
                  <img class="f2" src="img/e (60).jpg" />
                  <img class="f2" src="img/e (61).jpg" />
                  <img class="f2" src="img/e (62).jpg" />
                  <img class="f2" src="img/e (63).jpg" />
                  <img class="f2" src="img/e (64).jpg" />
                  <img class="f2" src="img/e (65).jpg" />
                  <img class="f2" src="img/e (66).jpg" />
                  <img class="f2" src="img/e (67).jpg" />
                  <img class="f2" src="img/e (68).jpg" />

                  


                  <!-- 引入图片值页面 -->
                  <img class="f3" src="img/e (68).jpg" />
                  <img class="f3" src="img/e (69).jpg" />
                  <img class="f3" src="img/e (70).jpg" />
                  <img class="f3" src="img/e (71).jpg" />
                  <img class="f3" src="img/e (72).jpg" />
                  <img class="f3" src="img/e (73).jpg" />
                  <img class="f3" src="img/e (74).jpg" />
                  <img class="f3" src="img/e (75).jpg" />
                  <img class="f3" src="img/e (76).jpg" />
                  <img class="f3" src="img/e (77).jpg" />
                  <img class="f3" src="img/e (78).jpg" />
                  <img class="f3" src="img/e (79).jpg" />
                  <img class="f3" src="img/e (80).jpg" />
                  <img class="f3" src="img/e (81).jpg" />
                  <img class="f3" src="img/e (82).jpg" />
                  <img class="f3" src="img/e (83).jpg" />
                  <img class="f3" src="img/e (84).jpg" />
                  <img class="f3" src="img/e (85).jpg" />
                  <img class="f3" src="img/e (86).jpg" />
                  <img class="f3" src="img/e (87).jpg" />
                  <img class="f3" src="img/e (88).jpg" />
                  <img class="f3" src="img/e (89).jpg" />
                  <img class="f3" src="img/e (90).jpg" />
                  <img class="f3" src="img/e (91).jpg" />
                  <img class="f3" src="img/e (92).jpg" />
                  <img class="f3" src="img/e (93).jpg" />
                  <img class="f3" src="img/e (94).jpg" />
                  <img class="f3" src="img/e (95).jpg" />
                  <img class="f3" src="img/e (96).jpg" />
                  <img class="f3" src="img/e (97).jpg" />
                  <img class="f3" src="img/e (98).jpg" />
                  <img class="f3" src="img/e (99).jpg" />
                  <img class="f3" src="img/e (100).jpg" />
                  <img class="f3" src="img/e (101).jpg" />
                  


                  <p></p>
            </div>
      </div>
      <!--  src="JS/photo.js" -->
      <script type="text/javascript">
            var oImg = document.getElementsByClassName('f1')
            var oImg2 = document.getElementsByClassName('f2')
            var oImg3 = document.getElementsByClassName('f3')
            var len = oImg.length;
            console.log(len)
            var deg = 360 / len;
 
            var oWrap = document.getElementById("imgwrap");
            // var oWrap=document.querySelector('.wrap');
 
            //页面加载完毕在执行的代码
            window.onload = function () {
                  Array.prototype.forEach.call(oImg, function (ele, index, self) {
                        // 旋转并沿Z轴平移
                        ele.style.transform = "rotateY(" + deg * index + "deg) translateZ(645.75px)";
                        //过渡时间1s
                        ele.style.transition = "1s " + (len - index) * 0.1 + "s";
 
                  });
                  Array.prototype.forEach.call(oImg2, function (ele, index, self) {
                        // 旋转并沿Z轴平移
                        ele.style.transform = "rotateY(" + deg * index + "deg) translateZ(645.75px) translateY(240px)";
                        //过渡时间1s
                        ele.style.transition = "1s " + (len - index) * 0.1 + "s";
 
                  });
                  Array.prototype.forEach.call(oImg3, function (ele, index, self) {
                        // 旋转并沿Z轴平移
                        ele.style.transform = "rotateY(" + deg * index + "deg) translateZ(645.75px) translateY(480px)";
                        //过渡时间1s
                        ele.style.transition = "1s " + (len - index) * 0.1 + "s";
 
                  });
                  // Array.prototype.forEach.call(oImg, function (ele, index, self) {
                  //       // 旋转并沿Z轴平移
                  //       ele.style.transform = "rotateY(" + deg * index + "deg) translateZ(350px)";
                  //       //过渡时间1s
                  //       ele.style.transition = "1s " + (len - index) * 0.1 + "s";
 
                  // });
 
            }
            //翻动3D相册
            var newX, newY, lastX, lastY, minusX, minusY, rotX = -20, rotY = 0;
 
            document.onmousedown = function (e) {
                  // 点击设置初值
                  lastX = e.clientX;
                  lastY = e.clientY;
 
                  this.onmousemove = function (e) {
                        newX = e.clientX;
                        newY = e.clientY;
                        minusX = newX - lastX;
                        minusY = newY - lastY;
 
                        rotX -= minusY * 0.2;
                        rotY += minusX * 0.1;
                        oWrap.style.transform = "rotateX(" + rotX + "deg) rotateY(" + rotY + "deg)";
                        lastX = newX;
                        lastY = newY;
 
                  }
                  this.onmouseup = function (e) {
                        //鼠标松开
                        this.onmousemove = null;//清除鼠标移动
                  }
            }
 
      </script>
</body>
 
</html>
