# Source: https://docs.canvasflow.io/article/100-working-with-columns

# Working With Columns

The 'Column Component' allows advanced control over the structure of an article, enabling content to be organised in up to four columns. These columns act as the parent / containing elements for text and media components, each of which can be placed into a column.

To edit the properties of a column, a column component must exist on to the canvas. You can learn how to [add components here](https://docs.canvasflow.io/article/54-adding-components).

#### Managing column properties

Once a column is on the canvas, the properties can be changed by hovering over the column and clicking the `edit` button next to the column block.  

[![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bfd74fd2c7d3a31944e6d68/file-OdPGBBmwDw.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bfd74fd2c7d3a31944e6d68/file-OdPGBBmwDw.png)

This will display the properties menu. The options available will depend on if you're working with a single column, or a two/three/multi column:

[![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bfd756c2c7d3a31944e6d72/file-nB09pSlF5x.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bfd756c2c7d3a31944e6d72/file-nB09pSlF5x.png)

#### Apply a Custom Style Block

A column component is required to use a 'Custom Style Block'_._ For more info, see ['Custom Style Blocks'](https://docs.canvasflow.io/article/99-custom-style-blocks).

#### Full Bleed

'Full Bleed' only applies if a 'Custom Style Block' is attached to the column. With one attached, this option will full bleed the style block's background image or colour.

#### Container Width

'Container Width' allows control over the width of the container element on the page, by default this is 100%.

#### Controlling the Column Split

By default a new column is equally split, 50% | 50% for a 2x column block, 33% | 33% | 33% for a 3x column block, etc.

It's possible to change how the columns are divided using the 'Column Split' menu.  By changing the values, the column within the article will respond immediately and any content within them will adapt to the new width settings.

#### Alignment

Controls the alignment of single columns. Columns must have a container width below 100% for alignment changes to take effect.

#### Controlling the collapse action

By default, columns collapse on mobile devices, however it is possible to override this default action.  This is useful when there is no benefit in columns collapsing on a smaller screen, for example: A 3x column component used to display a number of logos.

- To prevent a column component collapsing on a mobile, select the `Collapse Action` menu and choose `Never`.
- To make the column collapse on tablet portrait orientation, select the 'Tablet Portrait' option.

### Multi-columns

Defining the number of columns you need is great if the amount of content to be placed into each column is known. However, when the amount of content is unknown, it may be more useful to make use of a multi-column layout.

With multi-columns, you can create a print-inspired layout that will automatically adapt beyond a fixed structure.  A multi-column will make calculations to automatically wrap and balance content into tidy columns.  Once the browser cannot fit at least two columns as wide as the column-width then no columns will appear and the layout will return to a single column layout.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5ad4c71604286307509275ad/file-FtRgR64d1I.png)

The GIF below demonstrates how the browser releases the columns and drops the gap when the browser width narrows. 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5aba1ff02c7d3a0e9366c44b/file-opf9FJzJDv.gif)

#### Multi column - Browser support

Multi-columns have good browser support and even if your favourite browser doesn't support multi-column layouts, keep in mind that they degrade gracefully into a single column layout. A multi-column layout cannot break, it can only become a single column layout.

### Column Ordering

When columns collapse, for example on a mobile device, the content will appear in the order of its column position, from left to right.  While this is usually fine, in some causes it is important to be able to control in what order column content appears.

Canvasflow gives you the ability to control this order by switching from the 'Default' to 'Mobile First' option.  When the 'Mobile First' order is applied to a column, the order of the content will be reversed when viewed on a desktop or landscape tablet for example.

[![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5aabcce12c7d3a56d887076f/file-WGHibHet3r.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5aabcce12c7d3a56d887076f/file-WGHibHet3r.png)

It is important to remember that because Canvasflow is built on a mobile first framework, when using 'Mobile First', the order of the content within columns should represent the order in which you want them displayed on mobile devices.

### Notes

1. A 1x column cannot be split, but it is possible to set the width of the column.
2. 4x column components can only be split equally.
3. Multi-columns cannot be customised in the same way as a standard column.  The multi-column will define how the content appears when published.

Still need help? [Contact Us](https://docs.canvasflow.io/article/100-working-with-columns#) [Contact Us](https://docs.canvasflow.io/article/100-working-with-columns#)

Last updated on May 20, 2025

No results found