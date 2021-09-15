<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642344/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T122997)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
## Files to look at:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/MainWindow.xaml.vb))
* **[MainView.xaml](./CS/View/MainView.xaml) (VB: [MainView.xaml](./VB/View/MainView.xaml))**
* [MainView.xaml.cs](./CS/View/MainView.xaml.cs) (VB: [MainView.xaml.vb](./VB/View/MainView.xaml.vb))
* [MainViewModel.cs](./CS/ViewModel/MainViewModel.cs) (VB: [MainViewModel.vb](./VB/ViewModel/MainViewModel.vb))
<!-- default file list end -->

# WPF MVVM Gramework - Bind a ViewModel's Property to a Control's Non Dependency Property

## Overview

To bind a ViewModel property to a control's non dependency property, specify the following  **DependencyPropertyBehavior**'s properties:

| Property | Description|
|-|-|
[Binding](https://docs.devexpress.com/WPF/DevExpress.Mvvm.UI.DependencyPropertyBehavior.Binding)| Gets or sets a binding that should be applied to the specified property. This is a dependency property. |
[EventName](https://docs.devexpress.com/WPF/DevExpress.Mvvm.UI.DependencyPropertyBehavior.EventName)| Gets or sets an event name that the **DependencyPropertyBehavior** processes to update the binding specified in the Binding property. |
[PropertyName](https://docs.devexpress.com/WPF/DevExpress.Mvvm.UI.DependencyPropertyBehavior.PropertyName)|Gets or sets a control’s property name that should be bound.|

## Documentation

- [DependencyPropertyBehavior](https://docs.devexpress.com/WPF/DevExpress.Mvvm.UI.DependencyPropertyBehavior)
- [Behaviors](https://docs.devexpress.com/WPF/17442/mvvm-framework/behaviors)
