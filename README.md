[![GitHub stars](https://img.shields.io/github/stars/nenes25/eicaptcha)](https://github.com/nenes25/eicaptcha/stargazers) 
[![GitHub forks](https://img.shields.io/github/forks/nenes25/eicaptcha)](https://github.com/nenes25/eicaptcha/network) 
[![GitHub release](https://img.shields.io/github/v/release/nenes25/eicaptcha)](https://github.com/nenes25/eicaptcha/)
[![Github All Releases](https://img.shields.io/github/downloads/nenes25/eicaptcha/total.svg)]()
[![Github issues](https://img.shields.io/github/issues-raw/nenes25/eicaptcha)]()

# eicaptcha
Module EiCaptcha for prestashop 1.7

The module is also available for prestashop version 1.6.x see here : https://github.com/nenes25/eicaptcha/tree/master  
or download 0.4.x releases

This module display Google recaptcha on the following forms :
 - contact form
 - account creation form
 - newsletter subscription ( since 2.1.0)

 This module relies upon the override of the folowing files :
 - AuthController
 - ContactForm Module

For newsletter subscription implementation it needs module **ps_emailsubscription at least  2.6.0**

 The last version used composer to get recaptcha lib.  
 Don't forget to use `composer install` in order to download the necessary recaptcha composer package.  
 Otherwise you can go on the github release page https://github.com/nenes25/eicaptcha/releases and download the last 2.0.x version release to get the full package  

 Screenshots
---

<p align="center">
	Captcha on contact form <br />
	<img src="https://www.h-hennes.fr/blog/wp-content/uploads/2017/07/eicaptcha-17-contact.jpg" alt="Captcha Contact Form" />
</p>

<p align="center">
	Captcha on account creation form <br />
	<img src="https://www.h-hennes.fr/blog/wp-content/uploads/2017/07/eicaptcha-17-account.jpg" alt="Captcha on account creation form" />
</p>

<p align="center">
	Captcha on newsletter form <br />
	<img src="https://www.h-hennes.fr/blog/wp-content/uploads/2021/03/captcha-newsletter.png" alt="Captcha on newsletter subscription form" />
</p>

 Additionnal informations (French)
---

https://www.h-hennes.fr/blog/module-recaptcha-pour-le-formulaire-de-contact-prestashop/  
https://www.h-hennes.fr/blog/2017/07/11/module-catpcha-pour-prestashop-1-7/

 Compatibility
---

| Prestashop Version | Compatible |
| ------------------ | -----------|
| 1.5.x | :x: use version 0.4.x or 0.5.x instead |
| 1.6.x | :x: use version 0.4.x or 0.5.x instead |
| 1.6.1.x | :x:use version 0.4.x or 0.5.x instead |
| 1.7.0.x | :heavy_check_mark: |
| 1.7.1.x | :heavy_check_mark: |
| 1.7.2.x | :heavy_check_mark: |
| 1.7.3.x | :heavy_check_mark: |
| 1.7.4.x | :heavy_check_mark: |
| 1.7.5.x | :heavy_check_mark: |
| 1.7.6.x | :heavy_check_mark: |
| 1.7.7.x | :heavy_check_mark: |
