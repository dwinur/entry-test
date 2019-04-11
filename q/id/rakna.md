# Rakna

---

Lihat kode dibawah ini
```js
function f(x){
    if(typeof x !== "string") throw new Error("input harus merupakan string");
    return Math.max(...x.split(' ').map(x => x.length));
}
```

## Task

Apakah hal yang ingin dilakukan oleh kode ini? Jelaskan!

---

### Expected Output

<p><sub>Kami mengharapkan jawaban dalam bentuk penjelasan yang ringkas, tetapi mendetil tentang masalah yang diberikan</sub></p>
<p><sub>Anda dapat menulis jawaban langsung di e-mail, digabung dengan jawaban lain di sebuah file jawaban (dalam format doc atau pdf), atau dilampirkan sebagai file. Tolong tulis id referensi dari pertanyaan yaitu "rakna"</sub></p>



---

#### Answer

Coding di atas pada baris kedua menjelaskan tentang pengecekan jenis data dari variabel, jika bukan string maka muncul error input harus string
coding di bawahnya berfungsi untuk mencari banyaknya dari kata terpanjang di dalam string. Contoh : ('I like tacos');   => 5

[switch to english](../en/rakna.md)

[javascript](tags/javascript.md) 
| [OOP](tags/OOP.md) 
| [Intermediate](tags/Intermediate.md) 

