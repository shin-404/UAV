<h1 style="text-align:center">社交型无人机</h1>
<hr/>
<p>这是一个轻量级的无人机项目，主要部件是一个网络收发器、控制器以及各种传感器。 </p>
<p>目前的设想是使用5G的快速传输来实现无延时的控制和图像传输。</p>
<p><del>过几天再把相关的部分写上</del>还是现在写一点吧。</p>
<br/>
<h1>硬件部分</h2>
<hr/>
<p>我们采用的是基于乐鑫
   <a href="https://www.espressif.com/">esp32</a>
  芯片的esp32-cam和采用全志
   <a href="http://www.allwinnertech.com/index.php?c=product&a=index&id=73">F1C100s</a>
  芯片的
   <a href="http://nano.lichee.pro/">荔枝派Nano</a>
  。
</p>
<p>esp32-cam用于图传和取代接收机，荔枝Nano用于主要的传感器参数接收和初步加工，二者使用I2C协议进行通信。</p>
<p>还没想好接下来怎么写，那就下一部分吧。</p>
<h2>软件部分</h2>
<hr/>
<p>esp32我们选用的是Arduino IDE，使用的是官方的固件，以后有机会可以用一下microPython来写。<br/>荔枝派就直接使用Ubuntu来编译一个系统。</p>
<p>
  这里推荐一篇傻瓜级的
    <a href="https://www.cnblogs.com/chengchen/p/12725056.html">教程</a>
  真的是手把手教刷系统，当然要是更精进的话就要访问一下
    <a href="https://whycan.com/">哇酷社区</a>
  。
</p>
