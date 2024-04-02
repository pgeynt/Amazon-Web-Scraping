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


This Python code is used to gather product information from a specific list of URLs and save this information to an Excel file. The code performs the following operations:

A function named get_product_data is defined to fetch product information from a specific list of URLs.
This function visits each URL, retrieves the page content, extracts the necessary information, and returns it.
External libraries such as requests, BeautifulSoup, and openpyxl are used to obtain the web page content, analyze it, and save it to an Excel file.
concurrent.futures.ThreadPoolExecutor() is utilized to employ multi-threading, allowing multiple URLs to be processed simultaneously.
Reads URLs from a file named urun_linkleri.txt and sends them to the get_product_data function for processing.
The obtained product information is written to an Excel sheet and saved as urun_bilgileri.xlsx.
A necessary fix is made for the created Excel file to function correctly.
Prints the message "Done!" once the process is completed.




