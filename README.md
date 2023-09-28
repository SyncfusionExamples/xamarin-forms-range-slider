# Xamarin Range Slider (SfRangeSlider) 

The Range Slider control for Xamarin.Forms allows you select a range of values within the specified minimum and maximum limits. The range can be selected by moving the thumb along track.

![image](https://github.com/SuryaKaran2143/xamarin-forms-range-slider/assets/113962276/aaf9dc69-8655-40b1-9bb2-873204a29e87)

Xamarin Range Slider (SfRangeSlider) provides option to set single thumb and double thumb. While setting the double thumb, each thumb value can be set using RangeStart and RangeEnd properties.

The ShowRange property is used to switch between a single thumb and double thumb.

SfRangeSlider provides option to restrict slider range between minimum and maximum values. Following code explains how to set the range using Minimum and Maximum properties in the SfRangeSlider.

The movement of the thumb can be varied in different ways. This is achieved by setting the SnapsTo property.

## Orientation in Xamarin Range Slider (SfRangeSlider)


SfRangeSlider provides options to display values and slider to slide either horizontally or vertically.

> The default option is Vertical.

### Horizontal

```XAML
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml" 
xmlns:Range="clr-namespace:Syncfusion.SfRangeSlider.XForms;assembly=Syncfusion.SfRangeSlider.XForms"
xmlns:Local="clr-namespace:GettingStarted;assembly=GettingStarted"
x:Class="GettingStarted.RangeSliderSample">
	<ContentPage.Content>
		<Range:SfRangeSlider  Orientation="Horizontal"/>
	</Range:SfRangeSlider>
	</ContentPage.Content>
</ContentPage>
```
![image](https://github.com/SuryaKaran2143/xamarin-forms-range-slider/assets/113962276/2f503d43-82e0-49d0-a490-ffb9ac9427b8)

### Vertical

```XAML
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml" 
xmlns:Range="clr-namespace:Syncfusion.SfRangeSlider.XForms;assembly=Syncfusion.SfRangeSlider.XForms"
xmlns:Local="clr-namespace:GettingStarted;assembly=GettingStarted"
x:Class="GettingStarted.RangeSliderSample">
	<ContentPage.Content>
		<Range:SfRangeSlider  Orientation="Vertical"/>
	</Range:SfRangeSlider>
	</ContentPage.Content>
</ContentPage>
```

![image](https://github.com/SuryaKaran2143/xamarin-forms-range-slider/assets/113962276/083ba6c8-89a2-4347-b2ee-f54b33d26c26)


## See also

For know more details about Range Slider: https://www.syncfusion.com/xamarin-ui-controls/xamarin-range-slider

Range Slider user guide documentation: https://help.syncfusion.com/xamarin/range-slider/getting-started
