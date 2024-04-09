# bing-image-cookie
Fetch Bing Image Cookie to use at npm bing image

## Install Requirement
### Termux (jika tidak support apt)
```bash
pkg update && pkg upgrade
pkg install git -y
pkg install nodejs -y
pkg install npm -y
git clone https://github.com/HabustNyeh/bing-image-cookie
cd bing-image-cookie
npm install
```

### Vps Ubuntu / Termux
```bash
apt update && apt upgrade
apt install git -y
apt install curl -y
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
apt-get install -y nodejs
apt install npm -y
git clone https://github.com/HabustNyeh/bing-image-cookie
cd bing-image-cookie
npm install
```

## Fetch Cookie Bing-Image
```bash
npm start
```

## Note
* `use file ".env" to add default email/password`
* Use cookie at module [bimg](https://github.com/nociza/Bimg) or use `npm install bimg-new`
* put `process.env.BING_IMAGE_COOKIE` in your script

## Media
* [Zennn](mailto:zennn@myzenin.my.id)
* [HabustNyeh](https://github.com/HabustNyeh)
