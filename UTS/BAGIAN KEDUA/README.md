# TOPIC MODELLING PADA Reviews_Filter.csv DENGAN LDA

Berikut hasil gambaran klaster topik dengan pyLDAvis

![image](https://user-images.githubusercontent.com/73022578/200147333-7c2db3a0-60b1-4586-9de7-872ad364e69e.png)

Berdasarkan gambar tersebut dapat dilihat terdapat 20 klaster yang menunjukkan jumlah topik yang terdapat pada isi data Reviews_Filter.csv tersebut. Pada gambar tersebut juga bisa dilihat jika masing-masing klaster juga ada yang beririsan satu sama lain dan ada yang terpisah. Klaster yang beririsan satu sama lain menunjukkan bahwa antara topik tersebut terdapat kata-kata sama yang digunakan. Sedangkan untuk klaster yang terpisah (tidak ada irisan dengan klaster lain) menunjukkan bahwa topik tersebut independen atau tidak ada kata-kata yang sama dengan klaster lainnya. 

Jika diambil salah satu klaster yang terpisah (misal diambil yang no 4), dapat dilihat hasil sebagai berikut :

![image](https://user-images.githubusercontent.com/73022578/200148254-55b40238-52af-4267-aa57-a5b66560b89a.png)

Berdasarkan analisa dari klaster tersebut, dapat dianalisis hasil sebagai berikut :

1. Kata-kata yang yang sering muncul teratas yaitu, treat, food, dog. Selain itu, terdapat juga kata product, healty, cat. Maka secara umum dapat disimpulkan bahwa pada klaster 4 tersebut topik yang dibahas mengenai makanan dan hewan (yang terdiri atas atas makanan hewan).
2. Terdapat kata lain juga yang sering muncul yang menyangkut review (ADJ) seperti good dan happy, sehingga secara umum dapat disimpulkan bahwa review konsumen terhadap prosuk tersebut positif.

Selain itu, Perplexity pada model tersebut -7.6316629823013775 dan Coherence score 0.3683066923002187. Perplexity tersebut menunjukan minus yang berarti pemodelan distribusi probabilitas topik tersebut sudah bagus. Selain itu, nilai coherence menunjukkan nilai yang sudah sesuai.
