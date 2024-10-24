<!--
*** Thanks for checking out c. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![NO LICENSE][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://gdansk.pja.edu.pl/pl/">
    <img src="images/logo.jpg" alt="Logo" width="540" height="80">
  </a>

  <h2 align="center">Computer Graphics</h2>

<p align="center">
    <h3>     Programming computer graphics in OpenGL library
 </h3>
    <!-- <br />
    <a href="https://github.com/dccstcc/GRK_PJATK_practice"><strong>» go to CODE »</strong></a>
    <br />
    <br />  -->
    <!-- <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a> -->
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-description">Project description</a>
      <ul>
        <li><a href="#libraries-and-frameworks">Libraries / Frameworks</a></li>
      </ul>
    </li>
    <li>
      <a href="#native-deploy">Native deploy</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#how-to-use">How to use ?</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li> -->
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact with me</a></li>
    <!-- <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Project description

In this subject I made four projects according to programming in C++ language and OpenGL library. These codes include implementation of 3D graphics models with animation.

### Libraries and frameworks

This project use technology below.

- [![debian][debian-shield]][debian-url]
- [![opengl][opengl-shield]][opengl-url]
- [![cpp][cpp-shield]][cpp-url]

<!-- GETTING STARTED -->

## Native deploy

This is instructions on setting up this project locally.

### Prerequisites

Linux based on Debian distribution is need. <br/>
OpenGL library is required. <br/>
C++ compilator is need. <br/>

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/dominik-stec/Graphics.git
   ```
2. Install required build tools
   ```sh
   sudo apt-get install g++ make
   ```
3. Install required dependencies
   ```sh
   sudo apt-get install freeglut3 freeglut3-dev libglew-dev
   ```
   <br/>
4. Install optional dependencies
   ```sh
   sudo apt-get install libglfw3-dev libgl1-mesa-dev libglu1-mesa-dev
   ```

<!-- USAGE EXAMPLES -->

## How to use

Into Debian based Linux distribution as background go to each of four catalogs and into all of them separately enter into terminal command:

```sh
make
```

After build all projects run each of them separately by GUI icon which should appear and which represent enter point to run simulation.

<br /><br />

TwoSpheres render:

<img src="images/ts1.png" width="300"/>
<img src="images/ts2.png" width="300"/>
<img src="images/ts3.png" width="300"/>
<br />

ThreeLights render:

<img src="images/tl1.png" width="300"/>
<img src="images/tl2.png" width="300"/>
<img src="images/tl3.png" width="300"/>
<br />

Kdron render:

<img src="images/kdron1.png" width="300"/>
<img src="images/kdron2.png" width="300"/>
<br />

Circle render:

<img src="images/circle1.png" width="300"/>
<img src="images/circle2.png" width="300"/>

<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->

<!-- ROADMAP
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).

-->

<!-- CONTRIBUTING
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

-->

<!-- LICENSE -->

## License

This project has not a license.
All rights are reserved and it is not Open Source or free. You cannot modify or redistribute this code without explicit permission from the copyright holder, because projects which I realised are private conception from PJATK studies.
See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Dominik Stec - dccstcc@gmail.com

[![LinkedIn][linkedin-shield]][linkedin-url]

Project URL:
<br />
`https://github.com/dominik-stec/Graphics.git`

<!-- ACKNOWLEDGEMENTS
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)

-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/dominik-stec/Graphics.svg?style=for-the-badge
[contributors-url]: https://github.com/dominik-stec/Graphics/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dominik-stec/Graphics.svg?style=for-the-badge
[forks-url]: https://github.com/dominik-stec/Graphics/network/members
[stars-shield]: https://img.shields.io/github/stars/dominik-stec/Graphics.svg?style=for-the-badge
[stars-url]: https://github.com/dominik-stec/Graphics/stargazers
[issues-shield]: https://img.shields.io/github/issues/dominik-stec/Graphics.svg?style=for-the-badge
[issues-url]: https://github.com/dominik-stec/Graphics/issues
[license-shield]: https://img.shields.io/badge/License-NONE-orange
[license-url]: https://github.com/dominik-stec/Graphics/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/dominik-stec
[product-screenshot]: images/screenshot.png
[debian-shield]: https://img.shields.io/badge/-Debian-red
[debian-url]: https://www.debian.org/index.pl.html
[opengl-shield]: https://img.shields.io/badge/-OpenGL-green
[opengl-url]: https://www.opengl.org/
[cpp-shield]: https://img.shields.io/badge/-C++-blue
[cpp-url]: https://isocpp.org/std/the-standard
