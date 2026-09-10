# Source: https://docs.canvasflow.io/article/198-publishing-from-wordpress-to-canvasflow

# WordPress to Canvasflow - Plugin

**To begin publishing from WordPress please** [request an API key](https://canvasflow.io/apikey-request) **to enable WordPress publishing for your account.**

To get started, follow the steps outlined below to set up your WordPress instance and Canvasflow account.

### Installing the Canvasflow for WordPress Plugin

1. Download the Canvasflow WordPress Plugin by searching from the Plugins page found in your WordPress dashboard (alternatively download [here](https://wordpress.org/plugins/canvasflow/) and extract to ‘/wp-content/plugins/canvasflow’)
2. Activate the plugin. Please [Click here](https://docs.canvasflow.io/article/199-unable-to-activate-cf-wp-plugin) If you have trouble when attempting to activate the plugin 

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61a72b2c7d3a03f89d3b57/file-gkgFocou68.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61a72b2c7d3a03f89d3b57/file-gkgFocou68.png)

**To configure your plugin:**

1. Navigate to the 'Canvasflow' tab now found in your WordPress dashboard
2. Select _'Settings'_
3. Paste the API key provided into the API field and save to validate and sync
4. Select the publication you wish to connect to
5. Select the default style you'd like applied to your published articles (This can be overridden when you publish an article if required
6. **Include Title**: Choose whether you'd like to include the article Title in content published to Canvasflow (When disabled, only the post's body content will be published)
7. **Auto Publish**: Choose whether you'd like content to be auto-published to the connected distribution platform when publishing from WordPress (e.g. Wordpress -> Canvasflow -> Twixl App)
8. **Custom Post Types**: Add any custom post types set up in your WordPress instance to make them eligible for publishing
9. **Merge Adjacent Paragraphs**: Disabling this option forces paragraphs to be treated as individual components within Canvasflow. For example, if the option is disabled and an article with adjacent paragraphs is published to Canvasflow, it will output in Canvasflow as:

\[Title\] \[Paragraph\] \[Paragraph\] \[Image\]     

\--rather than--

\[Title\] \[Paragraph\] \[Image\]

(each closed bracket representing an individual component)

[![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61c6b20428631d7a898cdd/file-pzoBsm7qOR.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61c6b20428631d7a898cdd/file-pzoBsm7qOR.png)

---

### Publishing an article from WordPress

With the plugin installed and connected to Canvasflow, a Canvasflow Publish Widget will be displayed in the Editor of any post, next to where you find Metatags, Feature Image and Category options. Here's an example: 

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61c8a90428631d7a898d01/file-LuiWTOoNK8.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61c8a90428631d7a898d01/file-LuiWTOoNK8.png)

### Note:

If this widget isn't visible after installing the plugin, it may need to be enabled using the ' _Screen Options_' menu at the top right

The publish widget enables content to be published from within the editor to fit seamlessly into your workflow. Simply select a Style (or leave as default) and select ‘ _Publish to Canvasflow_’.

If you are connected to an Issue-based publication or a Twixl Publisher channel which makes use of ‘Collections’, the option to publish to a specific Collection or Issue will also appear as an optional menu option.

**Publish Status**

When a post is successfully published, a ' _Success_' message will be displayed and its status will change to ' _In Sync_':

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61cb520428631d7a898d22/file-jh2wqvt5Kn.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61cb520428631d7a898d22/file-jh2wqvt5Kn.png)

Should for any reason the post fail to publish an 'Error' message will appear. If an error message is displayed, it's advised to check your plugin settings to ensure the correct API key and publication has been selected.  Please [contact our support team](mailto:support@canvasflow.io) if you have problems when attempting to publish article content.

### Using the Post & Upload Manager

For more control over publishing content, the Canvasflow plugin provides two additional menus:

**Posts Manager**

This is where you'll find a list of all content items that exist in your WordPress instance. This list consist of posts, pages and other eligible content types (see custom post types) that can be published to Canvasflow.

1. Select the article(s) you would like to make eligible to be published to Canvasflow
2. Click '_Save_' to confirm
3. The selected article(s) will now be available via the '_Upload Manager_' menu

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61cc572c7d3a03f89d3e49/file-JpJBDLieCk.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61cc572c7d3a03f89d3e49/file-JpJBDLieCk.png)

**Upload Manager**

Within the ' Upload Manager', you'll find all articles selected from the 'Posts Manager' and articles that have been previously published from the publish widget. Using the item options you can:

- Upload / Update - Uploads the article to Canvasflow.  This button can take several different forms which indicate the current status of the article.
 - Grey - Indicates a new article that has never been published to Canvasflow
 - Green - Once successfully published. the upload icon will appear green indicating it is synced with your Canvasflow publication
 - Orange - An article that has previously been uploaded to Canvasflow but whose content has been changed will display an 'orange' upload icon, indicating it is out of sync with your Canvasflow publication.  Click publish to update the article content.
- Collection/Issue/Style - The options are displayed depending on what is available in the connected publication. For example, an '_Issue_' tab will be available if connected to an Issue-Based Canvasflow publication, and '_Collection'_ will be available if connected to a publication with collections set up

[![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b61d07b2c7d3a03f89d3e80/file-g48jPpQ61b.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5b61d07b2c7d3a03f89d3e80/file-g48jPpQ61b.png)

#### 

---

#### [Now configure the HTML to Canvasflow connector](https://docs.canvasflow.io/article/201-wordpress-to-canvasflow-connector-config).

Still need help? [Contact Us](https://docs.canvasflow.io/article/198-publishing-from-wordpress-to-canvasflow#) [Contact Us](https://docs.canvasflow.io/article/198-publishing-from-wordpress-to-canvasflow#)

Last updated on September 5, 2019

No results found