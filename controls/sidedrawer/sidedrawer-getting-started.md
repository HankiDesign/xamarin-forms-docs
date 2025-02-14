---
title: Getting Started
page_title: Getting Started
position: 1
slug: sidedrawer-getting-started
---

# Getting Started

This article will guide you through the steps needed to add a basic **RadSideDrawer** control in your application.

## 1. Setting up the app

Take a look at these articles and follow the instructions to setup your app:

- [Setup app with Telerik UI for Xamarin on Windows]({%slug getting-started-windows%})
- [Setup app with Telerik UI for Xamarin on Mac]({%slug getting-started-mac%})

## 2. Adding the required Telerik references

You have two options:

* Add the Telerik UI for Xamarin Nuget packages following the instructions in [Telerik NuGet package server]({%slug telerik-nuget-server%}) topic.

* Add the references to Telerik assemblies manually, check the list below with the required assemblies for **RadSideDrawer** component:

| Platform | Assemblies |
| -------- | ---------- |
| Portable | Telerik.XamarinForms.Common.dll<br/>Telerik.XamarinForms.Primitives.dll |
| Android  | Telerik.Xamarin.Android.Common.dll<br/>Telerik.Xamarin.Android.Primitives.dll<br/>Telerik.XamarinForms.Common.dll<br/>Telerik.XamarinForms.Primitives.dll |
| iOS      | Telerik.Xamarin.iOS.dll <br/>Telerik.XamarinForms.Common.dll<br/>Telerik.XamarinForms.Primitives.dll |
| UWP      | Telerik.Core.dll<br/>Telerik.UI.Xaml.Primitives.UWP.dll<br/>Telerik.XamarinForms.Common.dll<br/>Telerik.XamarinForms.Primitives.dll |

## 3. Adding RadSideDrawer control

If your app is setup, you are ready to add a **RadSideDrawer** control.

You can proceed with defining the component. The DrawerContent represents the hidden view (in it you could place navigational UI, any common setting, etc), while the MainContent hosts the main View of your app.

<snippet id='sidedrawer-gettingstarted-xaml'/>
<snippet id='sidedrawer-gettingstarted-csharp'/>

You also have to add the following namespace:

<snippet id='xmlns-telerikprimitives'/>
<snippet id='ns-telerikprimitives'/>


Finally, set the drawer as content of your page.

Here is the result when you set `IsOpen="True"`:
 
![SideDrawer example](images/sidedrawer-gettingstarted.png)

>important **SDK Browser** and **QSF** applications contain different examples that show RadSideDrawer's main features. You can find the applications in the **Examples** and **QSF** folders of your local **Telerik UI for Xamarin** installation.

## See Also

- [Properties and Events]({% slug sidedrawer-features-properties-events %})
- [Transitions]({% slug sidedrawer-features-transitions %})