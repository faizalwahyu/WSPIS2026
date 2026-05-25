Dirty Fragmentation (Dirty Frag) Privilege Escalation

Dirty Fragmentation atau sering disebut Dirty Frag merupakan kerentanan pada kernel Linux yang dapat dimanfaatkan oleh penyerang untuk melakukan privilege escalation dari user biasa menjadi akses root. Kerentanan ini memanfaatkan kelemahan dalam pengelolaan fragmentasi memori/kernel sehingga memungkinkan proses tertentu memperoleh hak akses lebih tinggi secara tidak sah.

Dalam skenario latihan keamanan siber ini, kerentanan Dirty Frag digunakan sebagai simulasi tahapan post-exploitation, di mana attacker yang telah berhasil memperoleh akses awal ke server mencoba meningkatkan privilege untuk:

mendapatkan akses root,
membuat persistence,
menambahkan user baru,
menjalankan malicious process,
serta mempertahankan akses pada sistem.

Tujuan simulasi ini adalah membantu peserta memahami:

indikator privilege escalation,
analisis log serangan,
deteksi aktivitas abnormal,
serta proses investigasi insiden pada lingkungan Linux server.
