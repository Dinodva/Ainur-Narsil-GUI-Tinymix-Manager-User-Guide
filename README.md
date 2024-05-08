# Ainur-Narsil-GUI-Tinymix-Manager-User-Guide
It is not exactly correct to say that Tinymix Manager is the GUI for Ainur Narsil audio mod, since it does not inerract directly. But as the matter of fact, Ainur Narsil has Tinymix binary built in and try to use some of its functions, as it can be seen from here: https://github.com/Magisk-Modules-Repo/ainur_narsil/blob/master/service.sh More correct would be say that Ainur Narsil removes all audio fx, and Tinymix on top of it allows modify some system audio settings, in such way extending its functionality without lowering audio quality. So we have not only system level audio settings unobstructed, but also can further improve them, which is not possible by any other means. Installing other popular audio mods here is not solution, for it brings us back to from where we have started, to pcm 16 bit format. I have tested many audio players and most of Magisk audio mods with Flingerdamp.apk, and have found that where ever we enable them or equalisers built into media player, the sound becomes encoded into pcm 16bit. That is law. That is why, I use simplest media player, which is one built into Mixplorer.
Qualcomm Audio https://www.qualcomm.com/products/internet-of-things/consumer/audio is integrated into core of the qualcomm processors, but its full potential usually not properly implemented by Android developers and manufacturers due various reasons, such as licensing, personal interests, the safety of equipment (i.e. speakers & headphones), as well as safety of ears (which potentially could cost). That is why, as I have found, for example the HD mode for head phones wasn't activated by default on my Redmi 7, or Hifi sound was not activated by default on my Pixel 3, even after installing Ainur Narsil. On older versions of Android, we could relatively easily edit values of mixer_path.xml, in accordance with our demands, but the newer versions of android made this process much more difficult. And here Tinymix Manager comes to help. With the help of this programm we can change differnt audio setting easily. The most changes would survive till the next rebot, while some tweaks we have to enable while listening music, such as for example 'enable compression of gapless playback on-off'. Also potentially, using the combination of Ainur Narsil+Tinymix, we can change those values permanently. This function is not tested much by me yet, but I will describe how to use it below.   
