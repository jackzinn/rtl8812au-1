PARA INSTALAR O DRIVER DO ADAPTADOR TP-LINK AC600 V3 DOS EU NO UBUNTU 18 COM KERNEL 5+
EXECUTE APENAS ESTES COMANDOS


sudo apt install git dkms build-essential




git clone https://github.com/jeremyb31/rtl8812au-1.git






cd rtl8812au-1






sudo ./dkms-install.sh
