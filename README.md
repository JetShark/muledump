![Jakcodex/Muledump](https://img.shields.io/badge/jakcodex-muledump-blue.svg?style=flat-square)
[![Muledump Online](https://img.shields.io/badge/dynamic/json.svg?label=online&colorB=9e43f9&prefix=v&suffix=&query=$.version&uri=https%3A%2F%2Fjakcodex.github.io%2Fmuledump%2Fpackage.json)](https://jakcodex.github.io/muledump/muledump.html)
[![Muledump Preview](https://img.shields.io/badge/dynamic/json.svg?label=preview&colorB=5942f4&prefix=v&suffix=&query=$.version&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fjakcodex%2Fmuledump-preview%2Fmaster%2Fpackage.json)](https://jakcodex.github.io/muledump-preview/muledump.html)

## Welcome

This is a fork of Atomizer's [Muledump](https://github.com/atomizer) made to address the required changes since the most recent upstream release.

You can read about the reasoning for a new fork in the [upstream notes](UPSTREAM.md).

## Synopsis

This tool allows you to list contents of all your accounts in a single page (characters, their stats and items, items in vaults). Also it generates a summary of all the items - you probably saw screenshots of these in trading forum ([example](https://imgur.com/dDA2vC9)).

The point of playing the game is to have fun. Muling is not fun. I am trying to increase overall fun ratio by decreasing amount of time spent fussing with mules and storagekeeping.

## Requirements

Currently due to how Deca handles requests to ROTMG servers a browser extension is required to use this Muledump.

See the [Requirements](REQUIREMENTS.md) page for more information.

### Head over to [Installation and Setup](https://github.com/jakcodex/muledump/wiki/Installation-and-Setup) in the wiki for a detailed setup guide.

## Release Information

The current version is Jakcodex/Muledump v9.2.

Muledump Online is available hosted on Github [here](https://jakcodex.github.io/muledump/muledump.html).

All released versions are available for download [here](https://github.com/jakcodex/muledump/releases).

## Muledump Online Version

- Open [https://jakcodex.github.io/muledump/muledump.html](https://jakcodex.github.io/muledump/muledump.html)
- Returning users can upload a backup or import their existing accounts.js file
- New users will be guided through first time setup
- This version runs entirely on your local computer and is updated automatically with new releases
- All user and account data submitted and stored in this version never leaves your computer

## Muledump Local Version

- Unzip the latest muledump release
- Open **`muledump.html`**
- First time users will be guided thru Muledump setup
- Returning users are ready to go immediately

## Main Features

- Manage all of your ROTMG accounts from a single interface
- [SetupTools](docs/setuptools/index.md) - An easy to use, browser-based user interface for managing Muledump
- [Groups Manager](docs/setuptools/groups-manager/manager.md) - Account grouping and ordering utility to customize the Muledump accounts list
- [Muledump Online](https://jakcodex.github.io/muledump/muledump.html) - Load Muledump directly from Github using SetupTools
- MuleQueue - Task queuing to control the flow of requests from Muledump
- Vault display is now fully customizable and comes with four pre-defined layouts
- Full character skin and dye support in portraits
- Totals filtering on fame bonus, feed power, soulbound, ut, and st, and specified accounts
- Character Sorting by fame, exp, total fame, class, active time, maxed stats, and custom lists
- Character Lists allow you to create custom Muledump account layouts showing only characters you specify 
- Exporting works with the following modes: text, csv, json, image, imgur
- Fully compliant with Deca rate limiting

## Not so obvious features

- click on item to filter accounts that hold it
- click on account name for individual options menu
- ctrl-click account name to temporarily hide it from totals
- ctrl-click on an item to open its Realmeye menu
- ctrl-click on two items to open the Realmeye Trading menu
- logins thru muledump count towards daily login calendar
- account settings include automatic reload, login-only (daily calendar only), and cache disable
- right click anywhere on a mule to access the mule menu
- active mulequeue can be resumed if muledump is closed

## Check out the [Frequently Asked Questions](https://github.com/jakcodex/muledump/wiki/Frequently-Asked-Questions) and explore the [wiki](https://github.com/jakcodex/muledump/wiki) for more information!

<a id="jakcodex-supportandcontributions"></a>
## Support and Contributions

Jakcodex/Muledump operates its own support Discord server - [https://discord.gg/JFS5fqW](https://discord.gg/JFS5fqW).

Feel free to join and ask for help getting setup, hear about new updates, offer your suggestions and feedback, or just say hi.

If you encounter a bug, have a feature request, or have any other feedback you can also check out the [issue tracker](https://github.com/jakcodex/muledump/issues) to see if it's already being discussed. If not then you can [submit a new issue](https://github.com/jakcodex/muledump/issues/new).

If you are interested in helping test new versions of this software before release then check out [Muledump Preview](https://github.com/jakcodex/muledump-preview/) for the recent stable development builds of Muledump.

Feel free to submit pull requests or patches if you have any Muledump changes you'd like to contribute. See [Contributing](https://github.com/jakcodex/muledump/wiki/Contributing) for more information.

## Version and Update Information

Muledump versions are described as x.y.p where x is the major version, y is the minor version, and p is the patch version.

All incrementes of x or y are published as an official Muledump Local release. Subsequent patches after release will not be published as a new release.

Muledump Online always runs the latest version of Muledump with all patches.

## Special Thanks

Muledump Renders and Constants are maintained by [tuvior](https://github.com/tuvior).

## FYI

The following paths are for Github Pages configuration and are not apart of the Muledump code: _layouts, assets, and _config.yml.

## Donations

People ask about donating to the Jakcodex/Muledump project rather frequently. This project has not been without its expenses, so your contributions are welcome and appreciated.

If you are so inclined, you can donate to one of these locations:

##### Paypal
paypal@jakcodex.io

##### Bitcoin
bitcoin:1FfFBFNcWuvZMFRvZ7K9byh341h7yJte2P

## Privacy Policy

Click to read more about our [Privacy Policy](privacy-policy.md).

## Jakcodex/Muledump License

Copyright 2018 [Jakcodex](https://github.com/jakcodex)

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
