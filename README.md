# KWidget Sample   
<a target="_blank" href="https://twitter.com/intent/tweet?text=KWidget&url=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/35b0b8bfbd8840f35607fb56ad0a139047fd5d6e09ceb060c5c6f0a5abd1044c/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f747769747465722e737667" /></a><a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/8f245234577766478eaf3ee72b0615e99bb9ef3eaa56e1c37f75692811181d5c/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f66616365626f6f6b2e737667" /></a><a target="_blank" href="https://plus.google.com/share?url=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/15fdf0cbd71e1ca3db22839bf80a55d246e4a19e4a019021fdf121e2cc193488/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f676f6f676c655f706c75732e737667" /></a><a target="_blank" href="https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/kredibel-id/SampleKWidget&title=KWidget&summary=Easy use form widget components with material design which contains from KEditText and KSpinner&source=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/c8a9c5b414cd812ad6a97a46c29af67239ddaeae08c41724ff7d945fb4c047e5/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f6c696e6b6564696e2e737667" /></a><a target="_blank" href="https://pinterest.com/pin/create/button/?url=https://github.com/kredibel-id/SampleKWidget&description=Easy use form widget components with material design which contains from KEditText and KSpinner"> <img width="30" src="https://camo.githubusercontent.com/ef99a09dfa010e68c26ec4414631a47bbc1086677227bd97538d051b8b93ae21/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f70696e7465726573742e737667" /></a><a target="_blank" href="http://www.tumblr.com/share/link?url=https://github.com/kredibel-id/SampleKWidget&description=Easy use form widget components with material design which contains from KEditText and KSpinner"> <img width="30" src="https://camo.githubusercontent.com/f47b844e7015760d6fd9c1fb86834af2cf82d215fc9c20c24edc8173c85059a1/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f74756d626c722e737667" /></a>    
This is an example project of using KWidget on an android application.

## What is KWidget?
Easy use form widget components with material design which contains from KEditText and KSpinner

<img width="400dp" src="https://github.com/kredibel-id/SampleKWidget/blob/main/ezgif-2-204eb5c2f1.gif?raw=true"/>

## Getting started
### Support API Level
![minsdk](https://img.shields.io/badge/Min%20SDK-API%2019-%233DDC84?logo=android) ![targetsdk](https://img.shields.io/badge/Max%20Support-API%2031-%233DDC84?logo=android)


## Setup
#### 1. Add kredibel repository.
```groovy
maven{url 'https://repo.repsy.io/mvn/kredibel/sdk'}
```

#### 2. Add this dependency to gradle script on app module.
```groovy
dependencies {
    implementation 'io.kredibel:widget:0.0.3' // Please check latest version
}
```

## How to Use
### KEditText
```xml
<io.kredibel.widget.KEditText
      android:hint="Ketik Nama disinih.."
      android:layout_width="200dp"
      android:layout_height="wrap_content"/>
```

### KSpinner
```xml
<io.kredibel.widget.KSpinner
      android:layout_width="200dp"
      android:layout_height="wrap_content"
      android:entries="@array/platform"/>
```      

### Set Hint Color
You can customize color by adding the following key to your color resource xml.
```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
  ...
  ...
  <color name="common_color_focused">#0169FF</color>
  <color name="common_color_bg">#F3F5F8</color>
</resources>
```

### Border Width
You can customize border width by adding the following key to your dimens resource xml.
```xml
<dimen name="common_kwidget_border_width">1.5dp</dimen>
```

### Share Please 😊
<a target="_blank" href="https://twitter.com/intent/tweet?text=KWidget&url=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/35b0b8bfbd8840f35607fb56ad0a139047fd5d6e09ceb060c5c6f0a5abd1044c/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f747769747465722e737667" /></a><a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/8f245234577766478eaf3ee72b0615e99bb9ef3eaa56e1c37f75692811181d5c/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f66616365626f6f6b2e737667" /></a><a target="_blank" href="https://plus.google.com/share?url=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/15fdf0cbd71e1ca3db22839bf80a55d246e4a19e4a019021fdf121e2cc193488/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f676f6f676c655f706c75732e737667" /></a><a target="_blank" href="https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/kredibel-id/SampleKWidget&title=KWidget&summary=Easy use form widget components with material design which contains from KEditText and KSpinner&source=https://github.com/kredibel-id/SampleKWidget"> <img width="30" src="https://camo.githubusercontent.com/c8a9c5b414cd812ad6a97a46c29af67239ddaeae08c41724ff7d945fb4c047e5/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f6c696e6b6564696e2e737667" /></a><a target="_blank" href="https://pinterest.com/pin/create/button/?url=https://github.com/kredibel-id/SampleKWidget&description=Easy use form widget components with material design which contains from KEditText and KSpinner"> <img width="30" src="https://camo.githubusercontent.com/ef99a09dfa010e68c26ec4414631a47bbc1086677227bd97538d051b8b93ae21/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f70696e7465726573742e737667" /></a><a target="_blank" href="http://www.tumblr.com/share/link?url=https://github.com/kredibel-id/SampleKWidget&description=Easy use form widget components with material design which contains from KEditText and KSpinner"> <img width="30" src="https://camo.githubusercontent.com/f47b844e7015760d6fd9c1fb86834af2cf82d215fc9c20c24edc8173c85059a1/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f74756d626c722e737667" /></a> 
