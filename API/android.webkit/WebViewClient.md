# WebViewClient

## shouldOverrideUrlLoading
```java
public boolean shouldOverrideUrlLoading(WebView view, 
                WebResourceRequest request)
返回 true 当前WebView终止加载
返回 false 当前WebView照常加载



note:怎样才会触发该回调
1.js导航
2.用户点击链接
3.http重定向

```
