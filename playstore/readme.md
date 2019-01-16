## HG680-P Play Store via NanoDroid MicroG ##

1. Download paket NanoDroid MicroG dari situs Nanolx [di sini](https://nanolx.org/nanolx/nanodroid), saya pakai versi [NanoDroid-microG-20.5.1.20190115.zip](https://downloads.nanolx.org/NanoDroid/Stable/NanoDroid-microG-20.5.1.20190115.zip)
2. Download [TWRP311.zip](https://www57.zippyshare.com/v/85eCS93k/file.html)
3. Download [microg-framework.jar.zip](https://github.com/awaaas/hg680p/raw/master/playstore/microg-framework.jar.zip)
4. Taruh kedua berkas tersebut di micro SD atau flashdisk, lalu tancapkan ke STB
5. Koneksikan perangkat STB ke PC via ADB: 
`adb connect <alamat ip perangkat>`
6. Lakukan reboot ke mode recovery:  
`adb reboot recovery`
7. Di mode recovery, pilih menu **Apply update from EXT** menggunakan remote control STB  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/01-recovery.jpg)
8. Pilih menggunakan remote control STB **Update from sdcard** jika file ada di micro SD, atau **Update from udisk** jika file ada di flashdisk  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/02-applyfromext.jpg)
9. Pilih menggunakan remote control STB berkas TWRP311.zip, tunggu sampai TWRP selesai dimuat  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/03-twrp311.jpg)  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/04-twrploading.jpg)  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/05-twrploading2.jpg)
10. Di TWRP, masuk ke menu Install menggunakan **mouse**  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/06-twrp.jpg)
11. Pilih paket NanoDroid-microG-20.5.1.20190115.zip, lalu konfirmasi pemasangan  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/07-microginstall.jpg)
12. Kembali menu Install, pilih paket microg-framework.jar.zip, lalu konfirmasi pemasangan  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/07-2-microgframeworkinstall.jpg)
13. Lakukan reboot ke sistem setelah instalasi  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/09-rebootsystem.jpg)
13. Setelah masuk di sistem android, buka menu **My App** (saya contohkan pakai launcher bawaan)  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/10-android.JPG)  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/11-myapp.JPG)
14. Buka aplikasi **MicroG Services Core**  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/12-microglaunch.JPG)
15. Buka menu **Self-Check** menggunakan mouse  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/13-microgsettings.JPG)
16. Klik di bagian **System grants signature spoofing permission**  
![](https://github.com/awaaas/hg680p/raw/master/playstore/screenshots/14-microgselfcheck.JPG)
17. Konfirmasi pemberian izin kepada microG Services Core  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/15-microgspoofpermission.JPG)
18. Halaman Self-Check akan berubah menjadi seperti ini  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/16-microgselfcheck2.JPG)
19. Kembali ke halaman utama, aktifkan **Google device registration**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/17-microggdr.JPG)
20. Kembali ke halaman utama, aktifkan **Google Cloud Messaging**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/18-microggcm.JPG)
21. Kembali ke halaman utama, aktifkan **Google SafetyNet**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/19-microgsafetynet.JPG)
22. Kembali ke halaman utama, masuk ke menu **UnifiedNlp Settings**, lalu aktifkan **Deja Vu Location Service** di bagian **Configure location backends**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/20-micrognlp.JPG)
23. Konfirmasi pemberian izin kepada Deja Vu Location Service  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/21-microgdejavu.JPG)
24. Aktifkan juga **Nominatim** di bagian **Configure address lookup backends**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/22-micrognominatim.JPG)
25. Buka pengaturan STB, lalu buka pengaturan tambahan
26. Buka menu **More Settings** di bagian **Preferensi**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/23-moresettings.JPG)
27. Scroll ke bawah, buka pengaturan **Lokasi**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/24-location.JPG)
28. Ubah mode lokasi ke **Akurasi Tinggi**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/25-locationmode.JPG)
29. Kembali ke halaman utama, pilih menu **Aplikasi**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/26-apps.JPG)
30. Scroll ke bawah, buka **Google Play Store**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/27-playstore.JPG)
31. Buka menu **Izin** Google Play Store  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/28-playstorepermissions.JPG)
32. Buka menu **Izin tambahan**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/29-playstorepermissions2.JPG)
33. Aktifkan izin **Spoof package signature**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/30-playstorespoofsignature.JPG)
34. Reboot STB
35. Buka aplikasi **Google Play Store**  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/31-playstorelaunch.JPG)
36. Tekan tombol **SIGN IN** di pojok kanan bawah  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/32-playstoresignin.JPG)
37. Tunggu sampai halaman sign in muncul  
38. Lakukan sign in seperti biasa  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/33-playstoresigninloading.JPG)
39. Tunggu sampai proses sign in selesai  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/34-playstoresigninloading2.JPG)
40. Play Store sudah bisa dipakai  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/35-playstore.JPG)
41. Contoh pemasangan aplikasi MX Player via Play Store  
![](https://github.com/awaaas/hg680p/blob/master/playstore/screenshots/36-playstoremxplayer.JPG)
