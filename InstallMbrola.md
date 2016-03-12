# Introduction #

Gespeaker can use mbrola to play text with a more realistic speech. Just to install
  * mbrola package
  * one or more mbrola language packages

## Requirements for Ubuntu users ##

Until Ubuntu packagers will not include mbrola in the official repositories the Ubuntu users will need to install mbrola and the voices from the Ubuntu Trucchi repository in this way:

```
sudo wget -O /etc/apt/sources.list.d/ubuntutrucchi.list http://www.ubuntutrucchi.it/repository/ubuntutrucchi.list

wget -O - http://www.ubuntutrucchi.it/repository/ubuntutrucchi.asc | sudo apt-key add -

sudo apt-get update
```

## Install mbrola support (for both Ubuntu and Debian users) ##

First need to install the mbrola package from the repository with:
```
sudo apt-get install mbrola
```

Then one or more voice packages must be installed from the following table:

| **Description**                | **Package name** |
|:-------------------------------|:-----------------|
| Afrikaans male                 | mbrola-af1       |
| Brazilian Portuguese male      | mbrola-br3       |
| Croatian male                  | mbrola-cr1       |
| Czech male                     | mbrola-cz2       |
| German male                    | mbrola-de6       |
| German female                  | mbrola-de7       |
| British English male           | mbrola-en1       |
| Spanish male                   | mbrola-es1       |
| French female                  | mbrola-fr4       |
| Greek male                     | mbrola-gr2       |
| Hungarian male                 | mbrola-hu1       |
| Indonesian male                | mbrola-id1       |
| Italian male                   | mbrola-it3       |
| Italian female                 | mbrola-it4       |
| Latin male                     | mbrola-la1       |
| Dutch male                     | mbrola-nl2       |
| Polish female                  | mbrola-pl1       |
| European Portuguese female     | mbrola-pt1       |
| Romanian male                  | mbrola-ro1       |
| Swedish male                   | mbrola-sw1       |
| Swedish female                 | mbrola-sw2       |
| American English female        | mbrola-us1       |
| American English male          | mbrola-us2       |

Install a package language with:
```
sudo apt-get install mbrola-us2
```
This will install the American English male voice for mbrola.

## Check if mbrola voices are detected ##

Start Gespeaker and open **Preferences** dialog from **Edit** menu, then move to the **Mbrola voices** tab and check if **Main program mbrola** was detected and the same for the installed voice packages. Change voices path if needed, default voices install path is _/usr/share/mbrola/voices/_.

![http://www.muflone.com/projects/gespeaker/current/en/mbrola.png](http://www.muflone.com/projects/gespeaker/current/en/mbrola.png)