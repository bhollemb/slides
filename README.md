# slides
Central place for slide decks I have presented.

## Finding a Weak Link: Attacking Windows OEM Kernel Drivers

**Derbycon 2016**

Abstract:

The security of OEM drivers is an oft-overlooked blind spot that serves to undermine platform hardening efforts. To show that the rigorous security development lifecycle applied to Microsoft developed software does not extend to the OEM developers that bundle kernel drivers in with their hardware, we developed tools, methods, and techniques to efficiently produce exploitable kernel driver vulnerabilities in our fully patched Windows 10 installations. This talk will dive into the methodology and tools we created as well as the vulnerabilities we found during this investigation. We will take a close look at effective driver fuzzing and how modifications we made to a public fuzzing tool resulted in exploitable crashes. We introduce and demo our new IDA Pro plugin, DriverBuddy, that automates much of the repetitive tedium involved with kernel driver reverse engineering. We will then discuss vulnerability analysis techniques, such as the efficient triaging of crash dumps and patterns of exploitability. Finally, we will discuss the results of our methods by analyzing some of the vulnerabilities we discovered and deep-diving an exploit against our Windows 10 laptops that allows us to map and read physical memory, including the kernel memory containing the Bitlocker AES key, as an unprivileged user.

[Video of presentation](http://www.irongeek.com/i.php?page=videos/derbycon6/418-finding-a-weak-link-attacking-windows-oem-kernel-drivers-braden-hollembaek-adam-pond)

## Understanding Windows Kernel Exploitation

**Toorcon San Diego 2016** 

Abstract: 

As userland security protections have become more robust, vulnerability research has increasingly focused on the kernel as a way to circumvent userland protections such as sandboxes. In this presentation, we catalog exploitation techniques that can be used to turn various exploit primitives in the Windows kernel into useful escalations of privilege. We briefly cover the internals of the Windows security model and identify kernel structures that are interesting from an exploitation point of view. This includes select case studies of recent Windows kernel vulnerabilities as well as demonstrations of exploit techniques that can be used to gain arbitrary ring-0 code execution or SYSTEM shells.
