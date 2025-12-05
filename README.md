![Alt text for image](https://github.com/misjah/motioneyeOS/blob/main/Screenshot%20from%202025-11-17%2017-18-00.png)
![Alt text for image](https://github.com/misjah/motioneyeOS/blob/main/Screenshot%20from%202025-11-17%2017-18-14.png)

# motioneyeOS
Motioneye video surveillance out of the box for x86 architecture.
Based on lightweight Bodhi linux (ubuntu based). Not an .iso image but .img ready to flash to USB or SSD drive.
Inspired by motioneyeOS made for raspberry pi. The images are clean installations with minimal programs installed, basically just browser, motioneye service and light desktop environment. Minimum drive size should be 16GB.
Based on Bodhi-7.0.0-64, Bodhi 5.1.0-legacy and DietPi_x86-64-trixie which can fit on a 4GB flash drive. Legacy version tested on an old Amilo laptop with celeron M 1.7GHz and 768MB RAM, so you can turn your old machine into a surveillence DVR. User is meye and password is mm.
Extract multipart zip and flash with balena etcher (windows-linux)
Download images here: https://sourceforge.net/projects/motionarch/
To access web ui: http://localhost:8765/ or from a remote computer on the same network: http://ip address of a pc running motioneye:8765/

Projects used:

https://github.com/motioneye-project/motioneye

https://github.com/motioneye-project/motioneyeos

https://www.bodhilinux.com/
