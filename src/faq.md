# Frequently Asked Questions

## Open Hardware

**What parts of the project must be open?**

> Everything that is required for anyone to build and run a working copy of your hardware. This is (not limited):
>
> * Circuit diagrams
> * Gerber files (to order the PCB at a PCB manufacturer) or the related CAD project files
> * JEDEC files for programming CPLDs, PALs, etc.
> * Firmwares (e.g. EPROM, EEPROM, Flash ROM)
> * Amiga drivers (if necessary)
> * Documentation (so people will know how to build it)
>
> Rule of thumb: If a functional copy of your hardware cannot be made without having to purchase components, software or documentation exclusively from you (or an associated vendor), then your project is not eligible for this repository.
>
> CAD project files are sufficient if you use an open CAD tool like [KiCAD](https://www.kicad.org/) or [LibrePCB](https://librepcb.org/), so anyone interested can generate the Gerber files themself.

**Can I still earn money with my project?**

> Of course! You can sell the complete hardware, construction kits, PCBs, preprogrammed chips etc. You can also ask for donations.
>
> The only strict requirement is that anyone who is willing and able to build and run the hardware, will find all necessary resources in your project for free.

**There is an open source and an improved closed source version of my project.**

> You can apply (and get a Product ID) for the **open** part of your project. The closed part however is not eligible. The same applies if your project consists of an open main part, and proprietary extensions.

**Can I commercially use any of these projects, and become rich from other people's work?**

> We cannot tell you. **Please read the license of the respective project!** Some projects permit commercial use, while other explicitly forbid it.
>
> Anyway, it is generally frowned upon to make money off the hard work that other people provided for free. If you plan to sell PCBs, kits, or complete hardware, please contact the creator of the project, and make sure they will get a fair share of your profits! This includes selling on online marketplaces or auction sites on a small scale.
>
> We personally know a couple of makers who removed their projects from public, or even gave up making new open hardware, because other people sold their work for own profit.

## Manufacturer/Product ID

**What Manufacturer ID do you have?**

> Our manufacturer ID is 5194<sub>(10)</sub> = 144A<sub>(16)</sub>.

**Is this an official ID?**

> **Yes!** The Manufacturer ID is officially registered with Hyperion Entertainment CVBA for exclusive use by this project. Your individual Product ID is assigned to you by us, and is valid for a lifetime.

**Can I ask for a specific Product ID?**

> Sure, unless it is already taken. We reserve the right to give you another Product ID though.

**Can I have multiple Product IDs for the same project?**

> Sure, if multiple Product IDs are technically required.
>
> However, you cannot reserve Product IDs for future use. But there is also no need to do so, since it is easy to get more Product IDs as soon as you extend your project or start another one.

**Can I use your Manufacturer ID and a preliminary Product ID for my early prototype?**

> **No! You must not use our Manufacturer ID without our consent.** If your project is in an early prototype phase, you can use the prototype Manufacturer ID 2011⏨, which was reserved by Commodore for exactly that purpose. When you can show a working prototype, you can apply for your Product ID. As soon as you got your Product ID assigned by us, you can use it for your project. But not sooner!

**Can I have a different Manufacturer ID?**

> Sure, but not from us. 😉 You can [obtain your own Manufacturer ID](https://wiki.amigaos.net/wiki/Amiga_Hardware_Manufacturer_ID_Registry) at Hyperion Entertainment CVBA.
>
> If your project complies to our rules for open Amiga hardware projects, you can still [apply to be listed here](application.md) though.

**I want to exclusively sell components of my project. Can I still have a Product ID?**

> No. We can understand that you would like to have a financial compensation for the time you have invested in the project, but this repository is dedicated to promote Amiga hardware that is fully open. You can quote your own Manufacturer ID from Hyperion Entertainment CVBA though.

**boards.library does not show my name as manufacturer!**

> Yes, unfortunately the `boards.library` does not support diverging manufacturer names on product IDs. `identify.library` will show your name as manufacturer of your board though.

## Forking, Closing etc

**I have made a fork of an open Amiga hardware project. Can I get my own Product ID?**

> If it is just a fork, then no. You can still use the original product ID.
> 
> If your fork has evolved, and there are changes to the original project that justify an own product ID, you can apply for one. Example: You forked an USB expansion, and added an SD card adapter to it.

**I want to continue the development of my project as closed source.**

> You can do so if your license permits it.
>
> However, your Product ID was assigned to the **open** version of your project. If you close it, you must register your own Manufacturer ID with Hyperion Entertainment CVBA for the closed version.
>
> Note that we remove your project from this repository if it is not reachable at the given web address anymore.

**I have removed my project from the public.**

> That's sad. Your project will be removed from this repository if it is not reachable at the given web address anymore, unless you can provide us a link of an official fork or archive that still complies with our rules.
>
> Your Product ID will stay reserved for your project, and will not be assigned to other projects. Note that you cannot reuse the Product ID on another project of yours, since it is connected to this project.
