# RichEditotAndroid
WebView + JavaScript 方式的实现一个android富文本编辑器
>最近产品提出在移动端实现富文本编辑器功能，需要能编辑文字加粗、颜色、插入图片、下划线等一系列功能等，最后要生成一个html格式然后base64转码后上传服务端，最后在前端网页和移动端显示。
关于作者 的 《简书》 主页点击这里：[Android富文本编辑器](https://www.jianshu.com/p/9c2c1416d894)


这里的功能需要根据需求实现，通过insertImage传入一个URL或者本地图片路径都可以，这里用户可以自己调用本地相或者拍照获取图片，传图本地图片路径，也可以将本地图片路径上传到服务器（自己的服务器或者免费的七牛服务器），返回在服务端的URL地址，将地址传如即可（我这里传了一张写死的图片URL，如果你插入的图片不现实，请检查你是否添加网络请求权限<uses-permission android:name="android.permission.INTERNET" />）

![](https://upload-images.jianshu.io/upload_images/3278692-937a13db04c28c9f.gif?imageMogr2/auto-orient/strip)
