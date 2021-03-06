## 打印不出或不完整
有多种原因可以导致：

### 喷嘴脏、干燥
干燥的表现：
打印的颜色部分或全部缺失。

解决方法：哈气、用纸巾擦拭、长按清洗，其中哈气和长按清洗建议每次打印前都操作，连续打印除外。  
喷嘴挂墨比较多、粘了毛发等脏物时，需要用纸巾擦拭。  
（哈气的时候，最好用手指遮挡一下传感器，防止透镜起雾。）
<video width="100%" controls poster="video/dry1.png"><source src="video/dry1.mp4" type="video/mp4"></video>

如果以上方法效果有限，或者有效时间越来越短，则建议使用方法：泡水。  
刚泡完，颜色部分会很浅，多打印几次即可恢复。
<video width="100%" controls poster="video/dry2.png"><source src="video/dry2.mp4" type="video/mp4"></video>
泡水前：
<img style="max-width:100%;" src="img/dry2.1.jpg">
泡水后：
<img style="max-width:100%;" src="img/dry2.2.jpg">
甚至可以用注射器从墨盒上方，撕开贴纸后，三个颜色各注入少量纯净水。（完成后要贴回贴纸，不要贴歪封死透气槽。）  
HP 原装墨盒墨水浓度很高，容易堵喷头，泡水、加水可以缓解。

环境温度低、空气干燥的季节、场合或地区，喷嘴更容易干燥，哈气可以提升喷嘴的温度和湿度，另外 APP 设置页面可以尝试把驱动强度调大一些，并写入打印机。

打印机不用的时候，要及时合上底座，减少暴露在空气中蒸发水分。
合上底座时，要取下纹身支架，否则底座橡胶无法紧密贴合墨盒喷头：  
<img style="max-width:100%;" src="img/b1.jpg">  
可以考虑如此放置：  
<img style="max-width:100%;" src="img/b2.jpg">

### 墨水用尽
这种情况，通常是缺少三个颜色中的某一个颜色，判断的方法是，用纸巾前后方向擦拭喷嘴，看纸巾上三个颜色出墨量是否相当。  
<img style="max-width:100%;" src="img/tissue.jpg">

### 电量过低
请关机充电半小时再尝试。

### 接触不良好
接触不良的表现：
打印的画面中出现横条、画面有锯齿、1/2 或 1/4 处某个或多个颜色缺失：  
<img style="max-width:100%;" src="img/conn_b.jpg">
<img style="max-width:100%;" src="img/conn_a.png">
<img style="max-width:100%;" src="img/conn_c.png">

1. 检查透明门是否关到位：

<video width="100%" controls poster="video/conn1.png"><source src="video/conn1.mp4" type="video/mp4"></video>

<img style="max-width:100%;" src="img/conn1.png">  

2. 重新安装墨盒
3. 用橡皮擦擦拭墨盒接触点
4. 是否曾经用力过猛，安装墨盒的时候把排线扯出来一部分

<video width="100%" controls poster="video/conn2.png"><source src="video/conn2.mp4" type="video/mp4"></video>

如果以上都尝试无效，联络售后安排反修。

### 墨盒过期
墨盒背面有激光打印的截止使用日期，此日期只适用於 HP 原装墨盒。  
实验判断：用纸巾前后方向擦拭喷嘴，一种或多种颜色非常黏稠，出墨非常少，且泡水改善不大。  
<img style="max-width:100%;" src="img/tissue2.jpg">


### 打印表面过于光滑
现象：移动距离远远大于打印长度，绿灯也不灭，没有打印出画面或画面拉伸。
（画面拉伸也有可能是移动速度过快，过快会有蜂鸣器声音提示。）  
<img style="max-width:100%;" src="img/stretch.jpg">

打印机位置检测基于鼠标光电传感器，在表面反光或者特别细腻的表面检测不灵敏，如果有需要在这些场合打印，可以使用配套的黑卡尺。

极少数情况，光电传感器初始化异常，检测不到物体，重新开关机可以解决。


## WiFi 连接问题
WiFi 连接不上或者打不开 APP：

1. 可以重新开关打印机电源，再进行尝试。

2. 电量过低，请关机充电半小时再尝试。

3. 如果正常连接打印机 WiFi，但打不开 APP:

  1. 如果通过扫描二维码打开 APP，请确保二维码扫描程序是否可以离线使用，iOS 系统相机 APP 可以，Android 则需要第三方可离线使用的二维码扫描程序（IM 软件内置的扫描功能通常不支持离线使用）。也可以手动在浏览器中输入地址 `192.168.44.1`。

  2. Android 系统在 WiFi 不可以访问外网的时候，可能会自动切换使用移动网络，此时无法访问已经连接的打印机 WiFi 网络，可以关闭手机自动切换移动网络的功能，一个测试的方法是，连上打印机 WiFi 之后，如果还能访问常用网站，则代表当前已切换使用移动网络，可以临时关闭移动网络来测试打印机。

  3. 手机浏览器不支持新的 HTML5 特性，通常是手机很多年没有更新系统浏览器，或者是改动比较大的 Android 手机（譬如中国大陆的 Android 手机），如果 Android 自带的浏览器不能正常打开或使用 APP，建议安装 Firefox 浏览器进行测试。（已确认可以使用的浏览器有：Firefox、Chrome 和 Safari。）

4. WiFi 配置被修改，且不记得，可以在打开电源开关之后的五秒内长按打印键，直到兩側白燈閃爍，將恢復 WiFi 默認名稱及密碼。

5. 如果以上操作之后，手机连接打印机 WiFi 时，持续提示密码出错，或者一尝试连接就断开。基本可以判断是 WiFi 硬件频偏的问题，可以换新机。只有 2019 年发货的小部分机器存在此问题。

### 点击「打印」提示「正在加载，请稍后再试」
因为默认方法使用 APP，每次打开 APP 都要从打印机下载一个 3M 多的程序，如果 WiFi 环境拥堵，会导致下载缓慢，因此出现这个提示。  
如果经常遇到，又不想等待，请参考说明书中「软件离线操作」章节，把 APP 安装到桌面，以后通过点击桌面 APP 图标启动即可。

## 颜色异常
1. 墨盒有两种颜色顺序，如果默认设置与当前墨盒不符合，会导致红色和黄色调换的问题，在 APP 设置页面更改颜色顺序后，再重新传输图案到打印机即可。

2. 墨盒喷头芯片有两种宽度，如果默认设置与当前墨盒不符合，会导致打印出来的画面颜色错位 0.4mm，不是很明显。

3. 墨盒不使用的时候，不可以简单的把喷嘴保护膜贴回，或把墨盒放回墨盒包装，会因为虹吸现象导致三种墨水被吸出并混合，构成桥梁，最终导致墨盒内部颜色混色。

4. 墨盒干燥泡水的时候，放置在桌面时间不易过长，否则也有机会导致混色。

### 墨盒颜色校准
在设置页面，调整 3 个颜色的滑条，调整方法：如果当下打印出来的红色比重偏多，则设置页面把红色保持最大，把蓝色和黄色调小。其它颜色同理。  
对比色差建议不要对比显示器，因为显示器的颜色有一些在纸上是表达不出来的，可以试试普通的桌面彩色打印机，打印同样画面到纸上以做对比。

## 在不吸水表面打印
在玻璃、金属、塑胶表面打印，喷出来的墨水会结合成小墨珠，且一擦就掉。
解决方法是使用液态文具胶水，先在物件表面用海绵涂薄薄一层，等风干了之后（可以用热风加快），再打印即可。
如果想进一步防水和防擦，可再用手摇透明漆（清漆）喷一层保护层。

