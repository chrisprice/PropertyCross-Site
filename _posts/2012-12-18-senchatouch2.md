---
layout: framework
title: 'Sencha Touch 2'
framework: senchatouch2
platforms:
  - android
  - ios
  - windowsphone
pie:
  common: { segment: 'M150,150l0.00,-145.00A145,145,0,1,1,149.95,5.00z' }
contributors:
  - { name: 'Mark Rhodes', username: markrhodes }
  - { name: 'Joel Smith', username: joelwilliamsmith, hash: 6e5b209f9dced24655066d1128a13964 }
  - { name: 'Nicholas Wolverson', username: nwolverson, hash: c2fa082fa1ffbab1293262c599d459fb }
downloads:
  windowsphone: 'https://s3-eu-west-1.amazonaws.com/propertycross/PropertyCross-senchatouch2-119bb069ee155b0a75b8a0d9108b70379f3dc67d.xap'
phonegap: true

---

[Sencha Touch](http://www.sencha.com/products/touch) is a framework for building cross-platform mobile application using HTML5 technologies.  Similar to ExtJS, Sencha Touch provides a fully functional JavaScript API and a structured MVC approach for building mobile applications.  Coding is done (almost!) exclusively in JavaScript - with the majority of the HTML and CSS being abstracted away behind the concept of "components", which are configured and generated by the JavaScript code.

The PropertyCross implementation does not use any additional tools or libraries beyond those supplied by Sencha, with one exception - it makes use of PhoneGap Build to build and package the application as a native app (although it does not make use of the PhoneGap APIs itself).  This implementation also uses the default "Sencha" theme to style it - whereas other frameworks have attempted to mimic the default look and feel of native applications, Sencha Touch has opted for provided its own styling which provides a clean interface which looks the same on both iOS and Android browsers.


To view the code and detailed build steps, <a href='{{ site.githuburl }}/tree/master/senchatouch2'>see the github source</a>.