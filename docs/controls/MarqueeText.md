---
title: MarqueeText
author: avid29
description: A control containing text that scrolls text automatically.
keywords: windows 10, uwp, windows community toolkit, uwp community toolkit, uwp toolkit, MarkdownTextBlock, xaml, xaml control
---

# MarqueeText

The [MarqueeText](/dotnet/api/microsoft.toolkit.uwp.ui.controls.marqueetext) control scrolls text through a given area.

> [!div class="nextstepaction"]
> [Try it in the sample app](uwpct://Controls?sample=MarqueeText)

## Syntax

```xaml
<controls:MarqueeText x:Name="MarqueeText"/>
```

## Sample Output

![ImageEx animation](../resources/images/Controls/MarqueeText.gif)

## Properties

| Property | Type | Description |
| -- | -- | -- |
| Text | string | Gets or sets the text being displayed in Marquee. |
| Speed | double | Gets or sets the speed the text moves in the Marquee. |
| RepeatBehavior | RepeatBehavior | Gets or sets a value indicating whether or not the marquee scroll repeats. |
| Behavior | MarqueeBehavior | Gets or sets the marquee behavior. |
| Direction | MarqueeDirection | Gets or sets a value indicating whether or not the marquee text wraps. |
| TextDecorations | TextDecorations | Gets or sets a value that indicates what decorations are applied to the text. |

## Events

| Events | Description |
| -- | -- |
| MarqueeBegan | Event raised when the Marquee begins scrolling. |
| MarqueeStopped | Event raised when the Marquee stops scrolling for any reason. |
| MarqueeCompleted | Event raised when the Marquee completes scrolling. |

## Sample Project

[MarqueeText Sample Page Source](https://github.com/windows-toolkit/WindowsCommunityToolkit/tree/rel/7.1.0/Microsoft.Toolkit.Uwp.SampleApp/SamplePages/MarqueeText). You can [see this in action](uwpct://Controls?sample=MarqueeText) in the [Windows Community Toolkit Sample App](https://aka.ms/windowstoolkitapp).

## Default Template

- [MarqueeText Control XAML File](https://github.com/windows-toolkit/WindowsCommunityToolkit/blob/rel/7.1.0/Microsoft.Toolkit.Uwp.UI.Controls.Core/MarqueeText/MarqueeText.xaml) is the XAML template used in the toolkit for the default styling.

## Requirements

| Device family | Universal, 10.0.16299.0 or higher |
| -- | -- |
| Namespace | Microsoft.Toolkit.Uwp.UI.Controls |
| NuGet package | [Microsoft.Toolkit.Uwp.UI.Controls](https://www.nuget.org/packages/Microsoft.Toolkit.Uwp.UI.Controls/) |

## API

- [MarqueeText source code](https://github.com/windows-toolkit/WindowsCommunityToolkit/tree/rel/7.1.0/Microsoft.Toolkit.Uwp.UI.Controls.Core/MarqueeText)
