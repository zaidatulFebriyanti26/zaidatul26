# Zaidatul febriyanti khairunisa 09010182327004 MI3A
cara menghitung nilai dari throught, Packet loss, Delay, jitter dari wireshark waktu yang digunakan saya saat capturing packet kurang lebih 9 menit
hasil dari pengukuran dari throughput, packet Loss, Delay, dan jitter

PENGUKURAN          	NILAI	          KATEGORI
Throughput		     775 mbps            sedang
Packet Loss		     0,0 %               baik
Delay		           9.821.000 ms        Buruk
Jitter		        17.667.000 ms        Buruk

 hasil perhitungan dengan rumus dari throught, packet loss, Delay, Jitter
 1). throught 
             jumlah yang dikirim/ waktu pengiriman data
             jumlah data =  71458697 / 736.876
             hasil       = 96.975 b x 8
                         = 775 mbps
2). Packet Loss
             ((paket dikirim - paket diterima) : Paket dikirim) x 100)
                        = (75033 - 75016); 75033) x 100
                        = (17 : 75033) x 100
                        = 0,022%

3). Delay :
    total delay        = 736,875,636 s
    rata rata delay    = 9,821.s x 1000
                       = 9,821.000 ms

4). jitter
    total jitter       = -1325611518
    rata rata jitter   = 17667.2822 s x 1000
                       = 17.667.000 ms
                        
PENGUKURAN                  KETERANGAN
                     INDEKS          KATEGORI
Throughput		     775 mbps            sedang
Packet Loss		     0,0 %               baik
Delay		           9.821.000 ms        Buruk
Jitter		        17.667.000 ms        Buruk
RATA RATA INDEKS ; 6.872.193,75 

Kesimpulan
**Kesimpulan:**

Berdasarkan hasil pengukuran menggunakan Wireshark selama 9 menit untuk throughput, packet loss, delay, dan jitter, diperoleh beberapa poin penting:

1. Throughput sebesar 775 Mbps tergolong sedang. Ini berarti kecepatan transfer data yang terjadi cukup memadai, meskipun masih ada ruang untuk perbaikan agar menjadi optimal.
  
2. Packet Loss sebesar 0,022% dikategorikan baik. Hampir tidak ada paket yang hilang selama transmisi, yang menunjukkan kualitas jaringan yang baik dari segi keandalan pengiriman data.

3. Delay dengan nilai 9.821.000 ms tergolong buruk. Waktu tunda atau latency yang sangat tinggi menunjukkan bahwa ada keterlambatan yang signifikan dalam transmisi data. Hal ini bisa mempengaruhi performa jaringan, terutama untuk aplikasi real-time seperti video call atau gaming.

4. Jitter sebesar 17.667.000 ms juga tergolong buru. Variasi waktu antar paket yang besar menandakan ketidakstabilan jaringan, yang dapat menyebabkan gangguan dalam aliran data, terutama dalam komunikasi suara atau video yang memerlukan kestabilan.

Secara keseluruhan, meskipun throughput dan packet loss menunjukkan hasil yang cukup baik, performa jaringan secara keseluruhan tergolong kurang baik karena tingginya nilai delay dan jitter. Hal ini dapat berdampak negatif pada pengalaman pengguna dalam menggunakan layanan yang memerlukan latensi rendah dan stabilitas tinggi.
