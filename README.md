# ![Screenshot of XAMPP XAMPP Logo](assets/favicon/favicon-32x32.png)  XAMPP Dashboard  

# Welcome to the XAMPP Dashboard ! 

Attention developers!
Are you tired of sifting through a cluttered directory to find your projects and files? Look no further than our customized user interface designed specifically for your Laragon server.


🚀 Pros & Devs love [XAMPP](https://apachefriends.org) and for sure will love our [laragon Dashboard](https://github.com/LebToki/xampp-Dashboard) since the combination of that stack makes it unbeatable!

<br>

![Screenshot of XAMPP Dashboard Promo ](assets/LaragonDash.jpg)
![Screenshot of XAMPP Dashboard Page](assets/01-Dashboard.png)
![Screenshot of XAMPP Dashboard Mailbox](assets/02-MailBox.png)
![Screenshot of XAMPP Dashboard Server Vitals](assets/03-Server-Vitals.png)

<br>
Our UI automatically detects any projects and directories within your root directory, making it easy to manage your work. Plus, we've included an automated auto-detection for popular frameworks like WordPress, Laravel, and Symfony. We've gone the extra mile to provide a visually appealing and intuitive interface that's easy to navigate, so you can spend more time coding and less time searching for files. And with a responsive design, you can access our UI on any device.

# ![Screenshot of Laragon Dashboard Logo](assets/favicon/favicon-32x32.png)  Key Features

| Clean and Modern Design | Efficient Management |   Seamless on Any Device | Auto-Detection |  
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| Provides a clean and modern design that is both easy on the eyes and easy to navigate. | Automated auto-detection for popular frameworks like WordPress, Laravel, and Symfony. | Designed to work seamlessly on any device, from desktop computers to mobile phones.   | Automated auto-detection for popular frameworks like WordPress, Laravel, and Symfony.                                     

<br>

> Note: bigger better features coming soon just waiting for the next release of Laragon

<br>

# ![Screenshot of XAMPP Dashboard Logo](assets/favicon/favicon-32x32.png)  How to use

1. Replace the default index.php file in your XAMPP root directory with our customized index.php file.
2. your laragon hostname template (.local) will be automatically detected and served here (line 249 is your friend)

```[php]
   function getLocalSites($server = 'apache', $ignoredFiles = ['.', '..', '00-default.conf']): array{}
```

3. Upload the icons and CSS files to the assets directory (or simply import them as is).

4. add whatever directories that you don't intend to expose publicly (line 316)

```[php]
$ignore_dirs = array('.', '..', 'logs', 'access-logs', 'vendor', 'favicon_io', 'assets');
```

# ![Screenshot of XAMPP Dashboard Logo](assets/favicon/favicon-32x32.png)  Feedback
- We're confident that our dashboard will enhance your development experience and streamline your workflow. Try it out today and let us know what you think! Join the discussions and let's make Laragon Dashboard the best it can be.
- Don't forget to star the project to stay up-to-date on future improvements, and please share your feedback with us. We're always looking for ways to make our dashboard even better for you.

# ![Screenshot of XAMPP Dashboard Logo](assets/favicon/favicon-32x32.png)  Changelog
### What's New in 2.3.3 · May 31, 2024 
(major release re-written ground-up with languages support, mailbox and stack's Vitals )

**Introduced Language Translation Support**
- Implemented language translation support using JSON files.
- Fixed (de, en, es, fr, pt and tl for now)

**Introduced Breadcrumbs and Tabs:**
Introduced breadcrumb headers for each tab for better navigation.

These tabs are now in place:
- Servers Tab
- Mailbox Tab
- Server or Stack Vitals

**Other Updates and Improvements**

- HTML Structure:
Refactored HTML structure to include header for each tab within the tab content.
Updated navigation tabs to include servers, mailbox, and vitals.
- CSS Styling:
Improved overall styling with Bootstrap 5.
Added custom styles for tabs, headers, and overview cards.
- JavaScript Functionality:
Enhanced tab switching functionality with jQuery.
Added language selector change event to reload the page with the selected language.
- PHP Code Enhancements:
Refactored server information retrieval and display logic.
Enhanced error handling for server vitals data retrieval.

📢️ Thanks everyone for your support and words of love for XAMPP Dashboard, I am committed to creating the best Stack Dashboard to support the ever growing community of Laragon



<details>
<summary>Changes in Version 1.0</summary>

- Improved Error Handling and Security:
- Enhanced handleQueryParameter function with input validation and escaping of outputs to prevent XSS attacks.

**Updates and Enhancements:**
- Improved getServerExtensions function to handle Apache modules correctly.
- Updated getPhpVersion function to retrieve the latest PHP version from the official PHP website.
- Improved getSQLVersion function to handle MySQL version retrieval correctly.
- Enhanced getLocalSites function to ignore specific directories and files.
- Updated renderLinks function to prevent XSS attacks.
- Improved getSiteDir function to handle server software detection correctly.
- Removed the check for wp-admin when detecting Laravel.
- Removed the "Admin" link from the HTML output for Laravel applications.
</details>

<details>



For full details and former releases, check out the [changelog](changelog.md).


<br/>
And don't worry, we've taken care of cleaning up all PHP calls, providing error responses, and removing redundant codes.

This is good enough to be the official index page of XAMPP to replace the vanilla XAMPP server index page, and offers several key features that make it an essential tool for developers:

Stay ahead of the curve with Laragon Dashboard and connect with me and with the other contributors of the XAMPP Dashboard project. We now support language files so feel free to contribute and send us your translations to include them in the next upcoming releases.

We're confident that our dashboard will enhance your development experience and streamline your workflow. Try it out today and let us know what you think!

Don't forget to star the project to stay up-to-date on future improvements, and please share your feedback with us. We're always looking for ways to make our index page even better for you.

<br/>

# ![Screenshot of XAMPP Dashboard Logo](assets/favicon/favicon-32x32.png)  Get Involved

Whether you're a developer, system integrator, or enterprise user, you can trust that we did everything possible to make it as smooth and easy as 1,2,3 to set up our XAMPP Dashboard.

- [ ] ⭐ **Give us a star** on GitHub 👆
- [ ] ⭐ **Fork the project** on GitHub and contribute👆
- [ ] 🚀 **Do you like to code**? You're more than welcome to contribute [_Join the Discussions!_](https://github.com/LebToki/xampp-Dashboard/discussions) 
- [ ] 💡 Got a feature suggestion? [_Add your roadmap ideas_](https://github.com/LebToki/xampp-Dashboard/issues)

<br/>

This project is licensed under the Attribution License.
<p xmlns:cc="http://creativecommons.org/ns#" >This work by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://2tinteractive.com">Tarek Tarabichi</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>


2023-2024 · Tarek Tarabichi [2tinteractive.com](https://2tinteractive.com) · Made with 💙
