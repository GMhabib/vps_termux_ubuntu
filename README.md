<<<<<<< HEAD
# vps_termux_ubuntu
ini berjalan di termux ubuntu
install mongodb
```
sudo apt install gnupg
```
kemudian copy di bawah ini
```
curl -fsSL https://www.mongodb.org/static/pgp/server-7.0.asc | \
   sudo gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg \
   --dearmor
```
lalu buat repository
```
echo "deb [ arch=amd64,arm64 signed-by=/usr/share/keyrings/mongodb-server-7.0.gpg ] https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/7.0 multiverse" | \
sudo tee /etc/apt/sources.list.d/mongodb-org-7.0.list
```
kemudian kamu update
```
sudo apt update
```
lalu kamu lakukan penginstalannya
```
sudo apt install mongodb-org -y
```
selesai
=======
# vps_termux
vps termux nodejs
cara nya
```
git clone https://github.com/GMhabib/vps_termux.git
```
kemudian pindah direktori
```
cd vps_termux
```
kemudian install
```
npm install
```
kemudian jalankan di termux dengan url https://habib.serveo.net
```
node server.js
```
selesai terima kasih
>>>>>>> b84f547 (vps_termux_ubuntu)
