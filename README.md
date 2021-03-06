[![Build Status][build-shield]][build-url]
[![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT INFO -->
<br />
<p align="center">

  <h1 align="center">Laravel Vue Easy Run Script</h1>

  <p align="center">
    A Small Script to make you life easier
    <br>
    <br>
    This script works only on linux software
  </p>
</p>


<!-- ABOUT THE PROJECT -->
## About The Project

This is a Small script to make your life easier. With one simple words you start, restart or close your: NPM RUN WATCH and PHP ARTISAN SERVE. it is not much but it is nice and easy. It work all on the background so no bother with extra terminals.

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### required

* Linux software
  * Windows Linux terminal (works)
  * Git Bash (doesn't work)
* Laravel project
  * composer
  * node.js
* Screen
  ```sh
  sudo apt-get install screen
  ```

### Installation

1. Go to your home folder
    ```sh
    cd
    ```
2. Download the start.sh
    ```sh
    git clone https://github.com/L27SlubbyGames/Laravel-Vue-Easy-Run-Script.git
    ```
3. Than place is in your bin folder to use is every where
    ```sh
    mv Laravel-Vue-Easy-Run-Script/start.sh /usr/bin/vues
    ```
3. Give the script executable permission
    ```sh
    chmod +x /usr/bin/vues
    ```
5. Done

<!-- USAGE EXAMPLES -->
## Usage

Start the screens
```sh
sudo vues start
```

Restart the screens
```sh
sudo vues restart
```

Close the screens
```sh
sudo vues stop
```

Make new laravel project
```sh
sudo vues new [<name of project>] 
```

Shows all the commands
```sh
sudo vues help
```

Info about the commands
```sh
sudo vues info
```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[build-url]: #
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[contributors-url]: https://github.com/L27SlubbyGames
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://github.com/L27SlubbyGames/Laravel-Easy-Run-Script/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/pascal-huberts-b1a602179/
