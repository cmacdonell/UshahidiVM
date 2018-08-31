# Ushahidi Contributing Instructions #

The two relevant repositories are **platform** ([*https://github.com/ushahidi/platform*](https://github.com/ushahidi/platform)), and **platform-client** ([*https://github.com/ushahidi/platform-client*](https://github.com/ushahidi/platform-client)). It is recommended that you fork the original repositories, and contribute to your own repository.

Some useful resources to use when contributing to Ushahidi are as follows:

1.  Support Page for the Ushahidi Project\
    > [*https://www.ushahidi.com/support/*](https://www.ushahidi.com/support/)

2.  Getting involved with the Ushahidi Project
	> [*https://www.ushahidi.com/support/get-involved*](https://www.ushahidi.com/support/get-involved)

3.  Guide for adding code to Ushahidi
    > [*https://www.ushahidi.com/support/add-code-to-ushahidi*](https://www.ushahidi.com/support/add-code-to-ushahidi)

**Ushahidi Technical Overview**

Ushahidi can be broken down into two main components. The first main component is the back-end of Ushahidi that supplies the API through *http*, and can be found in the ‘platform’ directory. The second main component is the front-end which displays the relevant information about Ushahidi to the user. The front-end can be an android app, website, etc.
The front-end can be found in the ‘platform-client’ directory.

In order for the website to display information relevant to your specific deployment, it queries the API for the information that it requires. The front-end does not store the information shown on the website, but instead it pulls it from the API. The following diagram is a brief example of how the front-end interacts with the back-end.

<p align="center">
  <img src="https://github.com/cmacdonell/UshahidiVM/blob/master/images/development/01.png" width=60% height=60%/>
</p>

For more detailed information about APIs, please visit
[*https://en.wikipedia.org/wiki/Application\_programming\_interface*](https://en.wikipedia.org/wiki/Application_programming_interface)

**Translations**

Ushahidi is used around the world by speakers of all languages. If your
language is not yet supported by Ushahidi, you can contribute
translations that will help others. Please visit
[*https://wiki.ushahidi.com/display/WIKI/Localization+and+Translation+-+How+to*](https://wiki.ushahidi.com/display/WIKI/Localization+and+Translation+-+How+to)
to learn how to contribute translations.
