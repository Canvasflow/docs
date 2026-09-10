# Source: https://docs.canvasflow.io/article/211-linking-to-hidden-content

# Linking to Hidden Content

There are times when you may want to link to a content item, but restrict access to it via any other way. The process to do this is as follows:

1. Within Twixl, create a new cell style named, for example, 'HiddenContent'.
2. Change the structure of the cell style so it has zero columns, and zero rows, across Mobile, Tablet, and Desktop, then save.

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bffece904286304a71cc9bc/file-RBYfNBkS9y.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bffece904286304a71cc9bc/file-RBYfNBkS9y.png)

3. In Canvasflow, add the content you wish to hide, or edit existing content. Then apply the 'HiddenContent' cell style from the `Edit` menu.

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bffedd204286304a71cc9c3/file-KnuGHnl2ok.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bffedd204286304a71cc9c3/file-KnuGHnl2ok.png)

4. We recommend creating a 'HiddenCollection' denoted Twixl Collection purely to store content that will only be accessible via links, as this helps keep your brand organised.
5. Move the content item into `'HiddenCollection'`
6. Navigate to the article you'd like the link to be placed in.
7. Highlight the text you'll use to create a link from, this displays the text formatting tool.
8. Select the `Hyperlink` icon.
9. Under 'URL', enter `tp-collection://TWIXL-COLLECTION-NAME/TWIXL-ARTICLE-NAME`

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bffef4004286304a71cc9ce/file-ZmxD4bw3O8.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bffef4004286304a71cc9ce/file-ZmxD4bw3O8.png)

10. To find 'TWIXL-COLLECTION-NAME' and 'TWIXL-ARTICLE-NAME', navigate to the collection and article via the Twixl Distribution Platform, and are alphanumeric ID's (Not 'Titles')

 [![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5bfff02704286304a71cc9d7/file-s1KudSIAuX.png)](https://s3.amazonaws.com/helpscout.net/docs/assets/571df1d49033600cce434499/images/5bfff02704286304a71cc9d7/file-s1KudSIAuX.png)

Any published content using the 'HiddenContent' cell style will now publish just like any other content, but will not be visible in the Twixl frontend.

Although not recommended, if you would like to place hidden content into the same collection as the article you're linking from, you can use `tp-pagelink://articlename` instead, bypassing the need for a hidden collection.

Still need help? [Contact Us](https://docs.canvasflow.io/article/211-linking-to-hidden-content#) [Contact Us](https://docs.canvasflow.io/article/211-linking-to-hidden-content#)

Last updated on July 7, 2025

No results found