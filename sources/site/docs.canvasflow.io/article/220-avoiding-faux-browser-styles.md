# Source: https://docs.canvasflow.io/article/220-avoiding-faux-browser-styles

# Avoiding Faux Browser Styles

Using 'Style Builder' it’s easy to assign a custom font to one or more text components.

However, if content using a custom font is styled as **bold,** _italic,_ or **_bolditalic_**) and the font family does **not** include a bold or italic font, some browsers will compensate by trying to create the bold and italic styles themselves.  This effect is known as ‘faux browser styles’ and results in an awkward imitation of the real typeface.

## Saying ‘No’ to faux browser styles

If you have access to the bold or italic versions of your chosen font (and they have been enabled), it’s advisable to avoid these faux styles by setting the correct font styles for each of the possible states.  This ensures the design of your content is never compromised and it will display perfectly across all devices. 

### To find the names of fonts

1. Navigate to 'Publication Settings'.
2. Select `Fonts`.
3. From the list, note down the names of the font variations you wish to add.  For example, 'Aleo-Bold', 'Aleo-Italic' and 'Aleo-BoldItalic'.

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5da460dc2c7d3a7e9ae27676/file-zY4SwsJJ3K.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5da460dc2c7d3a7e9ae27676/file-zY4SwsJJ3K.png)

#### How to set the correct custom font

1. Open the style required.
2. From 'Style Builder', select the text component you want to customise.
3. Click the `Custom CSS Editor` button.  The ‘CSS Editor’ window will appear.
4. Select the `All` tab and apply the required rules (see below).
5. Click `Apply` and save the style.

The rule(s) you will require are:

```
p b {
    font-family: Aleo-Bold;  /* Bold font */
    font-weight: normal;
  };

  p i {
  font-family: Aleo-Italic;  /* Italic font */
  font-style: normal;
  };

  p b i {
  font-family: Aleo-BoldItalic;  /* Bold Italic font */
  font-weight: normal;
  font-style: normal;
 }
```

Once the above rules have been applied and saved, highlighting content (in the 'Article' or 'Template Builder') for an appropriate text component, then selecting  **bold**, _italic_ or **_bolditalic_** will apply the appropriate custom font instead of the inbuilt browser equivalent.

### Notes

1. The 'body {}' selector will always be pre-populated and cannot be edited. 
2. Ensure you include the **font-weight: normal;** & **font-style: normal;** rules.
3. Typically this rule will be applied to the paragraph component, but the rules can be used for any text component. 

Still need help? [Contact Us](https://docs.canvasflow.io/article/220-avoiding-faux-browser-styles#) [Contact Us](https://docs.canvasflow.io/article/220-avoiding-faux-browser-styles#)

Last updated on June 2, 2025

No results found