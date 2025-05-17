
sudo apt install bluez -y
sudo apt install pulseaudio -y
sudo apt install pulseaudio-utils -y
sudo apt install pulseaudio-module-bluetooth -y
pulseaudio --start

git clone https://github.com/blackhatvenomm/Venbluez.git
cd Venbluez
python3 venbluez.py
