# Klink User Privacy Policy

Thank you for using the Klink App, which was designed and developed by Klink Technologies Limited ("we"), which owns all intellectual property rights. We understand the importance of your personal information and will do our best to protect the security and reliability of your personal information. We are committed to maintaining your trust in us and abide by the following principles to protect your personal information: the principle of consistent rights and responsibilities, the principle of clear purpose, the principle of choice of consent, the principle of minimum sufficient, the principle of ensuring security, the principle of subject participation, the principle of openness and transparency. At the same time, we promise that we will take appropriate safety protection measures to protect your personal information in accordance with the mature safety standards in the industry. Please read and understand this Privacy Policy carefully before using our products (or services). 

![screen gif showing the header of the glitch-in-bio remix being updated to say "hello, world!"](https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif)

## I. How we collect and use your personal information

Personal information means all kinds of information recorded by e-mail or other means that, alone or in combination with other information, can identify a specific natural person or reflect the activities of a specific natural person. We will only collect and use your personal information for the following purposes as described in this policy：

(a) Provide you with the service of viewing exchange rates and collecting information. We provide exchange rates, Gas prices and gold prices for our users. If you are using the most basic exchange rate checking function, then you do not need to register an account. If you wish to gain access to certain advanced features, then you will need to create an account. In order to complete the creation of an account, you may need to provide the following information: your name, cell phone number, e-mail address, created user name and password. However, if you do not provide this information, it will not affect the use of the basic functions of the Service. The information you provide above will be authorized to us continuously for the duration of your use of the Service. When you cancel your account, we will stop using and delete the above information.

(b) To conduct internal data analysis and research, third party SDK statistical services, and to improve our products or services. We collect data based on your interactions with us and the choices you make, including your privacy settings and the products and features you use. The data we collect may include IP address, platform, timestamp, unique device identifier, iOS advertising identifier (IDFA), Android advertiser identifier, network card (MAC) address, International Mobile Equipment Identifier (IMEI), device model, end device operating system version, language location, time zone and network status. When we want to use the information for other purposes not described in this policy, we will ask for your consent in advance. When we use information collected for a specific purpose for other purposes, we will ask for your prior consent.。

(c) The permissions and related reasons that this App will request include the following categories.

(d) Requesting access to the network: as software that relies on real-time exchange rate, gas price and gold price data, it needs access to the network in order to properly obtain the latest data, upload feedback information, submit business transactions, etc.

(e) Request access to MAC address of cell phones: in order to collect abnormal or crash data and help technical staff to fix bugs in time

(f) Request permission to obtain IMEI information: in order to collect abnormal crash data and help technicians fix bugs in a timely manner

(g) Request permission to obtain directional push: if an abnormal situation such as repeated login is detected in the user account, it is necessary to rely on the device number and other information to send alert notifications to the user

## II.How we share, transfer and publicly disclose your personal information

Then click **Preview** at the bottom of this window and then **Preview in new window** to see the live app in its own window, with a free `glitch.me` domain ready to share. 

📝 _Make sure to log into Glitch to save your new app or else it will expire in 5 days._


### 2. Edit `settings.json` to add your own info and links

Replace the meta info, links and social sites we added for you in `settings.json` and you'll see your changes instantly updated in real time! 

If you want to include images, upload them in `assets` and copy the URLs into your settings JSON too–_make sure you have a theme selected that shows images like `gallery` or `menu`_.


### 3. Choose a theme

To help you make the site your own we've included some themes. In `settings.json` you can enter `glitch`, `gallery`, or `menu` as the value for `theme`. 

📝  _If you want to see how these themes are made, look in the `public/styles/themes` directory! If you don't have a valid theme entered, the site will default to the styles outlined in `style.css`._

### ...or create your own!

Customize your site by updating `custom-theme.css` inside the `public/styles/themes` folder with CSS to update colors, fonts, or any other style rules. Update your `theme` in `settings.json` to `custom-theme` to have the app use those new rules.

📝 _You can rename `custom-theme.css`, just make sure you use the new file name as your theme value in `settings.json`._

🖼️ Check out examples of other themes the community has created in [this Playlist](https://glitch.com/@glitch/featured-glitch-in-bio-remixes) and [submit your own](https://forms.gle/9WFWjSmhdiEoRgVs5) to share!

## Other Tips & tricks

Get **verified** links by adding `rel="me"` to your anchor tags in `layout/social.html` like this for Mastodon:

```
<!-- Mastodon -->
{{#if settings.social.mastodon}}
<a
  aria-label="{{settings.name}} on Mastodon"
  href="{{settings.social.mastodon}}"
  tabindex="-1"
  rel="me"
>
```

* Check out the [Glitch-in-bio section of our Help Center](https://help.glitch.com/kb/section/13/) for more documentation on how to customize or troubleshoot your new app!
* If you notice your preview is a little out of sync with your `settings.json`, hit the reload button in the preview window and it should update!
* Looking for ways to extend your app, or for inspiration? Check out the official [Glitch-in-bio page](https://glitch.com/glitch-in-bio).

## What's in this project?

← `README.md`: That’s this file. You can delete it, or keep it handy so you don't lose the instructions.

← `index.html`: This is the main page template vite uses to build your site. You'll see the handlebars syntax for importing the data you specify in `settings.json` (built into the structures in `layout/`). You'll also find some tips on configuring the page in the HTML comments.

← `settings.json`: Settings for your name, links, images, and social media. The `index.html` page includes the data using the structures defined in `layout/`.

← `layout/`: Markup templates — you can edit every line of HTML or never even look at any of it. The data you specify in `settings.json` will be built into the page using the HTML in here using handlebars syntax (e.g. `{{settings.name}}`).

← `public/styles/`: Stylesheets for Glitch in Bio, including alternate themes. Change your theme in `settings.json`. You can create a new theme by adding a CSS file to this folder and specifying it using its name in the settings (e.g. `glitch`, `gallery`, `menu`, or whatever yours is called!)

← `public/manifest.json` and `public/sw.js`: These set your site up to function as a Progressive Web App (PWA)–if you add new assets (e.g. stylesheets) you can include them in the list in `sw.js` to cache your site for offline viewing.

← `assets`: Add images here and copy the links into `settings.json` to show them in your site.

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.
