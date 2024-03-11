# Amazon Web Scraping
 
Bu Python kodu, belirli bir URL listesinden ürün bilgilerini toplamak ve bu bilgileri bir Excel dosyasına kaydetmek için kullanılır. Kod aşağıdaki işlemleri gerçekleştirir:

Belirli bir URL listesinden ürün bilgilerini çekmek için get_product_data fonksiyonu tanımlanır.
Bu fonksiyon, her bir URL'yi ziyaret eder, sayfa içeriğini alır, gerekli bilgileri çıkarır ve geri döndürür.
requests, BeautifulSoup, ve openpyxl gibi dış kütüphaneler kullanılarak web sayfası içeriği alınır, analiz edilir ve Excel dosyasına kaydedilir.
concurrent.futures.ThreadPoolExecutor() kullanılarak çoklu iş parçacığı kullanılır, böylece birden fazla URL aynı anda işlenebilir.
urun_linkleri.txt dosyasından URL'leri okur ve bunları işlemek için get_product_data fonksiyonuna gönderir.
Elde edilen ürün bilgileri Excel tablosuna yazılır ve urun_bilgileri.xlsx olarak kaydedilir.
Oluşturulan Excel dosyasının düzgün çalışması için gerekli bir düzeltme yapılır.
İşlem tamamlandıktan sonra "Done!" mesajı yazdırılır.
