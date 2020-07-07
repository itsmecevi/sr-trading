# Support & Resistance



Trading tanpa konsep support dan resistance akan memperkecil resiko trading yang besar, karena dalam konsep ini diperkenalkan bahwa sebenarnya, harga suatu instrumen keuangan mempunyai level-level tertentu yang bisa dijadikan ajuan untuk trading sehingga memudahkan menentukan acuan harga.

![sr1](https://user-images.githubusercontent.com/27078712/86505567-80dd2a00-bdf0-11ea-90ff-9618a920d915.png)


You can use the [editor on GitHub](https://github.com/itsmecevi/sr-trading/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Pengertian Support & Resistance


**Definisi teknis:**

* Support-> batas level dalam trading dimana mendukung harga untuk naik (menolak untuk turun)
* Resistance-> batas level dalam trading dimana menolak harga untuk naik (mendukung untuk turun)
* Jika level support dan resistance dikombinasikan dengan teori candlestick, maka kecenderungan pasar selanjutnya bisa kita fahami

**Definisi supply dan demand:** 

    Support-> penawaran > permintaan, harga akan naik

> Jika harga menembus level support, maka kemungkinan harga akan naik, karena level support jika ditembus akan menjadi level resistance baru

    Resistance-> penawaran<permintaan, harga akan turun 
    
> Jika harga menembus level resistance, maka kemungkinan harga akan turun, kareba level resistance jika ditembus akan menjadi level support baru

### Cara mementukan titik support & resistance

Ada banyak cara yang digunakan trader untuk menghitung titik ini, beberapa diantaranya yang sering dipakai adalah sebagi berikut:

**1-Titik Tertinggi (Top) dan Titik Terendah (Bottom)**

* Cara ini merupakan cara yang paling mudah. Hanya dengan menarik garis horizantal dimana titik support dan resistance berada di dalam timeframe (jangka waktu)  tertentu, maka akan didapat sebuah titik dimana harga tidak bisa naik lagi (resistance) atau harga bisa menembus angka tertentu (support)
* Semakin timeframe (jangka waktu) yang dipakai, maka akan semakin valid titik harganya


**2-Trendline (Garis Trend)**

* Trendline dapat berlaku sebagai support dan resistance
* Hubungkan minimal 2 titik lembah (Bottom) atau 2 titik bukit (Top) untuk membuat sebuah trend


**3-Fibonacci Retracement**

* Fibonacci retracement bisa dignakan sebagai titik level support dan resistance
* Fibonacci memiliki level-level yang biasa digunakan yakni:
    * Level 0.0%
    * Level 23.6%
    * Level 38.2%
    * Level 50.0%
    * Level 61.8% (titik terkuat untuk bouncing dan reversal)
    * Level 76.4% (titik siap-siap)
    * Level 100.0%
 * Penggunaan Fibonacci retracement adalah mencari peluang buy ketika harga berada di titik support. Sebaliknya, kita bisa mencari peluang sell ketika harga berada di kisaran titik resistance. Strategi tersebut adalah strategi bouncing pada saat posisi harga naik, dan strategi reversal pada saat harga turun
 * Cara menarik garis Fibonacci Retracement:
    * Uptrend (tren naik)-> menarik Fibonacci retracement dari swing low ke swing high
    * Downtrend (tren turun)-> menarik Fibonacci retracement dari swing high ke swing low

**4-Round Number (angka bulat)**

* Merupakan angka bulat dan merupakan level psikologis di dalam instrumen pasar dan dipergunakan untuk menentukan titik support dan resistance
* Contohnya adalah EUR/USD dengan level 1.30000, atau 1.40000

**5-Moving Average**

* Analisa teknikal bukanlaa alat untuk meramal masa depan dan selalu tepat
* Analisa teknikal hanyalah sebuah metode pendekatan untuk melihat kecenderungan pergerakan harga
* MA dapat digunaka juga untuk menentukan support dan resistance. Istilahnya adalah support dan resistance dinamis (dynamic support and resistance). Dinamakan demikian SR tersebut bergerak sesuai dengan pergerakan harga.
* Moving Average (MA) memperhalus pergerakan dalam waktu rentang tertentu, sehingga mempermudah melihat pergerakan harga dengan memperjelas tren
* Contoh: MA50-> mengambil 50 grafik terakhir ke belakang, lalu membuatnya menjadi sebuah garis seperti gambar di bawah ini
![sr3](https://user-images.githubusercontent.com/27078712/86524782-f99fbd00-bea8-11ea-8bc5-e5152e2707d8.PNG)
* Standar harga yang digunakan biasanya adalah harga penutupan (close), namun ada beberapa metode yang menggunakan harga open, high, atau low.
* Harga di bawah MA-> tren turun (bearish)
* Harga di atas MA-> tren naik (bullish)
* Dalam pembelajaran mengenai MA ini, kita hanya perlu mengenal 2 jenis MA sering digunakan yaitu:
    * Simple Moving Average (SMA)
    * Exponential Moving Average (EMA)

_____


**Simple Moving Average (SMA):**

Merupakan MA paling sederhana dengan konsep menjumlahkan X chart sebelumnya lalu dibagi dengan angka X tersebut. Sebagai contoh, jika pada timeframe 1 jam kita menggunakan MA50, artinya 50 chart per jam kebelakang lalu dibagi dengan 50 akan menghasilkan angka tertentu. Nah perhitungan nilainya bisa diambil dari titik tertinggi (high), titik terendah (low), harga pembukaan (open), atau harga penutupan (close). Semakin besar periode X semakin "halus" pula MA(X) yang dihasillan seperti contoh berikut ini:
![sr4](https://user-images.githubusercontent.com/27078712/86526557-c1f03f80-bebf-11ea-86e5-4629502ca99b.PNG)

Gambar diatas menunjukan bahwa:
* MA20 lebih pendek, dan lebih cepat bereaksi
* MA50 lebih panjang dan "halus", lebih lamban bereaksi

Berikut merupakan setting SMA yang paling banyak digunakan:
* 50
* 100
* 200
* SMA-200
* MA-5 (sepekan)
* MA-20 (sebulan)
* MA-60 (3 bulan)
* MA-20 dan MA-50
* MA-20 dan MA-100
* MA-20 dan MA-200
* MA-50 dan MA-200
* Semakin pendek period X, maka makin rendah timeframe aplikasinya, dan makin banyak pula sinyal trading yang akan diperoleh





**Exponential Moving Average (EMA):**

* Pembahasan teknis detail EMA tidak akan dibahasa disini, karena fokus kita bukanlah membuat sistem EMA yang baru, melainkan memakai EMA dengan sedikit pemahaman konsep yang baik
* Pegerakan EMA lebih agresif (sensitif) daripada SMA. EMA lebih menggambarkan apa yang terjadi di pasar saat ini
![sr5](https://user-images.githubusercontent.com/27078712/86527793-798b4e80-becc-11ea-806d-28bb06946b3b.PNG)


**SMA atau EMA?**

SMA maupun EMA mempunyai kekurangan dan kelebihan masing-masing, mari kita bahas satu persatu:

* SMA lebih lamban, tetapi akurasinya lbh bagus, profit oriented
* EMA lebih cepat, tetapi sinyal yang muncul banyak "fake signal"

**Crossover**

Pasangan MA yang sering dipakai adalah sebagai berikut:

* MA-20 dan MA-50
* MA-20 dan MA-100
* MA-20 dan MA-200
* MA-50 dan MA-200

Contoh untuk kasus MA-20 dan MA-50: yang jadi patokan crossover adalah MA-20 yang melewati chart seperti gambar di bawah:
![sr7](https://user-images.githubusercontent.com/27078712/86528151-ab51e480-becf-11ea-8ab6-9cfc5e7756c6.PNG)



**6-Bollinger Band**

* Bollinger Band merupakan salah satu indikator yang dibuat oleh seorang analis pasar keuangan John Bollinger
* Digunakan untuk mengukur volatilitas pasar dan dan memperkirakan range (rentang) pergerakan harga pasar
![sr8](https://user-images.githubusercontent.com/27078712/86529030-7cd80780-bed7-11ea-81b9-105c93c56006.PNG)
* BB memiliki 3 garis, yaitu low BB, mid BB, dan top BB
![sr9](https://user-images.githubusercontent.com/27078712/86529043-a8f38880-bed7-11ea-89c6-34c2c0469015.PNG)
* Bollinger band memiliki 4 kriteria untuk sebagai support dan resistance yang dinamis di dalam trading:
    * Squeeze 
![sr10](https://user-images.githubusercontent.com/27078712/86529876-76995980-bede-11ea-8b35-d3ce46361b67.PNG)
![sr11](https://user-images.githubusercontent.com/27078712/86529884-7bf6a400-bede-11ea-9a0c-cdb9368ca6fc.PNG)

    * Reversal
![sr12](https://user-images.githubusercontent.com/27078712/86530720-53be7380-bee5-11ea-93f2-9aba53013630.PNG)
![sr13](https://user-images.githubusercontent.com/27078712/86530555-d1817f80-bee3-11ea-9af2-3642f534156a.PNG)

    
    * Jajaran
![sr14](https://user-images.githubusercontent.com/27078712/86530625-64221e80-bee4-11ea-815a-f7a249f3c1a0.PNG)
![sr15](https://user-images.githubusercontent.com/27078712/86530632-6edcb380-bee4-11ea-9e2f-b54e43e57f0d.PNG)

    
    * Exit
![sr17](https://user-images.githubusercontent.com/27078712/86530702-1bb73080-bee5-11ea-8598-a75f1751f9d9.PNG)
![sr16](https://user-images.githubusercontent.com/27078712/86530704-21ad1180-bee5-11ea-8e9c-96aa9fd099cd.PNG)





**7-Pivot Point**

* Pivot point bukan merupakan sebuah indikator, melainkan cabang dari analisa teknikal
* Pivot point menghitung titik support dan resistance dengan perhitungan tertentu
* Ada beberapa cara untuk menghitung pivot point yang biasa digunakan oleh para trader:
    * Classic
    * Fibonacci
    * Camarilla
    * Woodie's
    * DeMark's
    * Floor
    
Sebelum membahas masing-masing cara perhitungannya, berikut keterang dari beberapa istilah:

High: Harga tertinggi periode sebelumnya
Low: Harga terendah periode sebelumnya
Open: Harga pembukaan periode sebelumnya
Close: Harga penutupan periode sebelumnya
   
____

**Classic:**

        Pivot Point (PP) = (High + Low + Close / 3)

        Level Resistance ketiga (R3) = High + 2 x (PP - Low)
        Level R2 = PP + (High - Low)
        Level R1 = (2 x PP) - Low


        Level Support pertama (S1) = (2 x PP) - High
        Level S2 = PP - (High - Low)
        Level S3 = Low - 2 x (High - PP)

 


    
**Fibonacci:**

    PP = (High + Low + Close) / 3

    R3 = PP + ((High – Low) x 1.000)
    R2 = PP + ((High – Low) x 0.618)
    R1 = PP + ((High – Low) x 0.382)

    S1 = PP – ((High – Low) x 0.382)
    S2 = PP – ((High – Low) x 0.618)
    S3 = PP – ((High – Low) x 1.000)

**Camarilla:**

    PP = (High + Low + Close) / 3

    R4 = Close + ((High - Low) x 1.1/2)
    R3 = Close + ((High - Low) x 1.1/4)
    R2 = Close + ((High - Low) x 1.1/6)
    R1 = Close + ((High - Low) x 1.1/12)

    S1 = Close – ((High - Low) x 1.1/12)
    S2 = Close – ((High - Low) x 1.1/6)
    S3 = Close – ((High - Low) x 1.1/4)
    S4 = Close – ((High - Low) x 1.1/2)

**Woodie's:**

    PP = (High + Low + (Open hari ini * 2)) / 4

    R3 = High + 2 * (PP - Low)
    R2 = PP + High – Low
    R1 = (2 X PP) – Low


    S1 = (2 X PP) – High
    S2 = PP – High + Low
    S3 = Low - 2 * (High - PP)


**DeMark's:**

    If Close < Open, then X = High(previous day) + [2 x Low(previous day)] + Close(previous day) 
    If Close > Open, then X = [2 x High(previous day)] + Low(previous day) + Close(previous day)

    If Close = Open, then X = High(previous day) + Low(previous day) + [2 x Close(previous day)]

    Pivot Point (P) = X/4

    Support 1 (S1) = X/2 – High(previous day)

    Resistance 1 (R1) = X/2 – Low(previous day)
    
**Floor:**

    Pivot Point = [High(previous day) + Low(previous day) + Close(previous day)]/3

    R1 = (2*Pivot Point) – Low(previous day)
    S1 = (2*Pivot Point) – High(previous day)

    R2 = Pivot Point + (R1 – S1)
    S2 = Pivot Point – (R1 – S1)

    R3 = Pivot Point + (R2 – S2)
    S3 = Pivot Point – (R2 – S2)
    
    
Metode manapun yang digunakan utuk menentukan titik pivot, tidak ada indikator yang menjamin keberhasilan atau indikator terbaik. Indikator tersebut hanya membantu untuk mengenali kecenderungan pergerakan pasar. Pemahaman trader sendiri lah menentukan keberhasil profit dalam trading, bukan sebuah indikator...


