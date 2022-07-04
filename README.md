## [封装一键登录aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/edit/master/OneClickLogin-release.aar "aar文件")
集成到项目里面,需要将三大运营的aar放进去
## [移动aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/edit/master/quick_login_android_5.9.3.aar "aar文件")
## [电信aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/edit/master/CTAccountSdk_HY_v3.7.6_all.aar "aar文件")
## [联通aar下载](https://raw.githubusercontent.com/zhongruiAndroid/OneClickLogin/edit/master/unicom_login_android_v5.1.0.aar "aar文件")


| 属性                                       | 说明                                                    |
|--------------------------------------------|---------------------------------------------------------|
| statusBarColor                             | 状态栏颜色，默认白色                                    |
| isLightColor                               | 状态栏内容颜色，默认黑色，true:黑，false：白            |
| authLayoutId                               | 授权页layoutId                                          |
| authWindowLayoutId                         | 窗口模式授权页layoutId                                  |
| authPhoneTextId                            | 显示脱敏手机号viewId                                    |
| authPhoneTextColor                         | 脱敏手机号字体颜色                                      |
| authPhoneTextSize                          | 脱敏手机号字体大小                                      |
| authPhoneTextIsBold                        | 脱敏手机号是否加粗                                      |
| authBrandId                                | 运营商标识                                              |
| authLoginId                                | 登录按钮viewId                                          |
| authLoginCompatId(电信专用)                | xml里面设置一个宽高为0的viewId                          |
| authLoginHeight                            | 登录按钮高度                                            |
| authLoginMargin                            | 登录按钮左右边距                                        |
| authLoginBgCheckResId                      | 勾选隐私协议时的登录按钮背景                            |
| authLoginBgUnCheckResId                    | 未勾选隐私协议时的登录按钮背景                          |
| authLoginTextId                            | 需要显示登录文本的viewId                                |
| authLoginText                              | 设置登录文本，如：本机号码一键登录                      |
| authLoginTextColor                         | 登录文本颜色                                            |
| authLoginTextSize                          | 登录文本size                                            |
| authLoginTextIsBold                        | 登录文本是否加粗                                        |
| authAppIconId                              | logo viewId                                             |
| authAppIconResourceId                      | logo资源id                                              |
| authBackId                                 | 返回按钮viewId                                          |
| authBackDrawableId                         | 返回按钮资源id                                          |
| authTitleId                                | 标题id                                                  |
| authTitle                                  | 标题文本                                                |
| authTitleSize                              | 标题文本大小                                            |
| authTitleColor                             | 标题颜色                                                |
| authTitleViewId                            | 标题栏viewId                                            |
| authTitleViewBgColor                       | 标题栏背景                                              |
| authSwitchLoginId                          | 切换账户viewId                                          |
| authSwitchLoginText                        | 切换账户文本，如：其他登录方式                          |
| authSwitchLoginTextColor                   | 切换账户文本颜色                                        |
| authSwitchLoginTextSize                    | 切换账户文本大小                                        |
| authAgreementCheckboxParentId              | 底部授权协议父控件viewId                                |
| authAgreementCheckboxParentMarginBottom    | 底部授权协议父控件距离底部距离                          |
| authAgreementCheckboxParentMarginLeftRight | 底部授权协议父控件左右margin距离                        |
| authAgreementCheckboxId                    | 授权协议checkbox id                                     |
| authAgreementCheckboxWidth                 | 授权协议checkbox宽度                                    |
| authAgreementCheckboxHeight                | 授权协议checkbox高度                                    |
| authAgreementCheckBoxCheckResId            | 授权协议checkbox选中和未选中资源(设置为0，取消默认设置) |
| authAgreementCheckBoxCheckId               | 授权协议checkbox选中时的资源                            |
| authAgreementCheckBoxUnCheckId             | 授权协议checkbox未选中时的资源                          |
| authAgreementCheckboxState                 | 授权协议checkbox默认选中状态                            |
| authAgreementTextId                        | 授权协议TextView的Id                                    |
| authAgreementSeparator                     | 授权协议分隔符                                          |
| authAgreementPrefix                        | 授权协议前缀                                            |
| authAgreementPostfix                       | 授权协议后缀                                            |
| authAgreementTextBaseColor                 | 授权协议非链接的文字颜色                                |
| authAgreementTextColor                     | 授权协议链接的文本颜色                                  |
| authAgreementTextSize                      | 授权协议文本大小                                        |
| useBookTitleMark                           | 授权协议链接文本是否使用“《》”                          |
| authUseAgreementTextUnderLine              | 授权协议链接文本是否加下划线                            |
| authAgreementUnCheckedToastText            | 未选中授权协议checkbox时的登录提示                      |
| authIntoPageActIn authIntoPageActOut       | 授权页进入动画                                          |
| authOutPageActIn authOutPageActOut         | 授权页离开动画                                          |
|             **webview页面设置**            |                                                         |
| privacyAgreementLayoutId                   | 隐私协议网页layoutId                                    |
| privacyAgreementBackId                     | 隐私协议网页返回按钮viewId                              |
| privacyAgreementBackResId                  | 隐私协议网页返回按钮viewId                              |
| privacyAgreementWebViewId                  | 隐私协议网页WebView viewId                              |
| privacyAgreementTitleId                    | 隐私协议网页标题viewId                                  |
| privacyAgreementTitleText                  | 隐私协议网页标题                                        |
| privacyAgreementTitleSize                  | 隐私协议网页标题大小                                    |
| privacyAgreementTitleColor                 | 隐私协议网页标题颜色                                    |
| privacyAgreementProgress                   | 隐私协议网页加载进度条viewId                            |
| privacyAgreementProgressDrawableResId      | 隐私协议网页加载进度条资源Id                            |
| privacyAgreementTitleViewId                | 隐私协议网页标题栏                                      |
| privacyAgreementTitleBgColor               | 隐私协议网页标题栏背景颜色                              |
