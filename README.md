# Outline
This repository contains an Windows 10 UWP app with OutlineTextBlock using Win2D. It can be uses to display a text which is outlined. It is a first release which is not yet tested thouroughly. I plan to move it to the https://github.com/windows-toolkit/WindowsCommunityToolkit

# Example
```xml
<Page x:Class="Outline.MainPage"
      xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
      xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
      xmlns:local="using:Outline"
      xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
      xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
      mc:Ignorable="d"
      Background="{ThemeResource ApplicationPageBackgroundThemeBrush}">

    <Grid>
        <StackPanel>
            <local:OutlinedTextBlock Text="Hello World"
                                     FontFamily="Showcard Gothic"
                                     FontWeight="Bold"
                                     FontSize="60"
                                     TextWrapping="Wrap"
                                     OutlineThickness="6"
                                     OutlineColor="Black"
                                     TextColor="White"
                                     HorizontalContentAlignment="Center"
                                     Width="250" />
            <local:OutlinedTextBlock Text="Fons Sonnemans"
                                     FontSize="60"
                                     FontStyle="Italic"
                                     OutlineThickness="6"
                                     HorizontalAlignment="Center"
                                     Padding="12" />
        </StackPanel>
    </Grid>
</Page>
```

# Output
![Screenshot](https://github.com/sonnemaf/Outline/blob/master/Screenshot.png)

