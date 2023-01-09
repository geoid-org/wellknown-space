<header>
  <p align="center">
    <img src=".github/images/geoid-logo_light.png" width="20%" height="20%" alt="Geoid Logo">
  </p>
  <h1 align='center' style='border-bottom: none;'>space.txt</h1>
  <h3 align='center'>A well-known .txt file for spatial identification.</h3>
</header>
<br/>
<div align="center">
  <a href="https://github.com/geoid-org/wellknown-space/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug_report.yml">Report a Bug</a>
  |
  <a href="https://github.com/geoid-org/wellknown-space/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Afeature-request%2CHelp+wanted+%F0%9F%AA%A7&template=feature_request.yml">Request a Feature</a>
  |
  <a href="https://github.com/geoid-org/wellknown-space/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aquestion&template=question.yml">Ask a Question</a>
  |
  <a href="https://github.com/geoid-org/wellknown-space/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aenhancement&template=suggestion.yml">Make a Sugestion</a>
  |
  <a href="https://github.com/geoid-org/wellknown-space/discussions">Start a Discussion</a>
</div>
<br/>
<div align="center">

  [![license](https://img.shields.io/github/license/geoid-org/wellknown-space?color=green&label=license&style=flat-square)](LICENSE.md)
  [![website](https://img.shields.io/website?color=blue&down_color=red&down_message=offline&label=website&style=flat-square&up_color=green&up_message=online&url=https%3A%2F%2Fwww.wellknwon.space)](https://www.wellknwon.space)

  ![stars](https://img.shields.io/github/stars/geoid-org/wellknown-space?color=blue&label=stars&style=flat-square)
  ![forks](https://img.shields.io/github/forks/geoid-org/wellknown-space?color=blue&label=forks&style=flat-square)
  ![downloads](https://img.shields.io/github/downloads/geoid-org/wellknown-space/total?color=blue&label=downloads&style=flat-square)
  ![sponsors](https://img.shields.io/github/sponsors/geoid-org?color=blue&label=sponsors&style=flat-square)
  ![contributors](https://img.shields.io/github/contributors/geoid-org/wellknown-space?color=blue&label=contributors&style=flat-square)
  
</div>
<br/>
<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
- [Quick Start](#quick-start)
- [Authors](#authors)
- [License](#license)
- [Contributing](#contributing)

</details>


## About

**`space.txt`** is a proposed standard which allows spatially enabled websites and applications to communicate their location.


## Quick Start

### 1. Create

#### 1.1 Filename
Create a text file called **`space.txt`**.
Always use lower-case formatting for the filename.

#### 1.2 Encoding
Make sure that the **`space.txt`** file is UTF-8 encoded to avoid issues with special characters and multiple languages.

### 2. Place

#### 2.1. well-known Directory
In principle, the **`space.txt`** file should be placed under the `/.well-known/` path of your website. For example:

```
https://example.com/.well-known/space.txt
```

#### 2.2. Root Directory
If the `/.well-known/` directory cannot be used for technical reasons, or if you want to use a fallback option, the **`space.txt`** file can also be placed in the `root` directory of your website. For example:

```
https://example.com/space.txt
```

The **`space.txt`** file can be placed in both locations of a website at the same time. Hence, the final directory structure for your website could look like this:

```
example.com/
├── index.html
├── space.txt
└── .well-known
    └── space.txt
```

### 3. Link

#### 3.1. Head

Place a reference to the file using a `“help”` tag to the `<head>` section of your website. For example:

```
<link type="text/plain" rel="help" href="https://example.com/space.txt"/>
```

#### 3.2. Button
Embed a **`space.txt`** button to your site and link it to your **`space.txt`** file.

### 4. Serve

#### 4.1. Internet Media Type
The **`space.txt`** file should have an Internet Media Type of `text/plain`.

#### 4.2. Protocol
The **`space.txt`** file must be served over HTTPS.


## Authors

**`space.txt`** is an open-source project by **[Geoid](https://www.geoid.org "Geoid website")**.

**Geoid is a spatial operating system that covers our entire planet with an extended intelligent dimension.**
This self-organizing network bridges our virtual and physical environments and is formed by all the people of our planet and the information and communication technologies that connect them. Geoid functions as a nervous system that mediates the data we produce and use in our daily lives, adds value to interconnectivity and cherishes spontaneous connections between people and the places and things they love.

website: [www.geoid.org](https://www.geoid.org "Geoid website")


## Contributing

We'd love for you to contribute and to make **`space.txt`** even better than it is today!
Please refer to the [contribution guidelines](.github/CONTRIBUTING.md) for information.


## License

Except where otherwise noted, **`space.txt`** by Geoid is licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons Attribution-ShareAlike 4.0 International License"). To view a copy of this license, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons Attribution-ShareAlike 4.0 International License") or write to Creative Commons, 171 Second Street, Suite 300, San Francisco, CA 94105, USA.


## Disclaimer

**THIS SOFTWARE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
