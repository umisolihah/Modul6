# Peran Bagian MVC
MVC adalah konsep arsitektur dalam pembangunan aplikasi berbasis web yang membagi aplikasi web menjadi 3 bagian besar. Yang mana setiap bagian memiliki tugas-tugas serta tanggung jawab masing-masing. Tiga bagian tersebut adalah: model, view dan controller.

## Tujuan
Memahami peran dan fungsi masing-masing bagian MVC. Serta untuk mengelompokkan fungsi-fungsi agar tidak berserakan, dan jelas menjadi satu kesatuan sesuai tipe datanya.

## About this Program
- Membuat aplikasi pemesanan makanan.
- Membuat keranjang sebagai wadah makanan dan minuman yang dipesan.
- Bagian yang bertanggung jawab melakukan kalkulasi, diwadahi dalam kelas Payment

## How does it works?
logika perhitungan untuk melakukan kalkulasi terdapat pad class `Payment.cs`

``` csharp
 class Payment
    {
        private double deliveryFee = 0;
        private double promo = 0;
        private double balance = 0;
        private OnPaymentChangedListener paymentCallback;
```


