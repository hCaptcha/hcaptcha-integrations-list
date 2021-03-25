# hCaptcha integrations list
A collection of all known integration packages for hCaptcha. 

**This is a community-maintained list.** Added or found another one? Open a PR to submit it! 
(Instructions: run `npm install`, edit README.md, then run `./upd_toc.sh` to re-create the TOC.)

## Table of Contents

<!-- toc -->

- [Frontend](#frontend)
  * [JavaScript](#javascript)
    + [ReactJS](#reactjs)
    + [Vue JS](#vue-js)
    + [Angular JS](#angular-js)
    + [Ember.js](#ember.js)
    + [Vanilla JS (use with Angular, Vue, etc)](#vanilla-js-use-with-angular-vue-etc)
    + [Plain JS reference](#plain-js-reference)
- [Backend](#backend)
  * [Plain PHP](#plain-php)
  * [Laravel](#laravel)
  * [Python: Django + Crispy](#python-django--crispy)
  * [node.js](#nodejs)
  * [Go middleware](#go-middleware)
  * [curl](#curl)
  * [Elixir](#elixir)
  * [Java](#java)
  * [Cloudflare Worker siteverify](#cloudflare-worker-siteverify)
- [Native Integrations: CMS platforms](#native-integrations-cms-platforms)
  * [XenForo](#xenforo)
  * [MyBB](#mybb)
- [Plugins](#plugins)
  * [Magento](#magento)
  * [Drupal](#drupal)
  * [SMF](#smf)
  * [XenForo](#xenforo-1)
  * [Vanilla Forums](#vanilla-forums)
  * [WordPress](#wordpress)
  * [WordPress WPForms Plugin](#wordpress-wpforms-plugin)
  * [Joomla](#joomla)
    + [Joomla RSForm!Pro Plugin](#joomla-rsformpro-plugin)
  * [Symfony](#symfony)
  * [Typo3](#typo3)
  * [Umbraco](#umbraco)
    + [UmbracoForms.uCaptcha](#umbracoformsucaptcha)
- [Chat protection bots](#chat-protection-bots)
  * [Telegram](#telegram)
- [Mobile apps](#mobile-apps)
  * [Android](#android)
  * [Flutter](#flutter)
- [More](#more)
  * [.NET and ASP.NET Core](#net-and-aspnet-core)
  * [RoundCube](#roundcube)

<!-- tocstop -->

## Frontend

### JavaScript

#### ReactJS
[hCaptcha Component Library for ReactJS](https://github.com/hCaptcha/react-hcaptcha)

#### Vue JS
[hCaptcha Component Library for Vue.js](https://github.com/hCaptcha/vue-hcaptcha)

#### Angular JS
[hCaptcha Component Library for Angular](https://github.com/leNicDev/ng-hcaptcha)

#### Ember.js
[hCaptcha Component Library for Ember.js](https://github.com/sinankeskin/ember-h-captcha)

#### Vanilla JS (use with Angular, Vue, etc)
[Source](https://github.com/DSergiu/vanilla-hcaptcha)
[NPM](https://www.npmjs.com/package/vanilla-hcaptcha)

#### Plain JS reference
[Official docs](https://docs.hcaptcha.com/)


## Backend

### Plain PHP 
[Full example blog with source](https://medium.com/@hCaptcha/using-hcaptcha-with-php-fc31884aa9ea)

### Laravel
[Full example blog with source](https://serversideup.net/laravel-hcaptcha-custom-validation-rule/)

[Package #1 source](https://github.com/tojorodialson/hc-laravel)
[Package #2 source](https://github.com/Scyllaly/hcaptcha)
[Package #3 source](https://github.com/thinhbuzz/laravel-h-captcha)

### Python: Django + Crispy
[Blog post with source](https://medium.com/python-in-plain-english/how-to-add-hcaptcha-to-your-django-crispy-form-and-be-more-privacy-conscious-273e7f39bbfd)

### node.js
[npm Package](https://www.npmjs.com/package/hcaptcha)

### Go middleware
[Source](https://github.com/kataras/hcaptcha)

### curl
[Official docs](https://docs.hcaptcha.com/#server)

### Elixir
[Hex](https://hex.pm/packages/hcaptcha)

### Java
[Blog with source](https://golb.hplar.ch/2020/05/hcaptcha.html)

### Cloudflare Worker siteverify
[Code](https://github.com/glenstack/glenstack/tree/master/packages/cf-workers-hcaptcha)

## Native Integrations: CMS platforms

### XenForo 
Starting from version 2.2: [Announcement](https://xenforo.com/community/posts/1437264)

### MyBB
Starting from verison 1.8.23: [Docs](https://docs.mybb.com/1.8/administration/spam/#captcha-images-for-registration--posting) & [Release Notes](https://mybb.com/versions/1.8.23/)

## Plugins

### Magento

[Plugin](https://magecomp.com/magento-2-hcaptcha.html)

### Drupal
[Plugin](https://www.drupal.org/project/hcaptcha)

### SMF

[Add-on](https://custom.simplemachines.org/mods/index.php?mod=4255)

### XenForo

[Add-on](https://xenforo.com/community/resources/hcaptcha-integration.7696/)
[Source](https://github.com/ticktackk/hCaptchaIntegrationForXF2)

### Vanilla Forums
[Plugin](https://open.vanillaforums.com/addon/hcaptcha-plugin)
[Source](https://github.com/unkorneglosk/hcaptcha)

### WordPress

[Plugin](https://wordpress.org/plugins/hcaptcha-for-forms-and-more/)
[Source](https://github.com/hCaptcha/hcaptcha-wordpress-plugin)

### WordPress WPForms Plugin
[Native integration: instructions to enable](https://wpforms.com/docs/how-to-set-up-and-use-hcaptcha-in-wpforms/)

### Joomla

[Source](https://github.com/pe7er/hCaptcha)
[Extension](https://extensions.joomla.org/extension/hcaptcha/)

#### Joomla RSForm!Pro Plugin

[Extension](https://www.rsjoomla.com/support/documentation/rsform-pro/plugins-and-modules/plugin-hcaptcha-spam-protection-.html)

### Symfony

[Source](https://github.com/Meteo-Concept/hcaptcha-bundle)
[Symfony/flex recipe](https://github.com/symfony/recipes-contrib/pull/979)

### Typo3

[Blog post](https://susi.dev/hcaptcha)
[Typo3 extension](https://extensions.typo3.org/extension/hcaptcha/)

### Umbraco

#### UmbracoForms.uCaptcha

[Source](https://github.com/AaronSadlerUK/UmbracoForms.uCaptcha)

[Plugin](https://our.umbraco.com/packages/website-utilities/umbracoformsucaptcha/)

[NuGet](https://www.nuget.org/packages/AaronSadler.uCaptcha/)

## Chat protection bots

### Telegram
[Blog post + code](https://medium.com/@hCaptcha/fight-spam-on-your-telegram-group-with-hcaptcha-2bab3efc34b3)


## Mobile apps

### Android
[Android example with source blog post](https://medium.com/@hCaptcha/how-to-use-hcaptcha-with-android-apps-bb546c610bc4)

### Flutter
[Flutter example with source blog post](https://medium.com/@hCaptcha/implementing-hcaptcha-in-your-flutter-app-13ea6ddca71b)


## More

### .NET and ASP.NET Core
[source](https://github.com/BenjaminAbt/hcaptcha)

### RoundCube
[source](https://github.com/NeverBehave/rc_hcaptcha)
