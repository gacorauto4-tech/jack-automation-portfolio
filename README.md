# Jack — Automation Portfolio (Selected / Terpilih)
# Portofolio Otomasi — yang sudah dibangun & berjalan

Pembuat otomasi no-code / low-code dengan n8n. Fokus: WhatsApp, Telegram,
Google Sheets, dan AI (Groq, Gemini, OpenAI, Claude). Otodidak.
No-code / low-code automation builder using n8n. Focus: WhatsApp, Telegram,
Google Sheets, AI (Groq, Gemini, OpenAI, Claude). Self-taught.

---

## Fungsi & Tujuan Portfolio Ini / Purpose
Portfolio ini menunjukkan workflow otomasi nyata yang saya bangun: mengubah
proses manual (catat laporan, kirim pesan, rekap keuangan) menjadi alur kerja
otomatis yang jalan sendiri tanpa intervensi tiap hari.
This portfolio shows real automation workflows I built: turning manual processes
(report logging, messaging, finance recap) into self-running workflows.

---

## 4 Proyek Terpilih / Selected Projects

### 1. LAPBULK3 — Sistem Pelaporan HSE Lapangan
**Fungsi:** WhatsApp grup → webhook Fonnte → n8n → parsing AI (Gemini) → Google Sheets.
5 lokasi di Sumatra, balasan auto-konfirmasi. Routing: #LOG #JSA #KEGIATAN #SAFETYTALK.
WhatsApp group → Fonnte webhook → n8n → AI parse (Gemini) → Google Sheets.
5 Sumatra locations, auto-confirmation. Routing: #LOG #JSA #KEGIATAN #SAFETYTALK.

- **Tujuan / Goal:** Catat laporan K3 (keselamatan kerja) dari lapangan secara
  terpusat, tanpa form manual. / Centralize field K3 reports without manual forms.
- **Manfaat / Benefit:** Laporan masuk otomatis ke 1 sheet, bisa dipantau dari mana saja.
  / Reports auto-land in one sheet, monitorable anywhere.
- **Yang diselesaikan / Solved:** Hilangnya laporan, data tersebar, input lambat.
  / Lost reports, scattered data, slow input.
- **Keuntungan bisnis / Business gain:** Audit K3 lebih mudah, risiko kecelakaan
  kecili karena temuan cepat terekam. / Easier K3 audit, lower accident risk.
- Status: dibangun & dijalankan / built & running

### 2. Reminder Harian Facility Management → WhatsApp Grup
**Fungsi:** Pesan K3 harian + berita + infografis, otomatis 1x sehari via Fonnte.
Daily K3 message + news + infographic, auto 1x/day via Fonnte.

- **Tujuan / Goal:** Bangun budaya safety harian lewat pengingat otomatis.
  / Build daily safety culture via auto reminder.
- **Manfaat / Benefit:** Karyawan dapat pesan edukasi tiap pagi tanpa admin kirim manual.
  / Staff get daily edu message without manual admin send.
- **Yang diselesaikan / Solved:** Pengingat sering lupa / tidak konsisten.
  / Forgotten / inconsistent reminders.
- **Keuntungan bisnis / Business gain:** Kesadaran K3 naik, admin hemat waktu.
  / Higher K3 awareness, admin time saved.
- Status: aktif & berjalan / active & running

### 3. COG — Intake Laporan Harian via Telegram
**Fungsi:** Terima laporan harian lewat Telegram → simpan ke Google Sheets.
Receives daily reports via Telegram → stores to Google Sheets.

- **Tujuan / Goal:** Kumpulkan laporan harian tim dari satu kanal chat.
  / Collect team daily reports from one chat channel.
- **Manfaat / Benefit:** Tidak perlu rekap email/WA manual, langsung jadi baris sheet.
  / No manual email/WA recap, goes straight to sheet row.
- **Yang diselesaikan / Solved:** Laporan tercecer di chat, susah ditarik.
  / Reports lost in chat, hard to pull.
- **Keuntungan bisnis / Business gain:** Manajemen dapat ringkasan harian instan.
  / Management gets instant daily summary.
- Status: dibangun & diuji / built & tested

### 4. Cash Flow Daily Dashboard / CASHFLOW V5
**Fungsi:** Dashboard keuangan harian dari Google Sheets: rekap, ringkasan, alert budget.
Daily finance dashboard from Google Sheets: recap, summary, budget alerts.

- **Tujuan / Goal:** Pemilik usaha tahu posisi kas tiap hari tanpa buka buku manual.
  / Owners see daily cash position without manual books.
- **Manfaat / Benefit:** Rekap & alert budget otomatis, error input kecil.
  / Auto recap & budget alerts, low input error.
- **Yang diselesaikan / Solved:** Rekap keuangan lambat & rawan salah ketik.
  / Slow & typo-prone finance recap.
- **Keuntungan bisnis / Business gain:** Keputusan keuangan lebih cepat & akurat.
  / Faster & more accurate finance decisions.
- Status: dibuat & diuji (belum aktif produksi) / built & tested (not yet in production)

---

## Tools / Alat
n8n · WhatsApp (Fonnte) · Telegram · Google Sheets · Groq · Gemini · OpenAI · Claude · OCR · JavaScript Code

## Note / Catatan
Data sensitif (nomor WA, group ID, sheet ID, node ID) sudah di-redaksi menjadi ***
di file JSON agar aman dipublikasikan.
Sensitive data (WA numbers, group IDs, sheet IDs, node IDs) redacted to *** for safe publish.

=================================================================
## REKOMENDASI AGAR PORTFOLIO LEBIH BAGUS & PROFESIONAL
=================================================================
1. Tambah README per-project (1 file tiap workflow) berisi screenshot alur + penjelasan
   singkat. Employer suka lihat "visual", bukan cuma JSON.
2. Buat 1 folder `demo/` berisi video 30 detik alur kerja jalan (loom/mp4) — nilai plus besar.
3. Di LinkedIn, taruh link repo ini di "Featured" + tulis 1 post: "I built X with n8n".
4. Pisahkan repo: 1 repo = 1 project (LAPBULK3 repo sendiri, Cashflow repo sendiri) biar
   lebih rapi & gampang di-share ke klien tertentu.
5. Tambah badge: "Built with n8n", "AI-powered" di README agar terlihat modern.
6. Jangan klaim "Founder/Engineer" kalau bukan — posisi sebagai "Automation Builder"
   lebih kredibel & aman.
7. Update berkala: tiap selesai project baru, commit ke repo. Portfolio hidup = nilai tinggi.
8. English konsisten di judul/section agar employer global paham (sudah dilakukan di sini).
