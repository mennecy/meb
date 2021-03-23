---
title: "Documents"
date: 2019-11-06T10:19:53+01:00
draft: false
images:
    imageA: "images A"
    imageB: "images B"
---
 {{< load-photoswipe >}}
___

{{< myshortcode red bg-success "Images de la famille Dicko" >}}
<!--foldergalelery shorcode  point on images in teh static directory only  --> 
{{<foldergallery src="img/" hover-effect="grow" >}}
{{</myshortcode>}}
___



<!--  create in the content a galleries content that contents only images in different 
directories called ohd, gallery1 etc -->
* [Galerie de Photo](/galleries/ohd/)



* [Galery1](/galleries/gallery1/)


* [Galery2](/galleries/gallery2/)

* [Ada Chez Kadji a Bamako](/documents/img/)

___
<!-- local images -->

<!--  this shortcode renders images under contents directories 
Some bug hover-effect ?? -->
{{< myshortcode red bg-light "Images de la famille Dicko B" >}}
    {{< gallery caption-effect="fade" hover-effect="grow" >}}
   
{{</myshortcode>}}
___






