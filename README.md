## :sparkles: CSS Selectors

| Preview                           | Selector                                                     | Description                                                  |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [![](./assets/css_selectors_1.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator) | <p align="center"><strong>a > b</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator">Дочерний селектор</a></p> | Выберите все элементы b, которые находятся непосредственно внутри элементов a. |
| [![](./assets/css_selectors_2.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator) | <p align="center"><strong>a &nbsp; b</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator">Контекстные или вложенные селекторы</a></p> | Выберите все элементы b, которые находятся где-либо внутри элементов a. |
| [![](./assets/css_selectors_3.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator) | <p align="center"><strong>a + b</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator">Соседний родственный селектор</a></p> | Выберите все элементы b, которые находятся непосредственно рядом с элементами a. |
| [![](./assets/css_selectors_4.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator) | <p align="center"><strong>a ~ b</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator">General sibling combinator</a></p> | Select all b elements that are anywhere after a elements. |
| [![](./assets/css_selectors_5.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | <p align="center"><strong>.cl</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors">Class selector</a></p> | Select all elements that have the cl class name. |
| [![](./assets/css_selectors_6.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) | <p align="center"><strong>a.cl</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors">Tag + Class selector</a></p> | Select all a elements that have the cl class name. |
| [![](./assets/css_selectors_7.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) | <p align="center"><strong>.cl1.cl2</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors">Multiclass selector</a></p> | Select all elements that have both the cl1 and cl2 class names. |
| [![](./assets/css_selectors_8.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors) | <p align="center"><strong>a\[x=y\]</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors">Attribute selector</a></p> | Select all a elements that have the x attribute set to y. |
| [![](./assets/css_selectors_9.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) | <p align="center"><strong>#id1</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors">ID selector</a></p> | Select the element with the id1 ID name. |
| [![](./assets/css_selectors_10.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) | <p align="center"><strong>*</strong><br /><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors">Universal selector</a></p> | Select all elements. |

| High Resolution | Grayscale Print |
| --------------- | --------------- |
| [![](./assets/lowres-css_selectors.png)](./assets/css_selectors.png) | [![](./assets/lowres-css_selectors_print.png)](./assets/css_selectors_print.png) |

## :sparkles: CSS Box Model

| Preview                           | Property                                                     | Description                                                  |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [![](./assets/css_box_model_1.png)](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) | <p align="center" markdown="true">[`box-sizing: border-box`](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)</p> | The `width` and `height` have the size of `content`+`padding`+`border` |
| [![](./assets/css_box_model_2.png)](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) | <p align="center" markdown="true">[`box-sizing: content-box`](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)</p> | The `width` and `height` have the size of just `content` |

| High Resolution |
| --------------- |
| [![](./assets/lowres-css_box_model.png)](./assets/css_box_model.png) |

## :sparkles: CSS Grid Layout

| Align Content                             |
| --------------------------------- |
| <p align="center" markdown="true">Distribute content along the horizontal axis.</p> |
| <table><tr><td markdown="true">[![](./assets/css_grid_align_content_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: start`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_grid_align_content_space_around.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: space-around`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr><tr><td markdown="true">[![](./assets/css_grid_align_content_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_grid_align_content_space_between.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: space-between`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr><tr><td markdown="true">[![](./assets/css_grid_align_content_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: end`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_grid_align_content_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr></table> |

| Justify Content                             |
| --------------------------------- |
| <p align="center" markdown="true">Distribute content along the vertical axis.</p> |
| <table><tr><td markdown="true">[![](./assets/css_grid_justify_content_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: start`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_grid_justify_content_space_around.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: space-around`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr><tr><td markdown="true">[![](./assets/css_grid_justify_content_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_grid_justify_content_space_between.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: space-between`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr><tr><td markdown="true">[![](./assets/css_grid_justify_content_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: end`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_grid_justify_content_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr></table> |

| Align Items                             |
| --------------------------------- |
| <p align="center" markdown="true">Distribute content along the horizontal axis within their grid area.</p> |
| <table><tr><td markdown="true">[![](./assets/css_grid_align_items_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: start`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[![](./assets/css_grid_align_items_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td></tr><tr><td markdown="true">[![](./assets/css_grid_align_items_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: end`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[![](./assets/css_grid_align_items_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td></tr></table> |

| Justify Items                            |
| --------------------------------- |
| <p align="center" markdown="true">Distribute content along the vertical axis within their grid area.</p> |
| <table><tr><td markdown="true">[![](./assets/css_grid_justify_items_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[`justify-items: start`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[![](./assets/css_grid_justify_items_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[`justify-items: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td></tr><tr><td markdown="true">[![](./assets/css_grid_justify_items_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[`justify-items: end`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[![](./assets/css_grid_justify_items_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td><td markdown="true">[`justify-items: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items)</td></tr></table> |

| High Resolution | Grayscale Print |
| --------------- | --------------- |
| [![](./assets/lowres-css_grid.png)](./assets/css_grid.png) | [![](./assets/lowres-css_grid_print.png)](./assets/css_grid_print.png) |

## :sparkles: CSS Flexbox Layout

| Flex Direction                             |
| --------------------------------- |
| <p align="center" markdown="true">The flex-direction CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).</p> |
| <table><tr><td markdown="true">[![](./assets/css_flexbox_flex_direction_row.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[`flex-direction: row`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[![](./assets/css_flexbox_flex_direction_column.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[`flex-direction: column`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_flex_direction_row_reverse.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[`flex-direction: row-reverse`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[![](./assets/css_flexbox_flex_direction_column_reverse.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td><td markdown="true">[`flex-direction: column-reverse`](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)</td></tr></table> |

| Align Content                             |
| --------------------------------- |
| <p align="center" markdown="true">The CSS align-content property sets the distribution of space between and around content items along a flexbox's cross-axis.</p> |
| <table><tr><td markdown="true">[![](./assets/css_flexbox_align_content_flex_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: flex-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_flexbox_align_content_space_around.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: space-around`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_align_content_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_flexbox_align_content_space_between.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: space-between`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_align_content_flex_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: flex-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[![](./assets/css_flexbox_align_content_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td><td markdown="true">[`align-content: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)</td></tr></table> |

| Justify Content                             |
| --------------------------------- |
| <p align="center" markdown="true">The CSS justify-content property defines how the browser distributes space between and around content items along the main-axis of a flex container.</p> |
| <table><tr><td markdown="true">[![](./assets/css_flexbox_justify_content_flex_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: flex-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_flexbox_justify_content_space_around.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: space-around`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_justify_content_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_flexbox_justify_content_space_between.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: space-between`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_justify_content_flex_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: flex-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[![](./assets/css_flexbox_justify_content_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td><td markdown="true">[`justify-content: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)</td></tr></table> |

| Align Items                             |
| --------------------------------- |
| <p align="center" markdown="true">The CSS align-items property sets the align-self value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis.</p> |
| <table><tr><td markdown="true">[![](./assets/css_flexbox_align_items_flex_start.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: flex-start`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[![](./assets/css_flexbox_align_items_center.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: center`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td></tr><tr><td markdown="true">[![](./assets/css_flexbox_align_items_flex_end.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: flex-end`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[![](./assets/css_flexbox_align_items_stretch.png)](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td><td markdown="true">[`align-items: stretch`](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)</td></tr></table> |

| High Resolution | Grayscale Print |
| --------------- | --------------- |
| [![](./assets/lowres-css_flexbox.png)](./assets/css_flexbox.png) | [![](./assets/lowres-css_flexbox_print.png)](./assets/css_flexbox_print.png) |