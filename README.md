# Cracked Password Complexity & Reuse Audit Tool

**Python script to audit cracked credentials**—analyzing **password length, complexity, reuse**, and producing **a visual terminal report** with optional **CSV export**.

## What It Does

This tool processes a text file where each line contains a cracked credential entry in the format:

```
Domain\Username:Password:…:(status=Enabled)
```

It then:

### **Performs Security Checks**

* **Password Length Enforcement** — minimum length is configurable (default is 7)
* **AD Complexity Rule Check** — validates presence of:

  * Lowercase character
  * Uppercase character
  * Numeral
  * Special character
* **Empty & Too-Short Password Detection**
* **Complexity Violations Reporting**
* **Password Reuse Detection** — flags and groups reused passwords

### **Features**

*  **Interactive CLI** — prompts for minimum password length input
*  **Active Directory Complexity Checks** — lowercase, uppercase, numeral, special character
*  **Password Reuse Grouping** — sorted by reuse count
*  **Masking** — only first 3 characters of usernames and passwords shown, followed by asterisks
*  **Sorted Output** — enabled accounts are prioritized in output
*  **Enhanced Visuals** — clean box headers with background colors and aligned formatting
*  **CSV Export** — saves detailed audit data for further analysis

---

 **Audit cracked credentials with confidence. Identify weak or reused passwords.**
 **Contributions & feedback are welcome!** 

### Support My Work

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor%20on-GitHub-ff4081?style=for-the-badge\&logo=github)](https://github.com/sponsors/Xalfie)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-orange?style=for-the-badge\&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/xalfie)
