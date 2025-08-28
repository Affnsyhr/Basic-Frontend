### 📘 Pengantar HTML

Catatan singkat hasil pembelajaran dasar HTML.

---

## 🧩 HTML itu apa?
- Bahasa markup untuk membangun **struktur halaman web**.  
- Ibarat kerangka tubuh sebelum diberi gaya (CSS) dan interaksi (JavaScript).  

---

## 🏗️ Anatomi Elemen
Sebuah elemen HTML terdiri dari:  
- **Tag pembuka** → `<p>`  
- **Konten** → isi/teks  
- **Tag penutup** → `</p>`  

Contoh:
```html
<p>Hello World</p>
````

---

## ⚙️ Atribut

* **Memberi info tambahan pada elemen.**
* **Tidak tampil di halaman web, tapi memengaruhi perilaku elemen.**
* **Bentuk penulisan:** `nama="nilai"`

Contoh:

```html
<img src="logo.png" alt="Logo Website">
```

---

## 📂 Struktur Dasar HTML

Contoh kerangka minimal sebuah halaman HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Judul</title>
  </head>
  <body>
    <h1>Halo Dunia!</h1>
    <p>Ini paragraf pertama saya.</p>
  </body>
</html>
```

---

## 🌳 DOM Tree

Struktur HTML akan membentuk **DOM Tree** (Document Object Model).
Ibarat pohon/silsilah keluarga → setiap elemen punya **induk (parent)** dan bisa punya **anak (child)**.

---

## 📌 Ringkasan

* ✅ HTML menyusun **kerangka web**.
* ✅ Elemen terdiri dari **tag pembuka, konten, tag penutup**.
* ✅ Atribut menambahkan informasi/aturan pada elemen.
* ✅ Semua elemen tersusun dalam struktur **DOM Tree**.
* ⬜ Latihan membuat halaman HTML sederhana.
* ⬜ Eksperimen dengan atribut (`href`, `src`, `alt`, `id`, `class`).


