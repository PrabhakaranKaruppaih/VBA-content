
# FillFormat.OneColorGradient Method (Excel)

Sets the specified fill to a one-color gradient.


## Syntax

 _expression_ . **OneColorGradient**( **_Style_** , **_Variant_** , **_Degree_** )

 _expression_ A variable that represents a **FillFormat** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Style_|Required| **[MsoGradientStyle](http://msdn.microsoft.com/library/1f0e723f-293c-3646-fd77-da2c8842c71f%28Office.15%29.aspx)**|The gradient style.|
| _Variant_|Required| **Integer**|The gradient variant. Can be a value from 1 through 4, corresponding to one of the four variants on the  **Gradient** tab in the **Fill Effects** dialog box. If _GradientStyle_ is **msoGradientFromCenter** , the _Variant_ argument can only be 1 or 2.|
| _Degree_|Required| **Single**|The gradient degree. Can be a value from 0.0 (dark) through 1.0 (light).|

## See also


#### Concepts


[FillFormat Object](b602e09e-97ab-bfbe-1796-bc44ebb7dc28.md)
