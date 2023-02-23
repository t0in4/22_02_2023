После создания виртуальной машины Debian:  
создать пользователя sudo  
в терминале пишем: su -
потом: gedit /etc/sudoers

найти строку: root ALL = (ALL:ALL) ALL
под ней дописать: <имя пользователя> ALL=(ALL:ALL) ALL
сохранить документ.

sudo apt-get install openjdk-11-jdk openjdk-17-jdk  



sudo apt-get install libc6-i386   

			libncurses5   

		libstdc++6-i386-cross   

		lib32z1   

		libbz2-1.0  

		

mkdir ~/Android; tar -xf android-studio-2022.1.1.3-linux.tar.gz -C ~/Android  



sudo apt-get install adb  



cd ~/Android  



wget https://bitbucket.org/iBotPeaches/apktool/downloads/apktool_2.4.1.jar  



wget https://github.com/skylot/jadx/releases/download/v1.4.6/jadx-1.4.6.zip  



wget https://github.com/appium-boneyard/sign/releases/download/1.0/sign-1.0.jar  



wget https://bitbucket.org/JesusFreke/smali/downloads/baksmali-2.4.0.jar  



mkdir jadx && cd jadx  

unzip ../jadx-1.4.6.zip  



cd ~  

gedit .bashrc  



alias apktool='java -jar -/Android/арktool_2.4.1.jar'  

alias jadx-gui='-/Android/jadx/bin/jadx-gui'  

alias baksmali='java -jar -/Android/baksmali-2.4.0.jar'  

alias sign='java -jar -/Android/sign.jar'  

cd ~/Android/android-studio/bin/ && ./studio.sh  

cd ~  

gedit .bashrc  

alias javac='javac -classpath /home/vboxuser/Android/Sdk/platforms/android-33-ext4/android.jar'  

alias dx='/home/vboxuser/Android/Sdk/build-tools/33.0.2/d8'  



