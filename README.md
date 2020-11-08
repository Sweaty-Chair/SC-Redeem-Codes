# SC Redeem Codes
[![Build status](https://ci.appveyor.com/api/projects/status/github/Sweaty-Chair/SC-Redeem-Codes?branch=main&svg=true)](https://ci.appveyor.com/project/Sweaty-Chair/Unity-Redeem-Code/branch/main)
[![Join the chat](https://img.shields.io/badge/discord-join-7289DA.svg?logo=discord&longCache=true&style=flat)](https://discord.gg/qwqeBtS)

> A redeem code system in Unity for compensating your players or rewarding them in events. A redeem code contains 12 characters (letters+number). You will need your own server to store and validate the redeem code. Use [this Laravel pagkage](https://github.com/furic/laravel-redeem-codes) for creating the server Redeem code function in Laravel, or you can create your own.

## Table of Contents
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [License](#license)

## Installation
Import this package into Unity, you will also need [SC-Essentials](https://github.com/Sweaty-Chair/SC-Essentials) package for the shared scripts.

## Configuration
Go to menu toolbar > Sweaty Chair > Settings > Server, and put your server API URL.

## Usage
Call `RedeemCodeManager.Show()` to show a input box for player to input the redeem code.
![Redeem code screenshot](https://static.sweatychair.com/images/no-humanity/no-humanity-redeem-code-2.png)

If the redeem code is valid, the corresponding reward will be given to the players. Make sure the item type enums match the ones in Unity, and being implemented.

## License

SC Redeem Codes is licensed under a [MIT License](https://github.com/Sweaty-Chair/Unity-Redeem-Code/blob/main/LICENSE).