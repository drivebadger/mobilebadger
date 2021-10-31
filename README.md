# Overview

[Mobile Badger](https://github.com/drivebadger/mobilebadger/wiki) is a subproject of [Drive Badger](https://github.com/drivebadger/drivebadger), dedicated for stealth data exfiltration from:

1. Mobile devices (all brands and models that connect to the computer using USB, and support either MTP or PTP protocol for transferring data):

- [Android phones, tablets and possibly other devices](https://github.com/drivebadger/mobilebadger/wiki/Tested-systems)
- iOS-based devices (iPhone, iPad)
- Windows Phone 8/10 (Lumia phones)
- Symbian

2. USB Mass Storage devices:

- mobile devices not supporting MTP/PTP
- mobile devices configured as mass storage (older phones, mp3 players etc.)
- external USB drives
- internal drives connected via USB bridge (eg. pulled from computers, where standard Drive Badger cannot be run, because [all USB ports are damaged](https://github.com/drivebadger/drivebadger/wiki/Hardware-problems-(damaged-USB-ports)))
- including [drives encrypted](https://github.com/drivebadger/drivebadger/wiki/Encryption-support) using [Bitlocker](https://github.com/drivebadger/drivebadger/wiki/Encryption-support-(Bitlocker)), [LUKS](https://github.com/drivebadger/drivebadger/wiki/Encryption-support-(LUKS)), [VeraCrypt](https://github.com/drivebadger/drivebadger/wiki/Encryption-support-(VeraCrypt)) or APFS with [Apple FileVault](https://github.com/drivebadger/drivebadger/wiki/Encryption-support-(FileVault)), using the same [exclusions and key configuration repositories](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories), that are used by Drive Badger

Unlike many tools from IT security area, Mobile Badger is not a Proof-of-Concept kind of tool, bringing some groundbreaking techniques. Everything, what it does, can be as well done manually.

The purpose of both Drive Badger and Mobile Badger is to **change the economics of covert data exfiltration attacks - make them more affordable**, by reducing the overall risk of the operation, and also by lowering the entry threshold for the attack operator.

This repository is intentionally empty. Mobile Badger and Drive Badger share the same [code repository](https://github.com/drivebadger/drivebadger), and this one is made only for [separate Wiki](https://github.com/drivebadger/mobilebadger/wiki).


# Further reading

Is Drive Badger for me?

- [Why ever use Drive Badger? This can be done manually, or by ad-hoc script.](https://github.com/drivebadger/drivebadger/wiki/Frequently-Asked-Questions-(beginner))
- [Legal and risk-related questions: when using Drive Badger is legal?](https://github.com/drivebadger/project/wiki/Legal-questions)
- Before you buy anything - recommended hardware for [Drive Badger](https://github.com/drivebadger/drivebadger/wiki/Recommended-hardware) and [Mobile Badger](https://github.com/drivebadger/mobilebadger/wiki/Recommended-hardware)...
- [Installation manual](https://github.com/drivebadger/mobilebadger/wiki/Installing) and [ready to use install script](https://github.com/drivebadger/mobilebadger/wiki/Install-script).
- [How the data storage is organized](https://github.com/drivebadger/mobilebadger/wiki/Data-storage)
- [Event display: what is actually happening with your device?](https://github.com/drivebadger/mobilebadger/wiki/Events-display)

I want to stay current...

- [News](https://github.com/drivebadger/project/wiki/News)
- [Project roadmap](https://github.com/drivebadger/project/wiki/Roadmap)


# Legal information

This software was written and is meant to be **used only by eligible entities**, eg:

- police officers
- special agents
- intelligence officers
- military forces
- private investigators
- corporate red teams
- diplomats or other people with personal immunity

Its usage is always a subject to local legislation, and the user is solely responsible for all potential law infringements
and/or misfeasances of duties.

Intention of this product, is not an incitement for a crime. Rather, Drive Badger is mainly intended to be used in countries, where
using such tools is legal, or at most, can be a subject to possible disciplinary action between the end user and his/her employer.
