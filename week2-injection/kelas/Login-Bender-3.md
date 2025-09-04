# Login Bender OWASP Juiceshop

Link resource: https://demo.owasp-juice.shop/#/score-board?categories=Injection

login pake akun bender

## Solusi

cari email bender, dan somehow pas demo ada yang udah login dan bikin review di salah satu product

<img src="../kelas/img/31.png" />

dari sini kita bisa langsung login menggunakan email bender dan ignore password dengan cara menambahkan karakter escape dan comment query pada akhir input email

kueri:

```sql
bender@juice-sh.op' --
```

<img src="../kelas/img/32.png" />
