---
title: "Automatic or Manual - Which is Better for MPG?"
author: "Carlos Schuler"
date: "8/17/2020"
output: 
  ioslides_presentation:
    keep_md: yes
---



## Automatic or manual better for MPG??

### A quick look at the *mtcars* dataset:


<!--html_preserve--><div id="htmlwidget-392a2a2a33ed8bcde13e" style="width:720px;height:288px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-392a2a2a33ed8bcde13e">{"x":{"visdat":{"14c3a41add0f2":["function () ","plotlyVisDat"]},"cur_data":"14c3a41add0f2","attrs":{"14c3a41add0f2":{"y":[21.4,18.7,18.1,14.3,24.4,22.8,19.2,17.8,16.4,17.3,15.2,10.4,10.4,14.7,21.5,15.5,15.2,13.3,19.2],"name":"Automatic","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a41add0f2.1":{"y":[21,21,22.8,32.4,30.4,33.9,27.3,26,30.4,15.8,19.7,15,21.4],"name":"Manual","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[21.4,18.7,18.1,14.3,24.4,22.8,19.2,17.8,16.4,17.3,15.2,10.4,10.4,14.7,21.5,15.5,15.2,13.3,19.2],"name":"Automatic","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[21,21,22.8,32.4,30.4,33.9,27.3,26,30.4,15.8,19.7,15,21.4],"name":"Manual","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

### suggests that **Manual transmissions** yield a better MPG

### BUT ...

## Grouping by Number of Cylinders ...

<!--html_preserve--><div id="htmlwidget-adb8cbf15d1845145703" style="width:720px;height:182.4px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-adb8cbf15d1845145703">{"x":{"visdat":{"14c3a8e82ec8":["function () ","plotlyVisDat"]},"cur_data":"14c3a8e82ec8","attrs":{"14c3a8e82ec8":{"y":[24.4,22.8,21.5],"name":"Automatic, 4 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a8e82ec8.1":{"y":[22.8,32.4,30.4,33.9,27.3,26,30.4,21.4],"name":"Manual, 4 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[24.4,22.8,21.5],"name":"Automatic, 4 cyl","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[22.8,32.4,30.4,33.9,27.3,26,30.4,21.4],"name":"Manual, 4 cyl","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve--><!--html_preserve--><div id="htmlwidget-cfc0347e20be82b9ac69" style="width:720px;height:182.4px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-cfc0347e20be82b9ac69">{"x":{"visdat":{"14c3a43575109":["function () ","plotlyVisDat"]},"cur_data":"14c3a43575109","attrs":{"14c3a43575109":{"y":[21.4,18.1,19.2,17.8],"name":"Automatic, 6 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a43575109.1":{"y":[21,21,19.7],"name":"Manual, 6 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[21.4,18.1,19.2,17.8],"name":"Automatic, 6 cyl","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[21,21,19.7],"name":"Manual, 6 cyl","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve--><!--html_preserve--><div id="htmlwidget-00f3e2619eba6795890f" style="width:720px;height:182.4px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-00f3e2619eba6795890f">{"x":{"visdat":{"14c3a19894869":["function () ","plotlyVisDat"]},"cur_data":"14c3a19894869","attrs":{"14c3a19894869":{"y":[18.7,14.3,16.4,17.3,15.2,10.4,10.4,14.7,15.5,15.2,13.3,19.2],"name":"Automatic, 8 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a19894869.1":{"y":[15.8,15],"name":"Manual, 8 cyl","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[18.7,14.3,16.4,17.3,15.2,10.4,10.4,14.7,15.5,15.2,13.3,19.2],"name":"Automatic, 8 cyl","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[15.8,15],"name":"Manual, 8 cyl","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

## Grouping by Weight ...

<!--html_preserve--><div id="htmlwidget-ec5a7ab69efc77c68552" style="width:720px;height:182.4px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-ec5a7ab69efc77c68552">{"x":{"visdat":{"14c3a3fc6db2d":["function () ","plotlyVisDat"]},"cur_data":"14c3a3fc6db2d","attrs":{"14c3a3fc6db2d":{"y":[21.4,24.4,22.8,21.5],"name":"Automatic, Light","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a3fc6db2d.1":{"y":[21,21,22.8,32.4,30.4,33.9,27.3,26,30.4,15.8,19.7,21.4],"name":"Manual, Light","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[21.4,24.4,22.8,21.5],"name":"Automatic, Light","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[21,21,22.8,32.4,30.4,33.9,27.3,26,30.4,15.8,19.7,21.4],"name":"Manual, Light","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve--><!--html_preserve--><div id="htmlwidget-ad8df4a29d396fb43ce0" style="width:720px;height:182.4px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-ad8df4a29d396fb43ce0">{"x":{"visdat":{"14c3a185f8811":["function () ","plotlyVisDat"]},"cur_data":"14c3a185f8811","attrs":{"14c3a185f8811":{"y":[18.7,18.1,14.3,19.2,17.8,16.4,17.3,15.2,10.4,10.4,14.7,15.5,15.2,13.3,19.2],"name":"Automatic, Heavy","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box"},"14c3a185f8811.1":{"y":15,"name":"Manual, Heavy","alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"box","inherit":true}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"paper_bgcolor":"#F2F2F2","plot_bgcolor":"#F2F2F2","xaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"#F2F2F2","gridwidth":0,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2},"yaxis":{"domain":[0,1],"automargin":true,"zeroline":true,"showline":true,"mirror":"ticks","gridcolor":"rgba(173,216,230,1)","gridwidth":1,"zerolinecolor":"rgba(255,0,0,1)","zerolinewidth":1,"linecolor":"rgba(0,0,0,1)","linewidth":2,"title":[]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(31,119,180,0.5)","y":[18.7,18.1,14.3,19.2,17.8,16.4,17.3,15.2,10.4,10.4,14.7,15.5,15.2,13.3,19.2],"name":"Automatic, Heavy","type":"box","marker":{"color":"rgba(31,119,180,1)","line":{"color":"rgba(31,119,180,1)"}},"line":{"color":"rgba(31,119,180,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(255,127,14,0.5)","y":[15],"name":"Manual, Heavy","type":"box","marker":{"color":"rgba(255,127,14,1)","line":{"color":"rgba(255,127,14,1)"}},"line":{"color":"rgba(255,127,14,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

## We notice it is not that clear!!

- For 4-cyl vehicles, a manual transmission appears to yield higher MPG
- However, that appears **not to be the case** for 8-cyl vehicles 
- Also, for lighter vehicles (weighing less than the median for the sample), the relationship between MPG and transmission type appears not to be significant 
    + (*note*: there is only one vehicle weighing higher than the median weight with an manual transmission in the sample, the **Maserati Bora**. Its MPG does not appear to be better than other vehicles in its weight class.)

## CODE

```r
library(tidyverse)
library(plotly)
data("mtcars")
mtcars <- as_tibble(mtcars)
mtcarsF<-mtcars
mtcarsF$cyl <-  factor(mtcarsF$cyl)
mtcarsF$vs <-   factor(mtcarsF$vs,labels = c("V block","S block"))
mtcarsF$am <-   factor(mtcarsF$am,labels = c("Automatic","Manual"))
mtcarsF$gear <- factor(mtcarsF$gear)
mtcarsF$carb <- factor(mtcarsF$carb)
wtMedian <- median(mtcarsF$wt)
lightWeight=paste("<",wtMedian)
heavyWeight=paste(">",wtMedian)
mtcarsF <- mtcarsF %>% mutate(wtQ=factor(ntile(wt,2),
                        labels=c(lightWeight,heavyWeight)))
rownames(mtcarsF)<-rownames(mtcars)
```

***

```r
ax <- list(zeroline = TRUE, showline = TRUE, mirror = "ticks", 
  gridcolor = "#F2F2F2", gridwidth = 0, 
  zerolinecolor = toRGB("red"), zerolinewidth = 1, 
  linecolor = toRGB("black"), linewidth = 2)
ay <- list(zeroline = TRUE, showline = TRUE, mirror = "ticks", 
  gridcolor = toRGB("lightblue"), gridwidth = 1, 
  zerolinecolor = toRGB("red"), zerolinewidth = 1, 
  linecolor = toRGB("black"), linewidth = 2)

y1<-mtcarsF[mtcarsF$am=="Automatic",]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual",]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic") %>% 
        add_trace(y= y2, name="Manual") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2'
               ,xaxis=ax, yaxis=ay)
fig
```

***

```r
y1<-mtcarsF[mtcarsF$am=="Automatic" & mtcarsF$cyl=="4",]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual"    & mtcarsF$cyl=="4",]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic, 4 cyl") %>% 
        add_trace(y= y2, name="Manual, 4 cyl") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2',
               xaxis=ax, yaxis=ay)
fig

y1<-mtcarsF[mtcarsF$am=="Automatic" & mtcarsF$cyl=="6",]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual"    & mtcarsF$cyl=="6",]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic, 6 cyl") %>% 
        add_trace(y= y2, name="Manual, 6 cyl") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2',
               xaxis=ax, yaxis=ay)
fig
```

***

```r
y1<-mtcarsF[mtcarsF$am=="Automatic" & mtcarsF$cyl=="8",]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual"    & mtcarsF$cyl=="8",]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic, 8 cyl") %>% 
        add_trace(y= y2, name="Manual, 8 cyl") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2',
               xaxis=ax, yaxis=ay)
fig

y1<-mtcarsF[mtcarsF$am=="Automatic" & mtcarsF$wtQ==lightWeight,]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual"    & mtcarsF$wtQ==lightWeight,]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic, Light") %>% 
        add_trace(y= y2, name="Manual, Light") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2',
               xaxis=ax, yaxis=ay)
fig
```

***

```r
y1<-mtcarsF[mtcarsF$am=="Automatic" & mtcarsF$wtQ==heavyWeight,]$mpg
y2<-mtcarsF[mtcarsF$am=="Manual"    & mtcarsF$wtQ==heavyWeight,]$mpg
fig <- plot_ly(y= y1, type="box", name="Automatic, Heavy") %>% 
        add_trace(y= y2, name="Manual, Heavy") %>% 
        layout(paper_bgcolor='#F2F2F2', plot_bgcolor='#F2F2F2',
               xaxis=ax, yaxis=ay)
fig
```
