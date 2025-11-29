# GKE Monitoring Projesi

Bu proje, Google Kubernetes Engine (GKE) ortamında çalışan uygulamaların ve altyapının nasıl izleneceğini göstermek amacıyla oluşturulmuştur. Proje kapsamında, metriklerin toplanması, görselleştirilmesi ve olası sorunlara karşı uyarı mekanizmalarının kurulması ele alınmıştır.

Bu proje, Google Cloud'un Operasyonel Paketini (eski adıyla Stackdriver) kullanarak GKE küme performansını izlemek için temel bir yapılandırma sunar.

## Amaç

*   GKE kümesindeki CPU, bellek ve disk kullanımı gibi temel kaynak metriklerini izlemek.
*   Uygulama performansını ve hata oranlarını takip etmek için özel metrikler oluşturmak.
*   Cloud Monitoring panoları (dashboard) aracılığıyla metrikleri görselleştirmek.
*   Belirlenen eşik değerler aşıldığında otomatik uyarılar (alerting) oluşturmak.

## Ekran Görüntüsü

Aşağıda, yapılandırılmış izleme panosunun bir örneği yer almaktadır:

![GKE İzleme Panosu]<img width="1133" height="638" alt="monitor" src="https://github.com/user-attachments/assets/e5c814fa-27f9-422e-8ef8-bca224bd5bd4" />


---
*Bu README dosyası, projenin amacını ve kapsamını açıklamak için bir başlangıç noktasıdır. Kendi projenizin detaylarına göre bu dosyayı güncellemeyi unutmayın.*
