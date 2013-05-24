Chattr Proposal
=======

This is a proposal for a Open Source PHP based persistant Chat tool.
Ideally, Chattr will be an free alternative to things like Camp Fire or HipChat.

Features
------
Basic Functionality

* Prep Room - A home screen for all of your conversations. A launch point for everything Chattr. Think of it as the Tumblr dashboard.
* Thought Map - This is a persistent chat log of messages, files, and web hook data that is easy to view.
* Multi-Project Interaction - Branch conversations for projects or features and merge them back to other conversations.
* Github/Bitbucket Web Hooks - Out of the gate, we want to support developers so I want the ability to have Github and Bitbucket web hooks show up in the Thought Map.
* Peekaboo - Sometimes you need to give guests access to what's going on, Chattr will let you give guests temporary glimpses at whole dashboards, specific user activity, conversations, or even just a small sliver of info.

Tech Features

* Single Page Web App - Chattr hopefully can have a nice responsive SPA that makes it very approachable.
* API - Everything in Chattr will be driven by a fully powered JSON API. From creating a message, loading a file, or creating guests. Chattr will expose a clean set of API end-points to allow for great third-party Apps.
* Package Utility - Chattr will expose a web-hook url to pull in data from external utilities. There will be an API for creating translators to bring in your custom data into the Thought Map
* Easily Modified Code Base - Other Open Source tools are very All-in solutions. I'd like to see Chattr have a build system or CLI based installer. Also, I would like it to be able to run along-side other MVC frameworks in PHP. I'm looking at modular Composer Packages.

Later Features

* Quick Start Wizard - On initial launch I'd like to see a setup screen. A user should be able to download Chattr, put in their database creds and not have to fiddle with file based config.
* Blogging platform integration - Collaboration isn't just for Agile development teams. So wouldn't it be nice if when new posts are added, the whole team is notified. Then when a customer asks about the post, you can go to your log and find just who said all of those awesome things!
