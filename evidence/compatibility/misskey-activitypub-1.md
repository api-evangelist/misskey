<!-- fetched 2026-10-15 from https://misskey-hub.net/en/docs/about-misskey/ by sweep-shape-compat.py; text extracted from the provider's own page -->

About Misskey | Misskey 
 Misskey Docs News Servers More! 
 日本語 
 English 
 Bahasa Indonesia 
 한국어 
 Italiano 
 Polski 
 Français 
 ภาษาไทย 
 Español 
 Deutsch 
 简体中文 
 繁体中文 
 🐙 
 About Misskey
 For Misskey Users
 Getting Started with Misskey
 Important notes
 Find a Misskey Server
 Register on a server
 Misskey Basics
 Various features
 Advertisements
 Antennas
 Charts
 Clips
 Custom Emoji
 Deck
 Developer Mode
 Drive
 Embed to Website
 Favorites
 Follow
 Hashtags
 Mentions
 MFM
 Mutes and Blocks
 Notes
 Online Status
 Page
 Plugins
 Polls
 Reactions
 Safe Mode
 Share Form
 Silence
 Themes
 Mute Thread
 Timelines
 Webhook
 Widgets
 Word Mute
 Additional Resources
 Troubleshooting
 Apps
 Frequently Asked Questions
 Glossary
 Misskey Hub
 Self-XSS Attack
 Step-by-step Guides
 How to delete your account
 How to Set Up Two-Factor Authentication (One-Time Password)
 How to use Misskey Web as a smartphone app
 For Server Operators
 Server Features
 通報
 Announcements
 管理コマンド
 連合モード
 Fan-out Timeline Technology (FTT)
 Managing Custom Emojis
 Roles
 ノート検索
 Install and Maintain Misskey
 Creating a Misskey Server
 Use Dedicated Service
 Misskey Installation Shell Script v3.0.0
 Building Misskey using Docker Compose
 Building Misskey with Kubernetes / TrueNAS
 Manual Misskey Installation
 Detailed guide to installing Misskey on Ubuntu
 Misskey Maintenance & Troubleshooting
 CDN Configuration
 Notes on Forking and Customizing Misskey
 Nginx configuration
 How to push to Docker Hub using GitHub Actions
 Scaling Misskey
 Troubleshooting Manual Installation
 Moderation Tips
 Disabling the LTL/STL/GTL
 For Developers
 AiScript
 Misskey API
 Endpoints
 List of Libraries
 List of permissions
 Streaming API
 Channel List
 globalTimeline
 homeTimeline
 hybridTimeline
 localTimeline
 main
 Note Capture Events
 Obtain an access token
 Obtaining an Access Token via MiAuth
 Obtaining an Access Token via OAuth
 Obtaining an Access Token by Creating an App (Legacy)
 Create a bot
 Creating a Plugin/Play
 Create Play
 Creating Plugins
 AiScript Misskey Extended API Reference
 Distributing Plugins and Themes
 Release Notes
 Donating to the project
 Become a Sponsor
 Misskey ID Card
 Misskey vs Misskey Servers
 Table of Contents History 
 What does "Decentralized" mean? 
 Always Open-Source 
 Joining development and supporting the project Adding features or fixing bugs 
 Participating in discussions 
 Translating text 
 Sharing your impressions 
 Increasing the number of Misskists 
 Making donations 
 Frequently Asked Questions What is this project aiming to achieve? 
 Is Misskey being developed by a company? 
 Who is managing Misskey? 
 Which server should I choose? 
 How can I create my own server? 
 What kind of technology does Misskey use? 
 Is this a fork of Mastodon? 
 Are there any apps for iOS / Android available? 
 Where can I download Misskey's logo or icon? 
 Who are those cute cat-eared girls that you see sometimes? 
 Help us translate
 This document is translated by the community. You can contribute on Crowdin . We appreciate your cooperation 🙏.
 About Misskey 
 Misskey is an open-source and distributed platform for microblogging. Development was started in 2014 by syuilo in Japan. It is characterized by its rich functionality, including drive and reaction, as well as a highly customizable UI. 
 History 
 While Misskey started centered around Bulletin Boards as its main feature, the growth in popularity due to the addition of a timeline that let users post short messages and view them in chronological order lead to a gradual shift in the main focus of development towards this kind of functionality. Misskey was not always a decentralized service, but became decentralized through the adoption of ActivityPub in 2018. Since then, it has become a service that is acknowledged and used by many. 
 Tips
 The name "Misskey" comes from a song called "Brain Diver" by a band that syuilo used to listen to at the time called May'n. 
 With anyone being able to join its development, Misskey is still continually being actively developed. 
 Misskey History Museum 
 What does "Decentralized" mean? 
 A distributed service, also called a decentralized service, refers to a service that divides its community into many servers (instances) that all mutually communicate (federate) with each other to share their contents, forming a network (Fediverse) . Services that only have one instance or multiple instances that are independent of each other are called centralized. Most services fall under the category of centralized, some examples being Twitter (X) and Facebook. The advantages of decentralized services include being able to freely choose the instance whose administration and theme suit you best. It's also possible for you to make your own server. Thanks to the federated nature, you will be able to access the same communities, no matter which server you choose. 
 Always Open-Source 
 Misskey has always been, and will always be, open source. Open source simply means that the source code of the software (a program) is publicly available . This also includes being able to adjust or redistribute the source code in its definition. The entirety of Misskey's source code is published under an open-source license called AGPL , which means anyone can freely inspect, use, adjust, change or redistribute as they see fit. Open source has many merits, including allowing anyone being able to make changes as they like, to make sure the code does not include any harmful components and being able to easily participate in its development. For realizing the distributed nature of Misskey, this concept of open source is indispensable. Using the same example as before, most profit-oriented services like Twitter, Facebook etc. are not open source. 
 Tips
 Technically speaking, Misskey's source code is managed via Git, and the repository is hosted on GitHub . 
 Joining development and supporting the project 
 If you like Misskey, please support the project. Supporting the project can be done in many ways, with some of them introduced below. Some of these do not require programming skills, so anyone can feel free to support Misskey their own way. We are always looking forward to hearing from you. 
 Adding features or fixing bugs 
 If you possess software engineering skills, you can contribute to the project through editing the source code. Check our contributing guidelines here . 
 Participating in discussions 
 You can also contribute by giving your opinion on new or existing features, or by reporting bugs. Such discussions will take place on GitHub . 
 Translating text 
 Misskey is available in many languages (also called i18n, which is an abbreviation for Internationalization). While the original language is generally japanese, volunteers are translating Misskey into other languages. Misskey uses a service called Crowdin to manage its translations. 
 Sharing your impressions 
 Besides reporting bugs, please also feel free to share positive impressions such as which parts of Misskey you personally like, or things about Misskey that you find fun. As things like these serve as motivation for the developers, it also counts as indirect support for the project. As things like these serve as motivation for the developers, it also counts as indirect support for the project. 
 Increasing the number of Misskists 
 "Misskist" refers to the people using Misskey. By spreading the word about Misskey through introducing it to your acquaintances, the number of Misskists may increase, which serves as motivation for the developers. 
 Making donations 
 Please click here 
 Frequently Asked Questions 
 What is this project aiming to achieve? 
 Unlike other platforms, Misskey is not grounded in a specific idea (for example, anti-centralization) or vision and being developed with that in mind, so it's a bit "aimless" in this respect. 
 Is Misskey being developed by a company? 
 No. Misskey is developed by individuals and not commercialized through connection with any particular company. Development members are generally volunteers. Additionally, while there are some corporate sponsors, development is still centered around the community. 
 Who is managing Misskey? 
 Due to the decentralized nature of Misskey, each individual server has their own administration. Therefore, not all of Misskey is managed by one individual person or company. To put it bluntly, while this is a bit vague, Misskey is aiming to be a widely-used all-purpose platform. On the other hand though, this creates a flexibility due to not being bound by a specific direction to go towards. Development members are generally volunteers. Additionally, while there are some corporate sponsors, development is still centered around the community. This means that, as the development team does not control individual servers, for management-related questions you should contact your server's administration instead. 
 Which server should I choose? 
 A list of servers is available here. Depending on the server, its community or central theme (for example, liking a show) may vary, so if there is a server that suits your interests, joining it would likely be a good choice. Besides that, server size, userbase, country or spoken language, reliance or trust in the administration team and many other things can also serve as criteria. There is however no single server that serves as the official server of Misskey. You also have the choice of creating a new server of your own. 
 Generally speaking, no matter which server you join, you will still be able to connect with users from all other servers. 
 How can I create my own server? 
 Thank you for your interest in creating a Misskey server.
 To create a Misskey server, you can use dedicated services or semi-automated methods to set up the environment (of course, it is also possible to manually build the server). Please refer to this document for more information. 
 What kind of technology does Misskey use? 
 As Misskey's development progressed, the technologies used have changed significantly. In the beginning, it used a combination of MySQL + PHP + jQuery, but currently uses the following: 
 Server-side: Node.js 
 Database: PostgreSQL, Redis 
 UI Framework: Vue.js 
 Programming language: TypeScript 
 In addition to this, from Misskey derived technology such as MFM or AiScript are also being used. 
 Is this a fork of Mastodon? 
 No. Misskey is a project completely different from Mastodon or other alike projects. It has been in development for a long time already. However, it only became a decentralized network after the appearance of Mastodon. Besides both projects implementing the ActivityPub protocol, there is no relation between the two. 
 Are there any apps for iOS / Android available? 
 We do not officially develop native apps for those operating systems, but there are several third-party apps available. Please see here for more information. 
 However, third-party applications will inevitably lag behind the official Web client in functionality, so unless you really want to use a native application, we recommend the official Web client instead. As the Misskey Web client supports PWA, you can use it as if it was a native application. 
 Tips
 For more information on how to set up a PWA, please click here for the detailed guide. 
 Where can I download Misskey's logo or icon? 
 Click here 
 Who are those cute cat-eared girls that you see sometimes? 
 Ai
 For more information about me, please visit this website ! 
 syuilo
 It's Misskey's guardian deity, Ai. (They called Ai cute, yay!) 
 Edit this page 
 Translate this page 
 Next
 User Guide
 Table of Contents
 History 
 What does "Decentralized" mean? 
 Always Open-Source 
 Joining development and supporting the project Adding features or fixing bugs 
 Participating in discussions 
 Translating text 
 Sharing your impressions 
 Increasing the number of Misskists 
 Making donations 
 Frequently Asked Questions What is this project aiming to achieve? 
 Is Misskey being developed by a company? 
 Who is managing Misskey? 
 Which server should I choose? 
 How can I create my own server? 
 What kind of technology does Misskey use? 
 Is this a fork of Mastodon? 
 Are there any apps for iOS / Android available? 
 Where can I download Misskey's logo or icon? 
 Who are those cute cat-eared girls that you see sometimes? 
 © 2025 syuilo and Misskey Project
