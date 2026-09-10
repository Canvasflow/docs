# Source: https://docs.canvasflow.io/article/292-inherited-styles

# Inherited Styles

When working with very large brands or brands which require many different styles in order to support subtle style changes, management can quickly become complicated and time consuming. 

'Inherited Styles' provide a simple and efficient way to allow the creation of subtle style changes, without having maintain multiple copies of very similar article level styles.  Duplication of 'Article Styles' is advised against, due to the individual management required if global updates to them are required in the future.

Let’s take a look at a couple of worked examples to demonstrate the value of 'Inherited Styles'.

**Worked example 1:** 

The majority of your publication uses a single ‘Default Style’ which in addition to all other styling, defines a 5% top padding to the Canvas. This is perfect for most articles as normally the first component on the page is a headline.

Next, you create a new article which requires an image as the first component. The 5% top padding is no longer desirable as it creates unwanted space above the image.  By creating an inherited style (i.e. ‘Default no top canvas padding’) and setting the canvas top padding value to 0%, the top padding is removed but all other styles inherited from the parent are applied correctly (fonts, colours, etc).

The key benefit here is that if in the future you need to make a core style change to the parent style, all ‘Inherited Styles’ will be updated automatically.

**Worked example 2:** 

All articles in your brand use the same font for its text components. You achieve this by creating a ‘Article Style’ named ‘Core Style’. However, you have twelve sections in your magazine and it's a requirement that all headline and subtitle text components need to be a different colour.  

Using 'Inherited Styles' in this way can be managed easily. Simply create an 'Inherited Style' for each colour variant required (Style-Red, Style-Blue, etc), then change the colour of the headline and subtitle text components in each new style. You can then apply the this 'Inherited Style' to the appropriate article(s). 

While this could be achieved by duplicating the core ‘Article Style’ and changing the text colour for each version, if changes to the core style are required in the future, you'd need to make time consuming individual changes to each style. This method also guarantees that all edits stay consistent and error free.

### Notes

1. All components of ‘Inherited Styles’ inherit the properties of their parent style unless otherwise specified.

#### Creating an Inherited Style

1. Navigate to the ‘Style Manager’ from the ‘Styles’ tab.
2. Select the `Add New` option.

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f93be8502d1120e90d2e9/file-7noFFebti0.png)

3. Enter a 'Style Name'.
4. Under ‘Source’ select `Inherit From` .
5. Under ‘Existing Style’ select the style you wish to inherit the properties of. 

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f94c88502d1120e90d2fb/file-MtKIo1E2Mt.png)

6. Select `Create`
7. The new 'Inherited Style' will be indicated by the arrow and placed below its parent. 

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f953f8502d1120e90d301/file-xXeSi0ZknG.png)

#### Editing an Inherited Style

When editing an 'Inherited Style' for the first time, all its properties will appear greyed out. This is because before any changes are made, the component inherits the entirety of its properties from the parent style.

When a property is changed (e.g. text size or colour), it is overridden and will stop inheriting the changed value(s) from the parent.  You can choose to override as many or as few properties as you require. 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f974e8502d1120e90d311/file-jwJStZEQfD.png)

In the example above, the ‘Line Height’ property is now overridden and no longer inherits from the parent style.

### Notes If the subtitle font of the parent style is changed, it will also change in the inherited style.

#### Reverting an Inherited Style Property

It is possible to revert an overridden property to its original state by double-clicking on the property name.  This will cause the value to return to the value of its parent style. 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f979d0a2dae5b58fb56ea/file-CG71Ac3pYa.png)

#### Applying an Inherited Style

Applying an 'Inherited Style' is the same as [applying a regular style](https://docs.canvasflow.io/article/68-changing-the-current-style). It can be achieved via both 'Article Manager' and 'Article Editor':

1. Access the article you want to edit.  'Article Builder' will appear.
2. From the 'Article Toolbar', click the `Style Menu` (top right) and select the style you want to apply.    

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f98cd8502d1120e90d319/file-pxDYfhpClb.png)

3. Once the required style has been applied, click outside of the 'Style Menu' to close the panel.
4. Click `Save` to apply the style change.

Still need help? [Contact Us](https://docs.canvasflow.io/article/292-inherited-styles#) [Contact Us](https://docs.canvasflow.io/article/292-inherited-styles#)

Last updated on June 2, 2025

No results found