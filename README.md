
# Rapport

Jag har lagt till en webview på XML-filen "MainActivity.java" och länkat en intern och extern sida, koden nedan visar hur detta gått till. Jag har även aktiverat internet på XML-filen "AndroidManifest.xml"
```
private WebView myWebView;

    public void showExternalWebPage(){
        myWebView.loadUrl("https://www.instagram.com/");
    }

    public void showInternalWebPage(){
        myWebView.loadUrl("file:///android_asset/inl2.html");
    }

```

Bilder läggs i samma mapp som markdown-filen.

![](Screenshot2.png)
![](Screenshot3.png)

