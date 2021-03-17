<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="https://user-images.githubusercontent.com/80778103/111392388-79129c80-8684-11eb-815e-9d02912d8949.png" alt="Spatium Logo" width="384" height="102">
  </a>

  <h3 align="center">README-Documentation</h3>

  <p align="center">
    A README section to explain our project!
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Project Binder</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">YWPN Presentation</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center">
    <img src="https://youngwomensprep.org/wp-content/uploads/2021/01/STEAM-Challenge-logo-.png" alt="YWPN Logo" width="384" height="102">
  </a>
   <br />
This project was completed for a Network STEAM Challenge. This code is for our prototype, which utilizes infrared signals to sense individuals within 6ft. We hope that this helps maintain individuals socially diatanced. This relies on the fact that others will have a simillar device and would be best implemented in areas where social distancing is particularly important to individuals like hospitals or grocery stores.

* A portable and wearable soloution to social distancing
* Battery Powered
* Easy to use

### Built With

Required materials to create this are...
* Arduino Pro mini
* Rocker Switch
* Piezo Buzzer
* IR Reciever Diode
* .93" OLED display 



<!-- GETTING STARTED -->
## Getting Started

Set up the circuit before beginning, preferibly using a bread board for testing.
Below is a wiring diagram.
<p align="center">
    <img src="https://user-images.githubusercontent.com/80778103/111394343-90538900-8688-11eb-9c5a-6417ac0b3ebb.png" alt="Breadboard Wiring diagram" width="500" height="347">
  </a>

### Prerequisites

To run this code you will need the Arduino IDE and several libraries (listed below).
* SPI.h
* Wire.h
* IRremote.h //IR Library
* Adafruit_GFX.h //Display Library
* Adafruit_SSD1306.h //OLED Library

  ```sh
  #include <SPI.h>
  #include <Wire.h>
  #include <IRremote.h>//IR Library
  #include <Adafruit_GFX.h> //Display Library
  #include <Adafruit_SSD1306.h> //OLED Library
  ```


<!-- USAGE EXAMPLES -->
## Usage

These are images of our protype in use. 
_For more examples, please refer to the [Binder](https://example.com)_


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Project Link: [https://github.com/AlinneRT1/Infrared-Detection-Prototype/blob/main/README.md](https://github.com/AlinneRT1/Infrared-Detection-Prototype/blob/main/README.md)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Adafruit OLED Library](https://learn.adafruit.com/monochrome-oled-breakouts/arduino-library-and-examples)
* [IR Remote LIbrary](https://github.com/Arduino-IRremote/Arduino-IRremote)
* [READ.ME Template](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
