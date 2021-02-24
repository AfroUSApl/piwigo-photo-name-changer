# piwigo-photo-name-changer
Six scripts to change the name for piwigo gallery.

I manage to write 6 bash scripts to make this automatic. I have over 57k, so this will be a pain. 

`apostrophe.sh` will change apostrophe into _ in your specified directory<br>
`apostrophe2.sh` will change it this ~(),ęóńłüßŚ into _ inside two folderd in depth from your specified directory

`characters.sh` will change this ~(),ęóńłüßŚ into _ inside your specified directory<br>
`characters2.sh` will do the same thing but two folders in depth from the main and change it into _

`whitespace.sh` will change all space into _ inside your specified directory<br>
`whitespace2.sh` will do the same thing, but in two folders depth from the main and change space in _

As I have mouniting points in TrueNAS instead of having all photos in Piwigo, I have all photos inside<br>
 /usr/local/www/Piwigo/galleries/my_folder_1<br>
 /usr/local/www/Piwigo/galleries/my_folder_2<br>
 /usr/local/www/Piwigo/galleries/my_folder_3<br>
 /usr/local/www/Piwigo/galleries/my_folder_4

Execute with 
`bash whitespace.sh /my_folder_1`

I dont remember why I split this directory tree into two separate commands, but this must be something with volume of photos.
