---
layout: default
title: Home Assistant
nav_order: 4
---

# Home Assistant

This page serves as a guide to help you connect your clock to Home Assistant. It provides step-by-step instructions and information to facilitate the process of integrating your clock with the Home Assistant platform.
{: .fs-6 .fw-300 }

{: .note }
Please note that connecting your clock to Home Assistant is optional and is recommended only for users who already have a smart home system powered by Home Assistant. 

There are two options available for connecting your clock to Home Assistant: the automatic method and the manual method. The automatic method is suitable for most users and is recommended as the primary approach. However, in the event that the automatic method fails, the manual method can be used as an alternative. Both methods will be explained next in detail to ensure you have a successful connection between your clock and Home Assistant.

# Connecting to Home Assistant (Automatic Method)
For the majority of users, Home Assistant will automatically detect and add the Clock without any additional steps required. This is made possible through ESPHome's mDNS discovery feature.

To add the Clock to Home Assistant, follow these simple steps:

1. Go to the Settings menu in Home Assistant.
2. Select Devices & Services.
3. You should see the Clock, identified as `word-clock-one-xxxxxx` already listed as an automatically discovered device.<br/>![Home Assistant Discovery](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connect-discovery.png)
4. Click on the configure button next to the Clock to add it to Home Assistant.<br/>![Home Assistant Automatic](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connect-automatic.png)
5. Click "Submit" and complete the integration process.<br/>![Home Assistant Connected](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connected.png)

That's it! The Clock is now successfully integrated with Home Assistant, and you can begin utilizing its features and functionalities within your smart home ecosystem.

# Connecting to Home Assistant (Manual Method)
If the Clock is not automatically discovered or your network is not configured for mDNS, you have the option to manually add the Clock to Home Assistant. Follow these steps to manually add the Clock:

1. First, determine the IP address of your Clock by checking your router's web page. You can find the IP address associated with the Clock in your router's device list.<br/>![Clock IP Address](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connect-ip-address.png)
2. Alternatively, you can use a network scanning tool like [Fing](https://www.fing.com/) to discover network devices and find the IP address of the Clock.
3. Once you have the IP address, navigate to Home Assistant and go to Settings > Devices and Services.
4. In the bottom right corner, click on the "Add Integration" button.
5. Search for "ESPHome" and select it to add an ESPHome device.<br/>![Home Assistant ESPHome](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connect-integration.png)
6. Enter the IP address of the Clock in the provided box.<br/>![Home Assistant Network Address](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connect-network-address.png)
7. Click "Submit" and complete the integration process.<br/>![Home Assistant Connected](https://skyextechnologies.github.io/word-clock-one/images/home-assistant-connected.png)

Now, the Clock is successfully connected to Home Assistant. You can begin utilizing its features and control it through the Home Assistant interface.

# Next Steps
Congratulations! The setup process for your Word Clock One is now complete, and you are ready to start automating and customizing it.

If you would like more information about the functionality and purpose of each entity within Home Assistant, you can refer to the [Setup Page](https://skyextechnologies.github.io/word-clock-one/setting-up.html). The entities described on that page correspond to the entities that you will find in your Home Assistant setup. 