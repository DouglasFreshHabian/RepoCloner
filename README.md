![Kali Linux](https://img.shields.io/badge/Tested-Kali%20Linux-153f86?logo=kalilinux&logoColor=blue&colorA=white)
![Parrot OS](https://img.shields.io/badge/Tested-Parrot%20OS-05EEFF?logo=parrot-security&logoColor=green)	
![Debian/Ubuntu](https://img.shields.io/badge/Tested-Debian%2FUbuntu-77216F.svg)
![Raspberry Pi](https://img.shields.io/badge/Tested-Raspberry%20Pi-C51A2B.svg)
![Arch](https://img.shields.io/badge/Tested-Arch%2FManjaro-blue.svg)
![Fedora](https://img.shields.io/badge/Tested-Fedora%2FRedHat-lightblue.svg)

[![asciicast](https://asciinema.org/a/718149.svg)](https://asciinema.org/a/718149)

<h1 align="center">
🌀 GitHub Repo Cloner: Interactive Bash Script
</h1>

This script allows you to interactively browse and selectively clone public repositories from any GitHub user by leveraging the GitHub REST API and jq.

## 📜 Features

 * Validates GitHub usernames by checking their profile URL

 * Fetches up to 100 public repositories using GitHub’s API

 * Prompts you for each repo, letting you choose whether to clone it

 * Uses clean ANSI-colored output for a better terminal experience

 * Written in portable Bash and depends only on jq and curl

 * The Script is capable of fetching every repo under a specific user without prompts 

## 🚀 How to Use
Ensure jq is installed:
```bash
sudo apt install jq
```

Run the script
```
chmod +x repoCloner.sh
./repoCloner.sh
```
>💡 **Tip**:
> Pass `-a` or `--all` to the script to Clone all repositories without prompting (remove the interactive prompt).
---
## 🎮 Modifications To The Script:
You can easily modify this script to:

 * Filter by name, creation date, or stars using additional jq queries

 * Use authentication tokens to access private repos or increase API rate limits

## 📜 License
This script is provided under the MIT License. Use it, tweak it, and share it — just give credit!

## ✍️  Author

| Name:             | Description                                       |
| :---------------- | :------------------------------------------------ |
| Script:           | repoCloner.sh                                     |
| Author:           | Douglas Habian                                    |
| Version:          | 1.1                                               |
| Repo:             | https://github.com/DouglasFreshHabian/RepoCloner  |
---

## 💰 Support RepoCloner™️

Thank you for using and supporting **RepoCloner™**! If this project has helped you, or if you appreciate the work put into it, there are several ways you can support the project.

Your support helps with continued development, testing, and future features. Any contribution is highly appreciated!

## 💖 Ways to Support

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%23FFDD00.svg?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/dfreshZ)
[![Youtube Membership](https://img.shields.io/badge/YouTube-Membership-blue.svg?style=for-the-badge&logo=paypal)](https://www.youtube.com/channel/UC17VZx3ERdQsNvAvXQYjKKw/join)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Me-ff5f5f?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/thefreshlab)
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-lightgrey?style=for-the-badge&logo=github)](https://github.com/sponsors/DouglasFreshHabian)

## 🛍  Fresh Forensics Store (Shopify)
Check out my Shopify 🛒 Store for creative artwork, custom Linux tools, and open-source solutions! 
[Fresh Forensics Store](https://t10fpe-zh.myshopify.com)

## 🛒 Amazon Affiliate Links
Purchase any products through Amazon by clicking on my affiliate links and I get a small percentage!
[Full List of Affiliate Links](https://github.com/DouglasFreshHabian/REPOSITORY/PRODUCTS.md)

---

### If you have not done so already, please head over to the channel and hit that subscribe button to show some support. Thank you!!!

## 👍 [Stay Fresh](https://www.youtube.com/@DouglasHabian-tq5ck) 

<!-- Reach out to me if you are interested in collaboration or want to contract with me for any of the following:
	Building Github Pages
	Creating Youtube Videos
	Editing Youtube Videos
	Youtube Thumbnail Creation
	Anything Pertaining to Linux! -->

<!-- 
 _____              _       _____                        _          
|  ___| __ ___  ___| |__   |  ___|__  _ __ ___ _ __  ___(_) ___ ___ 
| |_ | '__/ _ \/ __| '_ \  | |_ / _ \| '__/ _ \ '_ \/ __| |/ __/ __|
|  _|| | |  __/\__ \ | | | |  _| (_) | | |  __/ | | \__ \ | (__\__ \
|_|  |_|  \___||___/_| |_| |_|  \___/|_|  \___|_| |_|___/_|\___|___/
        dfresh@tutanota.com Fresh Forensics, LLC 2025 -->
