# Login Admin OWASP Juice Shop

Link Resource: https://demo.owasp-juice.shop/#/score-board?categories=Injection&showDisabledChallenges=false

login dengan akun admin

## Solusi

Dicoba dengan menggunakan token komen pada sql yaitu ' pada input email

<img src="../kelas/img/11.png" />

Untuk Login ke akun admin saya coba menggabungkan email untuk masuk ke akun admin untuk melakukan itu kita akan menggunakan SQLi berbasis boolean untuk itu kita akan menggunakan di bawah ini

```sql
' or 1=1 --
```

dengan begitu kita berhasil masuk ke akun admin:

<img src="../kelas//img/12.png" />
