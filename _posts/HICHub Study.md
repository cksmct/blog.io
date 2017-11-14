---
layout: post
title: HICHub Study
date: 2017-11-14
categories: blog
tags: [记录生活的点点滴滴]
description: 流水账
---

1 

[Log] collection log pattern
Phone mode change: radio.log:

adb logcat -v threadtime -b radio | grep -iE 'phonefactory:|> SET_PREFERRED_NETWORK_TYPE|phoneObjectUpdater|EVENT_VOICE_RADIO_TECH_CHANGED|EVENT_REQUEST_VOICE_RADIO_TECH_DONE|aus-test gsm|switchphondeifneeded|oldss|phone_mode|to gsm|to cdma|< voice_reg|SWITCH_PHONE|oldss|switching voice|< SET_PREFERRED_NETWORK_TYPE|EVENT_ALL_NAA_RECORDS_LOADED|setPreferredNetworkType:|isCustomizeCDMARadioTech|not CDMA radioTechnology|UNSOL_VOICE_RADIO_TECH_CHANGED|RIL_REQUEST_VOICE_RADIO_TECH'



