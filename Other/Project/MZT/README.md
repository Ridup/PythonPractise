#### 关于
功能：爬取www.meizitu.com 整站图片
有多线程版本

#### 使用环境

python3.6+

#### 操作说明
main.py（无多线程）
-------------------
**第一步：**
python3 main.py save_page_url
> 获取页面缩略图url

**第二步：**
python3 main.py save_img_url
> 获取页面缩略图里的图片rul

**第三步：**
python3 main.py save_img_jpg -p [路径]
> 获取图片内容并且保存到文件夹 需要指定路径



**main_thread.py (多线程 不指定线程数 默认为25)**
---------------------
**第一步：**
python3 main.py save_page_url -t [线程数]
> 获取页面缩略图url

**第二步：**
python3 main.py save_img_url -t [线程数]
> 获取页面缩略图里的图片rul

**第三步：**
python3 main.py save_img_jpg -p [路径] -t [线程数]
> 获取图片内容并且保存到文件夹 需要指定路径


#### 注意事项
- 1 . 保持网络畅通 会影响爬取速度
- 2 . 路径格式  如：/home/图片/MZT/
- 3 . 注意从第一步依次执行
- 4 . 可同时执行三操作（必须依次执行）


#### windows10 下正常运行

![第一步](http://qiniu.tencentwl.cn/%5Bwindows%5D%E7%AC%AC%E4%B8%80%E6%AD%A5.png)

![第二步](http://qiniu.tencentwl.cn/%5Bwindwos%5D%E7%AC%AC%E4%BA%8C%E6%AD%A5.png)

![第三步](http://qiniu.tencentwl.cn/%5Bwindows%5D%E7%AC%AC%E4%B8%89%E6%AD%A5.png)
结果图：
![结果图](http://qiniu.tencentwl.cn/%5Bwindows%5D%E7%BB%93%E6%9E%9C%E5%9B%BE.png)

#### ubuntu18.04 下正常运行

![第一步](http://qiniu.tencentwl.cn/[ubuntu]第一步.png)

![第二步](http://qiniu.tencentwl.cn/[ubuntu]第二步.png)

![第三步](http://qiniu.tencentwl.cn/[ubuntu]第三步.png)
结果图：
![结果图](http://qiniu.tencentwl.cn/[ubuntu]结果图.png)


