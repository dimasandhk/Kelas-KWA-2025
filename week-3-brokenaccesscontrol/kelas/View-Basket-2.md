# View Basket OWASP Juice Shop

Broken Access Control - View Basket:<br>
View another user's shopping basket.

Link resource: https://github.com/juice-shop/juice-shop

# Solusi

Pertama2 kita coba lihat basket kita secara normal

<img src="./img/21.png" />

dapat dilihat pada endpointnya terdapat path parameter pada endpoint basket, disitu terlihat angka 2. Dengan begitu kita asumsi bahwa identifier tersebut dapat diganti

<img src="./img/22.png" />

dan benar saja, ternyata identifier `2` itu adalah basketId Jim. Dengan begitu kita bisa langsung coba saja pada postman untuk get endpoint tersebut dengan identifier yang lain tetapi menggunakan bearer tokennya jim

<img src="./img/23.png" />

dan benar saja, kita bisa melihat basket / card user lain

<img src="./img/24.png" />
