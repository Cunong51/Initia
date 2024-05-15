# Initia
wget https://raw.githubusercontent.com/dante4rt/Ramanode-Guides/main/Initia/start_initia.sh && chmod +x start_initia.sh && ./start_initia.sh
screen -S initia
sudo journalctl -fu initiad -o cat
