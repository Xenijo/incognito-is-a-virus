# incognito is a virus

# 1.Overview:
Welcome to my investigation into the free Roblox exploit known as Incognito. 
This provides an overview of my findings and the evidence I've gathered.

### File used for the analyze : test.exe
Proof that test.exe is a file from Incognito
![Alt text](https://cdn.discordapp.com/attachments/1228376524407701665/1238949420184109167/image.png?ex=6641cdd0&is=66407c50&hm=0f75155c90474b9b364e551b26a9378d83fad64afa1d327f731d0c9fc540f7ea&)

# 2.Url scan
[File](https://raw.githubusercontent.com/Xenijo/incognito-is-a-virus/main/Proof/Urlscan)

When examining the Urlscan file, it reveals various URLs, with the most prevalent being the last one:
[Monero Wallet Address]
4485a5b21dfc4761beb1afa4851e88278626d95642923378eb5e3f8ec12d37d5fcd61422cfb853b8a514b26cae95266
Why should they add a Monero wallet address to the executor? Also, in the URLs, you can find different links to coding help websites like Stack Overflow.

# 3.File Analyze
[File](https://raw.githubusercontent.com/Xenijo/incognito-is-a-virus/main/Proof/Analyze)
At the start, you can observe different sockets connecting and listening/sending. Additionally, it pings. It seems like it gets information such as:

100% Sure: IPAddress, ComputerName
50% Sure (Not done with my decompiling investigation yet): get_Version, get_Platform
They also employ ntohs and htons, which is somewhat unusual.
