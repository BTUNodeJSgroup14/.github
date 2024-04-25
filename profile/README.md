## Hi there 👋
- [TR : Açıklama :boom:](#tr)
- [EN : Description :boom:](#en)  

****

 #### [TR]
 # BTÜ Node.js Grubu 14 API Projesi 🚀

## Proje Hakkında ℹ️

Bu organizasyon, Bursa Teknik Üniversitesi Node.JS ile Web Programlama dersinde 14. laboratuvar grubunun geliştirdiği yazılım projesi için açılmıştır. PostgreSQL veritabanı oluşturma ve Express.js ile REST API geliştirme üzerine odaklanmaktadır. Proje, öğrenci ve bölüm bilgilerini yönetmek için bir API sunmayı hedeflemektedir.

## Proje Aşamaları 📅

Proje 4 aşamadan oluşmaktadır. Aşamalar ve yapılan işler şunlardır:

1. **Veritabanı Oluşturma ve REST API Geliştirme**
   - PostgreSQL veritabanı oluşturma
   - Öğrenci, Öğrenci_Bölüm ve Bölüm şemalarının oluşturulması
   - REST API'nin geliştirilmesi: öğrenci ve bölüm için CRUD işlemleri

2. **Veritabanı Güncelleme ve Raporlama**
   - Veritabanına Öğrenci_Sayaç tablosunun eklenmesi
   - Haftalık raporlama için e-posta gönderiminin sağlanması
  (Haftalık raporlama işlemi için Nodemailer ve Cron kütüphaneleri kullanmıştır)

3. **Veritabanı Genişletme ve Zaman Takibi**
   - Tüm veritabanı şemalarının genişletilmesi
   - Kayıtlara created_at ve updated_at sütunlarının eklenmesi

4. **Kimlik Doğrulama ve Gelişmiş İşlevler**
   - API erişimi için kimlik doğrulaması sisteminin geliştirilmesi
   - Kullanıcı kimlik doğrulaması için token tabanlı güvenlik sağlanması

## Kullanılan Teknolojiler 🛠️

- Dil: Node.js
- Framework: Express.js
- Veritabanı: PostgreSQL

## Kurulum 📋

1. Projeyi bilgisayarınıza klonlayın: `git clone https://github.com/BTUNodeJSgroup14/api.git`
2. Proje dizinine gidin: `cd api`
3. Bağımlılıkları yükleyin: `npm install`
4. .env dosyasını oluşturun ve gerekli ortam değişkenlerini ayarlayın.
5. Projenin çalıştırılması: `npm start`

## Kullanım ✨ 

Proje çalıştırıldıktan sonra API'ye istekler göndererek öğrenci ve bölüm bilgilerini yönetebilirsiniz.

## Yazarlar ve İletişim 👩‍💻 👨‍💻

Created by 

- **Deniz Erdem** [@deniz7erdem](https://github.com/deniz7erdem)
- **Melike Yoğurtcu** [@melikeyogurtcu](https://github.com/melikeyogurtcu)
- **Oğuzhan Kahraman** [@OguzhanbilalKahraman](https://github.com/OguzhanbilalKahraman)
- **Saba Ürgüp** [@SabaUrgup](https://github.com/SabaUrgup) 
- **Selin Öz** [@selinnoz](https://github.com/selinnoz)

Bizimle iletişime geçebilir veya organizasyon üzerinden ekip ile iletişim kurabilirsiniz.!

## Katkıda Bulunma 🤝

Katkıda bulunmak isteyenler için projenin [GitHub deposu](https://github.com/BTUNodeJSgroup14/api) üzerinden forklayabilir ve pull request gönderebilirler.

## Lisans 📝

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

****

 #### [EN]
# BTU Node.js Group 14 API Project 🚀

## About the Project ℹ️

This organization was opened for the software project developed by the 14th laboratory group in Bursa Technical University's Web Programming with Node.JS lesson. It focuses on creating a PostgreSQL database and developing a REST API with Express.js. The project aims to provide an API for managing student and department information.

## Project Stages 📅

The project consists of 4 stages. The stages and tasks performed are as follows:

1. **Database Creation and REST API Development**
   - Creating PostgreSQL database
   - Creating schemas for Student, Student_Department, and Department
   - Developing REST API: CRUD operations for students and departments

2. **Database Update and Reporting**
   - Adding a new table, Student_Counter, to the database
   - Implementing weekly reporting with email notifications
   (Used Nodemailer and Cron libraries for weekly reporting)

3. **Database Expansion and Time Tracking**
   - Expanding all database schemas
   - Adding 'created_at' and 'updated_at' columns to records using the Moment package

4. **Authentication and Advanced Features**
   - Implementing authentication for API access
   - Providing token-based security for user authentication

## Technologies Used 🛠️

- Language: Node.js
- Framework: Express.js
- Database: PostgreSQL

## Installation 📋

1. Clone the project to your computer: `git clone https://github.com/BTUNodeJSgroup14/api.git`
2. Navigate to the project directory: `cd api`
3. Install dependencies: `npm install`
4. Create a .env file and set the required environment variables.
5. Run the project: `npm start`

## Usage ✨

After running the project, you can manage student and department information by sending requests to the API.

## Authors & Contact 👩‍💻 👨‍💻

Created by 

- **Deniz Erdem** [@deniz7erdem](https://github.com/deniz7erdem)
- **Melike Yoğurtcu** [@melikeyogurtcu](https://github.com/melikeyogurtcu)
- **Oğuzhan Kahraman** [@OguzhanbilalKahraman](https://github.com/OguzhanbilalKahraman)
- **Saba Ürgüp** [@SabaUrgup](https://github.com/SabaUrgup) 
- **Selin Öz** [@selinnoz](https://github.com/selinnoz)

You can contact us or communicate with the team through the organization.!

## Contributing 🤝

Those who want to contribute can fork the project from the [GitHub repository](https://github.com/BTUNodeJSgroup14/api) and send pull requests.

## License 📝

This project is licensed under the [MIT License](LICENSE).

