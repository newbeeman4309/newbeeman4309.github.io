<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>侧边导航栏</title>
    <style>
        body{
            margin: 0;/* 外边距 0不用给单位 */
        }
        ul{
            list-style: none;/* 清除小黑圆点 */
            margin: 0;
            padding: 0;/* 内边距 */
        }
        .wrap{
            width: 60px;
            height: 225px;
            border: 0.5px solid;
            position: fixed;      
        }
        .head{
            font-weight: bold;
            width: 60px;
            height: 40px;
            background-color: white;
            line-height: 40px;/* 行高=高度 垂直居中 */
            font-size: 14px;
            color: #000000;/* 文字颜色 白色 */
            text-align: center;/* 文本对齐方式 居中 */
        }
        .list:hover{
            color: tomato;
            background-color: silver;
        }
      
        .list{
            box-sizing: border-box;/* content box css3盒模型 怪异盒 */
            width: 60px;
            padding: 3px;
            margin-top: 0.5px;/* 上边距 */
            margin-bottom: 0.5px;
            background-color: white;
            text-align: center;
            font-size: 12px;
            color: #9A9C9E;
        }
      
    </style>
</head>
<body>
   <div class="wrap">
        <ul>
            <li class="head">热门品牌</li>
            <li class="list"><a href="#m1"style="text-decoration: none;">运动户外</a></li>
            <li class="list"><a href="#m2"style="text-decoration: none;">美妆专区</a></li>
            <li class="list"><a href="#m3"style="text-decoration: none;">个人家清</a></li>
            <li class="list"><a href="#m4"style="text-decoration: none;">奢品馆</a></li>
            <li class="list"><a href="#m5"style="text-decoration: none;">手表配饰</a></li>
            <li class="list"><a href="#m6"style="text-decoration: none;">美食生鲜</a></li>
            <li class="list"><a href="#m7"style="text-decoration: none;">服饰鞋靴</a></li>
            <li class="list"><a href="#m8"style="text-decoration: none;">家居生活</a></li>
        </ul>
   </div>

   <div>
       <h2 id="m1">运动户外</h2>
       锚点
       <div style="height: 800px;"></div>
   </div>

   <div>
       <h2 id="m2">美妆专区</h2>
    锚点
    <div style="height: 800px;"></div>

    <div>
        <h2 id="m3">个人家清</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

    <div>
        <h2 id="m4">奢品馆</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

    <div>
        <h2 id="m5">手表配饰</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

    <div>
        <h2 id="m6">家居生活</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

    <div>
        <h2 id="m7">服饰鞋靴</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

    <div>
        <h2 id="m8">热门品牌</h2>
        锚点
        <div style="height: 800px;"></div>
    </div>

</body>
</html>



<html>
	<body>
		<nav>
			<a href="https://kx-liang.github.io"><b>English</b></a>
			<a href="#introduction"><b>个人简介</b></a>
			<a href="#education"><b>学习经历</b></a>
			<a href="#news"><b>最新消息</b></a>
			<a href="#publication"><b>个人成果</b></a>
			<a href="#honor"><b>荣誉与奖项</b></a>
		</nav>
	</body>
</html>

---

<img src="/introduction in chinese.jpg" width="100%">

---

<h3 id="introduction"> <img src="/biography.jpg" width="18px"> 个人简介</h3>

&emsp;&emsp;本人于2021年7月毕业于广州大学，获得机械设计制造及其自动化学士学位并以推荐免试方式进入广州大学攻读机械设计及理论研究型硕士研究生。在本科阶段，本人以绩点排名专业第一（排位1/168，绩点3.97/5.0）毕业且获得广州大学本科优秀毕业论文；在硕士研究生阶段继续保持严谨、认真的科研态度，截至目前本人研究生课程绩点排名第一（排位1/82，绩点3.99/5.0）。

&emsp;&emsp;本人对拓扑优化、并联机器人、软体机器人及其传感、柔顺机构、机器学习等拥有强烈的兴趣，并已在国际顶级SCI期刊<b><i>Computer Methods in Applied Mechanics and Engineering</i></b>、<b><i>Mechanism and Machine Theory</i></b>等发表研究论文。

---

<h3 id="education"> <img src="/education.jpg" width="18px"> 学习经历</h3>
- 2021.09至今，硕士，广州大学 (排名: 1/82 绩点: 3.99/5.0)
- 2019.08，人工智能与机器人项目，华盛顿大学，西雅图
- 2017.09-2021.07，学士，广州大学 (排名: 1/168 绩点: 3.97/5.0)

---

<h3 id="news"> <img src="/news.jpg" width="18px"> 最新消息</h3>
- 2023.02: 一篇论文被CMAME接收
- 2023.01: 进入新研究领域：机器学习与力学
- 2022.09: 一篇论文投稿至CMAME

---

<h3 id="publication"> <img src="/publication.jpg" width="18px"> 个人成果</h3>

<img src="/journal.jpg" width="18px"> <b>期刊论文</b>

<ul>
  
  <li><p><u><a href="https://www.sciencedirect.com/science/article/pii/S0094114X22003718">Macro-microscale topological design for compliant mechanisms with special mechanical properties</a></u></p>
  <p><b>Kaixian Liang</b>, Dachang Zhu, Fangyi Li</p>
  <p><b><i> Computer Methods in Applied Mechanics and Engineering</i></b></p> 
  <img src="/TO macro-microscale.jpg" width="100%"></li>
  
  <li><p><u><a href="https://www.sciencedirect.com/science/article/pii/S0094114X22003718">Topology optimization of a spatial compliant parallel mechanism based on     constant motion transmission characteristic matrix</a></u></p>
  <p><b>Kaixian Liang</b>, Dachang Zhu, Jie Liu</p>
  <p><b><i>Mechanism and Machine Theory</i></b></p> 
  <img src="/TO parallel mechanism.jpg" width="100%"></li>
  
</ul>


<img src="/conference.jpg" width="18px">  <b>会议论文</b>

- <p><b>K. Liang</b>, D. Zhu, J. Liu, Topology optimization realization of a spatially parallel compliant mechanism with constant motion transmission characteristics, the 42nd ASME 2022 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference, St. Louis, Missouri, August 14-17, 2022.<p>

---

<h3 id="honor"> <img src="/award.jpg" width="18px"> 荣誉与奖项</h3>
- 2022.09 广州大学研究生三等奖学金
- 2021.09 广州大学研究生特等奖学金
- 2021.06 广州大学优秀本科毕业论文
- 2021.02 广州大学本科生三等奖学金
- 2020.09 广州大学本科生二等奖学金
- 2019.09 广州大学本科生一等奖学金
- 2018.09 广州大学本科生一等奖学金




