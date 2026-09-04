<a href="https://virgilsecurity.com"><img src="images/VirgilLogo.png"></a>

[Virgil Security](https://virgilsecurity.com) is a stack of security libraries and all the necessary infrastructure to enable seamless, end-to-end encryption for any application, platform or device.

Our libraries allow developers to get up and running with Virgil API quickly and add full end-to-end security to their existing digital solutions to become HIPAA and GDPR compliant and more.

Virgil Security, Inc. guides software developers into the forthcoming security world in which everything will be encrypted (and passwords will be eliminated). In this world, the days of developers having to raise millions of dollars to build secure chat, secure email, secure file-sharing, or a secure anything have come to an end. Now developers can instead focus on building features that give them a competitive market advantage while end-users can enjoy the privacy and security they increasingly demand.

# Awesome Content with stars

* [Community](#community)

* [Products](#products)
  * [Tools](#tools)
  * [Secure Communications Platform (coming)](#secure-communications-platform-coming)
  * [Security Frameworks](#security-frameworks)
  * [Core SDK](#core-sdk)
  * [Services](#services)
  * [Cryptographic Libraries](#cryptographic-libraries)

* [E3Kit](#E3Kit)
  * [With any platform](#with-any-platform)
  * [With Firebase](#with-firebase)
  * [With Twilio](#with-twilio)
  * [With PubNub](#with-pubnub)
  * [With Nexmo](#with-nexmo)

* [PureKit](#PureKit)
  * [With any backend language](#with-any-backend-language)
  * [With MariaDB](with-mariadb)
  * [With WordPress](#with-wordpress)

* [IoTKit](#iotkit)

* [WaveKit](#wavekit)

* [Production Applications](#production-applications)

* [Blog Posts](#blog-posts)

* [Videos](#videos)

* [HashTags](#hashtags)

* [License](#license)

* [Contacts](#contacts)

# Community

### Web resources

* [Main Website](https://VirgilSecurity.com)
* [Developer Documentation](https://developer.virgilsecurity.com/docs)
* [Virgil Developer Dashboard](https://dashboard.VirgilSecurity.com)
* [Help Center](https://help.VirgilSecurity.com)

### Social media

* [Facebook](https://www.facebook.com/VirgilSec)
* [Twitter](https://twitter.com/VirgilSecurity)
* [LinkedIn](https://www.linkedin.com/company/virgil-security-inc-/)
* [DOU](https://jobs.dou.ua/companies/virgil-security-inc/)

### Blogs

* [Medium Blog](https://medium.com/@VirgilSecurity)
* [Habr](https://habr.com/company/VirgilSecurity)
* [Website blogs](https://virgilsecurity.com/blog/)

### Support

* [Slack](https://VirgilSecurity.slack.com/)
* [Email](mailto:support@VirgilSecurity.com)

# Products

### Secure Communications Platform (coming)

* **[Secure Communications Platform](https://virgilsecurity.com/secure-communications-platform/)** - Virgil Security introduces the most secure programmable communications platform that allows protecting your company communications, intellectual property and privacy. Now, you can build your own communication applications with secure voice & video calls and other communications features faster, secure and cheaper.

### Security Frameworks

* **[E3Kit](https://virgilsecurity.com/e3kit/)** -  an open-source client-side framework that allows developers to add end-to-end encryption to their messaging applications, file sharing programs, and other digital communication products in just a few simple steps to become HIPAA and GDPR compliant and more. E3Kit interacts with Cards Service, Keyknox Service and Pythia Service and supports multi-device access and group chat features.
  * [JavaScript/TypeScript](https://github.com/VirgilSecurity/virgil-e3kit-js) ⭐ 61 | 🐛 4 | 🌐 TypeScript | 📅 2024-05-28
  * [Swift](https://github.com/VirgilSecurity/virgil-e3kit-x) ⭐ 14 | 🐛 7 | 🌐 Swift | 📅 2026-06-03
  * [Java/Kotlin](https://github.com/VirgilSecurity/virgil-e3kit-kotlin) ⭐ 12 | 🐛 8 | 🌐 Kotlin | 📅 2026-06-02

* **[PureKit](https://virgilsecurity.com/purekit/)** - an open-source security framework for enabling post-compromise protection for stored data. PureKit allows developers to protect users' passwords and personal data from hacking and securely share data. The framework can be used within any database or login system that uses a password, so it’s applicable for a company of any industry or size.
  * [Golang](https://github.com/VirgilSecurity/virgil-purekit-go) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2026-05-12
  * [Java/Kotlin](https://github.com/VirgilSecurity/virgil-purekit-kotlin) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2020-05-08
  * [PHP](https://github.com/VirgilSecurity/virgil-purekit-php) ⭐ 6 | 🐛 4 | 🌐 PHP | 📅 2026-03-25
  * [C#.NET](https://github.com/VirgilSecurity/virgil-purekit-net) ⭐ 4 | 🐛 3 | 🌐 C# | 📅 2023-05-30

* **IoTKit** - A framework for connecting IoT devices to Virgil IoT Security PaaS. IoTKit helps you easily add security to your IoT devices at any lifecycle stage for secure provisioning and authenticating devices, secure updating firmware and trustlists, and for secure exchanging messages using any transport protocols.
  * [C](https://github.com/VirgilSecurity/virgil-iotkit/) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13

### Tools

* [Virgil CLI](https://github.com/VirgilSecurity/virgil-cli) ⭐ 82 | 🐛 5 | 🌐 Go | 📅 2023-02-25 - a tool to manage your Virgil account and applications, and perform cryptographic operations.
* [IoT Dev Tools](https://github.com/VirgilSecurity/virgil-iotkit#iot-dev-tools) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13. Virgil Security also provides a set of tools for secure device lifecycle:
  * **Virgil Trust Provisioner**. The Virgil Trust Provisioner is a CLI used to manage your distributed trust between all parties, including IoT devices, in your IoT solutions. The CLI is aimed at key pairs and TrustList generation and management, which together make each IoT device identifiable, verifiable and trusted by each party of IoT solution. To start working with the tool, read more [here](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/tools/virgil-trust-provisioner) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13.
  * **Virgil Device Initializer**. In order to make each IoT device identifiable, verifiable and trusted by each party of IoT solution, you have to provide it with specific provision files, generate private keys and create the digital cards for further device registration on the Virgil Cloud. Virgil Device Initializer allows you to make IoT device provisioning and prepare your IoT device (create digital cards) for its further registration on the Virgil Cloud. To start working with the tool, read more [here](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/tools/virgil-device-initializer) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13.
  * **Virgil Device Registrar**. Virgil IoT Device Registrar is used to register IoT devices and their digital cards with the Virgil Security Cloud. To start working with the tool, read more [here](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/tools/virgil-device-registrar) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13.
  * **Virgil Firmware Signer**. Virgil Firmware Signer is a CLI that allows you to sign firmware in order to provide integrity before distributing it. To start working with the tool, read more [here](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/tools/virgil-firmware-signer) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13.
  * **Virgil SnapD**. Virgil SnapD is a local web utility which allows you to obtain information and statistics about your IoT devices. In order to get such device information, SnapD interacts with Virgil SNAP protocol, which operates directly with your IoT devices. As far as Virgil SnapD is a local service, the obtained information can be displayed in browser under <http://localhost:8080/> (by default). If you're working with the Virgil IoT Simulator, you can run SnapD under <http://localhost:8081/>. To start working with the tool, read more [here](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/tools/virgil-snapd) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13.

### Core SDK

* **Cards Service SDK** - interacts with Virgil Cards Service and allows developers to add end-to-end encryption (E2EE) security to their new and existing digital products. SDK can be used on both client-side and server-side.
  * [JavaScript/TypeScript](https://github.com/VirgilSecurity/virgil-sdk-javascript) ⭐ 33 | 🐛 5 | 🌐 TypeScript | 📅 2023-01-27
  * [Swift/Objective-C](https://github.com/VirgilSecurity/virgil-sdk-x) ⭐ 28 | 🐛 1 | 🌐 Swift | 📅 2026-06-03
  * [Java/Android](https://github.com/VirgilSecurity/virgil-sdk-java-android) ⭐ 27 | 🐛 1 | 🌐 Java | 📅 2026-06-02
  * [C++](https://github.com/VirgilSecurity/virgil-sdk-cpp) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2020-05-18
  * [C#/.NET](https://github.com/VirgilSecurity/virgil-sdk-net) ⭐ 15 | 🐛 35 | 🌐 C# | 📅 2022-12-08
  * [PHP](https://github.com/VirgilSecurity/virgil-sdk-php) ⭐ 10 | 🐛 1 | 🌐 PHP | 📅 2026-01-27
  * [Python](https://github.com/VirgilSecurity/virgil-sdk-python) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-04-28
  * [Golang](https://github.com/VirgilSecurity/virgil-sdk-go) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2026-06-02
  * [Ruby](https://github.com/VirgilSecurity/virgil-sdk-ruby) ⭐ 5 | 🐛 0 | 🌐 Ruby | 📅 2020-04-27

* **Pythia Service SDK** - allows developers to communicate with Virgil Pythia Service to generate a Brainkey (private Key that is based on a password) and protect user passwords in a database.
  * [Golang](https://github.com/VirgilSecurity/virgil-pythia-go) ⚠️ Archived
  * [Node.js](https://github.com/VirgilSecurity/virgil-pythia-node) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2024-03-22
  * [Swift](https://github.com/VirgilSecurity/virgil-pythia-x) ⚠️ Archived
  * [C#/.NET](https://github.com/VirgilSecurity/pythia-net) ⭐ 0 | 🐛 1 | 🌐 C# | 📅 2022-12-08
  * [Java/Kotlin](https://github.com/VirgilSecurity/virgil-pythia-java) ⚠️ Archived

* **Keyknox Service SDK** - allows developers to communicate with the Virgil Keyknox Service to upload, download, and synchronize encrypted sensitive data (private keys) between user's devices.
  * [Swift](https://github.com/VirgilSecurity/virgil-keyknox-x) ⭐ 4 | 🐛 0 | 🌐 Swift | 📅 2021-07-22
  * [JavaScript/TypeScript](https://github.com/VirgilSecurity/virgil-keyknox-javascript) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-04-19
  * [Java/Kotlin](https://github.com/VirgilSecurity/virgil-keyknox-kotlin) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2019-07-12

### Services

* [Cards Service](https://developer.virgilsecurity.com/docs/platform/api-reference/cards-service/) - Stores and manages users' Virgil Cards with Public Keys and associated information.
* [Pythia Service](https://developer.virgilsecurity.com/docs/platform/api-reference/pythia-service/) - Provides developers with an ability to generate a user's restorable keypair based on a password.
* [Keyknox Service](https://developer.virgilsecurity.com/docs/platform/api-reference/keyknox-service/) - Allows developers to securely store private keys and secrets in the Virgil Cloud and share them between their devices.

### Cryptographic Libraries

[Virgil Crypto](https://github.com/VirgilSecurity/virgil-crypto) ⭐ 85 | 🐛 1 | 🌐 C++ | 📅 2020-07-03 is an open-source high-level cryptographic library that allows you to perform all necessary operations for secure storing and transferring data in your digital solutions. Crypto Library is written in C++, suitable for mobile and server platforms and supports bindings with the following programming languages: Swift, Obj-C, Java (Android), С#/.NET, JS, Python, Ruby, PHP, Go.

* **Wrappers**
  * [C](https://github.com/VirgilSecurity/virgil-crypto-c) ⭐ 38 | 🐛 1 | 🌐 C | 📅 2026-08-09
  * [JavaScript/TypeScript](https://github.com/VirgilSecurity/virgil-crypto-javascript) ⭐ 35 | 🐛 8 | 🌐 TypeScript | 📅 2024-05-13
  * [Swift](https://github.com/VirgilSecurity/virgil-crypto-x) ⭐ 34 | 🐛 3 | 🌐 Swift | 📅 2026-06-02
  * [PHP](https://github.com/VirgilSecurity/virgil-crypto-php) ⭐ 33 | 🐛 2 | 🌐 PHP | 📅 2026-01-27
  * [Python](https://github.com/VirgilSecurity/virgil-crypto-python) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2020-05-08
  * [Ruby](https://github.com/VirgilSecurity/virgil-crypto-ruby) ⭐ 7 | 🐛 1 | 🌐 Ruby | 📅 2020-07-04
  * [C#/.NET](https://github.com/VirgilSecurity/virgil-crypto-net) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2016-12-12
  * [Golang](https://github.com/VirgilSecurity/virgil-crypto-go) ⚠️ Archived
  * [Java/Kotlin](https://github.com/VirgilSecurity/virgil-crypto-kotlin) ⭐ 0 | 🐛 0 | 📅 2018-05-10

# E3Kit

### With any platform

* [Add end-to-end encryption to your application to secure communication](https://developer.virgilsecurity.com/docs/e3kit/get-started/quickstart/) - In this tutorial, we will help you add end-to-end encryption to your product to secure your messages and user data.
* Demo backends:
  * [Python](https://github.com/VirgilSecurity/virgil-sdk-python/tree/master#sample-backend-for-jwt-generation) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-04-28
  * [NodeJS](https://github.com/VirgilSecurity/sample-backend-nodejs) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2020-08-19
  * [Golang](https://github.com/VirgilSecurity/sample-backend-go) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2020-07-25
  * [PHP](https://github.com/VirgilSecurity/sample-backend-php) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2020-12-07
  * [Java](https://github.com/VirgilSecurity/sample-backend-java) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2019-11-04
  * [Other Languages](https://developer.virgilsecurity.com/docs/e3kit/get-started/generate-client-tokens/)
* Demo applications:
  * [Demo iOS](https://github.com/VirgilSecurity/virgil-e3kit-x) ⭐ 14 | 🐛 7 | 🌐 Swift | 📅 2026-06-03
  * [Demo Web](https://github.com/VirgilSecurity/demo-e3kit-web) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-01-30

### With Firebase

* [Demo Web](https://github.com/VirgilSecurity/demo-firebase-js) ⭐ 33 | 🐛 14 | 🌐 TypeScript | 📅 2023-03-04 - A simple Web application that demonstrates how the end-to-end encryption works. The application uses Firebase as a backend service for authentication and chat messaging.
* [Virgil Cloud Function for Firebase](https://github.com/VirgilSecurity/virgil-e3kit-firebase-func) ⭐ 22 | 🐛 24 | 🌐 JavaScript | 📅 2023-01-07 use Firebase as a backend service for authentication and chat messaging and Virgil E3kit.
* [Add end-to-end encryption to your Firebase application](https://developer.virgilsecurity.com/docs/e3kit/integrations/firebase/) - In this tutorial, we will help you add end-to-end encryption to your Firebase application to secure your messages and user data.

### With Twilio

* [Twilio Sample Backend for Node.js](https://github.com/VirgilSecurity/twilio-sample-backend-nodejs) ⭐ 129 | 🐛 10 | 🌐 JavaScript | 📅 2022-12-30 - A sample backend that demonstrates how to generate a Virgil JWT and Twilio token used for authentication with the Virgil and Twilio services
* [Demo iOS](https://github.com/VirgilSecurity/demo-e3kit-ios-twilio) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2019-07-02 - A simple iOS application that demonstrates how the end-to-end encryption works with Twilio.
* [Add end-to-end encryption to your Twilio Programmable Chat](https://developer.virgilsecurity.com/docs/e3kit/integrations/twilio/) - In this tutorial, we will help you add end-to-end encryption to your product to secure your messages and user data that you deliver using Twilio Programmable Chat.

### With Pubnub

* [Add end-to-end encryption to your PubNub Chat](https://developer.virgilsecurity.com/docs/e3kit/integrations/pubnub/) - In this tutorial, we will help you add end-to-end encryption to your product to secure your messages and user data that you deliver using PubNub Chat.

### With Nexmo

* [Demo E3Kit Android chat](https://github.com/VirgilSecurity/demo-nexmo-chat-e3kit-android) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2019-05-14 - Demo Android chat that uses Virgil E3Kit and Nexmo.
* [Demo Java/Android backend](https://github.com/VirgilSecurity/demo-nexmo-chat-backend-java) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2019-10-04 - This repository contains a sample backend code that demonstrates how to generate a Nexmo and Virgil JWTs using the Java/Android SDK.

# PureKit

### With any backend language

* [Protect user passwords and data in your database from data breaches](https://developer.virgilsecurity.com/docs/purekit/get-started/) - In this tutorial, we will help you to set up PureKit on your backend to secure data and passwords in your database.

### With MariaDB

* [Virgil PureKit MariaDB Demo](https://github.com/VirgilSecurity/virgil-mariadb-demo) ⭐ 6 | 🐛 21 | 🌐 Java | 📅 2023-01-05 - The Demo App is a simple web application that illustrates how Virgil PureKit can be used with MariaDB to store and share data in the most secure way. The Demo App is based on use case involving a hypothetical business scenario involving a patient, physician and laboratory, and shows how distinct roles within a customer's application can be defined and used to restrict ePHI access in a HIPAA-compliant manner.

### With WordPress

* [Virgil Pure Wordpress Plugin](https://github.com/VirgilSecurity/virgil-pure-wordpress) ⭐ 6 | 🐛 0 | 🌐 PHP | 📅 2024-10-01 - Free Wordpress Plugin based on a powerful and revolutionary cryptographic technology that protects user passwords from data breaches and both online and offline attacks.

# IoTKit

* [Virgil IoTKit Sandbox](https://github.com/VirgilSecurity/virgil-iotkit/tree/master/scripts) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2020-10-13 - A demo IoT sandbox is based on Virgil IoTKit and its dev tools. It allows you to emulate IoT devices, manage Firmware, TrustList and see the security for IoT devices in action. The Sandbox is conditionally divided into 3 actors (Vendor, Factory, and End-User) to easily understand the whole development process.
* [IoTKit Demo Samples for UNIX-like OS](https://github.com/VirgilSecurity/demo-iotkit-nix) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2020-03-16 - The demo samples contain key elements that are necessary for implementation of the secure IoT lifecycle, and tests for all the provided features.

# WaveKit

* [Virgil WaveKit](/WaveKit.md) - an easy-to-use client-side framework that provides developers with full security functionality to implement and manage secure V2X communication according to the architecture and operations of a WAVE system based on IEEE 1609 family standards.

# Production Applications

* **Virgil Messenger** - End-to-end encrypted messenger with passwordless authentication. Perfect solution for those who care about their privacy.
  * [Virgil Messenger iOS](https://itunes.apple.com/us/app/virgil-messenger/id1374223472)
    * [Source code](https://github.com/VirgilSecurity/chat-twilio-ios/) ⭐ 3 | 🐛 0 | 🌐 Swift | 📅 2020-05-25
  * [Virgil Messenger Android](https://play.google.com/store/apps/details?id=com.virgilsecurity.android.virgilmessenger)
    * [Source code](https://github.com/VirgilSecurity/demo-twilio-chat-android/tree/extended_e2ee) ⭐ 5 | 🐛 11 | 🌐 Kotlin | 📅 2020-03-25

# Blog Posts

* MariaDB: [Enable post-compromise data protection with MariaDB and Virgil Security’s PureKit](https://mariadb.org/enable-post-compromise-data-protection-with-mariadb-and-virgil-securitys-purekit/)
* TechCrunch: [Adding end-to-end encrypted messaging to your app just got a lot easier](https://techcrunch.com/2016/05/03/adding-end-to-end-encrypted-messaging-to-your-app-just-got-a-lot-easier/)
* eWeek: [Virgil Security Raises $4M for Application Security](https://www.eweek.com/security/virgil-security-raises-4m-for-application-security)
* Atomicorp: [Adding Elliptic Curve Noise Socket Crypto to Your OSSEC Deployment](https://www.atomicorp.com/adding-elliptic-curve-noise-socket-crypto-ossec-deployment/)
* Cointelegraph: [Research: Telegram Passport Is Vulnerable to Brute Force Attacks](https://cointelegraph.com/news/research-telegram-passport-is-vulnerable-to-brute-force-attacks)
* Medium: [Implement Virgil Security’s End-to-End Encryption in your Firebase App — Why and How?](https://medium.com/@geekyants/implement-virgil-securitys-end-to-end-encryption-in-your-firebase-app-why-and-how-dc5286920a32)
* The IOT Magazine: [Shaken and Stirred - The challenge of IoT cyber security and privacy](https://theiotmagazine.com/shaken-and-stirred-5f96ff135bf9)
* Firebase Blog: [The Latest Firebase Tutorials - Fall 2018](https://firebase.googleblog.com/2018/09/the-latest-firebase-tutorials-fall-2018.html)

# Videos

**Our Youtube channel:** [Virgil Security Academy](https://www.youtube.com/channel/UCU8BhA1nVzKKRiU5P4N3D6A)

**Featuring videos:**

* [MacVoices #18140: WWDC/AltConf - Virgil Security Provides End-To-End Encryption SDK's For Developers](https://www.youtube.com/watch?v=MSnKQXvXe-g)
* [TiE50 Room 212 - Virgil Security, Inc](https://www.youtube.com/watch?v=avYpSTfbb14)
* [REAL-TIME COMMS TRACK | Add Encryption to Chat - Dmitry Dain (Virgil Security)](https://www.youtube.com/watch?v=wITDSt9RgUE)
* [How to protect 1 trillion IoT devices / Alexey Ermishkin (Virgil Security)](https://www.youtube.com/watch?v=qLidSKPJCiQ)
* [Key transparency: Blockchain meets NoiseSocket / Alexey Ermishkin (Virgil Security)](https://www.youtube.com/watch?v=hQZ9tSF6g1Y)
* [Introduction to IoT Sandbox](https://youtu.be/18DqlNoou4M)

# HashTags

You can use the following hashtags while tagging Virgil Security Inc.: [#SecuredByVirgil](https://virgilsecurity.com/), [#SecureTheFuture](https://virgilsecurity.com/), [#VirgilSecurity](https://virgilsecurity.com/).

# License

BSD 3-Clause. See [LICENSE](https://github.com/VirgilSecurity/virgil/blob/master/LICENSE) ⭐ 158 | 🐛 0 | 📅 2020-05-08 for details.

# Contacts

Our developer support team is here to help you. Find out more information on our [Help Center](https://help.virgilsecurity.com/).

You can find us on [Twitter](https://twitter.com/VirgilSecurity) or send us email <support@VirgilSecurity.com>.

Also, get extra help from our support team on [Slack](https://virgilsecurity.com/join-community).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
