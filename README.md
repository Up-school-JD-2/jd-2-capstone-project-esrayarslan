[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zmClullX)
## Havayolları Biletleme Sistemi Backend Servis Uygulaması

**Teknolojiler:**
- JAVA 17
- Maven
- Spring Boot 3
- MySQL Database
- Restful Web Service (JSON)

**Gereksinimler:**
- Havayolu şirketi eklenebilmeli ve aranabilmeli.
- Havaalanı eklenebilmeli ve aranabilmeli.
- Rota eklenebilmeli ve aranabilmeli.
- Havayolu şirketine uçuş tanımlanabilmeli ve aranabilmeli.
- Bilet satın alınabilmeli:
    - Satın alma işlemi sırasında kredi kartı bilgileri maskelenmeli. (Örneğin "4221161122330005" -> "422116******0005").
    - Kredi kartı numarasının aralarında boşluklar ya da ayraçlar olması gibi durumları da kapsayacak şekilde geliştirme yapılmalı. Örneğin; Request’te kart numarası farklı formatlarda da gelse (Örnek: "4221-1611-2233-0005", "4221,1611,2233,0005"), kart bilgisi beklenen şekilde ("422116******0005") maskelenerek satın alma işlemine alınmalı.
    - Bilet numarası ile arama yapılabilmeli ve bilet iptali yapılabilmeli.
- Silme gerektiren işlemlerde soft delete yapılması gereklidir.
- Global Exception Handling yapısının kurulması.
- API response’larının ortak bir yapı üzerinden dönülmesi.
- Private metodlar harici her yerin testleri yazılmalıdır (coverage minimum %60 olmalıdır).

**Proje Formatı:**
- Proje GitHub üzerinden paylaşılmalı.
- Proje sadece backend servisler olarak gerçekleştirilmeli.
- Servislere ait dökümantasyon oluşturulmalı ve servislere ait JSON örnekleri paylaşılmalı.
- Örneğin; "Postman" request'leri olarak iletilebilir.

**Not:**
Proje isteklerinin karşılanması durumunda ekstra yapılan geliştirmeler artı puan sayılabilir, ancak proje isteklerinin önceliği vardır.
