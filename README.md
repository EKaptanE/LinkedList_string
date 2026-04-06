---

# LinkedList Labwork

Bu proje, temel veri yapılarından biri olan **Bağlı Liste (Linked List)** yapısının mantığını anlamak ve uygulamak amacıyla geliştirilmiş bir laboratuvar çalışmasıdır. Proje, dinamik bellek yönetimi ve veri organizasyonu üzerine odaklanmaktadır.

## 📌 Proje Hakkında

Bağlı Listeler, verilerin bellekte ardışık olmayan konumlarda saklandığı ve her bir öğenin (düğüm) bir sonraki öğeye işaret ettiği doğrusal bir veri yapısıdır. Bu projede, bu yapının temel operasyonları ve yönetim stratejileri uygulanmıştır.

### Desteklenen Temel Özellikler:

* **Düğüm Ekleme:** Listenin başına, sonuna veya belirli bir konumuna veri ekleme.
* **Düğüm Silme:** Verilen bir değere veya konuma göre veri çıkarma.
* **Arama:** Liste içerisinde belirli bir verinin varlığını kontrol etme.
* **Listeleme:** Tüm liste elemanlarını ekrana yazdırma.
* **Bellek Yönetimi:** Dinamik bellek kullanımı (C/C++ için `malloc`/`free` veya `new`/`delete` işlemleri).

---

## 🏗 Veri Yapısı Mimarısı

Proje içerisinde kullanılan temel düğüm yapısı şu şekildedir:

Her bir düğüm (**Node**) iki ana kısımdan oluşur:

1. **Data:** Saklanacak olan değer.
2. **Next Pointer:** Bir sonraki düğümün bellek adresini tutan işaretçi.

---

## 🚀 Başlangıç

Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz.

### Gereksinimler

* C/C++ Derleyicisi (GCC, Clang veya MSVC)
* Git (Opsiyonel)

### Kurulum ve Çalıştırma

1. **Depoyu Klonlayın:**
```bash
git clone https://github.com/EKaptanE/LinkedList-Lab-Project.git
cd LinkedList-Lab-Project

```


2. **Derleyin:**
```bash
gcc main.c -o linkedlist

```


3. **Çalıştırın:**
```bash
./linkedlist

```



---

## 🛠 Kullanım Örneği

Kod içerisinde bağlı listeyi şu şekilde başlatabilir ve kullanabilirsiniz:

```c
// Örnek bir ekleme işlemi
insertNode(head, 10);
insertNode(head, 20);
displayList(head); // Çıktı: 10 -> 20 -> NULL

```

---

**Geliştirici:** [EKaptanE](https://www.google.com/search?q=https://github.com/EKaptanE)

---
