# AppPyramid

本仓库是用来整理 Android & iOS 移动应用开发的技术架构。

## 内容概览

### 1.IDE 与开发语言

|No.|Android|iOS
|---|---|---
|1|Android Studio|Xcode/AppCode

|No.|Android|iOS
|---|---|---
|1|Java/Kotlin/C/C++/JavaScript/HTML/Dart|Objective-C/Swift/C/C++/JavaScript/HTML

### 2.框架模式

|No.|Android|iOS
|---|---|---
|1|MVC|MVC
|2|MVP|MVP
|3|MVVM|MVVM
|4|-|Viper

### 3.第三方库

<table border="0">
<tr>
<td style="text-align:center;font-size:12pt" rowspan="2">Library</td>
<td style="text-align:center;font-size:12pt" colspan="2">Android</td>
<td style="text-align:center;font-size:12pt" colspan="2">iOS</td>
</tr>
<tr>
<td style="text-align:center;font-size:12pt">Java</td>
<td style="text-align:center;font-size:12pt">Kotlin</td>
<td style="text-align:center;font-size:12pt">Objective-C</td>
<td style="text-align:center;font-size:12pt">Swift</td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Log</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/orhanobut/logger">Logger <SUP>2.2.0</SUP></a></td>
<td style="text-align:left;font-size:12pt">TBD</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/CocoaLumberjack/CocoaLumberjack">CocoaLumberjack <SUP>3.4.2</SUP></a></td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/SwiftyBeaver/SwiftyBeaver">SwiftyBeaver <SUP>1.6.0</SUP></a></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Network</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/square/retrofit">Retrofit <SUP>2.4.0</SUP><br>✅ <a href="https://github.com/roths/GlideWebpSupport">GlideWebpSupport <SUP></SUP><br>✅ <a href="https://github.com/2coffees1team/GlideToVectorYou">GlideToVectorYou <SUP>1.1.0</SUP><br>✅ <a href="https://github.com/bumptech/glide">Glide <SUP>4.8.0</SUP></a></td>
<td style="text-align:left;font-size:12pt">TBD</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/yuantiku/YTKNetwork">YTKNetwork <SUP>2.0.4</SUP><br>✅ <a href="https://github.com/rs/SDWebImage">SDWebImage/WebP <SUP>4.4.2</SUP></a><br>✅ <a href="https://github.com/tonymillion/Reachability">Reachability <SUP>3.2</SUP></a></td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/Alamofire/Alamofire">Alamofire <SUP>4.7.3</SUP><br>✅ <a href="https://github.com/onevcat/Kingfisher">Kingfisher <SUP>4.8.1</SUP></a><br>✅ <a https://github.com/Yeatse/KingfisherWebP">KingfisherWebP <SUP>0.4.1</SUP></a><br>✅ <a href="https://github.com/tonymillion/Reachability">Reachability <SUP>3.2</SUP></a></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Database</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/square/retrofit">greenDAO <SUP>3.2.2</SUP><br>✅ <a href="https://github.com/realm/realm-java">realm <SUP>5.4.2</SUP></a></td>
<td style="text-align:left;font-size:12pt">TBD</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/ccgus/fmdb">fmdb <SUP>2.7.4</SUP><br>✅ <a href="https://github.com/realm/realm-cocoa">realm <SUP>3.7.6</SUP></a></td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/magicalpanda/MagicalRecord">MagicalRecord <SUP>2.3.3</SUP></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Permission</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">QRCode</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Crash</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Doc</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">IDE Plugin	</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">JSON</td>
<td style="text-align:left;font-size:12pt">TBD</td>
<td style="text-align:left;font-size:12pt">TBD</td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/CoderMJLee/MJExtension">MJExtension <SUP>3.0.14</SUP></td>
<td style="text-align:left;font-size:12pt">✅ <a href="https://github.com/SwiftyJSON/SwiftyJSON">SwiftyJSON <SUP>4.0.0</SUP></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Bluetooth</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Hot Fix	</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">Animation</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">JavaScript</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
<tr>
<td style="text-align:left;font-size:12pt">...</td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
<td style="text-align:left;font-size:12pt"></td>
</tr>
</table>

### 4.开发规范文档

### 5.代码版本管理

### 6.Code Review

### 7.CI & CD

**持续更新中！**
