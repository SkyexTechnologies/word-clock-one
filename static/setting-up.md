---
title: Setting Up
layout: default
nav_order: 3
---

# Setting Up

{: .no_toc }

This page provides a comprehensive guide on setting up your clock after powering it up. You'll learn how to connect to WiFi, use the clock's webpage for customization, and adjust color, brightness, time settings, and more.
{: .fs-6 .fw-300 }

The design of this clock allows it to function independently, eliminating the need for downloading an app or creating an account on unfamiliar platforms. However, to configure the device and access features like obtaining the current time, selecting colors, and making customizations, it is necessary to connect to WiFi. 

# Connecting to the Wifi

To begin the setup process, open your device's WiFi settings and locate the network named `word-clock-one-xxxxxx` (where `xxxxxx` corresponds to the unique ID of your clock). Connect to this network to establish a direct connection between your device and the clock, enabling further configuration.

![Connect to Word Clock](https://skyextechnologies.github.io/word-clock-one/images/wifi-connect-to-word-clock.png)

Once you have connected to the `word-clock-one-xxxxxx` network, a popup should appear, allowing you to enter your WiFi credentials. This step enables the clock to connect to your personal WiFi network. From there, you can provide your WiFi credentials and establish the connection between the clock and your WiFi network.

![Connect to Word Clock to Wifi](https://skyextechnologies.github.io/word-clock-one/images/wifi-connect.png)

{: .warning-title }
If the popup does not appear automatically, you can manually browse to the IP address [192.168.4.1](http://192.168.4.1) in your web browser to access the configuration page.

{: .warning-title }
Make sure to remember the unique ID (`xxxxxx`) of your clock, which is the same as the `word-clock-one-xxxxxx` network name, for the next step in the setup process.

# Webpage
-> word-clock-one.local or ip-address
* -> Make it a link on the website to navigate to "word-clock-one-xxxx.local"
*-> Make sure the screen is large enough, otherwise the sliders will not work as expected. Laptop is ideal.

## Selecting the Color

-> warm white preset; different options for Kelvin Temperatures including colored text.
* Note: Brightness is not controlled with these sliders, its only for setting the color channels.
* Note: When connected to Home Assistant, it is possible to setup the color via "01. Word Clock"

## Brightness Control
-> Automatic control
    Setup Brightness in bright room, on daytime, and select with slider maximum brightness slider the preferred brightness of the led's
    Then dark room, select with slider minimum brightness.
-> Manual Control
    Select the brightness with the slider at 01, this brightness will remain constant.

## Adjust Time
-> Time is set automatically once connected based on the time settings of the router. I.e. time and time-zone. If for some reason, the time is incorrect, you can adjust the minutes and hours with the sliders, which will add the correct number of hours/minutes.

## Customizing
-> Transition; It is possible that when the time changes, to let the words change instantly, or to gradually fade out the old time and fade in the new time. This can be selected with the transition slider. Transition of 0 corresponds with an instant change of the time. Transition of 10 means that it takes 10 seconds to change from the old to new time. In other words, the /time fade-out in 5 seconds and fades-in in 5 seconds as well.
-> It is possible to turn on/off differents parts of the clock. Such as the "it is", minutes and week days indications. This is done via the options 08 Indication: It is, 09 Indication: Minutes and 10 Indication: Week Days respectively. 