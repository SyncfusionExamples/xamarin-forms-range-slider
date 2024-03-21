# Xamarin Range Slider (SfRangeSlider) 

The Range Slider control for Xamarin.Forms allows you select a range of values within the specified minimum and maximum limits. The range can be selected by moving the thumb along track.

For know more details about Range Slider: https://www.syncfusion.com/xamarin-ui-controls/xamarin-range-slider

Range Slider user guide documentation: https://help.syncfusion.com/xamarin/range-slider/getting-started

## Getting Started with Xamarin Range Slider (SfRangeSlider)

This section explains you the steps to configure a Xamarin Range Slider (SfRangeSlider) control in a real-time scenario and also provides a walk-through on some of the customization features available in SfRangeSlider control.

### Adding SfRangeSlider reference
You can add SfRangeSlider reference using one of the following methods:

####  Method 1: Adding SfRangeSlider reference from nuget.org

Syncfusion Xamarin components are available in nuget.org. To add SfRangeSlider to your project, open the NuGet package manager in Visual Studio, search for Syncfusion.Xamarin.SfRangeSlider, and then install it.

####  Method 2: Adding SfRangeSlider reference from toolbox

Syncfusion also provides Xamarin Toolbox. Using this toolbox, you can drag the SfRangeSlider control to the XAML page. It will automatically install the required NuGet packages and add the namespace to the page. To install Syncfusion Xamarin Toolbox, refer to Toolbox.

####  Method 3: Adding SfRangeSlider assemblies manually from the installed location

If you prefer to manually reference the assemblies instead referencing from NuGet, add the following assemblies in respective projects.

### Adding namespace for the added assemblies.

**[XAML]**
```
<xmlns:range="clr-namespace:Syncfusion.SfRangeSlider.XForms;assembly=Syncfusion.SfRangeSlider.XForms"/>
```
**[C#]**

```
using Syncfusion.SfRangeSlider.XForms;
```
Now instantiate and add the SfRangeSlider control with a required optimal name.

**[XAML]**
```
<range:SfRangeSlider x:Name="rangeSlider"/>
```
**[C#]**

```
SfRangeSlider rangeSlider=new SfRangeSlider();
this.Content = rangeSlider;
```
##   Set Range
Xamarin Range Slider (SfRangeSlider) provides option to set single thumb and double thumb. While setting the double thumb, each thumb value can be set using RangeStart and RangeEnd properties.

**[XAML]**
```
<range:SfRangeSlider x:Name="rangeslider" RangeEnd="20" RangeStart="4"  ShowRange="true"/>
```
###   Restricting Values
SfRangeSlider provides option to restrict slider range between minimum and maximum values. Following code explains how to set the range using Minimum and Maximum properties in the SfRangeSlider.

**[XAML]**
```
<range:SfRangeSlider x:Name="rangeslider" Minimum="0" Maximum="24"/>
```
###   Adding Snapping Mode
The movement of the thumb can be varied in different ways. This is achieved by setting the SnapsTo property.

**[XAML]**
```
<range:SfRangeSlider x:Name="rangeslider" SnapsTo="Ticks" StepFrequency="6"/>
```

## How to run this application?

To run this application, you need to first clone the xamarin-forms-range-slider repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.