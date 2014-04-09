---
layout: post
title: 'Qt developers rejoice: KDE Frameworks has been announced.'
date: '2011-06-08T04:01:00+02:00'
tags: []
tumblr_url: http://gregschlom.com/post/6316733102/kde-frameworks-qt-developers
---
I’m back from a week in Randa, Switzerland, where 60 KDE developers where gathered to discuss, among other things, the future of KDE. And it is quite exciting.

As you probably know, KDE is a large project built on top of Qt. It features a desktop environment, many applications, and a full set of very useful libraries that either fix broken stuff in Qt or add totally new features.

Those libraries are a gold mine for Qt applications, but most Qt developers either are totally unaware of their existence, or think they only work for KDE applications. This is about to change with the KDE Frameworks.

Basically, we took a look at every single class inside KDE and decided whether each of them could be useful for Qt applications, or if they where solving KDE-specific problems. We then further broke down between libraries with only Qt as a dependency, libraries with dependencies on other Qt-only libraries, and so on.

All this work resulted in a set of [guidelines](http://www.devheads.net/desktop/kde/core/intended-organization-kde-frameworks.htm) and [specifications](http://www.devheads.net/desktop/kde/core/rules-be-approved-part-kde-frameworks.htm) to make sure that all the incredibly useful stuff in KDE will be available for Qt applications in a simple and modular way, called the KDE Frameworks.

Qt developers will be able to browse the libraries in the KDE Frameworks, pick stuff that fits their needs, drop it into their project, and start coding. Problem solved.

Head over [here](http://www.devheads.net/desktop/kde/core/future-our-frameworks.htm) for the full announcement, and keep an eye on the [KDE-devel mailing lists](https://mail.kde.org/mailman/listinfo/kde-devel) for more information.
