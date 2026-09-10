# Source: https://docs.canvasflow.io/article/201-wordpress-to-canvasflow-connector-config

# WordPress to Canvasflow - Connector Config

Once the plugin has been successfully connected, a new menu option - _HTML To CF Connector_ - is exposed in the settings area of the Canvasflow publication.  This menu provides additional connector configuration.  To begin, click _Configure Connector,_ you will be presented with a _c_onfiguration screen.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b685d4e2c7d3a03f89d64bb/file-ttKkJoUbKC.png)

## Components

The component section makes it possible to control how the mark-up from a WordPress article is converted when published to Canvasflow.  By matching the incoming HTML tag (eg. H1, H2) to the required Canvasflow component type (Title, Subtitle), you can minimise any post publish editing while ensuring the correct structure of your article.

By default, Canvasflow matches the basic HTML tags to the corresponding Canvasflow components.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b685db52c7d3a03f89d64c1/file-p4y4MxPR2G.png)

#### To add a new component

1.  In the components section, click the '_Add'_ button.
2. In the HTML TAG field, enter the name of the HTML tag, e.g.: H6
3. In the corresponding CF component field, select the component you wish to match it to
4. Click '_Save Changes_'.
5. The next time you publish from WordPress, any HTML tag that matches a component will be automatically converted and styled appropriately

#### To edit an existing component

1. In the components section, find the corresponding Canvasflow component to the HTML tag you wish to edit and click to select a new option.
2. It's also possible to just rename an existing HTML Tag
3. Click '_Save Changes'_

#### To delete an existing component

1. In the components section, find the component you wish to remove
2. Click the '_delete'_ (trash icon) button
3. The component will be deleted
4. Click '_Save Changes_'

## Galleries

Coming soon – does not currently have an effect.  

## Column Structures

Coming soon – does not currently have an effect.  

## Content Excludes

By default, everything that exists in the ‘body’ field of an WP post will be transferred to Canvasflow at the point of publish.  There may however be occasions where it is not desirable to publish all body content. For example, a post may include social links or author information that may not be required when publishing to Canvasflow.

The 'Content Excludes' feature provides a simple way to exclude content from being processed by Canvasflow, by filtering out all content that matches a particular attribute. For example you may wish to exclude all `<span>` with a `<span class='author'>`, all div's with an `<div id='social'>`, or a paragraph with `<p class='intro'>`.

#### To add a new exclude

1. In the custom exclude section, click the _Add_ button.
2. Enter the name of the HTML ATTRIBUTE you wish to target.  This will typically be **class** or **div**
3. In the ATTR VALUE field, enter the value of the ATTRIBUTE you wish to target, eg. **author** or ‘**social**
4. Click '_Save Changes_'.  The next time you publish, any content that matches an active exclude will no longer appear in a published article

#### ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b685e600428631d7a89b1c4/file-u7FLvZHwz4.png)To delete an existing exclude

1. In the Exclude section, find the exclude you wish to remove.
2. Click the '_delete_' (trash icon) button
3. The exclude will be deleted
4. Click '_Save Changes_'.

Still need help? [Contact Us](https://docs.canvasflow.io/article/201-wordpress-to-canvasflow-connector-config#) [Contact Us](https://docs.canvasflow.io/article/201-wordpress-to-canvasflow-connector-config#)

Last updated on July 7, 2025

No results found