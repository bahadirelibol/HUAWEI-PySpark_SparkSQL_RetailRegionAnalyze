
# Huawei Retail Analytics: PySpark & SparkSQL

## Proje Açıklaması

Bu proje, Huawei için hazırlanan, perakende satış verilerinin PySpark ve Spark SQL ile detaylı analizini içermektedir. Veri setleri, bölgesel satışları, ürün bazlı performansları ve perakendecilerin cirolarını analiz etmek amacıyla kullanılmıştır.

## Kullanılan Teknolojiler

-   **Apache Spark:** Büyük veri işlemede güçlü bir motor.
    
-   **Spark SQL:** SQL sorgularıyla Spark üzerinden veri analizi yapma imkânı.
    
-   **PySpark DataFrame API:** Python ile fonksiyonel tarzda veri analizi.
    

## Projenin İçeriği

1.  **Veri Hazırlama ve Yükleme:**
    
    -   Parquet formatında saklanan veriler yüklenmiş ve Spark SQL sorguları için geçici tablolar oluşturulmuştur.
        
2.  **Temel Veri İşleme Adımları:**
    
    -   Kolon seçimi, veri manipülasyonu, filtreleme, gruplama ve JOIN işlemleri hem Spark SQL hem PySpark yöntemleriyle gösterilmiştir.
        
3.  **Önemli Analizler (Case Studies):**
    
    -   **Jacket Sales Analysis (Haziran–Ağustos 2023):** Bölge bazlı toplam jacket satış miktarları ve ciroları analiz edilmiştir.
        
    -   **Retailer Maximum Turnover Region:** Her perakendecinin en yüksek ciroya sahip olduğu bölge belirlenmiştir.
        

## Projeyi Çalıştırma

-   `findspark` ve `pyspark` kütüphaneleri yüklenmeli.
    
-   Veri setleri Parquet formatında ve `data` klasörü altında yer almalıdır.
    

```bash
pip install findspark pyspark
```

## Sonuçlar ve Bulgular

Proje sonunda elde edilen analizler sayesinde bölge bazlı satış eğilimleri, perakendecilerin performansları ve ürünlere göre tüketici tercihleri net olarak ortaya konmuştur. Bu analizler, iş kararları almak için sağlam bir veri tabanı sağlamaktadır.

### Yasin Bahadır ELibol
