




```
r language BS29, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis iskemik kolit TR, echo = (language == "TR")
## BS29 - iskemik kolit {#sec-BS29 }
```


```
asis ischemic colitis EN, echo = (language == "EN")
## BS29 - ischemic colitis {#sec-BS29 }
```






```
r BS29 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS29-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS29/HE.html",
  file = "./screenshots/BS29-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS29/HE.html](https://images.patolojiatlasi.com/BS29/HE.html)





```
asis, echo = (language == "TR")

**iskemik kolit**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS29-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS29/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS29/HE.html)
```

```
asis, echo = (language == "EN")

**ischemic colitis**

[![Click for Full Screen WSI](./screenshots/BS29-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS29/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS29/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS29/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS29/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```






:::::











