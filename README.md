# Effective Stress Management
Soal stress management yang dibuat untuk lebih memahami javascript function dan memberikan kita feedback apakah kita memiliki stress seperti berikut:

### Result
| No | Total Score | Keterangan | 
| --- | ----------------- | ----- | 
| 1 | 0-7 | Normal | 
| 2 | 8-11 | Stress Ringan | 
| 3 | 12-15 | Stress Sedang | 
| 4 | 16-20 | Stress Cukup Berat | 
| 5 | >21 | Stress Berat | 
---

## Restrictions
- tidak ada aturan, silakan coding ugal-ugalan yang penting tujuannya tercapai sesuai jawaban seperti di bawah ini
```js
Halo, Kelvin! Terkadang hidup sedang tidak baik-baik saja. Kamu memiliki stress point sebanyak 17 point. Stress kamu tergolong Stress Sedang. Kamu punya pilihan untuk  membuat stress tersebut menjadi Eustress atau Distress. Cari lebih lanjut Eustress atau Distress dari sumber manapun.
```
- pakai semua cara yang bisa digunakan yaitu: looping, condition, function

## Objectives
- Mampu menyelesaikan masalah yang diberikan
- Mengerti konsep dan cara penggunaan `conditional`
- Mengerti konsep dan cara penggunaaan `nested loop`
- Mengerti konsep dan cara penggunaan `modular function`
- Mengerti konsep dan cara penggunaan operator pembanding `===` atau `!==`

## Direction
Buatlah program di mana dapat memberi feedback point dan menentukan seberapa berat stress kamu. 

### Release 1 - `split`
- Function `split` merupakan fungsi untuk memisahkan nama dan jawaban-jawaban yang sudah ada
- Function `split` memiliki 2 parameter input yaitu:
  - `arr` berupa _array single dimensi_ yang berisi **nama dan jawaban kamu**
  - `params` berupa _character string_ yang berisi delimiter seperti ";", "," atau apapun yang bisa kamu pilih.

```js
function split(arr,params)
{
    //silakan coding ugal-ugalan di bawah sini
}
```

### Release 2 - `countPoints`
- Function `countPoints` merupakan fungsi untuk menghitung jumlah point dari jawaban-jawaban yang sudah ada.
- Function `countPoints` memiliki 1 parameter input yaitu:
  - `arr` berupa _array single dimensi_ yang berisi jawaban-jawaban atas pertanyaan effective stress management
```js
function countPoints(arr){
    //silakan coding ugal-ugalan di bawah sini
}
```

Buatlah jawaban kamu sebagai berikut dengan ketentuan penulisan seperti `tp`,`htp`,`kk`,`as` atau `ss` dipisahkan dengan tanda `;` atau `,` atau `|`, silakan tentukan yang kamu suka.

Di bawah ini adalah contoh penulisan jawaban kamu.
```js
console.log(
effectiveStressManagement
(
    `namakamu`;
    `jawabankamu0`;
    `jawabankamu1`;
    `jawabankamu2`;
    `jawabankamu3`;
    `jawabankamu4`;
    `jawabankamu5`;
    `jawabankamu6`;
    `jawabankamu7`;
    `jawabankamu8`;
    `jawabankamu9`;
));
```

## Pertanyaan Stress Management sebagai berikut
1. Seberapa sering Anda merasa kesal karena terjadi sesuatu yang tidak Anda harapkan?
2. Seberapa sering Anda merasa bahwa Anda tidak dapat mengontrol hal-hal penting dalam hidup Anda?
3. Seberapa sering Anda merasa grogi dan tertekan?
4. Seberapa sering Anda merasa yakin dengan kemampuan Anda untuk menghadapi masalah personal Anda?
5. Seberapa sering Anda merasa hal-hal terjadi sesuai rencana Anda?
6. Seberapa sering Anda merasa bahwa Anda tidak dapat mengatasi hal-hal yang harus Anda lakukan?
7. Seberapa sering Anda dapat mengatasi gangguan yang terjadi dalam hidup Anda?
8. Seberapa sering Anda merasa bahwa Anda dapat mengontrol segala hal dengan sangat baik?
9. Seberapa sering Anda merasa marah karena hal-hal yang terjadi di luar kontrol Anda?
10. Seberapa sering Anda merasa berada dalam kesulitan yang berat sehingga Anda tidak dapat mengatasinya?

## Penilaian berdasarkan Norma & Scoring berikut:

### Soal nomor 1,2,3,6,9,dan 10
| No | Keterangan | console | Point/item |
| --- | ----------------- | ----- | ------ |
| 1 | Tidak Pernah | tp | **0** |
| 2 | Hampir Tidak Pernah | htp | **1** |
| 3 | Kadang-Kadang | kk | **2** |
| 4 | Agak Sering | as | **3** |
| 5 | Sangat Sering | ss | **4** | 
---


### Soal nomor 4,5,7,8
| No | Keterangan | console | Point/item |
| --- | ----------------- | ----- | ------ |
| 1 | Sangat Sering | ss | **0** |
| 2 | Agak Sering | as | **1** |
| 3 | Kadang-Kadang | kk | **2** |
| 4 | Hampir Tidak Pernah | htp | **3** |
| 5 | Tidak Pernah | tp | **4** | 
---
