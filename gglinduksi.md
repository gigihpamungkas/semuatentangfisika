---
layout: default
title: ggl induksi
parent: Simulasi       # Nama bapaknya
mathjax: true
nav_order: 2
---

# GGL Induksi & Hukum Faraday

Hukum Faraday menyatakan bahwa jika terjadi perubahan fluks magnetik di dalam sebuah kumparan, maka akan timbul Gaya Gerak Listrik (GGL) Induksi pada ujung-ujung kumparan tersebut.

## Simulasi Interaktif
Eksperimen virtual ini memungkinkan Anda untuk menggerakkan magnet di sekitar kumparan dan mengamati arus listrik yang dihasilkan pada Amperemeter.

<iframe src="Asset/simulasi/gglinduksi.html" width="120%" height="600px" frameborder="0"></iframe>

## Konsep Utama
Besarnya GGL induksi yang dihasilkan dipengaruhi oleh beberapa faktor sesuai persamaan:

  \epsilon =-N \frac{\Delta \Phi }{\Delta t}
   \int \frac{a}{2}x+ x^{2}dx

Berikut adalah rumusnya:

\epsilon = -N \frac{\Delta \Phi}{\Delta t}

Di mana \epsilon adalah GGL.

Keterangan:
* **N**: Jumlah lilitan kumparan.
* **\Delta \Phi**: Perubahan fluks magnetik (dalam simulasi dipengaruhi oleh Kuat Medan $B$).
* **\Delta t**: Selang waktu (kecepatan gerakan magnet).

## Instruksi Eksperimen
1.  **Pengaruh Kecepatan:** Gerakkan magnet dengan lambat, lalu bandingkan dengan gerakan cepat. Amati penyimpangan jarum amperemeter.
2.  **Pengaruh Lilitan:** Ubah slider **N** ke nilai maksimal, lalu gerakkan magnet. Apa perbedaannya dengan jumlah lilitan sedikit?
3.  **Pengaruh Medan Magnet:** Ubah nilai **Tesla (B)** dan perhatikan bagaimana hal tersebut memengaruhi arus yang terbaca.


# Uji Coba Rumus Fisika

Ini adalah rumus GGL Induksi dalam satu baris: $\epsilon = -N \frac{\Delta \Phi}{\Delta t}$

Dan ini adalah rumus dalam blok terpisah:

$$\vec{F} = q(\vec{E} + \vec{v} \times \vec{B})$$