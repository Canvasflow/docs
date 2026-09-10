# Source: https://docs.canvasflow.io/article/205-custom-code

# Custom Code

In addition to the native media components, Canvasflow supports the ability to extend what is possible via the _'_Custom Code_'_ component. 

Using _'_Custom Code_'_ is a great way to enhance articles or templates by adding 3rd party content which is not natively supported.  This may be simple HTML markup, 3rd party embed scripts or custom created Zip files.

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5c7e591604286350d088a359/file-nUQJLyw7Oh.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5c7e591604286350d088a359/file-nUQJLyw7Oh.png)

#### Writing custom markup

In its most simple form, the custom code component can be used to add HTML markup, for example:

`<h1>Hello World</h1> <br> <p>My markup is added here</p>`

It is also possible to include a style block to apply styling.  

`<style> h1 {color:red; font-size:2em;} </style>`

`<h1>Hello World</h1><br>`

#### Using a 3rd party script

You can use custom code injection to add 3rd party scripts that enhance specific parts of your article. These might include live chat services, tweets, Facebook posts or form capture such such as Mail Chimp or Hubspot.

To embed a 3rd party script, paste the full script (including <script></script> tags) into the text area and save the article.  In most cases the newly embedded content will appear immediately but some scripts may require the page to be refreshed after saving.

#### Embedded content isn't displaying

As a security measure, sometimes embedded code or content doesn't appear when logged into the editor. As long as the code is valid, it should display to your visitors once published. To confirm visitors can see it, publish the article and try viewing it, or open it via the webreader viewer.

If you still can't see it, there's probably something wrong with the code. We recommend contacting the third-party service that provided the code for help.

#### Upload a Zip file

If your project requires more complex custom code, it might be more manageable to create the custom code in an external _Integrated Development Environment_ and create a Zip file which can then be uploaded directly to your article.

When creating a Zip file, you **must** ensure that an index.html file exists in the root of the Zip and all assets references are relative to the root of the file.  It is possible to reference external assets but these will not be available to an offline app. 

Once the Zip file has been created, use the `Select Zip` button to locate and upload the file.  Canvasflow will then process this file and display it in your article.  When publishing to a supported channel, all included assets will be delivered to the device and will be available offline. 

#### Full Bleed

Fits the custom code component to the full width of the canvas, overwriting any padding.

#### Inline Content

By default, custom code added is added to an article via an iframe.  This ensures the code being injected does not conflict with the existing Canvasflow codebase.  In most cases this is the best way to add custom code to your articles, however in some cases, depending on the type of custom code being added, it may be necessary for the code to be injected _inline_ to the page.

Examples of when using inline content is advisable:

- The script being used does not render correctly in an iframe. 
- The script being used needs to dynamically adjust the height of its container.
- You wish to reference CSS created in Canvasflow.

When inline content is enabled, you will be presented with the following warning:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5c7d5c5a2c7d3a0cb93231fd/file-5UuIbbWzGM.jpg)

Clicking `Yes`, will inject the code directly into the article.  If you notice any negative effects it is recommended that you do not save the article but simply refresh the browser to revert the change.

#### Display On Device

The _'_Display On Device' option allows you to choose which devices the custom code component will be displayed on. The defaults are mobile, tablet and desktop.

Still need help? [Contact Us](https://docs.canvasflow.io/article/205-custom-code#) [Contact Us](https://docs.canvasflow.io/article/205-custom-code#)

Last updated on May 20, 2025

No results found