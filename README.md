# Abusive-Language-Detection-on-Indonesian-Online-News-Comments

## Abstract
Abusive language is an expression used by a person with insulting delivery of any person’s aspect. In the modern era, the use of harsh words is often found on the internet, one of them is in the comment section of online news articles which contains harassment, insult, or a curse. An abusive language detection system is important to prevent the negative effect of such comments. Detecting abusive language in the online comment section is a challenge since abusive languages can be expressed in various words. Moreover, only a few studies have been conducted in Indonesian language. In this paper, we present an Indonesian abusive language detection system by tackling this problem as a classification task and solving it using the following classifiers: Naive Bayes, SVM, and KNN. We also performed feature selection procedure based on Mutual Information value between words. The experimental results show that SVM is the best classifier for detecting the abusive language in news comment with an accuracy score of 90,19% and the use of Mutual Information able to improve the classification accuracy by 1.63%. Mutual Information can increase the accuracy performance of the classifier.

My Research Paper: https://ieeexplore.ieee.org/document/9034620

This dataset consists of comments that are in some of the top news stories in 2019. comments obtained from the kompas, kaskus, and detik.

The following are the headline headlines taken:
- Sandi Butuh Rp 9,9 T untuk 'Rebut' Indosat dari Investor Qatar
- Fadli Zon Dicurhati Tol Mahal, Ini Tarif Trans Jawa & Sumatera
- Menuai Protes, Pemprov DKI Batalkan Kegiatan yang Undang Muslimah HTI
- KPU Sindir Kubu Prabowo: TIM IT Mereka Terlalu Pintar
- Kasus Ujaran Idiot, Ahmad Dhani Divonis 1 Tahun Penjara
- Demokrat: SBY Minta Prabowo Sebut Kebaikan Ani, Bukan soal Politik
- Penyesalan Luna Maya Posting Cuplikan Film Aladdin, Ini Jadi Pelajaran
- Masih Ingat Operator Esia? Begini Nasibnya Sekarang
- Jika Revisi UU KPK Disahkan, UII Siap Ajukan Mosi Tak Percaya ke Jokowi
- Orang Tua Anak Peserta Audisi PB Djarum: KPAI Survei Ke Anak Yang Mana??
- Penayangan Big Movie Family The Spongebob Squarepants Movie di GTV 
- #bubarkanKPAI Trending di Twitter, KPAI Angkat Bicara
- Jokowi Setuju Penyadapan KPK Melalui Izin Dewan Pengawas
- Menolak Lupa Janji Jokowi soal Pemberantasan Korupsi
- PB Djarum Hentikan Audisi Bulutangkis, Ini Kata KPAI


The labeling process is carried out by 10 people and 3 annotators. Each comment is labeled with: 
- 1 'not abusive' : stating comments that are "Pengetahuan tidak dapat menggantikan persahabatan. Aku (Patrick) lebih suka jadi idiot daripada kehilanganmu (Spongebob)"
- 2 'abusive but not offensive': stating comments that are "Kencing onta asli apa onta bonbin bray yg bagus ?"
- 3 'abusive and offensive' : ⁣⁣stating comments that are "GOBLOK,ngapain beli indosat ? g ada untungnya, jaringan aja super lemot,di papua aja g ada jaringannya, mentok2 cuma 2G, harusnya pikir pakai otak bagaimana beli seluruh saham telkomsel dari singtel ???"
