Version 18.04.3 LTS
------------------------------------------------------------------------------------------
Install Ubuntu Restricted Extra for media codecs and Flash support:
> sudo apt-get install ubuntu-restricted-extras
 
Install VLC:
> sudo apt install vlc
 
Install Unity-Tweak Tool for Customization:
> sudo apt install unity-tweak-tool

Improve battery life and reduce overheating with TLP
> sudo apt install tlp tlp-rdw
>> sudo tlp start
>>>###### Read More about TLP: https://vitux.com/improving-battery-life-in-ubuntu-with-tlp/

Install Microsoft Fonts
> sudo apt update
>> sudo apt install ttf-mscorefonts-installer
>>> sudo fc-cache -f -v

Install Wine
> sudo apt-add-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ bionic main'
>> sudo apt-get install --install-recommends winehq-stable

Clean Up your Ubuntu Linux System:

////////////////////////////////////////////////////////////////////////
>###### To remove the packages that failed to install completely:
>> sudo apt-get autoclean

>###### To remove the apt-cache:
>> sudo apt-get clean

>###### Remove the unwanted software dependencies:
>> sudo apt-get autoremove

////////////////////////////////////////////////////////////////////////
