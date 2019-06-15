# ChromeHeadlesTest
Detecting Chrome Headless  Copy From intoli
# 小技巧：如何找到chrome对应的chromedriver版本
1、打开chrome输入chrome://version，查看第一行的版本。比如我的是：74.0.3729.169
2、访问网址：https://chromedriver.storage.googleapis.com/LATEST_RELEASE_74.0.3729
  记住“LATEST_RELEASE_”下划线后跟的是第一步看到的版本，需要去掉最后.169
3、你会看到打开第二步网址返回的需要具体下载的chromedriver的版本 比如我的返回是：74.0.3729.6
4、打开 https://chromedriver.storage.googleapis.com/index.html?path=74.0.3729.6/
   记住path后面跟的是第三步的版本号
5、最后出来的便是与本机chrome完全匹配的船新版本的chromedriver，点击下载就是