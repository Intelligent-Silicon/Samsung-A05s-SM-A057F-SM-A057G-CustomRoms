# Samsung-A05s-SM-A057F-SM-A057G-Custom ROMs

### What are Custom ROM's 

A custom ROM is a third-party, modified version of the Android operating system, built from [Android Open Source Project (AOSP)](https://source.android.com/) code to replace a device's stock software. Developed by 3rd Party's, they offer increased customization, sometimes better performance, sometimes better privacy, fewer bloatware apps, and newer Android versions for older devices. 

The Samsung A05s is a cheap Android operating system phone, so to make life easier, this repo investigates what's involved with flashing different Android ROM's to see how they perform and how to build a custom rom because there are no custom rom's for this phone. This will mean an element of detective work will be involved, which can then be applied to other android phone's not currently supported by custom rom's.

Whilst bugs can be found in the phone manufacturer's stock rom's, bugs can also be found in custom rom's, and both can make phone's more unstable especially when you start to use all its features and not just the most popular feature's.


### Why do this?

Bug's in Samsungs OneUI and app's, a clunky not very appealing interface (opinion), to obtain more configurable privacy options, and to make the phone usable for longer so it doesnt become e-waste. Organisations may also want alternative options than what is offered by Android Fleet Managment software aka Mobile Device Management (MDM) or Enterprise Mobility Management (EMM) solutions.

Key Aspects of Android Fleet Management

Centralized Control: A single, browser-based interface allows IT managers to monitor status, push updates, and troubleshoot devices in real-time.

Security & Compliance: Protects company data through enforced PINs, full device encryption, and remote locking/wiping of lost or stolen devices, if instructions can be sent to the device.

Deployment Methods: Supports fast onboarding, including Google Zero-Touch Enrollment for out-of-the-box, automatic configuration.

Device Modes: Manages various setups, including Work Profiles (BYOD), full device management (COBO), and dedicated kiosk modes for task workers.

Application Management: Managed Google Play allows silent app installation and update  

The knowledge gained here can also be used to make custom rom's for smart TV's like LG's WebOS tv's, TalkTalk TV Boxes, Vehicle (Infotainment) systems, Drones, Control system and other device's which use Linux as its base OS. 

This can be handy for adding features you require if you have multiple device's in the building to add features or to simply remove features which are not required, like the one described here by Google on Hard Braking Events for Raod Safety : https://research.google/blog/hard-braking-events-as-indicators-of-road-segment-crash-risk/. In this instance, its not so much the data thats the issue, its the apparant inability to keep users informed about what is being logged. 

Once data is logged (whatever that data is), it can be interpreted in many ways by "scientists", and Hard Braking Event's is just one way this data can be used. If the vehicle is logging the driver's braking habits, it can also give away infomation thats also typically seen with dashcam users, especially the one's who upload data to Youtube channels. 

More and more, viewers can see DashCam user's being highly passive aggressive when they wouldnt otherwise have been, a classic example of the saying "acting up for the camera", and also engaging in deliberate late braking to the point of deliberately crashing as if they were Andy Pipkin from Little Britain! The data uploaded on to Youtube and/or handed over to the insurance company can then be used by them to put markers on driver's which can then affect their premiums. In todays day and age, data sharing is more prevalent in disengenious ways than is commonly reported, with the state having a head start at interpreting esoteric data sources with [Signals Intelligence](https://en.wikipedia.org/wiki/Signals_intelligence) via the military. Sure its tells a more accurate picture, but the data collection is also altering people's behaviour, and that's not always for the best! This also demonstrates an argument against the saying, if you have nothing to hide, you have nothing to fear. https://blog.dmcc.io/journal/2026-bluetooth-privacy-bluehood/

### Why not do this?

Banking app's in particular, may not work so you wont be able to access your bank account's easily. They rely heavily on security measure's which go deep into the Android operating system and hardware, out of the way of your regular mobile phone user so they cant tamper with it. Here's a [website](https://privsec.dev/posts/android/banking-applications-compatibility-with-grapheneos/) dedicated to listing the banking app's around the world which works with GrapheneOS, one of the custom ROM's mentioned below.

### Bricking. 

Bricking a device is another way of saying killing a mobile phone. Manufacturer's use esoteric means to keep people away from installing custom rom's because it helps to cement their position in the market, as a result diverse options and choice's become non existant leading to a market place thats close to being a monopoly. So have the US tech giants turned the world into a giant global Soviet Union with the lack of choice? That is after all Globalisation.

You will encounter many steps which could cause your device to brick because of manufacturer quirks. When a device is bricked, there's also two form's, one is called a soft brick, which refer's to software/firmware causing the device to not work, and a hard brick which refer's to hardware components not working which typically results in the component having to be replaced. 

A soft brick is more easily recoverable with the right software, a hardware brick will involve specialist tools and less specialist tools like a soldering iron.

### How frequently will this repo be updated?

Over the next few months, the time of writing being Feb 2026. This is currently a work in process repo, mainly to investigate whats involved in making a custom rom for educational purposes, nothing more.

### Custom ROM's 

These are some of the off-the-shelf custom rom's which exist for Android phone's (not to be interpreted as endorsements), however none of these can be downloaded and used on a Samsung A05s, so the next steps will be to investigate whats involved in making these work on the Samsung A05s. These custom rom's were current as at Feb 2026.

[LineageOS](https://lineageos.org/): The successor to CyanogenMod, it is considered the most stable, widely supported, and foundational ROM, providing a near-stock Android experience.

[crDroid](https://crdroid.net/): Based on LineageOS, it is known for being highly stable while offering a huge variety of customization options for the UI and system.

[PixelOS](https://pixelos.net/): A popular ROM that aims to bring the experience, features, and UI of a Google Pixel phone to other devices.

[Evolution X](https://evolution-x.org/): Focuses on bringing Pixel-like functionality with extra customization, offering "Pixel-ism".

[GrapheneOS](https://grapheneos.org/): The gold standard for security and privacy, focusing on hardening the Android OS (best for Pixel devices).

[Project Infinity X](https://projectinfinity-x.com/): Recognized for advanced, next-level customization and modern Android updates.

[Derpfest](https://derpfest.org/) & [AlphaDroid](https://alphadroid.org): Popular options known for being fast, stable, and offering extensive user interface tweaks.

[Paranoid Android](https://paranoidandroid.co/): A historically significant, refined ROM that focuses on design and unique feature


### XDA Developer's 

A special mention goes to [XDA Developers](https://www.xda-developers.com/) as the world's largest online community for mobile software development, founded in 2002! It serves as a premier forum and resource hub for Android enthusiasts, developers, and users to discuss, troubleshoot, and customize mobile devices, including rooting, custom ROMs, and hacks. Now owned by Valnet Inc., it also provides news, reviews, and coverage on broader technology topics like PC components and Ai. Its proved useful over the years.


## Step's 

1. [Obtaining Phone Specs](Obtaining-Phone-Specs.md) Before a custom rom can be built, knowing the device hardware spec's is crucial in order to make the custom rom work.





### Links used in the detective work

The following links look interesting and hold the possibility of providing so useful instructions, guidance or hint's that could prove useful in the task of flashing this Samsung A05s with custom ROM's.

It show's how much documentation has to be perused to achieve the objective, if the objective is even attainable.


https://source.android.com/docs/core/architecture/dto

https://source.android.com/docs/core/architecture/bootloader/dtb-images

https://brandolamarck.substack.com/p/how-to-extract-and-decompile-the

https://derpfest.org/build

https://gist.github.com/mvaisakh/1a45694e33584592e8fae37fe29d757d

https://xdaforums.com/t/how-to-convert-back-qualcomms-dtb-to-dts-file-extract-kernel-config.3221223/

https://xdaforums.com/t/rom-wt88047-l-5-1-1-cyanogenmod-unofficial-builds.3200883/

https://github.com/moetayuko/split-appended-dtb

https://discourse.coreelec.org/t/extracting-dtb-file-from-a-running-android-os/1218

https://wiki.postmarketos.org/wiki/Device_Tree_(dtb)

https://blog.tomaszdunia.pl/grapheneos-eng/

https://news.ycombinator.com/item?id=47045612

https://grapheneos.org/faq#supported-devices

"Many other devices are supported by GrapheneOS at a source level, and it can be built for them without modifications to the existing GrapheneOS source tree. Device support repositories for the Android Open Source Project can simply be dropped into the source tree, with at most minor modifications within them to support GrapheneOS. In most cases, substantial work beyond that will be needed to bring the support up to the same standards. For most devices, the hardware and firmware will prevent providing a reasonably secure device, regardless of the work put into device support.

GrapheneOS does not support being used as a Generic System Image, which only exists for development/testing purposes and isn't usable for GrapheneOS since we require kernel changes and the userspace part of the OS cannot run on top of a kernel without the required functionality. 

See more on the link above"


https://news.ycombinator.com/item?id=47035560

https://blog.dmcc.io/journal/2026-bluetooth-privacy-bluehood/


https://news.ycombinator.com/item?id=47014002 

https://dbg.re/posts/car-file-format/

https://news.ycombinator.com/item?id=47014460

https://www.intertronics.co.uk/wp-content/uploads/2017/05/PCB-Rework-and-Repair-Guide.pdf

https://news.ycombinator.com/item?id=47011548

https://github.com/NationalSecurityAgency/ghidra


https://news.ycombinator.com/item?id=47025085

https://github.com/pocketblue/pocketblue

https://ooh.directory/blogs/technology/









