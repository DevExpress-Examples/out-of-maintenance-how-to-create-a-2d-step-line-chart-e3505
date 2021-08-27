<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569322/11.2.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3505)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/LineStep2DChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LineStep2DChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Step Line chart

The following example demonstrates how to create a [2D Step Line](https://docs.devexpress.com/WPF/9991/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/point-line-and-bubble-series/step-line?p=netframework) chart.


### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add a [LineStepSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.LineStepSeries2D?p=netframework) object with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a [chart title](https://docs.devexpress.com/WPF/7844/controls-and-libraries/charts-suite/chart-control/chart-elements/chart-titles?p=netframework).
