<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/LineStep2DChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LineStep2DChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Step Line chart

The following example demonstrates how to create a [2D Step Line](https://docs.devexpress.com/WPF/9991/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/point-line-and-bubble-series/step-line?p=netframework) chart.


### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add a [LineStepSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.LineStepSeries2D?p=netframework) object with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a [chart title](https://docs.devexpress.com/WPF/7844/controls-and-libraries/charts-suite/chart-control/chart-elements/chart-titles?p=netframework).
