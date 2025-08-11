# Mitigation-techniques & **[Segmentation](https://github.com/sherazi1214/Segmentation)**

## Secure Design
**English:**
Secure design means creating systems, applications, or networks in a way that security is built-in from the start, not added later. The goal is to minimize vulnerabilities and protect against attacks.

**Urdu:**
Secure design ka matlab hai ke jab system ya application banai jati hai to shuru se hi security ka khayal rakha jaye, baad me patch lagane ke bajaye. Iska goal vulnerabilities kam karna aur attacks se bachna hota hai.

## Secure Design Configuration Principles

### Least Privilege
**English** Give users/applications the minimum permissions they need to do their job.

**Urdu** User/app ko sirf wohi access do jo unke kaam ke liye zaroori ho.

### Defense in Depth
**English** Use multiple layers of security controls (e.g., firewall + IDS + encryption).
**Urdu** Multiple security layers lagao taki agar ek fail ho jaye to doosra protect kare.

### Fail-Safe Defaults
**English** Systems should default to deny access unless explicitly allowed.

**Urdu** Default setting me access deny ho jab tak explicitly allow na kiya jaye.

### Separation of Duties
**English** Split responsibilities so no one person controls all critical actions.	

**Urdu** Kaam aur access rights ko alag alag logon me divide karo.

### Secure Defaults
**English** Default configurations should be secure (no weak passwords, no open ports).	

**Urdu** Default settings secure hon, kamzori na ho jaise weak passwords ya open ports.

### Keep It Simple (KISS)	Simpler
**English** designs reduce errors and vulnerabilities.	

**Urdu** Simple design rakho taki bugs aur vulnerabilities kam ho.

### Regular Updates & Patch Management
**English** Continuously update systems to fix known vulnerabilities.


## Secure Design Configuration Principles

### Principle	---------------------------English Explanation-----------------------------------	Urdu Explanation

Least Privilege	-------------Grant only the minimum access rights needed.	-----------------Sirf wohi access do jo zaroori hai.

Defense in Depth	--------------Multiple security layers for protection.	-----------------------Har level pe security ka layer lagao.

Fail-Safe Defaults-------------------	Deny by default, allow only when needed.-----------------	Default me deny ho, jab tak explicitly allow na karein.

Separation of Duties --------------	Divide critical tasks between people.	------------------Kaam alag logon me distribute karo.

Secure Defaults---------------	Default configurations must be secure.	------------------------Default settings safe aur secure honi chahiye.

KISS (Keep It Simple)----------------	Simple designs reduce vulnerabilities.-----------------	Simple design rakho, kam flaws honge.

Complete Mediation ----------------	Check every access request every time.	-----------------Har access request ko bar bar verify karo.

Open Design	Security --------------- should rely on secrecy of keys, not secrecy of design.	--------------Design public ho sakta hai, sirf key secret honi chahiye.

Economy of Mechanism	----------------Use the least complex solution possible.	----------------------Simple aur chhoti mechanism rakho, kam bugs.

Least Common Mechanism ---------------	Minimize shared components between users.---------------	Users ke beech shared cheez kam ho, taake leak kam ho.

Secure by Default-------------------	New systems should start in secure mode.	----------------------New system start se secure mode me ho.

Zero Trust Principle	--------------------Never automatically trust any device or user.	-----------------Kisi bhi user/device ko auto trust mat karo.

Regular Patch Management------------------	Update software/hardware to fix vulnerabilities.--------------	Har update aur patch timely install karo.

Monitoring and Logging-------------------	Keep track of system activities and access.----------------	System ki activities log aur monitor karo.

Backup and Recovery	------------Maintain backups for disaster recovery.	Data ka backup rakho taake crash me recover ho.

Configuration Baseline -------------------	Maintain a secure standard configuration template.----------------	Ek secure configuration ka standard template rakho.

Hardening ---------------------	Remove unnecessary services, accounts, and features.	---------------------Extra services aur accounts delete karo jo zaroori na ho.

