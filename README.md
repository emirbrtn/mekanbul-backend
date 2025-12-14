# Mekanbul Backend Projesi

**Geliştirici:** Emircan Bartan

**Canlı Demo:** https://mekanbul-backend-olive.vercel.app/

Bu proje Node.js, Express ve MongoDB kullanılarak geliştirilmiş, Vercel üzerinde çalışan bir REST API uygulamasıdır.

## 📍 API Uç Noktaları (Endpoints)

Projede kullanılan tüm API adresleri ve açıklamaları aşağıdadır:

| Metot | Uç Nokta (Endpoint) | Açıklama |
| :--- | :--- | :--- |
| **GET** | `/api/venues?lat={lat}&long={long}` | Konuma göre mekanları listeler. |
| **POST** | `/api/venues` | Yeni bir mekan ekler. |
| **GET** | `/api/venues/:venueid` | Belirli bir mekanı getirir. |
| **PUT** | `/api/venues/:venueid` | Belirli bir mekanı günceller. |
| **DELETE** | `/api/venues/:venueid` | Belirli bir mekanı siler. |
| **POST** | `/api/venues/:venueid/comments` | Mekana yeni yorum ekler. |
| **GET** | `/api/venues/:venueid/comments/:commentid` | Belirli bir yorumu getirir. |
| **PUT** | `/api/venues/:venueid/comments/:commentid` | Belirli bir yorumu günceller. |
| **DELETE** | `/api/venues/:venueid/comments/:commentid` | Belirli bir yorumu siler. |

---

## 📸 API Test Ekran Görüntüleri (Kanıtlar)

Aşağıda Postman kullanılarak yapılan tüm API testlerinin başarılı sonuçları yer almaktadır.

### 1. Mekan (Venue) İşlemleri

**Mekan Ekleme (POST):**
![Mekan Ekleme](tests/AddVenue.png)

**Mekanları Listeleme (GET):**
![Mekan Listeleme](tests/ListNearbyVenues.png)

**Tek Mekan Getirme (GET):**
![Mekan Getirme](tests/GetVenue.png)

**Mekan Güncelleme (PUT):**
![Mekan Güncelleme](tests/UpdateVenue.png)

**Mekan Silme (DELETE):**
![Mekan Silme](tests/DeleteVenue.png)

### 2. Yorum (Comment) İşlemleri

**Yorum Ekleme (POST):**
![Yorum Ekleme](tests/AddComment.png)

**Yorum Getirme (GET):**
![Yorum Getirme](tests/GetComment.png)

**Yorum Güncelleme (PUT):**
![Yorum Güncelleme](tests/UpdateComment.png)

**Yorum Silme (DELETE):**
![Yorum Silme](tests/DeleteComment.png)