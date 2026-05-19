**Joel Larsson**
Uppsala, Sweden
Email: [ifully@autom8ed.me](mailto:ifully@autom8ed.me)
GitHub: https://github.com/autom8edIT

---

### Executive Summary

Highly versatile IT systems engineer and infrastructure tactician with over 20 years of experience in high-performance computing, automation, overclocking, and hardcore system customization.

Known as "The Machine" for focus, output and endurance that exceeds most people.

Combines unmatched technical intuition with raw efficiency, enabling elite performance in system hardening, endpoint control, and automation development.

Open to relocate to the United States to work on forward-thinking infrastructure, cyber defense, and automation projects that empower Western innovation and digital sovereignty.

---

### Core Competencies

* RAM-only architecture and stealth automation (TOTP, MFA, token workflows, apps, scripts, you name it, I'll run it)
* PowerShell 5 & 7+ / Python automation (privileged execution, GUI control, secure memory usage, uninstalling, configuring etc.)
* Web code, my MFA extension is made from JS, HTML and CSS.
* Basic C/C++ for using WinDBG, compile and build things from repos that isn't complete.
* Windows internals, bloat removal, hardening, and system security
* Mac / PC Win10/11, Linux / Apache.
* Enterprise environments like Windows domain/AD/M365 administration.
* Offensive mindset with defensive application (EDR bypass knowledge, ethical scope)
* Network stack control (firewall scripting, remote access lockdown, stealth tunneling) and setup of routers and AP's, VLAN rules and so on.
* TeamViewer, RustDesk.
* Overclocking and thermal/power management expert, been overclocking everything since my first computer.
* GitHub/GitOps flow, Visual Studio 2022/2026, VS Code, documentation discipline, automation branding (Autom8ed)

---

### Professional Experience

\*\* IT Expert \*\*

&#x20;University – IT Department
*2021–Present*

* Pre 2021 SysAdmin at Mannheimer Swartling (https://www.mannheimerswartling.se)

* CTO at Addus Law, a small law firm where I got to choose / decide everything.

Was the only non lawyer in the company so I got to determine and pick their entire IT environment. Which computers, law document handling system, if they should lease anything exceot for an MFP and so on.
Then install and configure everything from the LAN and WIFI at the office and setup VPN and M365 so they could work seamlessly together no matter location and device.
If something of any kind didn't work I solved it no matter if it was their OS, device, password etc. that was the root cause.

* SysAdm at CVO, a company that focused on helping people with mental annd often physical disabilites.

So they had no IT-department before I started working there and began the huge task of setting up a functionining environment.
It included everything from helping them select and use laptops that wasn't just bought randomly from Elgiganten or similar.

Also every building they used and/or aquired at best had a consuner router and a contract with an ISP.
So I drilled a lot of holes for installing ethernet cables that any of their patients could rip apart and setup working AP:s so they got coverage everywhere instead of just around where they initally had put the router.
In some of the bigger buildings I also installed patch panels with switches so you knew where office outlet X went.
Also consolidated their services like using a single ISP for better price and control.

Unfortunately they got aquired by a larger group of companies that specified in aquiring healthcare companies to build a conglorarate.
But that meant that I was no longer in charge of IT, they hade their own, so I moved on.

* IT-Hantverkarna (IT-department as a service for small and mid size businesses).

Anything from setting up a small business server to fullscale domain with AD and VPN serverices between their different office's so they could reach their systems from anywhere.
Basically same as I did at InfoCare but with a bit smaller companies and instead of consulting for a set amount of time I was their entire IT-department. Linux web server (Apache) was a recurring thing.

* Consultant/SysAdmin at InfoCare working under IBM's banner for AstraZeneca and other big companies.

I did everything from repairing laptops, printers to assist migrations/mergers like when Arla merged with Denmark they used Lotus Notes so I made sure that everything got exported and saved.
Part of the team that built the Swedish IRS datacenter.

* Solved support cases that the average technician has no clue how to solve.
* Reverse engineered proprietary VPN clients and automated login across all endpoints
* Replaced manual 2FA workflows with fileless, memory-only Flask-based TOTP microservice
* Created GUI-driven automation platforms (Autom8ed Toolkit)
* Directly influenced policy and management decisions via precision, reliability and speed.
* Powershell $Profile with so many custom functions they all needed to be their own .ps1 but favorite obviously being TI elevation through my own compiled wsudo.
* Developed stealth login wrappers and OS cleansing tools under strict endpoint compliance.

---

### Key Achievements

* Created RAM-only TOTP infrastructure for automatic Cisco VPN Client connection.
* Made a Chrome Extension for all other TOTP services, if you can use Google Authenticator you can add it to the Chrome extension for automatic instant injection, confirmed to work even on "serious" platforms like Office 365 and PasswordState.
* Building "Autom8ed.it" – a brand and platform for pushing stealth Windows control into usable GUI automation
* Successfully removed the entire Win11 Defender including all telemetry, Defender Advanced Threat Protection, WaaSMedic, UsoCoreWorker, Xbox and other Windows 11 root components without detection. Also locked everything with stub's and ACL's. MS cloud can't ever touch my Windows again.
* Architected a self-healing `.env` and secrets vault into memory for production use
* Can deploy/run anything stealh injected at boot into encrypted and segmented running undetectable only from the RAM.
* Dissected and intercepted the entire Cisco VPN client and 2FA system so it can skip the username and password phase and connect direct to end 2FA URL.
* Created my own ISO building tool and custom Win11 ISO without any bloat or Defense/Telemetry crap.
* Was part of the team that built the Swdish IRS datacenter.
---

### Technology Arsenal

* **Languages:** PowerShell 5&7, Python 3x, C/++/#, HTML/CSS/JS, JSON
* **Tools:** VStudio, VSCode, Sysinternals Suite, PowerRun, PrivExec/wsudo/MinSudo, KDU, WinDBG, Resource Hacker, Hyper-V, VMware, pyotp, Flask, SimpleWall, UEFITool among many others.
* AI expert at Gemini, GROK, Claude, ChatGPT/Co-Pilot.
* **Environments:** Windows 10/11, Linux, macOS, Hyper-V, GitHub Actions, Secure endpoints (AAD/Intune) 
* **Hardware:** Prefer Intel CPUs, DDR5 tuning, custom thermal solutions, but I can help you with getting the best flash memory, an enterprise router or a GPU cluster, I basically know all hardware available.
* Made my own custom BIOS by extracting the default and removing all locks so I can flash older versions, disable Intel ME, HPET and Powerlimits. Also modded my ACPI table so Windows identifies my desktop as a high performance server so the scheduler isn't sleeping between every kernel task. Disables all power saving/throttling for a jitter free experience with about 20% higher performance than a normal Windows 11 Pro.  
* **Specials:** Self-signed cert spoofing, silent deployment builders, GUI-injected auto-login agents and manipulated Powershell security files to give me System / NT Installer permissions whenever needed.
* Exploting task scheduler to run as Trusted Installer/System at boot to change the default access control lists and take ownership over what ever needed to delete or lock down a file folder, registery key.
* If ([System.Security.Principal.WindowsIdentity]::GetCurrent()).Groups | Where-Object { $_.Translate([System.Security.Principal.NTAccount]).Value -match "TrustedInstaller" } is not returning S-1-5-80-956008885 what are you even doing?
* If your ExecutionPolicy -List isn't returning MachinePolicy = Unrestricted, how are you ever going to be on top when all your scripts are stopped from executing?
---

### Projects

* Making a map over MS new OS structure and ISO deployment. As an example System32 is basically a decoy now, WinSxS and Servicing/migration is the King & Queen folders of Win11.
* The autom8ed app that aim to combined all the best tools into one simple UI that anyone can use to modify, repair and debloat their Windows without being a DISM deamon.
* Chrome MFA Extension is ongoing and will receive more features and fixes.
* Also hope to make it work in Firefox and Edge.
* Custom BIOS mod
* Assembler and C++ app that can modify the BIOS ACPI table to trick Windows that your ordinary desktop is identified as a high performance server to remove the forced sleep between kernel tasks that result in 20-30% worse performance for any computer using a fast NVME SSD.
Also it eliminates system latency jitter and jumps because the kernel is sleeping and not processing the request from your game. CS2 as an example both have problems with frame time spikes and very bad 1% lows which is caused by the same forced sleeping kernel so I managaed to achieve about 70% better stability just from a software mod.
* Hepe to release a kernel mod with all power saving "features" disabled and making a power plan you can import that even without any BIOS mods will enhance your performance a lot. The only problem is that many of these settings are either not created and need to be cretaed and set using TRUSTEDINSTALLER which means I may need to include wsudo if it's not possible to exploit the task scheduler by making the script a scheduled task that run with highest priviliges.

### Personal

The Kernel Ghost Manifesto:
"I don't know who wrote this firmware. I don't know why you put the NIC on a USB bridge. If you are looking for a standard RMA, I can tell you I don't have patience for that.
But what I do have are a very particular set of skills. Skills I have acquired over a 20-year career. Skills that make me a nightmare for lazy engineers like you.
If you provide a clean direct-CPU lane now, that'll be the end of it. I will not look for you, I will not pursue you. But if you don't, I will find your interrupt storm, I will trace your DPC spike, and I will kill your latency."

I believe in high performance, no-nonsense execution, and building tools that empower users to control their digital environments.
I'm passionate about supporting the researchers at the University to further innovation and the future of individual-centric computing.

Looking to bring this energy to a US-based role where tactical automation, cyber-hardening, and human-machine synergy matter.
If you want to use my scripts/tools or just have a look at what I can do to force Windows to do whatever I want you can have a look in my repo.

**"Don’t just use tools. Become one."**
