# CentralizedPotatoes

This repository attempts to centralize all of the various Potato exploits. Feel free to open a PR and update the [README](./README.md) if you wish to add another.

The "potato" family of privilege escalation attacks on Windows was started with the introduction of Hot Potato in 2016. These attacks typically exploit authentication mechanisms, credentials, and services with impersonation privileges to elevate from a service account to system level access.

Almost every one of the potatoes target a different component of Windows to take advantage of the 𝑆𝑒𝐼𝑚𝑝𝑒𝑟𝑠𝑜𝑛𝑎𝑡𝑒𝑃𝑟𝑖𝑣𝑖𝑙𝑒𝑔𝑒 or 𝑆𝑒𝐴𝑠𝑠𝑖𝑔𝑛𝑃𝑟𝑖𝑚𝑎𝑟𝑦𝑇𝑜𝑘𝑒𝑛𝑃𝑟𝑖𝑣𝑖𝑙𝑒𝑔𝑒 permissions.

To increase your chances of success in using them, you'll want to start at the newest (9), and work your way back to (1).

Here are all the popular potatoes in chronological order from oldest (1) to newest (9):
1.    [Hot Potato](https://github.com/foxglovesec/Potato) - NTLM relay (HTTP->SMB relay) and NBNS spoofing
2.    [Rotten Potato](https://github.com/foxglovesec/RottenPotato) - Windows Service Accounts
3.    [Juicy Potato](https://github.com/ohpe/juicy-potato) - Windows Service Accounts
4.    [Lonely Potato](https://github.com/NotMedic/lonelypotato) - DCOM (Distributed Component Object Model)
5.    [Rogue Potato](https://github.com/antonioCoco/RoguePotato) - RPC over custom ports
6.    [Sweet Potato](https://github.com/CCob/SweetPotato) - Print Spooler
7.    [Generic Potato](https://github.com/micahvandeusen/GenericPotato) - HTTP and named pipes
8.    [God Potato](https://github.com/BeichenDream/GodPotato) - DCOM (Distributed Component Object Model)
9.    [Local Potato](https://github.com/decoder-it/LocalPotato) - NTLM authentication challenge process


