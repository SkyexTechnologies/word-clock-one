---
title: Updating Firmware
layout: default
nav_order: 2
parent: Advanced Features
---

# Updating Firmware

{: .no_toc }

This page provides instructions for updating the clock's firmware to the latest version using Over-the-Air (OTA) functionality.
{: .fs-6 .fw-300 }

{: .warning }
Please note that the firmware on your clock will not require updates. Incorrectly performing the update process or uploading a corrupted file can potentially damage your clock. Repairing a broken clock may require specialized hardware and flashing tools, which can be a complex and risky procedure. Therefore, if you are not confident in your ability to perform the firmware update correctly, it is advisable to refrain from doing so. Proceeding with the firmware update is entirely at your own risk.

The firmware on your clock will not require updates. However, if you encounter connectivity issues with platforms like Home Assistant and wish to switch to the latest firmware, this page provides instructions on how to update the firmware using the Over-the-Air (OTA) functionality. By following the steps outlined on this page, you can easily update your clock's firmware to the latest version and address any connectivity-related issues you may be experiencing.

1. Check the software stability by ensuring the badge shows a passing status. This indicates that the latest firmware is stable.
![Build and Publish ESPHome Firmware and Website](https://github.com/SkyexTechnologies/word-clock-one/actions/workflows/publish.yml/badge.svg)

2. Download the latest firmware file "word-clock-one.bin" using the download button provided below. 
[Download latest firmware](https://skyextechnologies.github.io/word-clock-one/word-clock-one-esp8266/word-clock-one-esp8266.bin){: .btn }

3. Utilize the OTA functionality on the clock's webpage to upload the firmware file downloaded in the previous step.
![Webpage OTA Updates](https://skyextechnologies.github.io/word-clock-one/images/web-server-entities-ota-update.png)

4. Wait for the firmware installation to complete. Once successfully installed, the clock will automatically restart.

<!-- <p class="button-row" align="left">
  <esp-web-install-button manifest="./word-clock-one-manifest.json"></esp-web-install-button>
</p>

<script
  type="module"
  src="https://unpkg.com/esp-web-tools@9.0.3/dist/web/install-button.js?module"
></script> -->