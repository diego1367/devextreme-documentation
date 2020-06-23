---
dep: Use the 'selected(state)' method of the Layer Element
---
---
##### deprecated
Use the **Layer Element** | [selected(state)](/api-reference/20%20Data%20Visualization%20Widgets/70%20dxVectorMap/7%20Map%20Elements/Layer%20Element/3%20Methods/selected(state).md '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Map_Elements/Layer_Element/Methods/#selectedstate') method instead.

##### shortDescription
Sets a new selection state for an area.

##### param(state): boolean
Specifies whether to select or deselect the area.

---
To select an area, pass *true* as the parameter. Otherwise, pass *false*. To specify the selection state of a certain area when configuring **VectorMap**, use the **isSelected** fields of the object returned by the [customize](/api-reference/20%20Data%20Visualization%20Widgets/70%20dxVectorMap/1%20Configuration/areaSettings/customize.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/areaSettings/#customize') function.