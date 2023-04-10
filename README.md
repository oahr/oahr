# The Open Amiga Hardware Repository

> **WORK IN PROGRESS**: This project is currently under construction. Please do not apply for Product IDs yet!

The Commodore Amiga platform is still alive, and enthusiasts around the world are still developing new hardware and software for it.

The **Open Amiga Hardware Repository** is meant to promote Amiga related open hardware projects.

Amiga hardware expansions need a _Manufacturer ID_ and _Product ID_ in order to be discovered on the Zorro bus. The _Manufacturer ID_ was assigned by Commodore, while the _Product ID_ was assigned by the manufacturer. Manufacturer IDs can still be requested today, but it is some kind of hurdle for hobbyists. This is where the _Open Amiga Hardware Repository_ comes into play. We have reserved an own _Manufacturer ID_, and are now assigning individual _Product IDs_ to open hardware projects, free of charge!

If you have developed an open Amiga hardware, you have come to the right place. Please read on!

Please also read our [FAQ](faq.md).

## Your Benefits

* Your hardware product can get an official and unique _Product ID_ that is reserved for you for a lifetime. There is no need to use the prototype ID, or to waste time acquiring your own manufacturer ID. All you have to do is to [open an issue](https://github.com/oahr/oahr/issues/new) here.
* Your hardware will be recognized by `boards.library` and `identify.library` with their next update.

## The Rules

The goal of this project is to promote open Amiga hardware projects. You need to comply with the following rules:

* All parts of your project (hardware, firmware, drivers, JEDEC files etc) must be publically available under an open source license that is [OSI](https://opensource.org/licenses/) approved. Of course you are still allowed to use and distribute your project commercially. However, it **must** be possible for anyone to build a working version of your project by all the resources that are publically provided.
* Your project must have reached at least a working prototype state. You must be able to show a working board (no experimental boards) with working firmware or drivers. It is okay if there are still bugs, or if your board still needs a small number of botch wires and manual fixes. Reason is that the number of Product IDs are limited, so we don't want to use them on projects that might never leave their conceptional phase.
* Product IDs will be assigned on a "first-come, first-served" base. The creation date of the GitHub issue is decisive.
* We reserve the right to refuse to assign you a Product ID, without giving any reason.

## How To Apply

Please [open an issue](https://github.com/oahr/oahr/issues/new) with this project. You will find a form there that you will need to fill out.

If we have further questions, we will follow up in that issue.

At the end, if everything went fine, your project will be listed in this repository, and you will get your Product IDs assigned.

## The Repository

The official repository can be found here: [https://github.com/oahr/oahr](https://github.com/oahr/oahr)

The maintainers are (in alphabetical order):

* [bubbob42](https://github.com/bubbob42) - Maintainer of the `boards.library`
* [shred](https://github.com/shred) - Maintainer of the `identify.library`
