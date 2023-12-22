# kinesisflash
a small script to make flashing your kinesis adv 360 pro easier

when run it will:
- rebuild your firmware
- mount and flash each side (on your signal)
- use the most recently built firmware

optionally:
- accepts a `-d DIRECTORY` flag where `DIRECTORY` is the path to your [Adv360-Pro-ZMK](https://github.com/KinesisCorporation/Adv360-Pro-ZMK) directory, default is `~/.config/kinesis/Adv360-Pro-ZMK`
- accepts `-s` flag if you want to skip rebuilding the firmware and just want to reflash

if anyone uses this, feel free to contribute or leave an issue with questions, comments, requests or whatever
