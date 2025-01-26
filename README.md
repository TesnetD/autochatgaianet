Gaianet Farming Throughputs Use Autochat Bot

git clone https://github.com/sipalingnode/autochatgaianet

" cd autochatgaianet "

gaianet stop

gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json

gaianet start

nano autochat.js
Edit dibagian nodeidmu. Kalo udah CTRL+XY Enter

apt-get install npm

npm i

➡️ Install screen, skip step ini kalo dah ada

apt-get install screen

ufw allow ssh
ufw enable

➡️ Running bot use Screen

screen -S gaianet

node autochat.js
