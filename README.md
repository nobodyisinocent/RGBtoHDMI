# RGBtoHDMI
The RGBtoHDMI device adds an HDMI output to your AMIGA only in OCS display mode thanks to the use of a Raspberry Pi0.
The very first RGB2HDMI design has been made by c0pperdragon. It can be found here:

https://github.com/c0pperdragon/Amiga-Digital-Video/

Originally, I made my own version since I wanted the smallest possible pcb for my personnal use, and also for the use of my friend Lolof.
The aim of these designs is to allow the combined use of the RGB2HDMI and others expansions as accelerator boards for example like the big board of the Mega Midget Racer.

Here, you'll find the three lowprofile following versions of the RGBtoHDMI I designed with Kicad:

1- CPLD design for A500/2000 (the last board I designed).

2- Original Design for the CDTV.

3- Original Design for the A500 & A2000.

# Tiny RGB2HDMI CPLD design
Always with the same goal, as small as possible, this board uses the CPLD Rev1.1 design from solarmon. But, since the configuration menu is accessible with one button, the 3 buttons and the OSD connector (no interest for my use) have been removed.

The firmware can be downloaded onto the official Github of the original CPLD version from hoglet67 here:

https://github.com/hoglet67/RGBtoHDMI/releases

To install the firmware, as for the first version of the RGBtoHDMI, simply extract the files to the µ-SD card's root and follow the instruction from Amiga_Readme.txt inside the Amiga_CPLD_Setup directory.

Here some pictures from Lolof of the Tiny CPLD RGBtoHDMI installed onto an A500 with the excellent TK030 from Matze !

![1633015126219_resultat](https://user-images.githubusercontent.com/80821708/135524331-9036771d-9546-4b01-b948-35bdff91a01b.jpg)

![1633015126210_resultat](https://user-images.githubusercontent.com/80821708/135524359-c0f95306-6099-479f-9994-665e182bb074.jpg)

![1633026660919_resultat](https://user-images.githubusercontent.com/80821708/135524387-35aabe34-98bd-4051-b039-a7081cd79ce7.jpg)

![1633026660925_resultat](https://user-images.githubusercontent.com/80821708/135524398-519e852d-e841-4ca8-b396-10a858cff933.jpg)



# Low profile board based on design from c0pperdragon

# CDTV board

Here is the version specially designed for the CDTV.
The goal is always the same,having a nice and small board. :-)

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

And some pictures from Lolof of this second version rgb2hdmi in action onto his A500 !

![IMG_20210423_145139](https://user-images.githubusercontent.com/80821708/132981505-030add7e-4199-458c-a330-fcac5729eac1.jpg)

![IMG_20210423_211447](https://user-images.githubusercontent.com/80821708/132981508-14c5bdd8-64be-44bb-870c-06a4b601cd61.jpg)

![IMG_20210213_005351](https://user-images.githubusercontent.com/80821708/132981515-8da6a3e6-85f4-4889-8c44-c4605345ae53.jpg)

![IMG_20210213_005358](https://user-images.githubusercontent.com/80821708/132981519-db6cba76-727e-43c0-984e-e7bd96fe2b86.jpg)

![IMG_20210213_005457](https://user-images.githubusercontent.com/80821708/132981528-32f65116-420a-4bd4-ae75-6ccdb10f2052.jpg)

![IMG_20210213_005314](https://user-images.githubusercontent.com/80821708/132981533-9b068d35-23b8-4d4f-8aa6-f0ac9f72b23c.jpg)

And the first version onto my A500+ Red edition!

![IMG_20210501_200834_resultat](https://user-images.githubusercontent.com/80821708/132984767-08344267-75b9-4640-849e-3868458e6e78.jpg)

![IMG_20210501_200843_resultat](https://user-images.githubusercontent.com/80821708/132984772-09681e47-98d3-4730-8c78-369d51cbf282.jpg)


I hope you'll enjoy these versions of this great device !

-Tuxbar81
