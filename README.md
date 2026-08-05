## Belajar Golang Dasar

**Golang** dibuat di Google menggunakan bahasa pemrograman C, rilis ke public sebagai open source pada tahun 2009. Go-Lang populer sejak digunakan untuk membuat Docker pada tahun 2011 . Saat ini mulai banyak teknologi baru yang dibuat menggunakan bahasa Go-Lang dibanding bahasa C, seperti Kubernetes, Prometheus, CockroachDB, dan lain-lain. Saat ini mulai populer untuk pembuatan Backend API di Microservices

### Kenapa Belajar Golang?

- Bahasa Go-Lang sangat sederhana, tidak butuh waktu lama untuk mempelajarinya
- Go-Lang mendukung baik concurrency programming, dimana saat ini kita hidup di zaman multicore processor
- Go-Lang mendukung garbage collector, sehingga tidak butuh melakukan management memory secara manual seperti di bahasa C
- Salah satu bahasa pemrograman yang sedang naik daun

---

**Cara membuat projek untuk pertama kali :**

> **ilhambonardoo@192 golang-dasar % go mod init golang-dasar**

**Struktur Folder :**

```text
golang-dasar/
├── file .go
├── README.md
├── go.mod
└────────────
```

**Build :**

```text
ilhambonardoo@192 golang-dasar % go build
ilhambonardoo@192 golang-dasar % ./namafile-executable
```

**Menjalankan tanpa build :**

```text
ilhambonardoo@192 golang-dasar % go run helloworld.go
```
