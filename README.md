# mini-project-2
Tugas mini project ke 2

import pypandoc, os, zipfile, shutil, textwrap

readme = r"""# Mini Project 2 — Asisten Ibadah Haji dan Umroh Berbasis RAG

## 📌 Deskripsi

**Asisten Ibadah Haji dan Umroh** adalah aplikasi chatbot berbasis AI yang dibuat menggunakan **Streamlit**. Aplikasi ini dirancang untuk menjawab pertanyaan seputar ibadah haji dan umroh dengan memanfaatkan dokumen PDF sebagai sumber informasi.

Proyek ini menggunakan konsep **RAG (Retrieval-Augmented Generation)**. Sederhananya, chatbot tidak langsung menjawab pertanyaan, tetapi terlebih dahulu mencari informasi yang relevan dari dokumen yang tersedia, kemudian memberikan informasi tersebut kepada model AI untuk membantu menyusun jawaban.

> **Catatan:** Proyek ini dibuat untuk tujuan pembelajaran. Chatbot bukan pengganti kiai, ustadz dan tidak ditujukan untuk memberikan nasihat personal.

---

## 🎯 Tujuan Proyek

Proyek ini bertujuan untuk mempelajari:

- Cara membuat chatbot menggunakan Streamlit.
- Cara menghubungkan aplikasi dengan model AI.
- Cara menggunakan dokumen PDF sebagai sumber pengetahuan.
- Konsep dasar RAG.
- Cara melakukan pencarian informasi yang relevan dari dokumen.
- Penggunaan vector database untuk menyimpan data yang dapat dicari berdasarkan kemiripan.
- Cara membuat aplikasi AI sederhana yang dapat digunakan melalui antarmuka web.

---

## 🧠 Apa Itu RAG?

**RAG (Retrieval-Augmented Generation)** adalah pendekatan yang menggabungkan pencarian informasi dengan AI generatif.

Alur sederhananya:

```text
Pertanyaan pengguna
        ↓
Mencari informasi yang relevan
        ↓
Mengambil bagian dokumen yang sesuai
        ↓
Memberikan informasi tersebut kepada AI
        ↓
AI menyusun jawaban
        ↓
Jawaban ditampilkan kepada pengguna
