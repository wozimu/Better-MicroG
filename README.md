# ENGLISH
# Google Contacts and Calendar Sync adapters for use with MicroG

This is a Magisk module that contains the required files to be able to sync your Google Contacts and Calendar to your device.

For use with MicroG. WARNING: Compatible only with arm64/64-bit devices running Android 12!

# Versions

Taken from [APKMirror](https://www.apkmirror.com/apk/google-inc/).

- Google Calendar Sync (`com.google.android.syncadapters.calendar`): Version 2024.14.0-622676295-release
- Google Contacts Sync (`com.google.android.syncapadaters.contacts`): Version 12-8361351

# How to
## Step 1
Download this git repo, and zip the folders. You cannot download this repo as zip and flash that zip because then the folder structure is incorrect. The zip contents must look like this:
```
ZIP
---> META-INF
---> system
---> module.prop
---> readme.md
```

If you download this repo as zip from GitHub it will be as follows (incorrect and Magisk/KSU(N) will throw an error):
```
ZIP
---> Magisk-Play-Store-Patched-MicroG-master
     ---> META-INF
     ---> system
     ---> module.prop
     ---> README.md
```

## Step 2
When you have the zip, copy it to your phone, and in Magisk Manager/KSU(N) Manager go to Modules -> tap on the + symbol and select the zip.

## Step 3
Reboot your device, and you should have the sync adapters.

## Step 4
Go to settings -> apps -> menu -> Show system

Find Google Calendar Sync and Google Contacts sync, for both, grant the permissions they want. Also enable networking permission (Mobile data & Wi-Fi -> Allow network access).

Reboot your device again. After this you should see the option to sync contacts and calendar when you go to settings -> accounts -> the Google account you added using MicroG.

# INDONESIA
# Google Contacts dan Calendar Sync adapters untuk digunakan dengan MicroG

Ini adalah modul Magisk/KSU(N) yang berisi file yang diperlukan untuk dapat menyinkronkan Kontak dan Kalender Google Anda ke perangkat Anda.

Untuk digunakan dengan MicroG. PERINGATAN: Hanya kompatibel dengan perangkat arm64/64-bit yang menjalankan Android 12!

# Versi Aplikasi
Diambil dari [APKMirror](https://www.apkmirror.com/apk/google-inc/).

Google Calendar Sync (com.google.android.syncadapters.calendar): Versi 2024.14.0-622676295-release
Google Contacts Sync (com.google.android.syncapadaters.contacts): Versi 12-8361351

# Cara Penginstallan
# Langkah 1
Unduh repositori git ini, dan zip foldernya. Anda tidak dapat mengunduh repositori ini sebagai zip dan meng-flash zip tersebut karena struktur foldernya akan salah. Konten zip harus terlihat seperti ini:
```
ZIP
---> META-INF
---> system
---> module.prop
---> readme.md
```

Jika Anda mengunduh repositori ini sebagai zip dari GitHub, itu akan terlihat seperti berikut (salah dan Magisk/KSU(N) akan mengeluarkan kesalahan):
```
ZIP
---> Magisk-Play-Store-Patched-MicroG-master
     ---> META-INF
     ---> system
     ---> module.prop
     ---> README.md
```

# Langkah 2
Setelah Anda memiliki zip, salin ke ponsel Anda, dan di Magisk Manager/KSU(N) Manager pergi ke Modules -> ketuk simbol + atau Tombol Tambahkan Module dan pilih zip tersebut.

# Langkah 3
Reboot perangkat Anda, dan Anda seharusnya memiliki Adapter Sinkronisasi.

# Langkah 4
Pergi ke pengaturan -> aplikasi -> menu -> tampilkan sistem

Temukan Google Calendar Sync dan Google Contacts sync, untuk keduanya, berikan izin yang mereka inginkan. Juga aktifkan izin jaringan (Data seluler & Wi-Fi -> Izinkan akses jaringan).

Reboot perangkat Anda lagi. Setelah ini, Anda seharusnya melihat opsi untuk menyinkronkan kontak dan kalender ketika Anda pergi ke pengaturan -> akun -> akun Google yang Anda tambahkan menggunakan MicroG.