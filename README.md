<!-- SHIELDS LINKS -->
<!--GITHUB STARS-->
[stars-shield]: https://img.shields.io/github/stars/Duxi4/Uwuntu-Aisleriot-Cards?style=for-the-badge&logo=Linux&logoColor=C689C6&color=FFABE1
[stars-url]: https://github.com/Duxi4/Uwuntu-Aisleriot-Cards/stargazers

<!--UWUNTUOS.SITE-->
[gotoweb-shield]: https://img.shields.io/badge/UwUntu%20Website-hi?style=for-the-badge&logo=Internet%20Explorer&logoColor=C689C6&color=FFABE1
[gotoweb-url]: https://uwuntuos.site

<!--KO-FI-->
[kofi-shield]: https://img.shields.io/badge/Buy%20us%20a%20cofee-KoFi?style=for-the-badge&logo=KoFi&logoColor=C689C6&color=FFABE1
[kofi-url]: https://ko-fi.com/uwuntu

<!-- Tweet about us-->
[tweet-shield]: https://img.shields.io/badge/Tweet%20about%20us-hi?style=for-the-badge&logo=Twitter&logoColor=C689C6&color=FFABE1
[tweet-url]: https://bit.ly/380p4nL

<!--Discord server -->
[discord-shield]:https://img.shields.io/badge/Join%20our%20discord-hi?style=for-the-badge&logo=Discord&logoColor=C689C6&color=FFABE1
[discord-url]:https://discord.gg/US38bG9n8c

<!-- MAIN REPO -->
[github-uwu]:https://img.shields.io/badge/REPO:-UwUntu-hi?style=for-the-badge&logo=GitHub&logoColor=C689C6&color=FFABE1
[UwUntu-url]:https://github.com/Duxi4/UwUntu

<br />
<br />

HOW TO CREATE THE SVG FILE:
Make sure the modified (or new) vectors are inside of each card (if you place a figure on the 10 of clubs, move the vectors inside the 10 of clubs).

If you use Adobe Illustrator, use File > Export as > svg instead of File > Save as. If you save instead of export, the vectors will move down the card.

################################################################################

HOW TO CREATE THE SVGZ FILE:

Download the aisleriot git (or use the downloaded repository)
https://gitlab.gnome.org/GNOME/aisleriot

add your svg file into the aisleriot-master/cards folder
open aisleriot-master/cards/meson.build and add the svg file (+/- line 29)

go to aisleriot and run meson setup builddir && cd builddir
install all the required dependences and then run:
meson compile

Check the svgz file in aisleriot-master/builddir/cards/yourfile.svgz


To add the cards set to the game, copy the file into /usr/share/aisleriot/cards
If there is not that directory, install the package gnome-cards-data