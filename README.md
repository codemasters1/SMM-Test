<div class="content pb-4">

<section class="my-3" id="section-intro">

# Intro

**smmbooster** is an online social media marketing tool (web application) built using laravel, this application that allows you to sell ayour Social Media Marketing Services or resell other SMM panel services via api providers . You can provide quality and cheap SMM Services to your customers, they can buy all packages or services like Facebook likes, Instagram followers, Twitter followers, Youtube Viewers, website traffic and many more using your the panel. You can create as many as services & packages according to your expertise, this is a completely dynamic panel. Whether it is something you need for your social media accounts or you are a SMM services reseller.

</section>

<section class="my-3" id="section-requirements">

# Requirements

**smmbooster** script is built with Laravel 8, The Laravel framework 8 has a few system requirements. You should ensure that your web server has the following minimum PHP version and extensions

<table class="table mb-3 table-bordered table-hover table-vcenter">

<tbody>

<tr>

<td>Server</td>

<td>Apache/Nginx</td>

</tr>

<tr>

<td>PHP version</td>

<td>PHP version >= 7.3</td>

</tr>

<tr>

<td>allow_url_fopen</td>

<td>`allow_url_fopen=On` (php.ini file)</td>

</tr>

<tr>

<td>PHP cURL</td>

<td>Required. (Curl Library, Curl_init Function and Curl_exec)</td>

</tr>

<tr>

<td>PHP OpenSSL</td>

<td>Required. (For secure data encryption.)</td>

</tr>

<tr>

<td>PHP PDO</td>

<td>Required. (To create secure connection to MySQL server)</td>

</tr>

<tr>

<td>Zip</td>

<td>PHP zip extension is required (for updating, installing etc)</td>

</tr>

<tr>

<td>PHP CURL</td>

<td>PHP CURL extension is required</td>

</tr>

<tr>

<td>Mod Rewrite Enabled</td>

<td>Required</td>

</tr>

<tr>

<td>Mbstring PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>XML PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>Tokenizer PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>JSON PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>Ctype PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>BCMath PHP Extension</td>

<td>Required</td>

</tr>

<tr>

<td>Fileinfo PHP Extension</td>

<td>Required</td>

</tr>

</tbody>

</table>

</section>

<section class="my-3" id="section-install">

# How to install

Step-by-step guides to set up this script on your web application. Please read the following guide carefully.

<div class="font-weight-bold">Step 1 - Upload and Extract a Zip Archive</div>

Upload the installed zip archive to your web hosting. And then extract all files

<div class="font-weight-bold">Step 2 - Go to installation page</div>

Open your browser and go to installation page. (In this case, this is `www.yourdomain.com`)

<div class="font-weight-bold">Step 3 - Fill out all the requested informations.</div>

After redirecting to installation page, you have to fill the form with all the requested informations (purchase code, database name, database password ...etc)

<div class="font-weight-bold">Step 4 - Finish Installation.</div>

Click Finish Button after filling all the requested informations on the step 3\. You will see successfully message after few seconds, if everything is exactly.

</section>

<section id="section-category">

# Add category

Admin Panel is completely dynamic, so you can add/update categories.

1.  Log into admin, Go to categories
2.  Click add new.
3.  Write Name of Category, description and Status which is active by default, choose sort number etc
4.  When you want to deactivate category, just make status deactive.
5.  Click Save button

</section>

<section id="section-service">

# Add service

Admin Panel is completely dynamic, so you can add/update services.

1.  Log into admin, Go to services
2.  Click add new.
3.  Choose service type api or normal.
4.  Write Name of Service, description and Status which is active by default etc
5.  Price Per Single item. Ex: price for 1 Like = 0.01 etc.
6.  Minimum quantity - Ex: 100.
7.  Maximum quantity - Ex: 3000.
8.  When you want to deactivate Service, just make status deactive.
9.  Click Save button

</section>

<section id="section-order">

# Add order

Any User can place new order.

1.  Log into admin, Go to orders
2.  Choose order category.
3.  Select a service.
4.  Add a valid link.
5.  Add quantity.
6.  Click Save button

</section>

<section id="section-api">

# Add new API provider

Any Admin can place new API provider.

1.  Log into admin, Go to API providers
2.  add name and URL .
3.  add Api key provided by the api provider.
4.  When you want to deactivate Service, just make status deactive.
5.  Click Save button
6.  You will see the api is connected and the api will fetch all the service and categories automatically

the script is compatible with the most many smm panels if you want to resell services.

*   [MOMO panel](https://momopanel.com/)
*   [VINA SMM](https://vinasmm.com/)
*   [HQ SmartPanel](https://hqsmartpanel.com/)

</section>

<section id="section-settings">

# Adjust settings

There are many settings that an admin can change as needed.

1.  general Settings : to adjust general settings.
2.  Service Settings : to adjust service settings.
3.  Appearance Settings : to adjust appearance settings.
4.  Languages : to add new language or adjust any existing languages.
5.  Seo Manager : to adjust seo and and meta informations and key words.
6.  Terms and Policy : to adjust terms and policy pages.
7.  Email Settings : to adjust emails templates.
8.  Faqs : to manage faqs.
9.  Announcements : to manage announcements.

</section>

<section id="section-integrations">

# Integrations

### Paypal Integration

create PayPal API Client ID and Client Secret :

1.  Open the following website [https://developer.paypal.com](https://developer.paypal.com) and click on "Log into Dashboard".
2.  After you have logged in, create a Sandbox Business Account to be able to make test payments later.
3.  If you have created a sandbox account, click on "My Apps and Credentials" in the menu on the left and then on "Create App"
4.  Give your Paypal app a name and choose your previously created developer (sandbox) account. After you have finished, click on "Create App".
5.  As soon as the app is created, the details of the app you just created will open. You should now see the Client ID and an option (Show) below to see the Secret Key.
6.  switch between Live and Sandbox click first on "My Apps & Credentials" in the left main menu then click on Live or Sandbox and then on the desired app you want to know the Client and Secret keys. Note that Sandbox and Live have different Client IDs and Secret Keys.

enable Paypal payment method :

1.  Log into admin, Go to Payments Methods
2.  choose paypal.
3.  Edit your paypal parameters.

### Stripe Integration

Get Credentials for Stripe Connect Payments :

1.  Log in to your Stripe account or create a new one at the [Stripe website](https://stripe.com/).
2.  Choose Settings and then select API keys on the sidebar of the Stripe dashboard.
3.  On the API keys page find the Publishable key and Secret key fields and copy their values.

enable Paypal payment method :

1.  Log into admin, Go to Payments Methods
2.  Choose Stripe.
3.  Paste these keys into the corresponding fields of the Stripe Connect payment method settings.

</section>

<section id="section-support">

# Support & Tickets

To answer your customers tickets or create new one.

1.  Log into admin, Go to tickets
2.  Select ticket to answer or click new to add new ticket
3.  Every time ticket status changed you well see notification in your dashboard

</section>

<section class="mb-4" id="section-changelog">

# Version History (Changelog)

version 1.0 – 06-12-2021 - Initial Release

</section>

<section class="mt-4" id="section-thank-you">

# Thank You!

Thank you so much for supporting our work by choosing our item! We wish you all the best with your upcoming projects and endeavours in life! If you would like to check out more of our work, be sure to visit our website.

As I said at the beginning, I'd be glad to help you if you have any questions relating to this item

If you have any queries, please feel free to contact as at: `mediarayek.me@gmail.com`

</section>

</div>