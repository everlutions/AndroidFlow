# AndroidFlow

##Alfred Android resource helper workflow

With this workflow you can easily create an image for all your Android resource folders mipmap or drawable hpdi/xhdpi/xxhdpi/xxxhdpi. The only thing you need is a .svg (vector) image file from your designer. 

requirements:
 - Inkscape https://inkscape.org/en/download/mac-os/ (move to Application folder) 
 - XQuartz https://www.xquartz.org/

How to use:
1. Import alfred workflow
2. Enter 'svg' as tag word and type the name of your .svg file
3. Enter the desired width(MDPI)
4. Enter the desired file name (be carefull of Android resource naming convention)
5. Enter the name of your Android Project
6. Celebrate! Because it only took 30 sec's to create an img for each  screen density in the mipmap



- the tag word 'svg' exports to mipmap folder
- the tag 'svgDrawable' exports to drawable folder


