# [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
#### App Store 审核指南

<div class="column first">
	<ol class="toc">
		<li><a href="#terms-conditions">Terms and conditions</a></li>
		<li><a href="#functionality">Functionality</a></li>
		<li><a href="#metadata">Metadata</a></li>
		<li><a href="#location">Location</a></li>
		<li><a href="#push-notifications">Push Notifications</a></li>
		<li><a href="#game-center">Game Center</a></li>
		<li><a href="#advertising">Advertising</a></li>
		<li><a href="#trademarks-trade-dress">Trademarks and trade dress</a></li>
		<li><a href="#media-content">Media content</a></li>
		<li><a href="#user-interface">User interface</a></li>
		<li><a href="#purchasing-currencies">Purchasing and currencies</a></li>
		<li><a href="#scraping-aggregation">Scraping and aggregation</a></li>
		<li><a href="#damage-device">Damage or injury</a></li>
		<li><a href="#personal-attacks">Personal attacks</a></li>
		<li><a href="#violence">Violence</a></li>
		<li><a href="#objectionable-content">Objectionable content</a></li>
		<li><a href="#privacy">Privacy</a></li>
		<li><a href="#pornography">Pornography</a></li>
		<li><a href="#religion-culture-ethnicity">Religion, culture, and ethnicity</a></li>
		<li><a href="#contests">Contests, sweepstakes, lotteries, raffles, and gambling</a></li>
		<li><a href="#charities-contributions">Charities and contributions</a></li>
		<li><a href="#legal-requirements">Legal requirements</a></li>
		<li><a href="#wallet">Wallet</a></li>
		<li><a href="#kids-category">Kids Category</a></li>
		<li><a href="#extensions">Extensions</a></li>
		<li><a href="#homekit">HomeKit</a></li>
		<li><a href="#healthkit">HealthKit and Human Subject Research</a></li>
		<li><a href="#testflight">TestFlight</a></li>
		<li><a href="#apple-pay">Apple Pay</a></li>
	</ol>
</div>


<h2 id="terms-conditions"></h2>
>## 1. Terms and conditions 条款和条件

1.1 As a developer of Apps for the App Store you are bound by the terms of the Program License Agreement (PLA), Human Interface Guidelines (HIG), and any other licenses or contracts between you and Apple. The following rules and examples are intended to assist you in gaining acceptance for your App in the App Store, not to amend or remove provisions from any other agreement.

为App Store开发应用程序，开发者必须遵守程序许可协议(PLA)、人机交互指南(HIG),以及开发者和苹果公司签订的任何许可协议和合同，以下规则和示例旨在帮助你通过AppStore的审核，而不是修改或删除任何其他协议的条款。


<h2 id="functionality"></h2>
>## 2. Functionality 功能

2.1 Apps that crash will be rejected

崩溃的应用程序将会被拒绝。

2.2 Apps that exhibit bugs will be rejected

存在bug的应用程序将会被拒绝。

2.3 Apps that do not perform as advertised by the developer will be rejected

跟开发者宣传不符的应用程序将会被拒绝。

2.4 Apps that include undocumented or hidden features inconsistent with the description of the App will be rejected

无应用文档或者隐藏功能与描述不符的应用程序将会被拒绝。

2.5 Apps that use non-public APIs will be rejected

使用非公开API的应用程序将会被拒绝。

2.6 Apps that read or write data outside its designated container area will be rejected

在指定容器范围外读写数据的应用程序将会被拒绝。

2.7 Apps that download code in any way or form will be rejected

以任何方式或形式下载代码的应用程序将会被拒绝。

2.8 Apps that install or launch other executable code will be rejected

安装或运行其他可执行代码的应用程序将会被拒绝。

2.9 Apps that are "demo", "trial", or "test" versions will be rejected. Beta Apps may only be submitted through TestFlight and must follow the TestFlight guidelines

demo、trial和test等版本将会被拒绝。Beta版只能通过TestFlight提交而且必须遵循TestFight指南。

2.10 iPhone Apps must also run on iPad without modification, at iPhone resolution, and at 2X iPhone 3GS resolution

iPhone应用程序必须不经过修改就能以iPhone分辨率和2倍的iPhone 3GS的分辨率（iPhone 3GS的分辨率为480x320像素）在iPad上运行。

2.11 Apps that duplicate Apps already in the App Store may be rejected, particularly if there are many of them, such as fart, burp, flashlight, and Kama Sutra Apps

与App Store已有应用重复的应用程序可能会被拒绝，尤其是数量很多的情况下例如：fart, burp, flashlight, and Kama Sutra 等类型的APPs。

2.12 Apps that are not very useful, unique, are simply web sites bundled as Apps, or do not provide any lasting entertainment value may be rejected

有用性不显著、不独特的应用程序或者与网站简单捆绑或者不提供持久娱乐价值的应用程序可能会被拒绝

2.13 Apps that are primarily marketing materials or advertisements will be rejected

主要用于营销或广告的应用程序将会被拒绝

2.14 Apps that are intended to provide trick or fake functionality that are not clearly marked as such will be rejected

提供欺骗或虚假功能，却没没有明确标示的应用程序将会被拒绝

2.15 Apps larger than 100MB in size will not download over cellular networks (this is automatically prohibited by the App Store)

大于100MB无法
通过蜂窝网络下载的应用程序（App Store会自动禁止）

2.16 Multitasking Apps may only use background services for their intended purposes: VoIP, audio playback, location, task completion, local notifications, etc.

多任务应用程序使用后台服务仅限与几种目的：VoIP(Voice over Internet Protocol),音频播放，地理位置，完成任务以及本地提醒等。

2.17 Apps that browse the web must use the iOS WebKit framework and WebKit Javascript
应用程序只允许使用iOS WebKit框架和Webkit Javascript浏览web内容。

2.18 Apps that encourage excessive consumption of alcohol or illegal substances, or encourage minors to consume alcohol or smoke cigarettes, will be rejected

鼓励酗酒或使用违禁药物，或引诱青少年饮酒的应用程序都会被拒绝。

2.19 Apps that provide incorrect diagnostic or other inaccurate device data will be rejected

提供错误的系统诊断或设备数据的应用程序将会被拒绝。

2.20 Developers "spamming" the App Store with many versions of similar Apps will be removed from the iOS Developer Program

向App store上传大量相似版本应用程序的开发者会从iOS开发者计划中除名

2.21 Apps that are simply a song or movie should be submitted to the iTunes store. Apps that are simply a book should be submitted to the iBooks Store

简单的歌曲或者影片应用程序应该提交到iTunes store，书籍类应用程序应该提交到iBooks Store。

2.22 Apps that arbitrarily restrict which users may use the App, such as by location or carrier, may be rejected

任意地根据环境（如定位或者运营商）限制用户使用的应用程序会被拒绝。

2.23 Apps must follow the iOS Data Storage Guidelines or they will be rejected。

应用程序必须遵守iOS数据存储指南（iOS Data Storage Guidelines），否则会被拒绝。

2.24 Apps that are offered in Newsstand must comply with schedules 1, 2 and 3 of the Program License Agreement or they will be rejected

存放在Newsstand的应用程序必须遵守开发者程序许可协议（PLA）的表1,表2以及表3，否则将会被拒绝。

2.25 Apps that display Apps other than your own for purchase or promotion in a manner similar to or confusing with the App Store will be rejected

类似App Store基于购买或者推广的目的而展示其他的应用程序，将会被拒绝

2.26 Apps may display and recommend apps other than your own only if the collection is designed for a specific approved need (e.g. health management, aviation, accessibility, etc.) or provides significant added value for a specific group of customers, or they will be rejected


只有应用程序的采集是出于特殊审核需求时（比如：健康管理、航空以及无障碍需求等）或为特定的客户群体提供显着的附加价值，应用才可以展示和推荐自身以外的程序，否则应用将会被拒绝。

2.27 If your app’s core functionality doesn’t work with the Siri remote it will be rejected. The app may, however, provide enhanced functionality in connection with a game controller or other peripheral

如果你的应用程序的核心功能并不能与Siri远程使用将被拒绝。然而，应用程序可以提供与游戏控制器或其他外设连接的增强功能

<h2 id="metadata"></h2>

>## 3.Metadata (name, descriptions, ratings, rankings, etc.)
>###元数据(名字，描述，分级，等级，etc.)

3.1 Apps or metadata that mentions the name of any other mobile platform will be rejected

应用程序或者元数据中提到其他任何移动平台将会被拒。

3.2 Apps with placeholder text will be rejected

带有占位符的应用程序将会被拒绝

3.3 Apps with names, descriptions, screenshots, or previews not relevant to the content and functionality of the App will be rejected

名称、描述、截图或预览中有与应用程序内容和功能不相关的信息的应用程序将会被拒绝

3.4 App names in iTunes Connect and as displayed on a device should be similar, so as not to cause confusion

为了不混淆用户，iTunes Connect中应用程序名称应该和展示在设备上的应用程序名称一致

3.5 Small and large App icons should be similar, so as not to cause confusion

不同尺寸的应用程序图标要一致，否则会造成混淆

3.6 Apps with App icons, screenshots, previews, and images displayed when an Apple TV app is in the top shelf of the Apple TV home screen that do not adhere to the 4+ age rating will be rejected

应用程序图标、截图、预览和Apple TV应用程序在Apple TV屏幕上显示的图像不符合4+年龄评级的应用将会被拒绝。

3.7 Apps with Category and Genre selections that are not appropriate for the App content will be rejected

应用程序的类别和类型选择与应用程序的内容不符将会被拒绝。

3.8 Developers are responsible for assigning appropriate ratings to their Apps. Inappropriate ratings may be changed/deleted by Apple

开发者有责任为其应用程序指定适当的评级，不恰当的评级可能会被苹果公司修改或删除

3.9 Developers are responsible for assigning appropriate keywords for their Apps. Inappropriate keywords may be changed/deleted by Apple

开发者有责任为其应用程序指定适当的关键字。不恰当的关键词可能会被苹果公司修改或删除

3.10 Developers who attempt to manipulate or cheat the user reviews or chart ranking in the App Store with fake or paid reviews, or any other inappropriate methods will be removed from the iOS Developer Program

试图操纵或者欺骗用户评级，伪造或者付费评级，以及有其他不适当的行为的开发者将会从iOS开发者计划中除名

3.11 Apps that recommend that users restart their iOS device prior to installation or launch may be rejected

在安装下载之前推荐用户重启iOS设备的应用程序会被拒绝

3.12 Apps should have all included URLs fully functional when you submit it for review, such as support and privacy policy URLs

在提交审核过程中，应用程序应包含正常运作的URL，例如提供支持的网址和隐私政策网址

3.13 Apps with screenshots, previews, and marketing text that do not clearly identify supplemental content or items that must be purchased separately (e.g. using IAP) will be rejected

应用程序的截图、预览和营销文本中没有明确的补充内容或条款指明要额外单独购买的内容(例如 使用IAP(Internet服务提供者))，那么程序将会被拒绝

3.14 App previews may only use video screen captures of the app, voice-overs, and textual and design overlays, or the app will be rejected

应用程序预览仅可以使用从应用捕获的视频屏幕，旁白和文本以及设计覆盖，否则应用将会被拒绝

3.15 App previews may only use video screen captures of the app, voice-overs, and textual and design overlays, or the app will be rejected

应用程序的预览展示未经许可的真人个人信息将会被拒绝

3.16 App previews may only include music that is licensed for that purpose in all selected territories

应用程序预览仅可以包含所有选定地区内经过授权许可用于此目的的音乐

3.17 App previews and screenshots that include content played or streamed via the app (e.g. music, video, and related cover art) that is not licensed for use in the preview or screenshots will be rejected

应用程序预览和截图包含未经许可用于预览和截图的通过app播放或加载的内容（例如 音乐，视频和相关的艺术封面），将会被拒绝

<h2 id="Location"></h2>
>## 4. Location 定位

4.1 Apps that do not notify and obtain user consent before collecting, transmitting, or using location data will be rejected

应用程序在不通知和获得用户同意前，收集，发送，或使用位置数据的应用程序将会被拒绝

4.2 Apps that use location-based APIs for automatic or autonomous control of vehicles, aircraft, or other devices will be rejected

使用基于位置API来的自动或自主控制的车辆，飞机或其他设备的应用程序将会被拒绝

4.3 Apps that use location-based APIs for emergency services will be rejected

使用基于位置API的应急服务应用程序将会被拒绝

4.4 Location data can only be used when directly relevant to the features and services provided by the App to the user or to support approved advertising uses

位置数据仅可以用于当直接相关的功能和服务提供的应用程序，或者用于授权使用的广告用途

<h2 id="push-notifications"></h2>
>## 5. Push Notifications 推送通知

5.1  Apps that provide Push Notifications without using the Apple Push Notification (APN) API will be rejected

不使用苹果推送通知（APN)API提供推送通知的应用程序将会被拒绝

5.2 Apps that use the APN service without obtaining a Push Application ID from Apple will be rejected

使用APN服务没有从苹果获得应用程序ID的应用程序将会被拒绝

5.3 Apps that send Push Notifications without first obtaining user consent, as well as apps that require Push Notifications to function, will be rejected

推送通知没有首先获得用户授权以及没有请求推送功能，将会被拒绝

5.4 Apps that send sensitive personal or confidential information using Push Notifications will be rejected

使用推送通知发送个人敏感或机密信息的应用程序将被拒绝

5.5 Apps that use Push Notifications to send unsolicited messages, or for the purpose of phishing or spamming will be rejected

应用程序使用推送通知发送非请求消息或用于钓鱼或发送垃圾邮件用途的应用程序将会被拒绝

5.6 Apps cannot use Push Notifications to send advertising, promotions, or direct marketing of any kind

应用程序不能使用推送通知发送广告、促销或任何类型的直接营销

5.7 Apps cannot charge users for use of Push Notifications

应用程序不能向使用推送通知服务的用户收取费用

5.8 Apps that excessively use the network capacity or bandwidth of the APN service or unduly burden a device with Push Notifications will be rejected

使用 推送通知会过度利用APN服务的网络流量或带宽给设备带来过度负担的应用程序将会被拒绝

5.9 Apps that transmit viruses, files, computer code, or programs that may harm or disrupt the normal operation of the APN service will be rejected

发送病毒、文件、计算机代码，或可能损害或破坏的APN服务的正常运行的应用程序将会被拒绝

<h2 id="game-center"></h2>
>## 6. Game Center 游戏中心

6.1 Apps that display any Player ID to end users or any third party will be rejected

向终端用户或者任意第三方显示玩家ID的应用程序将会被拒绝

6.2 Apps that use Player IDs for any use other than as approved by the Game Center terms will be rejected

将玩家ID用于任何未经游戏中心条款批准用途的应用程序将会被拒绝

6.3 Developers that attempt to reverse lookup, trace, relate, associate, mine, harvest, or otherwise exploit Player IDs, aliases, or other information obtained through Game Center will be removed from the iOS Developer Program

试图进行反向搜索、跟踪、关联、挖掘、获得或者利用玩家ID、别名或通过游戏中心获得其他信息的开发者将会被iOS开发者计划除名

6.4 Game Center information, such as Leaderboard scores, may only be used in Apps approved for use with Game Center

游戏中心信息（例如 排行榜分数）只能通过游戏中心用于应用中。

6.5 Apps that use the Game Center service to send unsolicited messages, or for the purpose of phishing or spamming will be rejected

使用游戏中心服务发送非请求消息或者用于钓鱼或发送垃圾邮件的应用将会被拒绝

6.6 Apps that excessively use the network capacity or bandwidth of Game Center will be rejected

使用游戏中心过度占用网络流量或带宽的应用程序将会被拒绝

6.7 Apps that transmit viruses, files, computer code, or programs that may harm or disrupt the normal operation of the Game Center service will be rejected

发送病毒，文件，计算机代码，或程序，可能会损害或破坏游戏中心服务的正常运行的应用程序将会被拒绝

<h2 id="Advertising"></h2>
>## 7. Advertising 广告

7.1 Apps that artificially increase the number of impressions or click-throughs of ads will be rejected

人工刷浏览量或者广告点击率的应用程序将会被拒绝

7.2 Apps that contain empty iAd banners will be rejected

包含空iAd广告横幅的应用程序将会被拒绝

7.3 Apps that are designed predominantly for the display of ads will be rejected

主要设计的目的在于显示广告的应用程序将会被拒绝

>## 8. Content and Intellectual Property Rights 内容与知识产权

8.1 Apps must comply with all terms and conditions explained in the Guidelines for Using Apple Trademarks and Copyrights and the Apple Trademark List

应用程序必须遵守<<苹果商标和版权使用指南>>(Guidelines for Using Apple Trademarks and Copyrights)和<<苹果商标列表>>( Apple Trademark List)说明中的所有条款与条件

8.2 Apps that suggest or infer that Apple is a source or supplier of the App, or that Apple endorses any particular representation regarding quality or functionality will be rejected

任何提示或暗示苹果公司是该应用程序的来源或者提供商，或者苹果公司以任何形式表示认可其质量或者功能的应该程序将会被拒绝

8.3 Apps that appear confusingly similar to an existing Apple product, interface, or advertising theme will be rejected

与目前存在的苹果产品，界面，或者广告主题相似或混淆的应用程序将会被拒绝

8.4 Apps that misspell Apple product names in their App name (i.e., GPS for Iphone, iTunz) will be rejected
在应用程序名称中将苹果产品名称拼错的应用程序(例如,GPS for IPhone，iTunz)将会被拒绝

8.5 Apps may not use protected third party material such as trademarks, copyrights, patents or violate 3rd party terms of use. Authorization to use such material must be provided upon request

使用受保护的第三方材料(例如 商标,版权,专利)或者违反第三方条款，在申请时必须提供该材料的授权

8.6 Apps that include the ability to download music or video content from third party sources (e.g. YouTube, SoundCloud, Vimeo, etc) without explicit authorization from those sources will be rejected

应用程序包含能下载的音乐或视频内容来自第三方提供的资源(例如 YouTube,SoundCloud,Vimeo, etc)没有这些资源的明确授权将会被拒绝

>## 9. Media content 媒体内容

9.1 Apps that do not use the MediaPlayer framework to access media in the Music Library will be rejected

不使用媒体播放器框架(MediaPlayer Framework)获取音乐库中媒体内容的应用程序将会被拒绝

9.2 App user interfaces that mimic any iPod or iTunes interface will be rejected

用户界面模仿任何iPod界面的应用程序将会被拒绝

9.3 Audio streaming content over a cellular network may not use more than 5MB over 5 minutes

通过蜂窝网络传输的音频流内容每5分钟内不得超过5MB

9.4 Video streaming content over a cellular network longer than 10 minutes must use HTTP Live Streaming and include a baseline 192 kbps or lower HTTP Live stream

通过蜂窝网络传输超过10钟的视频流内容需要使用HTTP流媒体直播,并包含一个基准线为192kbps的音频或者更低的HTTP流媒体直播

>## 10. User interface 用户界面

10.1 Apps must comply with all terms and conditions explained in the applicable Apple Human Interface Guidelines:

应用程序必须遵守苹果的<<人机交互界面指南>>中的所有条款和条件:

>iOS Human Interface Guidelines </br>iOS 人机交互界面指南

>OS X Human Interface Guidelines</br>OS X 人机交互界面指南

>Apple TV Human Interface Guidelines</br> Apple TV 人机交互界面指南

>Apple Watch Human Interface Guidelines</br> Apple Watch 人机交互界面指南

10.2 Apps that look similar to Apps bundled on iOS or Watch OS devices, including the App Store, iTunes Store, and iBooks Store, will be rejected

应用程序外观与iOS或者Watch OS设备的自带应用(例如 App Store、iTunes Store和iBook Store)相似将会被拒绝

10.3 Apps that do not use system provided items, such as buttons and icons, correctly and as described in the Apple iOS Human Interface Guidelines may be rejected

未能按苹果<<iOS 人机交互界面指南>>中的描述正确使用系统提供的部件(例如 按钮、图标)的应用将会被拒绝

10.4 Apps that create alternate desktop/home screen environments or simulate multi-App widget experiences will be rejected

创造多桌面/主屏幕环境或者模拟multi-App插件体验的应用程序将会被拒绝

10.5 Apps that alter the functions of standard switches, such as the Volume Up/Down and Ring/Silent switches, will be rejected

修改音量大小和铃声/静音开关等标准开关功能的应用程序将会被拒绝

10.6 Apple and our customers place a high value on simple, refined, creative, well thought through interfaces. They take more work but are worth it. Apple sets a high bar. If your user interface is complex or less than very good, it may be rejected

苹果和我们的客户高度推崇简单、精致、富有创造性以及经过精心设计的界面。虽然需要付出更多，但却非常值得。苹果设立了很高的门槛。如果你的用户界面太过复杂或者水准不高，可能会被拒绝

10.7 Watch Apps whose primary function is telling time will be rejected

主要功能是看时间的Watch Apps将会被拒绝

>## 11. Purchasing and currencies 购买与货币

11.1 Apps that unlock or enable additional features or functionality with mechanisms other than the App Store will be rejected

使用App Store以外的渠道解锁或开启附加属性和功能的应用程序将会被拒绝

11.2 Apps utilizing a system other than the In-App Purchase API (IAP) to purchase content, functionality, or services in an App will be rejected

使用In-App Purchase API(IAP)以外的系统购买内容、功能或服务的应用软件将会被拒绝。

11.3 Apps using IAP to purchase physical goods or goods and services used outside of the App will be rejected

使用IAP购买的应用程序之外的实物商品或商品和服务的应用程序将会被拒绝

11.4 Apps that use IAP to purchase credits or other currencies must consume those credits within the App

应用程序使用IAP购买积分或者其他的货币必须在本应用程序中消费

11.5 Apps that use IAP to purchase credits or other currencies that expire will be rejected

使用IAP购买已过期积分或者其他货币的应用程序将会被拒绝

11.6 Content subscriptions using IAP must last a minimum of 7 days and be available to the user from all of their iOS devices

使用IAP订阅的内容至少要持续7天，而且允许在用户的其他iOS设备间共享

11.7 Apps that use IAP to purchase items must assign the correct Purchasability type

应用程序使用IAP购买项目必须分派到正确的购买类型中。

11.8 Apps that use IAP to purchase access to built-in capabilities provided by iOS, watchOS, and tvOS, such as the camera or the gyroscope, or Apple-branded peripherals, such as Apple Pencil or Apple Keyboard, will be rejected

使用IAP购买iOS,watchOS, and tvOS,内置功能(如照相机，陀螺仪,苹果品牌外设 例如 苹果铅笔或苹果键盘)的应用程序将会被拒绝。

11.9 Apps containing content or services that expire after a limited time will be rejected, except for specific approved content (e.g. films, television programs, music, books)

包含超过限定时间的内容或服务的应用程序将会被拒绝，除了特殊批准的内容(比如films、电视节目音乐以及书籍)

11.10 Insurance Apps must be free, in legal-compliance in the regions distributed, and cannot use IAP

保险类应用程序必须免费，遵守发布地区的法律，并且不能使用IAP

11.11 In general, the more expensive your App, the more thoroughly we will review it

一般而言,你的应用程序越贵,我们的审核越彻底

11.12 Apps offering subscriptions must do so using IAP, Apple will share the same 70/30 revenue split with developers for these purchases, as set forth in the Program License Agreement

提供订阅功能的应用必须使用IAP，苹果将会按照 Developer Program License Agreement 中的约定与开发者按30/70比例分成。

11.13 Apps that link to external mechanisms for purchases or subscriptions to be used in the App, such as a "buy" button that goes to a web site to purchase a digital book, will be rejected

在应用内使用跳转至外部购买或订阅链接的应用将会被拒,比如“buy”按钮跳转至一个购买电子书的web页面

11.14 Apps can read or play approved content (specifically magazines, newspapers, books, audio, music, video and cloud storage) that is subscribed to or purchased outside of the App, as long as there is no button or external link in the App to purchase the approved content. Apple will only receive a portion of revenues for content purchased inside the App

只要应用内没有跳转至外部购买、订阅的按钮或链接，苹果允许这些应用读取或展示经批准的、在应用外购买或订阅内容(特别是杂志、报纸、书籍、音频、音乐、视频以及云存储内容)。苹果只能通过应用程序内的购买获得一部分收益。

11.15 Apps may only use auto-renewing subscriptions for periodicals (newspapers, magazines), business Apps (enterprise, productivity, professional creative, cloud storage), and media Apps (video, audio, voice), or the App will be rejected

应用程序可以只使用自动更新订阅期刊(报纸、杂志)、商业应用程序(企业类、效率类、专业创意类以及云存储类)和媒体应用程序(视频、音频、声音)，否则应用程序将被拒绝。

11.16 Apps may enable additional approved features or functionality when used in combination with specific approved physical products (such as a toy) as long as the additional features and functionality are either completely dependent on such hardware (for example an App that is used to control a telescope) or also available through the App without the physical products, such as by way of reward for achievement or by use of IAP

当与特定的经过审核的实体产品（比如玩具）结合使用时，应用程序可以使用获得批准的附件功能，只要附加功能完全依赖于该硬件产品（比如一款用于控制望远镜的应用程序）或者也可以在不使用实物产品的情况下使用应用程序，比如作为成功的奖励或者使用IAP。

11.17 Apps may facilitate transmission of approved virtual currencies provided that they do so in compliance with all state and federal laws for the territories in which the app functions

如果应用程序功能遵照各州和联邦法律，那么应用程序可以用来促进被认可的虚拟货币的流通。

>## 12. Scraping and aggregation 抓取与整合

12.1 Apps that scrape any information from Apple sites (for example from apple.com, iTunes Store, App Store, iTunes Connect, Apple Developer Programs, etc.) or create rankings using content from Apple sites and services will be rejected

从苹果网站（例如apple.com、iTunes Store、App Store、iTunes Connect以及Apple Developer Programs等）抓取任何信息或者使用苹果网站内容和服务进行排名的应用程序将会被拒绝。

12.2 Apps may use approved Apple RSS feeds such as the iTunes Store RSS feed

应用软件可以使用获得批准的苹果RSS feeds，例如iTunes Store RSS feeds。

12.3 Apps that are simply web clippings, content aggregators, or a collection of links, may be rejected

应用程序是简单的网页剪辑，内容聚合，或收集的链接，可能会被拒绝


>## 13. Damage or injury 损害或伤害

13.1 Apps that encourage users to use an Apple Device in a way that may cause damage to the device will be rejected

怂恿用户以可能造成损害的方式使用苹果设备的应用软件将会被拒绝。

13.2 Apps that rapidly drain the device's battery or generate excessive heat will be rejected

快速耗光设备电量或产生过多热量的应用软件将会被拒绝。

13.3 Apps whose use may result in physical harm may be rejected

能导致用户人身伤害的app将会被拒绝


>## 14. Personal attacks 人身攻击

14.1 Any App that is defamatory, offensive, mean-spirited, or likely to place the targeted individual or group in harm's way will be rejected

涉及诽谤、人身攻击性质以及内容狭隘卑鄙的应用软件或者打击特定个人或组织的应用软件将会被拒绝。

14.2 Professional political satirists and humorists are exempt from the ban on offensive or mean-spirited commentary

职业政治讽刺家和幽默作家不受这一条款约束。

14.3 Apps that display user generated content must include a method for filtering objectionable material, a mechanism for users to flag offensive content, and the ability to block abusive users from the service
 
 app凡是带有可随用户自行产生内容的,必须包含内容过滤功能,或者用户自行标记屏蔽功能,以及拉黑功能

>## 15. Violence 暴力

15.1 Apps portraying realistic images of people or animals being killed or maimed, shot, stabbed, tortured or injured will be rejected

应用程序中出现人或动物被杀、致残以及枪击、刺伤、拷打等受伤情形的真实画面
将会被拒绝。

15.2 Apps that depict violence or abuse of children will be rejected

出现描绘暴力或虐待儿童等内容的应用程序将会被拒绝。

15.3 "Enemies" within the context of a game cannot solely target a specific race, culture, a real government or corporation, or any other real entity

游戏中出现的“敌人”不可指向一个特定种族、文化、一个真实存在的政府、企业或者其他任何现实中的实体。

15.4 Apps involving realistic depictions of weapons in such a way as to 
encourage illegal or reckless use of such weapons will be rejected

对武器进行真实描述以怂恿非法使用或滥用这些武器的应用程序将会被拒绝。

15.5 Apps that include games of Russian roulette will be rejected

包含俄罗斯轮盘赌博内容的游戏将会被拒。


>## 16. Objectionable content 负面内容

16.1Apps that present excessively objectionable or crude content will be rejected

应用程序中出现过于令人反感或者低俗的内容将会被拒绝。

16.2 Apps that are primarily designed to upset or disgust users will be rejected

在设计上激怒用户或令人感到厌恶的应用程序将会被拒绝。

>## 17. Privacy 隐私

17.1 Apps cannot transmit data about a user without obtaining the user's prior permission and providing the user with access to information about how and where the data will be used

在未经用户事先许可，或未告知用户如何使用信息，在何处使用信息的情况下，应用程序不能传输用户数据。

17.2 Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected

要求用户提供电子邮箱地址和出生日期等私人信息才可使用其功能的应用程序将会被拒绝。

17.3Apps may ask for date of birth (or use other age-gating mechanisms) only for the purpose of complying with applicable children's privacy statutes, but must include some useful functionality or entertainment value regardless of the user's age

仅出于遵守适用的儿童隐私法规的目的，应用程序可以要求用户的出生日期(或者使用其他age-gating机制)，但是必须包括一些有用的功能或者娱乐价值，不管用户年龄大小。

17.4 Apps that collect, transmit, or have the capability to share personal information (e.g. name, address, email, location, photos, videos, drawings, the ability to chat, other personal data, or persistent identifiers used in combination with any of the above) from a minor must comply with applicable children's privacy statutes, and must include a privacy policy

应用程序收集、传输以及分享未成年用户个人信息(比如名字、地址、邮件、位置、照片、视频、绘画、聊天以及其他个人数据，或者与以上所述相关的永久性标示符)必须遵守应用儿童隐私法规，并且必须包含隐私条款。

17.5 Apps that include account registration or access a user’s existing account must include a privacy policy or they will be rejected

包含账号注册或者访问用户现有账号的应用程序必须包含隐私策略，否则将会被拒绝。

>## 18. Pornography 色情

18.1 Apps containing pornographic material, defined by Webster's Dictionary as "explicit descriptions or displays of sexual organs or activities intended to stimulate erotic rather than aesthetic or emotional feelings", will be rejected

含有色情素材，也就是《韦氏词典》中定义的“旨在激发情欲，对性器官或性行为的明确描述或展示，而无关美学或情绪感受”的程序将会被拒绝。

18.2 Apps that contain user generated content that is frequently pornographic (e.g. "Chat Roulette" Apps) will be rejected

用户频繁提供生成色情内容的应用程序(比如以前的Chat Roulette程序)将会被拒绝。

>## 19. Religion, culture, and ethnicity 宗教、文化和种族

19.1 Apps containing references or commentary about a religious, cultural or ethnic group that are defamatory, offensive, mean-spirited or likely to expose the targeted group to harm or violence will be rejected

涉及宗教、文化或种族群体的引用或评论包含诽谤性、攻击性或狭隘内容，或会使特定群体遭受伤害或暴力的应用程序将会被拒绝。

19.2 Apps may contain or quote religious text provided the quotes or translations are accurate and not misleading. Commentary should be educational or informative rather than inflammatory

程序可以包含或引用宗教经文，程序所提供的引用或翻译必须准确且不会引起误导。评论应该有教育意义，可以令人开阔眼界，而不应有煽动性。

>## 20. Contests, sweepstakes, lotteries, raffles, and gambling
>#### 竞赛，抽奖，奖券，抽奖，赌博

20.1 Sweepstakes and contests must be sponsored by the developer/company of the App
赌博和竞赛必须由应用程序的开发者或者app所属公司发起。20.2Official rules for sweepstakes and contests must be presented in the App and make it clear that Apple is not a sponsor or involved in the activity in any manner

应用程序必须展示赌博和竞赛的正式规则，并声明苹果不是发起者，也没有以任何方式参与活动。

20.3 It must be permissible by law for the developer to run a lottery App, and a lottery App must have all of the following characteristics: consideration, chance, and a prize

开发者运营一款具有抽奖性质的应用必须经过法律允许，并且抽奖应用必须具备以下特征：报酬、机会以及奖品。

20.4 Apps that allow a user to directly purchase a raffle ticket in the App will be rejected

允许用户在应用中直接购买彩票或彩券的应用将会被拒。

20.5 Apps that offer real money gaming (e.g. sports betting, poker, casino games, horse racing) or lotteries must have necessary licensing and permissions in the locations where the App is used, must be restricted to those locations, and must be free on the App Store

提供真钱游戏(比如体育博彩、扑克牌、赌场游戏以及赛马)的应用程序必须有应用使用区当地必要的许可和允许，必须限制在这些区域，必须可以从App Store免费下载。

20.6 Apps that use IAP to purchase credit or currency to use in conjunction with real money gaming will be rejected

使用IAP购买信誉或者货币，且结合真钱游戏的应用将会被拒绝。

>## 21. Charities and contributions 慈善与捐助

21.1 Apps that include the ability to make donations to recognized charitable organizations must be free

包含可以向已认证的慈善组织捐赠功能的应用程序必须是免费的。

21.2 The collection of charitable donations must be done via a web site in Safari or an SMS

捐赠款项的募集必须通过Safari浏览器访问web页面或是手机短消息完成。

>## 22. Legal requirements 法律要求

22.1 Apps must comply with all legal requirements in any location where they are made available to users. It is the developer's obligation to understand and conform to all local laws

应用程序必须遵守所有发布地区当地法律，开发者有义务了解并遵守所有当地法

22.2 Apps that contain false, fraudulent or misleading representations or use names or icons similar to other Apps will be rejected

包含虚假，欺诈或误导性陈述的程序将会被拒绝。

22.3 Apps that solicit, promote, or encourage criminal or clearly reckless behavior will be rejected

任何招徕、促进或鼓励犯罪或明显鲁莽行为的程序将会被拒绝。

22.4 Apps that enable illegal file sharing will be rejected
支持非法文件共享的程序将会被拒绝。

22.5 Apps that are designed for use as illegal gambling aids, including card counters, will be rejected

被设计用以非法赌博工具的应用程序(包括点算牌)将会被拒绝。

22.6Apps that enable anonymous or prank phone calls or SMS/MMS messaging will be rejected
具有匿名或恶作剧拨打电话或发送类似短信/彩信功能的程序将会被拒绝。

22.7 Developers who create Apps that surreptitiously attempt to discover user passwords or other private user data will be removed from the iOS Developer Program

任何开发暗中收集用户密码或用户私人数据程序的开发者将会从iOS开发者计划中除名。

22.8 Apps that contain DUI checkpoints that are not published by law enforcement agencies, or encourage and enable drunk driving, will be rejected

包含非法律执行部分发布的DUI检查点信息，或者怂恿/协助酒后驾车的应用将会被拒绝。

22.9 Apps that calculate medicinal dosages must be submitted by the manufacturer of those medications or recognized institutions such as hospitals, insurance companies, and universities
 
任何计算药用剂量的应用必须提交药品制造商或者认可机构(比如医院、保险公司以及高校)。

22.10 Apps that use iTunes music previews in an unauthorized manner will be rejected

在未授权的情况下使用iTunes音乐预览的应用程序将会被拒绝。

>## 23. Wallet 钱包

23.1 Wallet passes can be used to make or receive payments, transmit offers, or offer identification (such as movie tickets, airline tickets, coupons and reward offers). Other uses may result in the rejection of the App and the revocation of Wallet credentials

钱包通行证可用于支付或接收付款，发送优惠，或提供识别（如电影票，机票，优惠券和奖励提供）。用于其他用途的应用程序可能会遭到拒绝和撤销的钱包证书

23.2 Passes must include valid contact information from the issuer of the pass or the App will be rejected and Wallet credentials may be revoked

Passes必须包含有效的pass发行人有效的联系资料，否则app将会被拒绝，并且Passbook证书也会被取消。

23.3 Passes must be signed by the entity that will be distributing the pass under its own name, trademark, or brand or the App will be rejected and Passbook credentials may be revoked

Passes必须经过实体签名，并基于其名字、商标或者品牌进行分发，否则应用程序将会被拒绝，而Passbook证书也可能会被撤销。

>## Kids Category 儿童类

24.1Apps in the Kids Category must include a privacy policy and must comply with applicable children's privacy statutes

主要供儿童使用的应用程序必须包含隐私政策，必须适用于应用程序的儿童隐私法。

24.2 Apps in the Kids Category may not include behavioral advertising (e.g. the advertiser may not serve ads based on the user's activity within the App), and any contextual ads presented in the App must be appropriate for kids

主要供儿童使用的应用程序不允许包括行为广告（比如基于用户app内部活动的广告），任何在应用程序中展示的上下文广告必须适合儿童。

24.3 Apps in the Kids Category must get parental permission or use a parental gate before allowing the user to link out of the app or engage in commerce

主要供儿童使用的应用程序必须得到家长许可或使用parental gate才能链接至应用程序外部或进行交易。

24.4Apps in the Kids Category must be made specifically for kids ages 5 and under, ages 6-8, or ages 9-11

儿童类别中的应用程序必须标明“5岁以下，6-8岁或者9-11岁”。

>## 25. Extensions 扩展

25.1 Apps hosting extensions must comply with the App Extension Programming Guide

 包含扩展的应用程序必须遵照 App Extension Programming Guide要求。

 25.2Apps hosting extensions must provide some functionality (help screens, additional settings) or they will be rejected

 包含扩展的应用程序必须提供某些功能（辅助屏幕，附加设置）否则将会被拒绝。

 25.3Apps hosting extensions that include marketing, advertising, or in-app purchases in their extension view will be rejected

如果扩展的视图中包含营销推广、广告或者IAP内容，那么包含该扩展的应用将会被拒绝。

25.4 Keyboard extensions must provide a method for progressing to the next keyboard

键盘扩展必须提供一个切换至下个键盘的方法。

25.5 Keyboard extensions must remain functional with no network access or they will be rejected
 键盘扩展必须具有离线访问功能，否则将会被拒绝。

25.6 Keyboard extensions must provide Number and Decimal keyboard types as described in theApp Extension Programming Guide or they will be rejected

键盘扩展必须提供和 App Extension Programming Guide 描述一致的数字和十进键盘类型，否则将会被拒绝。

25.7 Apps offering Keyboard extensions must have a primary category of Utilities and a privacy policy or they will be rejected

提供键盘扩展的应用必须拥有基本的功能分类和隐私政策，否则将会被拒绝。

25.8 Apps offering Keyboard extensions may only collect user activity to enhance the functionality of their keyboard extension on the iOS device or they may be rejected

提供键盘扩展的应用程序只允许收集用户活动以增强键盘扩展在iOS设备上的功能，否则将会被拒绝。

>##26. HomeKit 

26.1 Apps using the HomeKit framework must have a primary purpose of providing home automation services

使用HomeKit框架的应用程序必须有提供家庭自动化服务的主要目的。

26.2 Apps using the HomeKit framework must indicate this usage in their marketing text and they must provide a privacy policy or they will be rejected

使用HomeKit框架的应用程序必须在营销文本中说明用途，同时必须提供隐私政策，否则将会被拒绝。

26.3 Apps must not use data gathered from the HomeKit APIs for advertising or other use-based data mining

应用程序不允许将从HomeKitAPI收集的数据用于广告宣传或者其他基于使用的数据挖掘。  

26.4 Apps using data gathered from the HomeKit API for purposes other than improving the user experience or hardware/software performance in providing home automation functionality will be rejected

出于其他目的使用从HomeKitAPI收集的数据，而不是用于提高用户体验或者家庭自动化功能中硬件/软件性能，这类应用将会被拒绝。

>## 27. HealthKit and Human Subject Research HealthKit和人的主体性研究

27.1 Apps using the HealthKit framework or conducting human subject research for health purposes, such as through the use of ResearchKit, must comply with applicable law for each Territory in which the App is made available, as well as Sections 3.3.28 and 3.3.39 of the iOS Developer Program License Agreement

使用HealthKit框架的应用程序必须遵守其所在区域的适用法律，以及iOS Developer Program License Agreement中的3.3.28和3.39条款。

27.2 Apps that write false or inaccurate data into HealthKit will be rejected

将虚假或者错误的数据写入HealthKit的应用程序将会被拒绝。

27.3  Apps using the HealthKit framework that store users’ health information in iCloud will be rejected

使用HealthKit框架iCloud中储存用户健康信息的应用程序将会被拒绝。

27.4 Apps may not use or disclose to third parties user data gathered from the HealthKit API or from health-related human subject research for advertising or other use-based data mining purposes other than improving health, or for the purpose of health research

research应用程序不允许将通过HealthKit API收集的用户数据用作广告宣传或者基于使用的数据挖掘目的，除了改善健康、医疗、健康管理以及医学研究目的。

27.5 Apps that share user data acquired via the HealthKit API with third parties without user consent will be rejected

未经用户许可与第三方分享通过HealthKit API获得的用户数据的应用程序将会被拒绝。 

27.6 Apps using the HealthKit framework must indicate integration with the Health app in their marketing text and must clearly identify the HealthKit functionality in the app’s user interface

使用HealthKit框架的应用程序必须在营销文本中说明集成了Health app，同时必须在app用户界面清楚阐释HealthKit功能。

27.7 Apps using the HealthKit framework or conducting human subject research must provide a privacy policy or they will be rejected

使用HealthKit框架的应用程序必须提供隐私政策，否则将会被拒绝。

27.8 Apps that provide diagnoses, treatment advice, or control hardware designed to diagnose or treat medical conditions that do not provide written regulatory approval upon request will be rejected

提供诊断、治疗建议或者控制硬件以诊断或者治疗疾病的应用，若没有根据要求提供书面的监管审批，将会被拒绝。

27.9 Apps conducting health-related human subject research must obtain consent from participants or, in the case of minors, their parent or guardian. Such consent must include the (a) nature, purpose, and duration of the research; (b) procedures, risks, and benefits to the participant; (c) information about confidentiality and handling of data (including any sharing with third parties); (d) a point of contact for participant questions; and (e) the withdrawal process

应用关于人类健康的研究必须得到参与者的同意或是未成年人的父母或监护人的同意，包括
	
	(1) 性质，目的和研究的时间期限；
	(2) 程序，风险和参与者的利益；
	(3) 信息的保密以及数据的处理（包括与第三方共享信息）；
	(4) 参与者问题联系
	(5) 退出过程。

27.10 Apps conducting health-related human subject research must secure approval from an independent ethics review board. Proof of such approval must be provided upon request.

应用关于人类健康相关的研究必须得到伦理审查委员会的同意并提供证明。


>## 28. TestFlight

28.1 Apps may only use TestFlight to beta test apps intended for public distribution and must comply with the full App Review Guidelines

应用程序仅能使用TestFlight对以公开发布为目的的应用进行beta版测试，且必须遵守完整的App Review Guidelines。

28.2 Apps using TestFlight must be submitted for review whenever a build contains material changes to content or functionality

当版本中包含的内容或功能有重大变化时，使用TestFlight的应用程序必须提交审核。

28.3 Apps using TestFlight may not be distributed to testers in exchange for compensation of any kind

使用TestFlight的应用程序不允许分发给测试者，以作为任何形式的补偿。


>## 29. Apple Pay

29.1 Apps using Apple Pay must provide all material purchase information to the user prior to sale of any good or service or they will be rejected; Apps using Apple Pay to offer recurring payments must, at a minimum, disclose the length of the renewal term and the fact that it will continue until canceled, what will be provided during each period, the charges that will be billed to the customer, and how to cancel.

使用Apple Pay的应用程序必须在出售任何商品或者服务之前为用户提供所有材料的购买信息，否则将会被拒绝。


29.2 Apps using Apple Pay must use Apple Pay branding and user interface elements correctly and as described in the Apple Pay Identity Guidelines or they will be rejected

使用Apple Pay的应用程序必须正确使用 Apple Pay Human Interface Guidelines 中的Apple Pay标识和用户界面元素，否则将会被拒绝。

29.3 Apps using Apple Pay as a purchasing mechanism may not offer goods or services that violate the law of any territory in which the good or service will be delivered and may not be used for any illegal purpose

使用Apple Pay的应用程序不能提供触犯任何领域范围法律的用于交付的商品或者服务，也不能用作任何非法目的。

29.4 Apps using Apple Pay must provide a privacy policy or they will be rejected

使用Apple Pay的应用程序必须提供隐私政策，否则将会被拒绝。

29.5 Apps using Apple Pay may only share user data acquired via Apple Pay with third parties when provided to facilitate or improve delivery of goods and services or to comply with legal requirements

只有为了促进或提高商品和服务的交付，或者依照法律要求，使用Apple Pay的应用程序才能与第三方分享通过Apple Pay获得的数据。

