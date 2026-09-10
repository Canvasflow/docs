# Source: https://docs.canvasflow.io/article/270-building-a-pwa

# Building a PWA

Progressive Web Apps (PWA’s) bring native app-like experiences and functionality to Coverflow. They are an extremely efficient way to deliver rich digital experiences which can be instantly consumed by anyone, on any device.  PWA’s can be built in just a few minutes, are fully customiseable and do not require submission to the Apple App Store or Google Play Store.

### **Creating a new PWA:**

1. Navigate to ‘Brand Manager’.
2. Click the `Settings` of the brand you would like to build a PWA for. 

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f5eb00a2dae5b58fb5507/file-aK2i4DOoKX.png)

3. From ‘Publish Channels’, select `Add New Channel` . 

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f5ed80a2dae5b58fb5508/file-CAGt4QS5X4.png)

4. Select `Web App (PWA)` , a number of configuration options will be displayed. 

 ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f5eed24d2d21e45edc062/file-7cFLCW8v4N.png)

### **Configuring the PWA:**

The configuration area is where your PWA can be customised and designed. This includes domain configuration, deployment settings and colour theming. The following properties can be defined:

- **Channel Name**: The name of your PWA channel.  This is only visible within the Canvasflow dashboard.
- **Language**: The default language of your content.
- **App Title**: The title for your app. This is displayed when an app is installed to a device's homescreen.
- **App Short Title**: The alternative title of the app to be used if there isn’t sufficient space for the full app title to be displayed on a particular device.
- **Domain**: The subdomain where the app will be hosted. This can be any valid subdomain (e.g. motornews, resulting in motornews.canvasflow.io).

### Notes

1. The domain cannot be changed via the UI once the PWA is built. 
2. The domain can be served from a custom or vanity domain / subdomain once in production. Please contact our support team for more information.

- **Issue Mode**:
 - **Single Issue**: When the app is opened, users will be taken directly to the first page of the latest issue. When a new issue is published it will replace the previous one.
 - **Multi Issue**: The app displays a newsstand layout and all available issues will be displayed when opening the app.
- **Paid Status**:
 - **Free** - The publication is free to access - all issues will be available without payment.
 - **Paid** -  Define the default price and currency for an issue. This can be overridden on a per issue basis if required. Enable this option if you wish to sell one or more issues under your brand.
- **Additional Languages**: Add support for multi language within the app. Additional languages can be enabled by adding comma delimited [ISO 639-1](https://www.google.com/url?q=https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes&sa=D&source=editors&ust=1614769019980000&usg=AOvVaw1orLusdc8Cpo9FT-mc1DxK) language codes (e.g. fr,de,en,es)
- **Reader Mode**: Provides users with an option to hide article images for a more condensed reading experience.
- **Font Size**: Provides users with a ‘Font Slider’ to manually control the size of text based content.
- **Text to Speech (TTS)**: When enabled, text to speech files will be automatically generated for each article and a play button will appear in the app.
- **Replica Mode**: Give users the option to switch between the replica (PDF) version and responsive versions of content.
 - **Is Default:** **Enabled**: Replica version will be shown by default, the user may switch to responsive mode if required.  
 - **Is Default: Disabled**: Responsive version will be shown by default, the user may switch to replica mode if required.

### Notes

Replica Mode only has an effect if the source content was imported via the Canvasflow PDF XFlow import service.  Please contact us to learn more about this service.

- **S3 Region**: Define the specific geographical region where app assets will be hosted. You are free to choose any region, however we recommend selecting the region geographically closest to your audience for minimal latency.  

The current regions available are:

- US East (Ohio)
- US East (N. Virginia)
- US West (N. California)
- US West (Oregon)
- Africa (Cape Town)
- Asia Pacific (Hong Kong)
- Asia Pacific (Mumbai)
- Asia Pacific (Osaka-Local)
- Asia Pacific (Seoul)
- Asia Pacific (Singapore)
- Asia Pacific (Sydney)
- Asia Pacific (Tokyo)
- Canada (Central)
- China (Beijing)
- China (Ningxia)
- Europe (Frankfurt)
- Europe (Ireland)
- Europe (London)
- Europe (Milan)
- Europe (Paris)        
- Europe (Stockholm)
- Middle East (Bahrain)
- South America (São Paulo)

### Notes

1. All PWA’s sit behind an AWS Cloudfront CDN that securely delivers all data to customers globally, with low latency and high transfer speeds.
2. The S3 region cannot be changed via the UI once the app is built.

- **Prompt Install Message**: When enabled, readers who navigate to the PWA domain on mobile will be prompted to install the app to their device.
- **Analytics and Marketing tools**: To enable 3rd party analytics and marketing services in an app, simply enter the appropriate ID or domain.
 - The currently supported services are:
 - Google Analytics
 - Google Tag Manager
 - Caymland M4
 - Ackee
 - Hotjar
 - Hubspot
 - ShareThis
- **Auto Download**:
 - **Disabled**: Users must explicitly click to download the current issue.
 - **Enabled**:  Content is automatically downloaded and intelligently cached for offline reading as soon as the first article is viewed.

### Notes

Enabling ‘Auto Download’ may result in higher bandwidth consumption for users.

- **Authentication**:
 - **Disabled**: Users are not required to authenticate to access content.  This option cannot be selected if content is being paid for.
 - **Enabled**: Users will be required authenticate via the relevant portal before content can be accessed or purchased using any of the following SSO authentication methods:
 - Apple
 - Google
 - Email
- **Protect App**: When enabled, a password is required before the app can be accessed.

### Notes

1. This feature is only intended for restricting access when testing a new app build or limiting access to a small number of users.
2. The app password is stored locally on the device and is only required to be entered once when accessing an app. 

- **Zoom**: If enabled, users can zoom in and out of the page.
- **Image Zoom**: If enabled, users can click an image to zoom in and out.

### Designing the PWA:

The design of the PWA is considered the 'Theme', split between a number of different components. This includes control of colours, buttons, backgrounds, and the choice of whether components such as 'Issue Ribbons' are displayed:

- **Splash Icon:** Show an app splash icon upon loading.
- **App Splash Background:** Background colour shown during loading.
- **App Icon Background:** Icon background colour.
- **Ribbons:** Displayed in the corner of an issue, denoting their free or paid status
- **Issue Title:**
- **Background:** Background colour in the PWA's root where the issues sit
- **Progress Bar:** Reader progress bar shown at the top of an issue
- **Top Nav Bar:** Top Navigation Bar that includes last page, download and Table of Contents controls
- **Buttons:** Buttons for purchases and subscriptions
- **Bottom Bar:**

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f649a661b720174a72c8a/file-oTYnv3ZmNV.png)

1. Once all options are configured, select `Edit Channel` at the bottom of the modal window to begin the PWA build.
2. When the app's build process completes, you can return to ‘Article Manager’ and begin publishing content. Alternatively, you can now navigate to the PWA via the subdomain you entered.

**Notes**

1. The app build process typically takes four to five minutes, however due to DNS resolution it may take up to 10 minutes before it becomes visible at the requested subdomain.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/603f66120a2dae5b58fb5558/file-ZnULXNReQm.png)

Still need help? [Contact Us](https://docs.canvasflow.io/article/270-building-a-pwa#) [Contact Us](https://docs.canvasflow.io/article/270-building-a-pwa#)

Last updated on June 30, 2025

No results found