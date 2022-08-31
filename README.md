<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Prerequisite

### Windows

- [Docker for Windows](https://docs.docker.com/desktop/install/windows-install).

### UBUNTU

If you are using Ubuntu please follow following steps from *CLI (Command Line Inteface)

- sudo apt update
- sudo apt install apt-transport-https ca-certificates curl software-properties-common
- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - | apt-get update
- sudo apt-get install docker-ce
- DOCKER_CONFIG=${DOCKER_CONFIG:-$HOME/.docker}
- mkdir -p $DOCKER_CONFIG/cli-plugins
- curl -SL https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64 -o $DOCKER_CONFIG/cli-plugins/docker-compose
- chmod +x $DOCKER_CONFIG/cli-plugins/docker-compose

To check installation run the follwing command in your cli

- sudo docker run hello-world

## Steps to setup application

Clone the Application in your local in CLI using following command 

- git clone https://github.com/ganeshdamuluri/loan-application.git
- cd loan-application

### Windows

- docker-compose up

### UBUNTU

- sudo docker-compose up -d

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
