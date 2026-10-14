# USOM Zararlı Adres Çekici (UsomApp) 🛡️

**UsomApp**, Ulusal Siber Olaylara Müdahale Merkezi (USOM) tarafından yayımlanan güncel zararlı adres ve bağlantıları (URL, IP, Domain) otomatik olarak çeken, işleyen ve masaüstü arayüzü üzerinden listeleyip dışa aktarmanızı sağlayan bir **.NET 8 Windows** uygulamasıdır.


<img width="801" height="671" alt="image" src="https://github.com/user-attachments/assets/26bfc388-0440-4d51-af87-a37e3e1ee298" />


## 🚀 Özellikler

* **USOM Veri Entegrasyonu:** USOM tarafından sağlanan güncel zararlı bağlantı listesini anlık olarak çeker.
* **Kolay Kullanım:** Masaüstü kullanıcı dostu arayüz ile verileri görüntüleme ve yönetme.
* **Filtreleme ve Dışa Aktarma:** Çekilen verileri ayrıştırarak güvenlik cihazları (Firewall, SIEM, DNS Sinkhole vb.) için uyumlu formatlarda kaydetme imkanı.
* **Performans:** .NET 8 altyapısı sayesinde hızlı çalışma ve düşük kaynak kullanımı.



---

## 💻 Gereksinimler

* **İşletim Sistemi:** Windows 10 / Windows 11 / Windows Server 2016 ve üzeri
* **Çalışma Zamanı:** [.NET Desktop Runtime 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) *(Sisteminizde .NET 8 Desktop Runtime kurulu olmalıdır)*


---

## 📦 Kurulum ve Çalıştırma

### 1. Hazır Derlenmiş Sürüm (Executable)

1. Reponun **Releases** bölümünden veya `net8.0-windows` derleme klasöründen en son sürümü indirin.


2. Klasör içerisindeki **`UsomApp.exe`** dosyasını çalıştırın.



> **Not:** Uygulamanın sorunsuz çalışması için `UsomApp.dll`, `UsomApp.deps.json` ve `UsomApp.runtimeconfig.json` dosyalarının `UsomApp.exe` ile aynı klasörde bulunması gerekmektedir.
> 
> 

### 2. Kaynak Koddan Derleme (Visual Studio / CLI)

Projeyi bilgisayarınıza kopyalayıp kendiniz derlemek isterseniz:

```bash
# Repoyu klonlayın
git clone [https://github.com/kullanici-adi/UsomApp.git](https://github.com/onder7/USOM-Zararl-Adres-ekici)

# Proje klasörüne gidin
cd UsomApp

# Projeyi derleyin
dotnet build -c Release

# Uygulamayı çalıştırın
dotnet run

```

---

## 🛠️ Teknolojiler

* **Framework:** .NET 8.0 (Windows Desktop)


* **Dil:** C#
* **Çıktı Tipi:** Windows Application (.exe)



---

## 🤝 Katkıda Bulunma

1. Bu depoyu (repository) **Fork** edin.
2. Yeni bir özellik dalı oluşturun (`git checkout -b feature/yeni-ozellik`).
3. Değişikliklerinizi kaydedin (`git commit -m 'Yeni özellik eklendi'`).
4. Dalınızı gönderin (`git push origin feature/yeni-ozellik`).
5. Bir **Pull Request** oluşturun.

---

## 📜 Lisans

Bu proje [MIT Lisansı](https://www.google.com/search?q=LICENSE) altında lisanslanmıştır.
