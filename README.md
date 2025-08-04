# Learning 
## Chrome Extension Automation in Python

• Python और Selenium की मदद से आप Chrome और उसके एक्सटेंशन्स (जैसे Metamask, Phantom, Sui Wallet) को ऑटोमेट कर सकते हैं 

• लेकिन इसके लिए आपको कुछ खास चीजें सीखनी होंगी और एक्सटेंशन के साथ काम करने के लिए थोड़ी Deep understanding चाहिए

• मैं आपको Chapter-wise Step-by-Step Guide दे रहा हूँ, जिससे आप शुरुआत से लेकर एक्सटेंशन ऑटोमेशन तक सब कुछ सीख सको 

## ✅ Phase 1: Python और Selenium की Strong Foundation
## 📘 Chapter 1: Python Basics
• Python installation (Windows/Linux/Mac)

• Variables, Data types (str, int, list, dict)
 
• Loops (for, while), Conditions (if, else)

• Functions & Modules

 ## ⏱ समय: 2-3 दिन



## 📘 Chapter 2: Selenium Basics
## Selenium क्या है?

ChromeDriver क्या होता है?

WebDriver Setup (Python + Chrome)

Website open करना (driver.get())

Elements find करना (find_element_by...)

Click, Input, Submit Actions

## ⏱ समय: 3-4 दिन




## ✅ Phase 2: Advanced Selenium + Browser Profile + Extension Handling
## 📘 Chapter 3: Chrome Profile और Extension के साथ Selenium
Custom Chrome Profile को Selenium में लोड करना

Existing Chrome Profile से ऑटोमेशन (MetaMask login के लिए जरूरी)

Chrome Extensions को .crx या .zip फ़ाइल से Selenium में लोड करना

## ⏱ समय: 3-4 दिन

## 📌 उदाहरण: Metamask का .crx एक्सटेंशन Selenium में लोड करके account import करना

## 📘 Chapter 4: Multiple Tabs, Windows और Alerts Handle करना
## New Tab Open & Switch

Popup Window / Alert Accept-Dismiss

Browser Back, Forward, Refresh

## ⏱ समय: 1-2 दिन

## ✅ Phase 3: Extension Specific Automation (Metamask, Phantom, Sui etc.)
## 📘 Chapter 5: Metamask Automation (Hard Part)
Metamask Install via Selenium

Seed Phrase Import करना

Password Set करना

Dapp (Website) से Metamask Connect करवाना

Transaction Approve करना

## 📌 यह थोड़ा tricky होता है क्योंकि Metamask एक Shadow DOM इस्तेमाल करता है जिसे पकड़ना कठिन होता है।

## ⏱ समय: 4-5 दिन (practice के अनुसार)

## 📘 Chapter 6: Phantom Wallet, Sui Wallet Automation
Phantom भी Shadow DOM यूज़ करता है

Phantom & Sui को Import करना

Site से Connect & Approve

## ⏱ समय: 2-3 दिन (अगर Metamask समझ गए तो बाकी आसान हैं)


## ✅ Phase 4: Project Level Task Automation
## 📘 Chapter 7: Testnet / Airdrop Tasks Automation
Faucet से Token लेना

Wallet Connect करना (Auto)

DEX पर Swap करना

Twitter/Discord Join Tasks (with Selenium + APIs)

Logs Save करना

## ⏱ समय: 5-7 दिन

✅ Extra Tools जो सीखना फायदेमंद रहेगा:
| Tool                             | Use                                  
| -------------------------------- | ------------------------------------ 
| **Playwright (Python)**          | Selenium से ज्यादा Stable            
| **Undetected\_ChromeDriver**     | अगर site "bot detected" बोले तो      
| **AutoHotKey (Windows)**         | GUI Control के लिए (advance level)   
| **BrowserMob Proxy / mitmproxy** | Network Inspect (Airdrop में useful) 



✅ Conclusion (क्या-क्या सीखना है एक नज़र में):
| Stage | Topic                                        |
| ----- | -------------------------------------------- |
| 1️⃣   | Python Programming (Basic)                   |
| 2️⃣   | Selenium with Chrome Setup                   |
| 3️⃣   | Load Chrome Profile & Extension              |
| 4️⃣   | Metamask / Phantom / Sui Extension Control   |
| 5️⃣   | Real World Task Automation (Testnet / Dapps) |




