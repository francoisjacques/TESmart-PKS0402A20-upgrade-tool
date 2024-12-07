# TESmart-PKS0402A20-upgrade-tool
Personal backup for TESmart firmware otherwise not available

## Context

macOS Sequoia is not compatible with the TESMart **_PKS0402A20_** unless you apply this firmware.

## Requirements

According to TESmart, Windows 10 and later. I don't know for previous versions and won't try. Again, this is a personal archive.

## Q&A

- Is there another version?
  - Frankly I don't know. They don't put the updates on the website as this is a power user tool. And people don't flash it on the correct hardware apparently. If there's one, please share. I accept PRs.

- Windows 10 / 11? Really?
  - Yup. It's like, if you had purchased that switch through your local computer dealer, you could bring back the switch, the geek in the back-store would flash it and you'll go back one with a fixed unit. But you purchased it online, they expect everyone is now a geek, runs Windows and provide a poorly written procedure.

- Do I really have to plug it on Port 1?
  - YMMV. I flashed mine with Windows 11 running on a computer connected to port 4 and it worked great.

- Why no VM?
  - Didn't trust the software (you'll understand it when you'll see it - it's UX is... _impressive_) so went bare metal. Didn't want to risk ending up with a brick due to a timing issue. The port 1 requirement was iffy, though.

- Who are you?
  - A professional software developer, such a dad, and an annoyed TESmart customer. I'm glad they fixed it, but come on, a technical memo could have been sent to registered users (Oh wait, it's just for marketing!) If you don't trust the software here, reach out to TESmart.

- How did you upload the binary files to github?
 - My very first commit was to set the gitattributes as paranoia to ensure git won't try any silly manipulations on the files. The upload was through the front-end so git should not have modified the file in anyway. A binary compare revealed an exact match, you should be good.
   
## DISCLAIMER

Anything that happens with the software in this repo is entirely up to you. You are (hopefully) in a free country and likely no one is coercing you to install this software so should _anything_ goes wrong, you have only yourself to blame =P

