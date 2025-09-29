# 📘 SecretMyPhoneBook  
_Secret My Phone Book — Educational Contact & Secret Storage App_

Bu proje, **kişisel telefon rehberi + gizli bilgiler saklama** işlevi gören bir uygulama örneğidir.  
**Tamamen eğitim ve kişisel gelişim amaçlıdır.**  
This project is a sample application for **personal phonebook + secret storage**.  
**It is purely for educational and personal development purposes.**

---

## 🎯 Projenin Amacı / Project Purpose

**TR**  
- Kişi / iletişim bilgilerini saklamak ve yönetmek  
- Gizli not, şifre, özel bilgiler gibi hassas verileri güvenli şekilde depolamak  
- CRUD işlemleri, şifreleme / şifreli veri saklama, kullanıcı arayüzü pratikleri  

**EN**  
- Store and manage contact / communication information  
- Securely store sensitive data like secret notes, passwords, private info  
- Practice CRUD operations, encryption / secure data storage, UI features  

---

## 🏗 Mimari & Yapı / Architecture & Structure

SecretMyPhoneBook/
├── PhoneBookDesktopApp/ # Masaüstü uygulama (örneğin WinForms / WPF)
├── Domain/ # Entity’ler (Contact, SecretItem, vs.)
├── Application/ # İş mantığı, servisler, DTO’lar
├── Infrastructure/ # Veri erişim, şifreleme altyapısı
├── Security/ # Şifreleme / kriptografi işlemleri
├── Tests/ # Birim testler
├── SecretMyPhoneBook.sln # Çözüm dosyası
├── .gitignore
└── README.md

- `PhoneBookDesktopApp/`: UI üzerinde kullanıcı arayüzü uygulaması  
- `Domain/`: İletişim kayıtları ve gizli bilgi veri modelleri  
- `Application/`: CRUD servisleri, iş kuralları  
- `Infrastructure/`: Veritabanı, dosya sistemi, repository desenleri  
- `Security/`: Şifreleme, hash, gizleme işlemleri  
- `Tests/`: Domain / servis / güvenlik bileşeni testleri  

---

## 🛠 Teknolojiler / Technologies

- C# / .NET (örneğin .NET Core, .NET Framework)  
- UI framework: WinForms, WPF veya başka masaüstü çözümleri  
- Veri tabanı / depolama: SQLite, SQL Server, dosya tabanlı (JSON, XML, vs.)  
- Şifreleme / Kriptografi: AES, RSA, Hashing + Salt  
- Unit Test çerçevesi (xUnit, NUnit)  
- (İsteğe bağlı) MVVM ya da Tasarım Desenleri  

---

## 🚀 Kurulum & Çalıştırma / Setup & Running

### 1. Depoyu Klonla / Clone the Repo  
```bash
git clone https://github.com/kalecaner/SecretMyPhoneBook.git
cd SecretMyPhoneBook

