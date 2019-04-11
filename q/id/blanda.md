# Blanda

---

Lihat kode dibawah ini
```js
function f(x){
    if(!Array.isArray(x)) throw new Error("input harus merupakan array");
    if(x.length <= 1) return x;
    for(let i=0; i<15; i++){
        let y = x.splice(Math.random()*x.length/4+x.length/2);
        y = f(y);
        x = y.concat(x);
    }
    return x;
}
```

## Task

Apakah hal yang ingin dilakukan oleh kode ini? Jelaskan!

---

### Expected Output

<p><sub>Kami mengharapkan jawaban dalam bentuk penjelasan yang ringkas, tetapi mendetil tentang masalah yang diberikan</sub></p>
<p><sub>Anda dapat menulis jawaban langsung di e-mail, digabung dengan jawaban lain di sebuah file jawaban (dalam format doc atau pdf), atau dilampirkan sebagai file. Tolong tulis id referensi dari pertanyaan yaitu "blanda"</sub></p>



---

#### Answer 
Fungsi dari coding diatas untuk mengambil nilai paling akhir dari array lalu diputar arraynya (angka paling terakhir jadi di depan angka sebelumnya)

---

[switch to english](../en/blanda.md)

[javascript](tags/javascript.md) 
| [OOP](tags/OOP.md) 
| [Intermediate](tags/Intermediate.md) 

