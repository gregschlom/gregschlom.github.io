---
layout: post
title: 'If someone steals your phone, they can log into your Paypal account - even if the phone is locked'
date: '2017-01-28T17:00:00-08:00'
categories: misc
---

A friend of mine just had this happen to her: her phone got stolen, and the next morning someone logged in her PayPal account, changed the password, and transferred $800 out of her account. How is that possible? She had fingerprint unlock activated on her phone.

It turns out it's very easy to log into someone's PayPal account if you have their phone, even if the phone is locked. By default Android phones will display notifications on the lock screen, so if you know the victim's email address all you have to do is go to PayPal and initiate a password reset, choosing to have a security code sent to the victim's phone:

![Android Lock Screen screenshot]({{ site.url }}/assets/android_security/screenshot1.png)

And getting the victim's email address is pretty easy too. Gmail notifications will show your email address, and so will the notifications from several other apps such as Google Photos. So in most cases, if someone steals your phone, chances are they will be able to log into your PayPal account.

The only way to protect yourself is to make sure you **hide all notification content** when the device is locked: Settings -> Sound & Notification -> When device is locked: Don't show notifications at all. 

![Android Hide Notifications Lock Screen]({{ site.url }}/assets/android_security/screenshot2.png)

I wouldn't trust the option to "hide sensitive notification content", as it still leaks your email address and it's probably not a good thing.

The good news is that my friend was able to contact PayPal security and sort things out. They will cancel the fraudulent transaction. But still, not a fun way to spend your weekend.

