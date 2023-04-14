# The Rules

Amiga hardware expansions need a _Manufacturer ID_ and _Product ID_ in order to be discovered on the Zorro bus. The _Manufacturer ID_ was assigned by Commodore, while the _Product ID_ was assigned by the manufacturer. Manufacturer IDs can still be requested today, but it is tedious for hobbyists.

This is where the _Open Amiga Hardware Repository_ comes into play. We have reserved an own _Manufacturer ID_, and are now assigning individual _Product IDs_ to open hardware projects, **simple and free of charge**!

## Your Benefits

* Your hardware product gets an official and unique _Product ID_ that is reserved for you for a lifetime. There is no need to use the prototype ID, or to waste time acquiring your own manufacturer ID. All you have to do is to [open a new issue](https://github.com/oahr/oahr/issues/new/choose) and apply for it.
* Your hardware will be recognized by `boards.library` and `identify.library` with their next update.

## The Rules

The goal of this project is to promote **open Amiga hardware projects**.

To get added to this repository, and get your own product IDs, you need to comply with the following rules:

### 1. Open Source

All parts of your project (hardware, firmware, drivers, JEDEC files etc) must be publically available either under [Creative Commons](https://creativecommons.org/licenses/) or with an [OSI](https://opensource.org/licenses/) approved open source license.

Of course you are still allowed to use and distribute your project commercially. However, the resources that you provide must be sufficient so anyone who wants to can build a working version of your project by themself.

### 2. Prototype State

Your project must have reached at least a working prototype state. You must be able to show a working board (no experimental boards) with working firmware or drivers.

It is okay if there are still bugs, or if your board still needs a small number of botch wires and manual fixes.

The reason for this rule is that the number of Product IDs are limited, so we don't want to use them on projects that might never leave their conceptional phase.

### Furthermore

* Product IDs will be assigned on a "first-come, first-served" base. If there are conflicting applications, the creation date of the GitHub issue will be decisive.
* We reserve the right to refuse to assign you a Product ID, without giving any reason.

## How To Apply

Please [open an issue](https://github.com/oahr/oahr/issues/new/choose) with this project. You will find a form there that you will need to fill out.

If we have further questions, we will follow up in that issue.

At the end, if everything went fine, your project will be listed in this repository, and you will get your Product IDs assigned.
