
## Getting Started
Siapkan Server dan Jalankan server files LS,
Pastikan MsSQL server jalan, 
Configurasi next.config.js sesuai dengan Data db.


Lalu jalankan : 
```bash
npm run dev
# or
yarn dev
```

Setelah perjalan kita bisa mencobanya di Postman
dengan Method POST
Authorization with Bearer Token "{mainkey}+{encodeKey_server}"
```
http://{host}/api/launcher
```
Lalu pada bagian body
pilih x-www-form-urlencoded
dan isi 
<table>
<tr>
<th>KEY</th>
<th>VALUE</th>
</tr>
<tbody>
<tr>
<td>username</td>
<td>usernameanda</td>
</tr>
<tr>
<td>password</td>
<td>passwordanda</td>
</tr>
</tbody>
</table>


## Client Launcher with C++

Untuk client launcher saya menggunakan bahasa pemrograman c++ berikut repo projectnya [Launcher With C++](https://github.com/rafaelnuansa/client-launcher) .
