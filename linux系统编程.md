# linux系统编程

## 第一章操作系统基本知识

### 从unix到linux

![image-20210818150423460](/home/wangjw/.config/Typora/typora-user-images/image-20210818150423460.png)



![image-20210818150453989](/home/wangjw/.config/Typora/typora-user-images/image-20210818150453989.png)



![image-20210818150731543](/home/wangjw/.config/Typora/typora-user-images/image-20210818150731543.png)

### unix/linux体系结构

![image-20210818150918078](/home/wangjw/.config/Typora/typora-user-images/image-20210818150918078.png)

![image-20210818151025890](/home/wangjw/.config/Typora/typora-user-images/image-20210818151025890.png)

![image-20210818151152892](/home/wangjw/.config/Typora/typora-user-images/image-20210818151152892.png)

![image-20210818151305113](/home/wangjw/.config/Typora/typora-user-images/image-20210818151305113.png)

![image-20210818151324474](/home/wangjw/.config/Typora/typora-user-images/image-20210818151324474.png)

![image-20210818151422395](/home/wangjw/.config/Typora/typora-user-images/image-20210818151422395.png)

### 系统调用和库函数

![image-20210818151551632](/home/wangjw/.config/Typora/typora-user-images/image-20210818151551632.png)

![image-20210818151741371](/home/wangjw/.config/Typora/typora-user-images/image-20210818151741371.png)

![image-20210818152002695](/home/wangjw/.config/Typora/typora-user-images/image-20210818152002695.png)

![image-20210818152137740](/home/wangjw/.config/Typora/typora-user-images/image-20210818152137740.png)

![image-20210818152239657](/home/wangjw/.config/Typora/typora-user-images/image-20210818152239657.png)

![image-20210818152531341](/home/wangjw/.config/Typora/typora-user-images/image-20210818152531341.png)



### 文件命令

![image-20210818152811529](/home/wangjw/.config/Typora/typora-user-images/image-20210818152811529.png)

#### ls pwd

![image-20210818152832401](/home/wangjw/.config/Typora/typora-user-images/image-20210818152832401.png)

#### cd mkdir rmdir

![image-20210818153026724](/home/wangjw/.config/Typora/typora-user-images/image-20210818153026724.png)

![image-20210818153053977](/home/wangjw/.config/Typora/typora-user-images/image-20210818153053977.png)

#### cat more less head tail

![image-20210818153151806](/home/wangjw/.config/Typora/typora-user-images/image-20210818153151806.png)

![image-20210818153216069](/home/wangjw/.config/Typora/typora-user-images/image-20210818153216069.png)

![image-20210818153318921](/home/wangjw/.config/Typora/typora-user-images/image-20210818153318921.png)

#### cp rm mv find grep tar

![image-20210818153527254](/home/wangjw/.config/Typora/typora-user-images/image-20210818153527254.png)

![image-20210818153648752](/home/wangjw/.config/Typora/typora-user-images/image-20210818153648752.png)

![image-20210818153829164](/home/wangjw/.config/Typora/typora-user-images/image-20210818153829164.png)

![image-20210818153921054](/home/wangjw/.config/Typora/typora-user-images/image-20210818153921054.png)

![image-20210818153957085](/home/wangjw/.config/Typora/typora-user-images/image-20210818153957085.png)

### 进程控制命令

#### ps

![image-20210818154701531](/home/wangjw/.config/Typora/typora-user-images/image-20210818154701531.png)

#### top

![image-20210818154822654](/home/wangjw/.config/Typora/typora-user-images/image-20210818154822654.png)

#### kill

![image-20210818155258868](/home/wangjw/.config/Typora/typora-user-images/image-20210818155258868.png)

#### killall

![image-20210818155405966](/home/wangjw/.config/Typora/typora-user-images/image-20210818155405966.png)

#### nice

![image-20210818155501053](/home/wangjw/.config/Typora/typora-user-images/image-20210818155501053.png)

#### renice

![image-20210818155624515](/home/wangjw/.config/Typora/typora-user-images/image-20210818155624515.png)

#### 后台运行&

![image-20210818155701772](/home/wangjw/.config/Typora/typora-user-images/image-20210818155701772.png)

#### 进程挂起和恢复

![image-20210818155803263](/home/wangjw/.config/Typora/typora-user-images/image-20210818155803263.png)

### 用户及权限管理类命令

![image-20210818155946593](/home/wangjw/.config/Typora/typora-user-images/image-20210818155946593.png)

![image-20210818160028548](/home/wangjw/.config/Typora/typora-user-images/image-20210818160028548.png)

![image-20210818160040926](/home/wangjw/.config/Typora/typora-user-images/image-20210818160040926.png)

![image-20210818160124043](/home/wangjw/.config/Typora/typora-user-images/image-20210818160124043.png)

![image-20210818160142700](/home/wangjw/.config/Typora/typora-user-images/image-20210818160142700.png)

#### 用户管理命令

##### useradd

![image-20210818160230899](/home/wangjw/.config/Typora/typora-user-images/image-20210818160230899.png)

##### passwd

![image-20210818160317739](/home/wangjw/.config/Typora/typora-user-images/image-20210818160317739.png)

##### usermod

![image-20210818160355626](/home/wangjw/.config/Typora/typora-user-images/image-20210818160355626.png)

##### userdel

![image-20210818160432895](/home/wangjw/.config/Typora/typora-user-images/image-20210818160432895.png)

##### su

![image-20210818160518026](/home/wangjw/.config/Typora/typora-user-images/image-20210818160518026.png)

##### id 

![image-20210818160534287](/home/wangjw/.config/Typora/typora-user-images/image-20210818160534287.png)

#### 用户组管理命令

##### groupadd

![image-20210818160627360](/home/wangjw/.config/Typora/typora-user-images/image-20210818160627360.png)

##### groupmod

![image-20210818160645691](/home/wangjw/.config/Typora/typora-user-images/image-20210818160645691.png)

##### groupdel

![image-20210818160730771](/home/wangjw/.config/Typora/typora-user-images/image-20210818160730771.png)

#### 文件权限

![image-20210818160803823](/home/wangjw/.config/Typora/typora-user-images/image-20210818160803823.png)

![image-20210818160816971](/home/wangjw/.config/Typora/typora-user-images/image-20210818160816971.png)

![image-20210818160846297](/home/wangjw/.config/Typora/typora-user-images/image-20210818160846297.png)

##### chmod

![image-20210818161043097](/home/wangjw/.config/Typora/typora-user-images/image-20210818161043097.png)

##### chown

![image-20210818161110100](/home/wangjw/.config/Typora/typora-user-images/image-20210818161110100.png)

##### chgrp

![image-20210818161140058](/home/wangjw/.config/Typora/typora-user-images/image-20210818161140058.png)

### 编译与调试

![image-20210818161759019](/home/wangjw/.config/Typora/typora-user-images/image-20210818161759019.png)

![image-20210818161903058](/home/wangjw/.config/Typora/typora-user-images/image-20210818161903058.png)

![image-20210818161918307](/home/wangjw/.config/Typora/typora-user-images/image-20210818161918307.png)

![image-20210818162028209](/home/wangjw/.config/Typora/typora-user-images/image-20210818162028209.png)

##### 调试

![image-20210818162100261](/home/wangjw/.config/Typora/typora-user-images/image-20210818162100261.png)

![image-20210818162259743](/home/wangjw/.config/Typora/typora-user-images/image-20210818162259743.png)

![image-20210818162328637](/home/wangjw/.config/Typora/typora-user-images/image-20210818162328637.png)

![image-20210818162347781](/home/wangjw/.config/Typora/typora-user-images/image-20210818162347781.png)

![image-20210818162401559](/home/wangjw/.config/Typora/typora-user-images/image-20210818162401559.png)

![image-20210818162416107](/home/wangjw/.config/Typora/typora-user-images/image-20210818162416107.png)

## 第三章进程与线程

### 进程在内核中的组织

![image-20210812161520869](/home/wangjw/.config/Typora/typora-user-images/image-20210812161520869.png)

![image-20210812161625479](/home/wangjw/.config/Typora/typora-user-images/image-20210812161625479.png)

![image-20210812161746093](/home/wangjw/.config/Typora/typora-user-images/image-20210812161746093.png)

![image-20210812161920429](/home/wangjw/.config/Typora/typora-user-images/image-20210812161920429.png)

![image-20210812161936503](/home/wangjw/.config/Typora/typora-user-images/image-20210812161936503.png)

![image-20210812162139450](/home/wangjw/.config/Typora/typora-user-images/image-20210812162139450.png)

![image-20210812162208830](/home/wangjw/.config/Typora/typora-user-images/image-20210812162208830.png)

![image-20210812162709344](/home/wangjw/.config/Typora/typora-user-images/image-20210812162709344.png)

![image-20210812162807598](/home/wangjw/.config/Typora/typora-user-images/image-20210812162807598.png)

![image-20210812163101129](/home/wangjw/.config/Typora/typora-user-images/image-20210812163101129.png)

![image-20210812163243720](/home/wangjw/.config/Typora/typora-user-images/image-20210812163243720.png)

### 进程属性

![image-20210812164201059](/home/wangjw/.config/Typora/typora-user-images/image-20210812164201059.png)

![image-20210812164832705](/home/wangjw/.config/Typora/typora-user-images/image-20210812164832705.png)

![image-20210812165022475](/home/wangjw/.config/Typora/typora-user-images/image-20210812165022475.png)

#### 赋予可执行文件root权限

![image-20210812165420596](/home/wangjw/.config/Typora/typora-user-images/image-20210812165420596.png)

### 进程生命周期

![image-20210812165810896](/home/wangjw/.config/Typora/typora-user-images/image-20210812165810896.png)

![image-20210812170001283](/home/wangjw/.config/Typora/typora-user-images/image-20210812170001283.png)

![image-20210812170242745](/home/wangjw/.config/Typora/typora-user-images/image-20210812170242745.png)

![image-20210812170630093](/home/wangjw/.config/Typora/typora-user-images/image-20210812170630093.png)

![image-20210812170927415](/home/wangjw/.config/Typora/typora-user-images/image-20210812170927415.png)

![image-20210812171059511](/home/wangjw/.config/Typora/typora-user-images/image-20210812171059511.png)

![image-20210812171339207](/home/wangjw/.config/Typora/typora-user-images/image-20210812171339207.png)

#### atexit示例代码

![image-20210812172034949](/home/wangjw/.config/Typora/typora-user-images/image-20210812172034949.png)

#### on_exit示例

![image-20210812172255783](/home/wangjw/.config/Typora/typora-user-images/image-20210812172255783.png)

### 进程环境

![image-20210818133859124](/home/wangjw/.config/Typora/typora-user-images/image-20210818133859124.png)

![image-20210818133922434](/home/wangjw/.config/Typora/typora-user-images/image-20210818133922434.png)

![image-20210818134253405](/home/wangjw/.config/Typora/typora-user-images/image-20210818134253405.png)

![image-20210818134523373](/home/wangjw/.config/Typora/typora-user-images/image-20210818134523373.png)

![image-20210818134635954](/home/wangjw/.config/Typora/typora-user-images/image-20210818134635954.png)

![image-20210818134659128](/home/wangjw/.config/Typora/typora-user-images/image-20210818134659128.png)

### 创建进程

![image-20210818134840048](/home/wangjw/.config/Typora/typora-user-images/image-20210818134840048.png)

![image-20210818134915105](/home/wangjw/.config/Typora/typora-user-images/image-20210818134915105.png)

![image-20210818135026147](/home/wangjw/.config/Typora/typora-user-images/image-20210818135026147.png)



![image-20210818135307127](/home/wangjw/.config/Typora/typora-user-images/image-20210818135307127.png)



![image-20210818135707430](/home/wangjw/.config/Typora/typora-user-images/image-20210818135707430.png)



![image-20210818135746209](/home/wangjw/.config/Typora/typora-user-images/image-20210818135746209.png)



![image-20210818135932069](/home/wangjw/.config/Typora/typora-user-images/image-20210818135932069.png)



![image-20210818140015728](/home/wangjw/.config/Typora/typora-user-images/image-20210818140015728.png)



![image-20210818140130119](/home/wangjw/.config/Typora/typora-user-images/image-20210818140130119.png)



![image-20210818140257809](/home/wangjw/.config/Typora/typora-user-images/image-20210818140257809.png)

### 获知子进程运行状态的改变

![image-20210818140456126](/home/wangjw/.config/Typora/typora-user-images/image-20210818140456126.png)



![image-20210818140614999](/home/wangjw/.config/Typora/typora-user-images/image-20210818140614999.png)



![image-20210818140744108](/home/wangjw/.config/Typora/typora-user-images/image-20210818140744108.png)



![image-20210818141047021](/home/wangjw/.config/Typora/typora-user-images/image-20210818141047021.png)



![image-20210818141105045](/home/wangjw/.config/Typora/typora-user-images/image-20210818141105045.png)



![image-20210818141246978](/home/wangjw/.config/Typora/typora-user-images/image-20210818141246978.png)



![image-20210818141415625](/home/wangjw/.config/Typora/typora-user-images/image-20210818141415625.png)



![image-20210818141520447](/home/wangjw/.config/Typora/typora-user-images/image-20210818141520447.png)



![image-20210818141720620](/home/wangjw/.config/Typora/typora-user-images/image-20210818141720620.png)



![image-20210818141906095](/home/wangjw/.config/Typora/typora-user-images/image-20210818141906095.png)



### 在进程中运行可执行文件

![image-20210818142119880](/home/wangjw/.config/Typora/typora-user-images/image-20210818142119880.png)



![image-20210818142452346](/home/wangjw/.config/Typora/typora-user-images/image-20210818142452346.png)



#### exec类函数

![image-20210818142632251](/home/wangjw/.config/Typora/typora-user-images/image-20210818142632251.png)

![image-20210818142900283](/home/wangjw/.config/Typora/typora-user-images/image-20210818142900283.png)

![image-20210818142842456](/home/wangjw/.config/Typora/typora-user-images/image-20210818142842456.png)

![image-20210818142914700](/home/wangjw/.config/Typora/typora-user-images/image-20210818142914700.png)

![image-20210818143118890](/home/wangjw/.config/Typora/typora-user-images/image-20210818143118890.png)

![image-20210818143149557](/home/wangjw/.config/Typora/typora-user-images/image-20210818143149557.png)

![image-20210818143425397](/home/wangjw/.config/Typora/typora-user-images/image-20210818143425397.png)

![image-20210818143441375](/home/wangjw/.config/Typora/typora-user-images/image-20210818143441375.png)

### linux 线程控制

![image-20210818143730444](/home/wangjw/.config/Typora/typora-user-images/image-20210818143730444.png)



![image-20210818143916456](/home/wangjw/.config/Typora/typora-user-images/image-20210818143916456.png)



![image-20210818144027707](/home/wangjw/.config/Typora/typora-user-images/image-20210818144027707.png)



![image-20210818144159041](/home/wangjw/.config/Typora/typora-user-images/image-20210818144159041.png)



![image-20210818144320902](/home/wangjw/.config/Typora/typora-user-images/image-20210818144320902.png)



![image-20210818144429568](/home/wangjw/.config/Typora/typora-user-images/image-20210818144429568.png)



![image-20210818144539080](/home/wangjw/.config/Typora/typora-user-images/image-20210818144539080.png)



![image-20210818144652151](/home/wangjw/.config/Typora/typora-user-images/image-20210818144652151.png)



![image-20210818144928046](/home/wangjw/.config/Typora/typora-user-images/image-20210818144928046.png)



![image-20210818145041108](/home/wangjw/.config/Typora/typora-user-images/image-20210818145041108.png)



![image-20210818145122585](/home/wangjw/.config/Typora/typora-user-images/image-20210818145122585.png)



![image-20210818145238829](/home/wangjw/.config/Typora/typora-user-images/image-20210818145238829.png)



![image-20210818145335802](/home/wangjw/.config/Typora/typora-user-images/image-20210818145335802.png)



![image-20210818145530904](/home/wangjw/.config/Typora/typora-user-images/image-20210818145530904.png)



![image-20210818145650635](/home/wangjw/.config/Typora/typora-user-images/image-20210818145650635.png)
