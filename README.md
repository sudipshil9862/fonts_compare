## Fonts-Compare
[fonts rendering and comparing]
This project is all about comparing different fonts of a particular language with respect to FontWeight, FontSize and FontStyle.
---------------------------------------------------------------------
# The font packages need to be installed:
[install font packages depending upon the languages, you are going to work with]

# In Command Line type this command
```
$ sudo dnf search noto-sans-cjk
[sudo] password for sshil: 
Last metadata expiration check: 1:40:00 ago on Mon 10 Oct 2022 12:04:09 PM CEST.
================================ Name Matched: noto-sans-cjk ================================
google-noto-sans-cjk-hk-fonts.noarch : Traditional Chinese Multilingual Sans OTF font files
                                     : for google-noto-cjk-fonts
google-noto-sans-cjk-jp-fonts.noarch : Japanese Multilingual Sans OTF font files for
                                     : google-noto-cjk-fonts
google-noto-sans-cjk-kr-fonts.noarch : Korean Multilingual Sans OTF font files for
                                     : google-noto-cjk-fonts
google-noto-sans-cjk-sc-fonts.noarch : Simplified Chinese Multilingual Sans OTF font files
                                     : for google-noto-cjk-fonts
google-noto-sans-cjk-tc-fonts.noarch : Traditional Chinese Multilingual Sans OTF font files
                                     : for google-noto-cjk-fonts
google-noto-sans-cjk-ttc-fonts.noarch : Sans OTC font files for google-noto-cjk-fonts

```
# [NOTE]:
- You can either install every font's packages manually or you can directly install 'ttc'
- TTC file can combine the multiple font files into a single bundle

-----------------------------------------------------------------------

# install fonts for other languages
```
sudo dnf install @fonts
```
- This will download fonts for languages like hindi(Devanagari), maratha, gujrati, odia, tamil, telegu,, arabic etc.
- if you are still facing problem with fonts then download individual packages mentioned below
----------------------------------------------------------------------

# install devanagari fonts for hindi
```
sudo dnf install google-noto-sans-devanagari-fonts.noarch
```
```
sudo dnf install google-noto-serif-devanagari-fonts.noarch
```

# install Gujrati fonts
```
sudo dnf install google-noto-sans-gujarati-fonts.noarch
```

# install Japanese fonts
```
sudo dnf install google-noto-sans-cjk-jp-fonts.noarch
```
```
sudo dnf install google-noto-serif-jp-fonts.noarch
```

# install Arabic fonts
```
sudo dnf install google-noto-sans-arabic-fonts.noarch
``` 
