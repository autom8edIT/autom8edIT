**Joel Larsson**
Uppsala, Sweden
Email: [ifully@autom8ed.me](mailto:ifully@autom8ed.me)
GitHub: [https://github.com/autom8edIT](https://github.com/autom8edT)
Website: [https://autom8ed.it](https://autom8ed.it)

---

### Executive Summary

The Kernel Ghost Manifesto:
"I don't know who wrote this firmware. I don't know why you put the NIC on a USB bridge. If you are looking for a standard RMA, I can tell you I don't have patience for that.
But what I do have are a very particular set of skills. Skills I have acquired over a 20-year career. Skills that make me a nightmare for lazy engineers like you.
If you provide a clean direct-CPU lane now, that'll be the end of it. I will not look for you, I will not pursue you. But if you don't, I will find your interrupt storm, I will trace your DPC spike, and I will kill your latency."

Highly versatile IT systems engineer and infrastructure tactician with over 20 years of experience in high-performance computing, automation, overclocking, and hardcore system customization.

Known as "The Machine" for focus, output and endurance that exceeds most people.

Combines unmatched technical intuition with raw efficiency, enabling elite performance in system hardening, endpoint control, and automation development.

Open to relocate to the United States to work on forward-thinking infrastructure, cyber defense, and automation projects that empower Western innovation and digital sovereignty.

The US innovates, China replicates and Europe regulates.

Have always wanted to live in the US, the only thing that has kept me in Sweden is my family and friends.

---

### Core Competencies

* RAM-only architecture and stealth automation (TOTP, MFA, token workflows, apps, scripts, you name it, I'll run it)
* PowerShell 5 & 7+ / Python automation (privileged execution, GUI control, secure memory usage, uninstalling, configuring etc.)
* Web code, my MFA extension is made from JS, HTML and CSS.
* Basic C/C++ for using WinDBG, compile and build things from repos that isn't complete.
* Windows internals, bloat removal, hardening, and system security
* Mac / PC Win10/11, Linux Debian / Ubuntu / Kali.
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
Pre 2021 SysAdmin at Mannheimer Swartling (https://www.mannheimerswartling.se)

Consultant/SysAdmin at InfoCare working under IBM's banner for AstraZeneca and other big companies.
I did everything from repairing laptops, printers to assist migrations/mergers like when Arla merged with Denmark they used Lotus Notes so I made sure that everything got exported and saved.
Part of the team that built the Swedish IRS datacenter.

IT-Hantverkarna (IT-department as a service for small and mid size businesses). Anything from setting up a small business server to fullscale domain with AD and VPN serverices between their different office's so they could reach their systems from anywhere.
Basically same as I did at InfoCare but with a bit smaller companies and instead of consulting for a set amount of time I was their entire IT-department. Linux web server (Apache) was a recurring thing.

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
* Making a map over MS new OS structure and ISO deployment. As an example System32 is basically a decoy now, WinSxS and Servicing/migration is the King & Queen folders of Win11.
* If ([System.Security.Principal.WindowsIdentity]::GetCurrent()).Groups | Where-Object { $_.Translate([System.Security.Principal.NTAccount]).Value -match "TrustedInstaller" } is not returning S-1-5-80-956008885 what are you even doing?
* If your ExecutionPolicy -List isn't returning MachinePolicy = Unrestricted, how are you ever going to be on top when all your scripts are stopped from executing?
---

### Personal

I believe in high performance, no-nonsense execution, and building tools that empower users to control their digital environments.
I'm passionate about supporting the researchers at the University to further innovation and the future of individual-centric computing.

Looking to bring this energy to a US-based role where tactical automation, cyber-hardening, and human-machine synergy matter.
If you want to use my scripts/tools or just have a look at what I can do to force Windows to do whatever I want you can have a look in my repo.

**"Don’t just use tools. Become one."**
