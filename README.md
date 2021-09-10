# RGBtoHDMI
The RGBtoHDMI device adds an HDMI output to your AMIGA only in OCS display mode thanks to the use of a Raspberry Pi0.
The original RGB2HDMI, designed by c0pperdragon can be found here:

https://github.com/c0pperdragon/Amiga-Digital-Video/

# Low profile board based on design from c0pperdragon
Originally, I made my own version since I wanted the smallest possible pcb for my personnal use, and also for the use of a friend.
The aim of these designs is to allow the combined use of the RGB2HDMI and others expansions as accelerator boards for example like the big board of the Mega Midget Racer.
Actually, There is one version specially designed for the CDTV, and various designs for the AMIGA computers.
The goal is always the same,having a nice and small board.

# CDTV board
![image](https://user-images.githubusercontent.com/80821708/132410431-fb2bdf61-70f5-4863-b9c6-cae65485336b.png)

![1622293352562](https://user-images.githubusercontent.com/80821708/132410642-dd25a9fc-f3ce-4397-81d3-e1ae0d64e1fb.jpg)

![IMG_20210501_222826_resultat](https://user-images.githubusercontent.com/80821708/132411526-43023d0d-eaa4-41f6-a8fa-b204dde81fd9.jpg)

![IMG_20210501_224244_resultat](https://user-images.githubusercontent.com/80821708/132411543-d681bf73-5469-496c-a949-94a47b4ae61e.jpg)

![IMG_20210501_225041_resultat](https://user-images.githubusercontent.com/80821708/132411590-94cab32f-e762-4a70-8c78-0f1da8f854bf.jpg)

![IMG_20210501_225333_resultat](https://user-images.githubusercontent.com/80821708/132411599-e366d9e6-0eb8-45a4-b487-9b2f5f358822.jpg)

![IMG_20210501_225625_resultat](https://user-images.githubusercontent.com/80821708/132411629-3db1580f-56d0-429d-8ea7-b17f3332dc45.jpg)

![1615405848653_resultat](https://user-images.githubusercontent.com/80821708/132411637-d0491843-9d2f-4cf6-9086-303502c5d252.jpg)

![1615405848665_resultat](https://user-images.githubusercontent.com/80821708/132411645-ddd7a561-771b-46e4-bd82-97a1b9bce416.jpg)



# AMIGA 500 boards

Two designs versions have been done. Here they are:

First design with Pi0 located between CIA and PAULA:
![V4](https://user-images.githubusercontent.com/80821708/132412268-e0bb7d3b-5a37-4486-aa96-4f820c219baa.png)

Second version, the smallest design version with the Pi0 installed just onto CIA with HDMI output on the back of the AMIGA.
It was special request of my friend Lolof, and perhaps the best one of the two A500 design:
![image](https://user-images.githubusercontent.com/80821708/132412629-29ea0ea0-a922-4344-a19a-af96bae85576.png)


# Tiny RGB2HDMI CPLD design
Always with the same goal, as small as possible, this board uses the CPLD Rev1.1 design from solarmon. But, since the configuration menu is accessible with one button, the 3 buttons, the OSD connector (no interest for my use) and finally, the JTAG port since the CPLD can be programmed directly from the Pi0 were removed.

Please note the sources of this board are not available here since the pcb is under production. The Kicad sources & Gerber will be uploaded when the board will be assembled and tested.

The firmware can be downloaded onto the official Github of the original CPLD version from hoglet67 here:

https://github.com/hoglet67/RGBtoHDMI/releases

To install the firmware, as for the first version of the RGBtoHDMI, simply extract the files to the µ-SD card's root.

![image](https://user-images.githubusercontent.com/80821708/132826561-6fb60b14-e7db-407c-a425-348a76279220.png)

![image](https://user-images.githubusercontent.com/80821708/132827916-c7b55879-f51a-4bb0-92b4-2e005b7a4995.png)


I hope you'll enjoy these versions of this great device !

-Tuxbar81
