# catears
makes a cat sound everytime you type 'cat' in the terminal
Inspired by some things Jaron Larnier mentioned in 'you are not a gadget'

# Mac OSX

* you'll need [Textexpander from Smile](https://smilesoftware.com/TextExpander)
* move the file 'cat.wav' to your ~/Library/Sounds folder
* doubleclick 'catears.textexpander' (after installing Textexpander)
* change category settings as displayed in 'example-settings.png' if needed

# Linux 

* depends on autokey

## for Rhel-family (redhat,centos,fedora)
sudo dnf install python-pyaudio python3-pyaudio autokey-gtk
pip install wave --user

## or for debian-family (ubuntu debian mint etc.) 
# not tested!
sudo apt install  python-pyaudio python3-pyaudio autokey-gtk
pip install wave --user


* copy the .json and .py file in one of your favourite autokey data subfolders
> eg. /home/USERNAME/.config/autokey/data/My Phrases
* and the catears2.wav in your music folder
> eg. /home/USERNAME/Music
* and finaly edite the username in autokey (change dddw into your username)

shoud work, and trigger with cat. Tweak to your likings

       cat cat cat cat  cat cat  cat cat  cat cat cat cat cat cat cat cat cat cat  cat  


# Windows

* maybe a autohotkey or winbash one in the future
