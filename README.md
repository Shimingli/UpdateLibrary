# UpdateLibrary(No AndroidX) 不是安卓X的版本

* [jitpack官网_https://jitpack.io](https://jitpack.io/)

* [GitHub+jitpack生成自己的Compile依赖](https://blog.csdn.net/DeMonliuhui/article/details/78066784)

* 不是AndroidX的版本
* UpdateApkFileProvider 继承是android.support.v4.content.FileProvider
```
    //V1.5.0 不是AndroidX的版本
    api 'com.github.Shimingli:UpdateLibrary:V1.5.0'
```

[![](https://jitpack.io/v/Shimingli/UpdateLibrary.svg)](https://jitpack.io/#Shimingli/UpdateLibrary)




* 是AndroidX的版本
```
    //是AndroidX的版本
    api 'com.github.Shimingli:UpdateLibrary:V1.5.0'
```
* UpdateApkFileProvider 继承是androidx.core.content.FileProvider