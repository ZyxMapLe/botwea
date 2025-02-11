# AriaBotz

<p align="center">
	<img src="https://avatars.githubusercontent.com/u/87540157?s=400&u=05a01466f5a1b687388c88d05f56c9a345be50e1&v=4" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>

Simple WhatsApp Bot

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/iniariaaa/botwea)

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/iniariaaa/botwea
cd botwea
npm install
npm update
```

---------

## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

# Features


|    DOWNLOAD      |  Availability  |
| :--------------: | :------------: |
| Ig Download      |       ✔️       |
| Play Music       |       ✔️       |
| Ig Highlight     |       ✔️       |
| Dll              |       ✔️       |

|       RPG MENU        | Availability |
| :-------------------: | :----------: |
| Adventure             |      ✔️      |
| Mancing               |      ✔️      |
| Berburu               |      ✔️      |
| Shop                  |      ✔️      |
| Pasar                 |      ✔️      |
| Claim                 |      ✔️      |
| Judi                  |      ✔️      |
| Nebang                |      ✔️      |

Masih Banyak Lainnya Gk Ke Tulis.

# Thanks to
* [`Nurutomo`](https://github.com/nurutomo)
* [`Ariffb25`](https://github.com/ariffb25)
* [`Aria Putra Pratama`](https://github.com/iniariaaa)
* [`Zero Bot`](https://github.com/ZeroChanBot)
