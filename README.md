## [封装一键登录aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/master/OneClickLogin-debug.aar "aar文件")
集成到项目里面,需要将三大运营的aar放进去
## [移动aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/master/quick_login_android_5.9.3.aar "aar文件")
## [电信aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/master/CTAccountSdk_HY_v3.7.6_all.aar "aar文件")
## [联通aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/master/unicom_login_android_v5.1.0.aar "aar文件")

 
 | 属性                                       | 说明                                                                                                           |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| statusBarColor                             | 状态栏颜色，默认白色                                                                                           |
| isLightColor                               | 状态栏内容颜色，默认黑色，true:黑，false：白                                                                   |
| authLayoutId                               | 授权页layoutId                                                                                                 |
| authWindowLayoutId                         | 窗口模式授权页layoutId                                                                                         |
| authPhoneTextId                            | 显示脱敏手机号viewId                                                                                           |
| authPhoneTextColor                         | 脱敏手机号字体颜色                                                                                             |
| authPhoneTextSize                          | 脱敏手机号字体大小                                                                                             |
| authPhoneTextIsBold                        | 脱敏手机号是否加粗                                                                                             |
| authBrandId                                | 运营商标识                                                                                                     |
| authLoginId                                | 登录按钮viewId                                                                                                 |
| authLoginCompatId(电信专用)                | xml里面设置一个宽高为0的viewId                                                                                 |
| authLoginHeight                            | 登录按钮高度                                                                                                   |
| authLoginMargin                            | 登录按钮左右边距                                                                                               |
| authLoginBgCheckResId                      | 勾选隐私协议时的登录按钮背景                                                                                   |
| authLoginBgUnCheckResId                    | 未勾选隐私协议时的登录按钮背景                                                                                 |
| authLoginTextId                            | 需要显示登录文本的viewId                                                                                       |
| authLoginText                              | 设置登录文本，如：本机号码一键登录                                                                             |
| authLoginTextColor                         | 登录文本颜色                                                                                                   |
| authLoginTextSize                          | 登录文本size                                                                                                   |
| authLoginTextIsBold                        | 登录文本是否加粗                                                                                               |
| authAppIconId                              | logo viewId                                                                                                    |
| authAppIconResourceId                      | logo资源id                                                                                                     |
| authBackId                                 | 返回按钮viewId                                                                                                 |
| authBackDrawableId                         | 返回按钮资源id                                                                                                 |
| authTitleId                                | 标题id                                                                                                         |
| authTitle                                  | 标题文本                                                                                                       |
| authTitleSize                              | 标题文本大小                                                                                                   |
| authTitleColor                             | 标题颜色                                                                                                       |
| authTitleViewId                            | 标题栏viewId                                                                                                   |
| authTitleViewBgColor                       | 标题栏背景                                                                                                     |
| authSwitchLoginId                          | 切换账户viewId                                                                                                 |
| authSwitchLoginText                        | 切换账户文本，如：其他登录方式                                                                                 |
| authSwitchLoginTextColor                   | 切换账户文本颜色                                                                                               |
| authSwitchLoginTextSize                    | 切换账户文本大小                                                                                               |
| authAgreementCheckboxParentId              | 底部授权协议父控件viewId                                                                                       |
| authAgreementCheckboxParentMarginBottom    | 底部授权协议父控件距离底部距离                                                                                 |
| authAgreementCheckboxParentMarginLeftRight | 底部授权协议父控件左右margin距离                                                                               |
| authAgreementCheckboxId                    | 授权协议checkbox id                                                                                            |
| authAgreementCheckboxWidth                 | 授权协议checkbox宽度                                                                                           |
| authAgreementCheckboxHeight                | 授权协议checkbox高度                                                                                           |
| authAgreementCheckBoxCheckResId            | 授权协议checkbox选中和未选中资源(设置为0，取消默认设置)                                                        |
| authAgreementCheckBoxCheckId               | 授权协议checkbox选中时的资源                                                                                   |
| authAgreementCheckBoxUnCheckId             | 授权协议checkbox未选中时的资源                                                                                 |
| authAgreementCheckboxState                 | 授权协议checkbox默认选中状态                                                                                   |
| authAgreementTextId                        | 授权协议TextView的Id                                                                                           |
| authAgreementSeparator                     | 授权协议分隔符                                                                                                 |
| authAgreementPrefix                        | 授权协议前缀                                                                                                   |
| authAgreementPostfix                       | 授权协议后缀                                                                                                   |
| authAgreementTextBaseColor                 | 授权协议非链接的文字颜色                                                                                       |
| authAgreementTextColor                     | 授权协议链接的文本颜色                                                                                         |
| authAgreementTextSize                      | 授权协议文本大小                                                                                               |
| useBookTitleMark                           | 授权协议链接文本是否使用“《》”                                                                                 |
| authUseAgreementTextUnderLine              | 授权协议链接文本是否加下划线                                                                                   |
| authAgreementUnCheckedToastText            | 未选中授权协议checkbox时的登录提示                                                                             |
| authIntoPageActIn authIntoPageActOut       | 授权页进入动画                                                                                                 |
| authOutPageActIn authOutPageActOut         | 授权页离开动画                                                                                                 |
|            **授权页window模式**            |                                                                                                                |
| windowWidthDp                              | window宽度，单位：dp 可设置WindowManager.LayoutParams.MATCH_PARENT 或者WindowManager.LayoutParams.WRAP_CONTENT |
| windowHeightDp                             | window高度，单位：dp 可设置WindowManager.LayoutParams.MATCH_PARENT 或者WindowManager.LayoutParams.WRAP_CONTENT |
| windowShowBottom                           | true:底部显示，false：居中显示，默认false                                                                      |
|             **webview页面设置**            |                                                                                                                |
| privacyAgreementLayoutId                   | 隐私协议网页layoutId                                                                                           |
| privacyAgreementBackId                     | 隐私协议网页返回按钮viewId                                                                                     |
| privacyAgreementBackResId                  | 隐私协议网页返回按钮viewId                                                                                     |
| privacyAgreementWebViewId                  | 隐私协议网页WebView viewId                                                                                     |
| privacyAgreementTitleId                    | 隐私协议网页标题viewId                                                                                         |
| privacyAgreementTitleText                  | 隐私协议网页标题                                                                                               |
| privacyAgreementTitleSize                  | 隐私协议网页标题大小                                                                                           |
| privacyAgreementTitleColor                 | 隐私协议网页标题颜色                                                                                           |
| privacyAgreementProgress                   | 隐私协议网页加载进度条viewId                                                                                   |
| privacyAgreementProgressDrawableResId      | 隐私协议网页加载进度条资源Id                                                                                   |
| privacyAgreementTitleViewId                | 隐私协议网页标题栏                                                                                             |
| privacyAgreementTitleBgColor               | 隐私协议网页标题栏背景颜色                                                                                     |

#### 设置运营商配置
```java
//初始化
OneClickLoginSDK.get().init(application);
//设置debug模式打印日志
OneClickLoginSDK.get().setDebug(true);
//设置移动配置
OneClickLoginSDK.get().setMobileConfig(appId,appKey);
//设置电信配置
OneClickLoginSDK.get().setTelecomConfig(appId,appSecret);
//设置联通配置
OneClickLoginSDK.get().setUnicomConfig(appId,appSecret);
//三大运营商的配置需要分别去运营商的平台申请
```

#### 设置自定义页面属性
```java
//设置属性
PageConfig config=new PageConfig();
config.authLayoutId=R.layout.layout_custion_login;
config.authAppIconResourceId=R.mipmap.ic_launcher;
//xml里面设置一个宽高为0的viewId(电信专用)
config.authLoginCompatId=R.id.xxx;

//设置授权页隐私协议链接
AgreementItem item = new AgreementItem("服务条款", "https://www.baidu.com");
item.setColor(Color.RED);
//单独设置分隔符，优先级高于authAgreementSeparator属性
item.setSuffixSeparator("和");
config.addAgreement(item);

config.addAgreement(new AgreementItem("隐私条款","https://www.taobao.com"));
...其他属性见上面表格

//isWindow,true:标识window模式下的view设置，false:全屏授权页view设置
OneClickLoginSDK.get().setViewConfig(isWindow,config);
```

#### 预登陆
```java
Operator operator = OneClickLoginSDK.get().getOperator();
MOBILE	：移动
TELECOM	：电信
UNICOM	：联通
UN		：未知
        
//预登陆(移动和电信预登陆一次，后面可以连续登录，联通登录之前必须再预登陆一次)
OneClickLoginSDK.get().preLogin(new OneClickListener() {
@Override
public void success(String securePhoneOrAccessCode, String originData, Operator operator){
	
}
@Override
public void error(String msg) {

}
});
```

#### 登录
```java
//第一个参数控制是全屏模式还是窗口模式

OneClickLoginSDK.get().login(false, new OneClickLoginListener() {
@Override
public void success(String accessCodeOrAccessTokenOrToken, String authCode, String originData,Operator operator) {
//授权成功
}
@Override
public void cancelLogin() {
//取消登录
}
@Override
public void switchLogin() {
//切换账户
}
@Override
public void viewClick(View view) {
//view点击，需要关闭授权页面时，可调用OneClickLoginSDK.get().finishAuthPage();
}
@Override
public void error(String msg) {
//登录错误
}
});


//自动判断登录之前是否需要预登陆
OneClickLoginSDK.get().loginCompat(false,new OneClickLoginListener(){});
```

#### 本机号码认证
```java
OneClickLoginSDK.get().mobileAuth(new OneClickListener() {
@Override
public void success(String securePhoneOrAccessCode, String originData, Operator operator) {
                
}
@Override
public void error(String msg) {

}
});
```

#### 手动退出授权页
```java
OneClickLoginSDK.get().finishAuthPage();
```
