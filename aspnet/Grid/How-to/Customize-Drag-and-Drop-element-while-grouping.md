---
layout: post
title: Customize Drag and Drop in ASP.NET Webforms Grid Control | Syncfusion
description: Learn here about customize drag and drop element while grouping in Syncfusion Essential ASP.NET Webforms Grid Control, its elements, and more.
platform: aspnet
control: Grid
documentation: ug
---

# Customize Drag and Drop element while grouping

In this section, you can learn how to customize drag and drop element. This drag and drop element is framed by using CSS classes with default values. When you want to change or customize drag and drop element, then just override default values of CSS class values. e-cloneproperties is the name of drag and drop element in CSS class.

{% highlight css %}

<style type="text/css">

.e-grid .e-cloneproperties {

            background-color: black;

        }

</style>

<ej:Grid ID="OrdersGrid" runat="server" AllowGrouping="True">

<DataManager URL="http://mvc.syncfusion.com/Services/Northwnd.svc/Orders/" Offline="true"></DataManager>

 </ej:Grid>



{% endhighlight %}





The following output is displayed as a result of the above code example.

![ASP.NET Webforms Grid Customize Drag and Drop element](Customize-Drag-and-Drop-element-while-grouping_images/Customize-Drag-and-Drop-element-while-grouping_img1.png) 



