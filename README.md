<p align="center">
  <img src="https://www.mookto.com/mookto.png" alt="Mookto Technologies Logo" width="150">
</p>

<h1 align="center">Mookto Technologies Activation Center</h1>

<p align="center">
  <em>Internal enterprise utility for Mookto Technologies staff workstation provisioning.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Access-Staff%20Only-red?style=for-the-badge&logo=shield" alt="Restricted Access">
  <img src="https://img.shields.io/badge/License-Bulk%20Volume%20Licensing-success?style=for-the-badge&logo=microsoft" alt="Volume Licensing">
  <img src="https://img.shields.io/badge/Version-v3.12%20Enterprise-blue?style=for-the-badge" alt="Version">
</p>

<p align="center">
  <kbd>&nbsp; <a href="#english">🇬🇧 English Version</a> &nbsp;</kbd> &nbsp;&nbsp;|&nbsp;&nbsp; <kbd>&nbsp; <a href="#bangla">🇧🇩 বাংলা সংস্করণ (Bangla)</a> &nbsp;</kbd>
</p>

<hr>

> [!WARNING]
> **RESTRICTED INTERNAL USE ONLY**  
> This script and documentation are strictly for **Mookto Technologies** office and global online staff usage. We use our own bulk license to facilitate one-click activation across full company hardware. If you are not a staff member of our company, do not use this.  
> 🌐 **Company Website:** [https://mookto.com/](https://mookto.com/)

<br>

<a id="english"></a>
## 🇬🇧 English Version

### 🚀 How to Activate Windows / Office / Extended Security Updates (ESU)?

Choose one of the officially supported enterprise deployment methods below:

| Method | Instructions | Priority |
| :--- | :--- | :---: |
| **Method 1**<br>*(PowerShell)* | **1.** Open the **Start Menu**, type `PowerShell`, and open it.<br>**2.** Copy and paste the command below and press **Enter**:<br><br><code>irm https://get.activated.win \| iex</code><br><br>**3.** In the menu that appears, type the number corresponding to one of the **Green** options. | ⭐ **Recommended** |
| **Method 1B**<br>*(DNS / ISP Bypass)* | **1.** If Method 1 is blocked by your ISP/DNS, run this command (Requires Windows 10/11):<br><br><code>iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win \| Out-String)</code><br><br>**2.** Select your required **Green** activation option. | 🛡️ *Fallback* |
| **Method 2**<br>*(Traditional File)* | **1.** Download the script package: [**MAS_AIO.cmd**](https://get.activated.win) or [**MAS_AIO.zip**](https://get.activated.win)<br>**2.** Right-click `MAS_AIO.cmd` and select **Run as Administrator**.<br>**3.** Select the **Green** option from the interactive menu. | 📁 *Offline* |

<br>

> [!TIP]
> 💡 **Troubleshooting & Network Configuration:**
> - Some ISPs/DNS providers block access to activation domains. You can bypass this by enabling [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser.
> - **Having trouble?** Contact internal IT support via [https://mookto.com/](https://mookto.com/).

> [!NOTE]
> - The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it.
> - Always double-check the URL before executing the command and verify the source is trustworthy.

<br>

<div align="center">
  <i>© 2026 Mookto Technologies. All rights reserved.</i><br>
  <a href="#english">⬆ Back to Top</a>
</div>

<br><br><br>

<hr>

<a id="bangla"></a>
## 🇧🇩 বাংলা সংস্করণ (Bangla Version)

### 🚀 কীভাবে উইন্ডোজ / অফিস / ইএসইউ (ESU) অ্যাক্টিভ করবেন?

নিচের যেকোনো একটি অফিশিয়াল পদ্ধতি নির্বাচন করুন:

| পদ্ধতি | নির্দেশনা | অগ্রাধিকার |
| :--- | :--- | :---: |
| **পদ্ধতি ১**<br>*(PowerShell)* | **১.** **Start Menu**-তে ক্লিক করুন, `PowerShell` লিখে এটি ওপেন করুন।<br>**২.** নিচের কোডটি কপি করে পেস্ট করুন এবং **Enter** চাপুন:<br><br><code>irm https://get.activated.win \| iex</code><br><br>**৩.** যে মেনুটি আসবে, সেখানে **সবুজ (Green)** অপশনগুলোর পাশের নম্বরটি টাইপ করুন। | ⭐ **সুপারিশকৃত** |
| **পদ্ধতি ১বি**<br>*(DNS Bypass)* | **১.** আইএসপি (ISP) বা ডিএনএস দ্বারা ব্লকেড থাকলে এই বিকল্প কমান্ডটি ব্যবহার করুন (উইন্ডোজ ১০ বা ১১ প্রয়োজন):<br><br><code>iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win \| Out-String)</code><br><br>**২.** মেনু থেকে **সবুজ (Green)** অপশন নির্বাচন করুন। | 🛡️ *বিকল্প (Fallback)* |
| **পদ্ধতি ২**<br>*(অফলাইন ফাইল)* | **১.** স্ক্রিপ্ট ডাউনলোড করুন: [**MAS_AIO.cmd**](https://get.activated.win) অথবা [**MAS_AIO.zip**](https://get.activated.win)<br>**২.** `MAS_AIO.cmd` ফাইলে রাইট-ক্লিক করে **Run as Administrator** নির্বাচন করুন।<br>**৩.** মেনু থেকে **সবুজ (Green)** নম্বরটি চেপে অ্যাক্টিভেট করুন। | 📁 *অফলাইন* |

<br>

> [!TIP]
> 💡 **সমস্যা সমাধান (Troubleshooting):**
> - কিছু আইএসপি (ISP) বা ডিএনএস সার্ভিস ডোমেন ব্লক করে থাকে। ব্রাউজারে [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) সক্রিয় করে এটি বাইপাস করতে পারেন।
> - **কোনো সমস্যা হচ্ছে?** অভ্যন্তরীণ সহায়তার জন্য অফিশিয়াল ওয়েবসাইটে যোগাযোগ করুন: [https://mookto.com/](https://mookto.com/)।

> [!NOTE]
> - পাওয়ারশেলে `irm` কমান্ড স্ক্রিপ্ট ডাউনলোড করে এবং `iex` সেটি মেমরিতে এক্সিকিউট করে।
> - কমান্ড চালানোর আগে ডোমেন ইউআরএল (URL) ঠিক আছে কিনা তা সবসময় যাচাই করে নিন।

<br>

<div align="center">
  <i>© ২০২৬ মুক্ত টেকনোলজিস। সর্বস্বত্ব সংরক্ষিত।</i><br>
  <a href="#bangla">⬆ উপরে যান</a>
</div>
