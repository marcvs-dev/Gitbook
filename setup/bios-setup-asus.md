---
description: How to configure your BIOS correctly
---

# BIOS setup Asus

## Flash BIOS

{% embed url="https://youtu.be/DwJS8-GTgRU" %}

1. Download your BIOS file from the manufacturer's site
2. Go into your BIOS
3. Update it to a newer or to the same version

## Disable TPM

1. Disable TPM in your **BIOS Security Tab (Trusted Computing)**
2. If you have an AMD CPU, also **disable fTPM** or set it to **Discrete**

## Enable Secure Boot

1. Enable Secure Boot in your **BIOS Boot Tab**&#x20;

## Confirm correct settings

1. In windows, search for **msinfo32** and press Enter. Check if the value for **Secure Boot State** is **On**
2. Search for **tpm.msc** and press Enter. It should say **Compatible TPM cannot be found**
