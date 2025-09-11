# Forged Review OWASP Juice Shop

Broken Access Control - Forged Review:
<br>
Post a product review as another user or edit any user's existing review.

Link resource: https://github.com/juice-shop/juice-shop

# Solusi

pertama coba login pada salah satu akun juiceshop yang ada, yang sudah dilakukan sebelumnya pada week2

setelah itu coba lakukan post review product seperti biasanya pada web dan sambil buka dev tool untuk melihat cara api fetching product reviewnya

<img src="./img/12.png" />

dapat dilihat payload berisikan author yang mana seharusnya tidak perlu menginclude payload author karena sudah ada bearer token untuk mengautentikasi user yang mengirim review. Jika payload seperti itu, asumsinya kita bisa mengubah authornya sesuka hati kita walaupun kita tidak terlogin ke akun yang bersangkutan

<img src="./img/11.png" />

dan benar saja, kita berhasil melakukan forged review

<img src="./img/image.png" />
<img src="./img/13.png" />
