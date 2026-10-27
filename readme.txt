====================================

jika ip terindikasi dengan port selain 443 dan 80,

maka pada bagian path: /id1 atau /my1, kita ganti dengan ip=port.

misal 
ip: 47.250.81.46 
port: 2087

pada bagian jalur websocket (path):
jadi seperti ini.
/47.250.81.46=2087

====================================
id3
36.95.152.58=12137

id4
172.232.249.224=2053

my2
47.250.81.46=2087

au1
170.64.152.77=7443

au2
152.67.101.72=23010

au3
192.9.190.80=23862
====================================
jika ada proxy yang mati, bisa diubah di exclave, darktunnel, v2rayng, httpcustom apk dsb, pada path, seperti contoh di atas.

kalau merubah proxy di githup ini, terlalu lama, harus deploy ulang juga, ke cloudflare.
====================================

If the IP uses a port other than 443 or 80,

replace the path section (e.g., `/id1` or `/my1`) with `ip=port`.

For example:
IP: 47.250.81.46
Port: 2087

In the WebSocket path section:
it becomes this:
/47.250.81.46=2087

====================================

file yang ada di github hanya 3 file:

_worker.js
package.json
wrangler.toml

lalu kita login ke cloudflare, worker&page, add create aplication, deploy with github, done, visit site, copy vless config.

tempel/paste ke exclave.apk, httpcustom.apk, darktunnel.apk, httpinjector.apk, v2ray.apk, dll.
====================================

There are only 3 files on GitHub:

_worker.js
package.json
wrangler.toml

then we log in to cloudflare, worker&page, add create application, deploy with github, done, visit site, copy vless config.

====================================

ubah / change / ganti di wrangler.toml , bagian name =  "simple-vless"

ganti sesuai dengan nama repository milik anda.

====================================
