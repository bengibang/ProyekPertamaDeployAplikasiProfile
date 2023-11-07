# ProyekDeployAplikasiProfile
Ini adalah repository untuk deploy aplikasi profile menggunakan Google Cloud

Untuk mendeploy aplikasi profile. Kita ada beberapa cara. Saya menggunakan app engine untuk pendeploannya. Karena kita menggunakan html dan css. Maka ini termasuk ke pendeployan web static. Maka kita harus mengiktuti aturan hosting statci website di google App Engine. Silahkan ikuti link berikut [ Aturan Hosting AppEngine ]( https://cloud.google.com/appengine/docs/legacy/standard/python/getting-started/hosting-a-static-website ). Ikuti aturan yang sudah ada dan kemudian jalankan perintah pada cloud shell dan tunggu sampai semuanya selesai
```cmd
gcloud app deploy
```
Kita bisa klin **Navigation Menu** >> **App Engine**. Dan sebelah kanan pojok atas akan ada link dan kita bisa klik linknya untuk melihat apakah website sudah terhosting atau belum.
