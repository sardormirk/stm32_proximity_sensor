<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
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
[![Issues][issues-shield]][issues-url]




<!-- PROJECT LOGO -->
<br />

<h3 align="center"> Object Proximity Alarm Device  </h3>

  <p align="center">
  A proximity alarm device that emits a varying frequency buzz depending on the distance of an object to the devices ultrasonic distance sensor
    <br />
    <a href="https://github.com/voidblob/TermText"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/voidblob/TermText">View Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
![Showcase](https://github.com/voidblob/stm32_proximity_sensor/blob/master/device.jpg?raw=true)


![Showcase](https://github.com/voidblob/stm32_proximity_sensor/blob/master/proximity-sensor-main/STM32Workspace/v.1.0-electric-schematic.png?raw=true)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![C++][C++]][C++-url]
* STM32F401RE Microcontroller
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Instructions for building the device yourself can be found in the design document pdf. Inside, you will find circuit diagrams, part names and cost, as well as an assembly guide.

### Prerequisites

* STM32CubeIDE
* STM32F401RE nucleo development board
* Breadboard
* Wires
* HCSR04 UltraSonic Distance Sensor
* Buzzer

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

The device works by converting the analog voltage signals returned by the HCSR04 distance sensor when an object is placed infront of it to float distance values. These distance values are then used to
determine the magnitude and frequency of the noises emitted by the buzzer. This conversion is done using input capture and PwM


<p align="right">(<a href="#readme-top">back to top</a>)</p>







<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/voidblob/TermText.svg?style=for-the-badge
[contributors-url]: https://github.com/voidblob/TermText/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/voidblob/TermText.svg?style=for-the-badge
[forks-url]: https://github.com/voidblob/TermText/network/members
[stars-shield]: https://img.shields.io/github/stars/voidblob/TermText.svg?style=for-the-badge
[stars-url]: https://github.com/voidblob/TermText/stargazers
[issues-shield]: https://img.shields.io/github/issues/voidblob/TermText.svg?style=for-the-badge
[issues-url]: https://github.com/voidblob/TermText/issues
[license-shield]: https://img.shields.io/github/license/voidblob/TermText.svg?style=for-the-badge
[license-url]: https://github.com/voidblob/TermText/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: https://github.com/voidblob/TermText/blob/master/demo.png
[C++]: https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white
[C++-url]: https://cplusplus.com/
[OpenGL]: https://img.shields.io/badge/OpenGL-%23FFFFFF.svg?style=for-the-badge&logo=opengl
[OpenGL-url]: https://www.opengl.org/
[Cmake]: https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white
[Cmake-url]: https://cmake.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
