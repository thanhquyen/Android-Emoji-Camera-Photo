# Android-Emoji-Camera-Photo
source code for https://play.google.com/store/apps/details?id=betcheg.emojicameramontage

##Description

![Example montage](https://lh3.googleusercontent.com/wrpY0MmvyO18yiL3ScBUHQ9tGJeDnhI4ODPI02WM33u3GPldoNllD4g9UIT6nf9vhm4=h900-rw)

Emoji Camera Photo is an Android application that let the user create montages with emojis and edit photos, with an intuitive drag and drop interface.

The user selects the emoji in the slider menu, resize it and rotate it thanks to 2 SeekBars, and drag it to the position of his choice.

The user can finally save his chef-d-oeuvre in his phone gallery.


## Creating process

The application logic is fairly similar to the one used it my other application "MLG Montage Parody", but this time i had to process with much more images (more than a hundred).

In order to make it, I created a shell script that search for every PNG's in a given repository, and generate a correct source code so I don't have anything more to do ( in  the shellscript/ repository).

It really help during debug developpement, and saved me tons of times (though the generated code is a bit hard to read).

The final source code was then made "github-readable", so that it could be understood by anyone not familiar with the code, so the code generated by the shell script is not 100% the one you'll find in app/... 

In fact, before commiting I deleted all the debug values used in the generated code, and tried to make it mostly english instead of french.

## Special thanks

I'd like to thanks the authors of the following library I used in my app:
- Emoji One : https://github.com/Ranks/emojione
- Simple side drawer : https://github.com/adamrocker/simple-side-drawer
- Android Five Stars : https://github.com/Angtrim/Android-Five-Stars-Library

## Screenshots

![Screen One](https://lh3.googleusercontent.com/V0zXMTuekiIT25de0icatACjkNbssd3ASB71hCeEPDD_3TyerBBt4brOv-ouaFQYm0I=h900-rw)
![Screen Two](https://lh3.googleusercontent.com/yXUGwnWJs2Fj4_O7rjEzXMvs-7tPK1OtcpddwlhzwdEfH-mP8iBl_OIDphFCxJiDhiU=h900-rw)
