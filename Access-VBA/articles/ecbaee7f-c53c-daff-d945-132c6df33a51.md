
# NavigationButton.BorderShade Property (Access)

Gets or sets the shade applied to the theme color in the  **BorderColor** property of the specified object. Read/write **Single** .


## Syntax

 _expression_ . **BorderShade**

 _expression_ A variable that represents a **NavigationButton** object.


## Remarks

The  **BorderShade** property contains a numeric expression that can be used to darken the theme color in the **BorderColor** property. The default value of the **BorderShade** property is 100, which is neutral, and does not change the theme color. To darken the color, first determine the percentage by which to darken from 1 to 100, then subtract that value as a whole number from 100 and use the remainder. For example, to darken the theme color by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.


## Example

The following code example darkens the  **BorderColor** property by 75%.


```
Me.ctl.BorderShade=25
```


## See also


#### Concepts


[NavigationButton Object](ac6ba9b4-45aa-0d92-d01d-fd8e8b9cede6.md)
#### Other resources


[NavigationButton Object Members](e1d63e3c-ee09-4302-21dc-96fa76cf50fd.md)
