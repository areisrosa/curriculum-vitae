  [![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/1MP7teHXCtZWYyAfD2q9ADAqLVUmACVjWU)](https://en.cryptobadges.io/donate/1MP7teHXCtZWYyAfD2q9ADAqLVUmACVjWU) [![Donate with Ethereum](https://en.cryptobadges.io/badge/micro/0xe54f3f6937b6f2a89863e51c7da88fee5e491b7d)](https://en.cryptobadges.io/donate/0xe54f3f6937b6f2a89863e51c7da88fee5e491b7d) [![Donate with Litecoin](https://en.cryptobadges.io/badge/micro/LX99xASdE2QLDg3jD6nmSf8sL3TyrxWjPF)](https://en.cryptobadges.io/donate/LX99xASdE2QLDg3jD6nmSf8sL3TyrxWjPF) [![Donate with Monero](https://en.cryptobadges.io/badge/micro/4929kMcgTmcfGgNQg4b6ExV7ywpd8wdmPP3byuJEALMvAX8mushD39jPhFELVkayX5Ai5jUqVCN2eJi7soAtCK6iVpibYK8)](https://en.cryptobadges.io/donate/4929kMcgTmcfGgNQg4b6ExV7ywpd8wdmPP3byuJEALMvAX8mushD39jPhFELVkayX5Ai5jUqVCN2eJi7soAtCK6iVpibYK8)
------

<h1 style="font-weight:normal">
  <a href="https://sourcerer.io/areisrosa">
    <img src=https://user-images.githubusercontent.com/20287615/34189346-d426d4c2-e4ef-11e7-9da4-cc76a1ed111d.png alt="AReis" width=35>
  </a>
  &nbsp;ourcerer.io my profile&nbsp;
</h1>

Welcome to my curriculum vitae! :sparkling_heart:
=================================================
This repository contend my curriculum on english, portuguese, moreover, and the statistics of the my GitHub, GitLab and Bitbucket.

### A visual profile for Software Engineers.
<br>

<p align="center">
  <img alt="sergey" src="https://user-images.githubusercontent.com/20287615/47371068-c70f5a00-d6ef-11e8-8988-dcdca71bf83c.gif">
</p>

Statistics of my Sourcerer.io
=============================

<center>
  <table>
    <tr>
      <td><a href="https://sourcerer.io/areisrosa"><img width="120" alt="areisrosa" src="https://user-images.githubusercontent.com/20287615/42243607-c7f6c40c-7ec6-11e8-9f8e-d4450d1d92d1.png"></a></td>
    </tr>
  </table>
</center>

Get started your Sourcerer.io
=============================

* Web browser

or

* Linux or macOS or Windows
* Java 8+ Platform ([JRE](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) for Linux and Windows or [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) for macOS)

Usage
=====

To install sourcerer run the following command:

```
curl -s https://sourcerer.io/app/install | bash
```

To run wizard use `sourcerer` command

Internals
=========

The app looks at repos locally on your machine, and then sends stats to sourcerer.io. The best way to verify is to look at the code. Protobuf messages declared in [src/main/proto/sourcerer.proto](https://github.com/sourcerer-io/sourcerer-app/blob/develop/src/main/proto/sourcerer.proto) is a good start as it describes the client-server protocol.
The Sourcerer app does **NOT** upload source code anywhere, and it **NEVER** will.

FAQ
===

### How can I process private repos?

We process only public repos using GitHub OAuth. To process private repos you need to run sourcerer app locally. See [Get started](#get-started) for instructions. Sourcerer app sends only statistical information to our servers and never sends code.

### Why do you need GitHub permissions?

We use emails to identify commit authorship, read orgs access to get list of public repositories that you've contributed to. You also need to grant access to read this public information from an organization.

### Other questions

See [sourcerer.io/faq](https://sourcerer.io/faq).

### Links

* [Sourcerer Site](https://sourcerer.io/)
* [Sourcerer Blog](https://blog.sourcerer.io)
* [Follow Sourcerer on Twitter](https://twitter.com/sourcerer_io)
* [Follow Sourcerer on Facebook](https://www.facebook.com/sourcerer.io/)
