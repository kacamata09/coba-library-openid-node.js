# coba-library-openid-node.js

Nyoba buat openid / oauth2 provider sekaligus openid clientnya. Code ini diambil dari tutorial https://medium.com/@nitesh_17214

aku sudah modifikasi di atas sedikit untuk penggunaan belajar, jadi kunjungi untuk penjelasan lebih lanjut nya https://medium.com/@nitesh_17214

untuk cara penggunaan nya, 
1. Kalian pertama harus run server dari si oidc provider, agar oidc client saat di run tidak mengalami error
2. Run server oidc client nya, 
3. Kalian kunjungi http://localhost:8080/ yang dimana si server oidc client ini berjalan


untuk tutorial nya kalian bisa liat di bawah ini:
- cara membuat openid atau oidc(openid connect) provider =>
  https://medium.com/@nitesh_17214/oauth-2-0-authorization-server-using-nodejs-and-expressjs-cf65860fed1e
  untuk web npm nya : https://www.npmjs.com/package/oidc-provider
  
- cara membuat web yang suppport login openid atau disebut oidc client =>
  https://medium.com/@nitesh_17214/how-to-create-oidc-client-in-nodejs-b8ea779e0c64
  untuk web npm nya : https://www.npmjs.com/package/oidc-client

untuk dokumentasi dari pakcage atau library nya bisa di liat di github nya:
- oidc-provider = https://github.com/panva/node-oidc-provider/blob/main/docs/README.md
- oidc-client = https://github.com/panva/node-openid-client
