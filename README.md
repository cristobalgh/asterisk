Configuracion de PBX Nogales

Para instalar:

sudo -i (para irse permanente a sudo)
wget link al .tar buscar en la web
tar -zxvf archivo
entrar a la carpeta descomprimida
contrib/scripts/intall_prereq install
./configure
make menuselect
make && make install
make samples
mover todo de /etc/asterisk a nueva carpeta (saca los samples generados)
make basic-pbx (deja el sistema de Awesome company)
make config (crea startup files)
systemctl enable asterisk
systemctl start asterisk
systemctl status asterisk

