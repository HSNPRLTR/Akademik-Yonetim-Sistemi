TR

# Üniversite Yönetim Sistemi

Bu proje, **Sentos Yazılım'da gerçekleştirdiğim 30 iş günlük staj sürecinde** geliştirdiğim kapsamlı bir **REST API** projesidir. **ASP.NET Core** ve **Entity Framework Core** kullanılarak geliştirilen sistem, bir üniversitedeki temel akademik süreçlerin dijital ortamda yönetilmesini amaçlamaktadır. Proje boyunca backend geliştirme, veritabanı tasarımı, API mimarisi, yetkilendirme, loglama ve modern yazılım geliştirme prensipleri üzerine kapsamlı deneyim kazandım.

## Proje Hakkında

Üniversitelerde yürütülen öğrenci, akademisyen, bölüm, ders, sınav, sınav sonuçları, duyurular, kullanıcı ve rol yönetimi gibi temel süreçleri merkezi bir REST API üzerinden yönetebilmek amacıyla geliştirildi.

Katmanlı mimari yapısı sayesinde sürdürülebilir, okunabilir ve geliştirilebilir bir altyapı oluşturuldu. Gerçek hayatta kullanılabilecek bir üniversite otomasyon sisteminin temel ihtiyaçlarını karşılayacak şekilde tasarlanmış olup, tüm işlemler REST standartlarına uygun uç noktalar üzerinden gerçekleştirilmektedir.

## Özellikler

* Öğrenci yönetimi
* Akademisyen yönetimi
* Yönetici kullanıcı sistemi
* Rol tabanlı yetkilendirme
* Bölüm yönetimi
* Ders oluşturma ve yönetimi
* Öğrencilerin ders kaydı yapabilmesi
* Sınav oluşturma
* Sınav sonuçlarının yönetimi
* Derslere özel duyuru sistemi
* Tüm temel varlıklar için CRUD işlemleri
* POST, PUT ve DELETE işlemleri için otomatik merkezi loglama sistemi
* Swagger UI ile API dokümantasyonu ve test ortamı
* Entity Framework Core Migration desteği
* SQLite veritabanı desteği

## Teknik Altyapı

* **Backend:** ASP.NET Core (C#)
* **ORM:** Entity Framework Core
* **Veritabanı:** SQLite
* **API Dokümantasyonu:** Swagger UI
* **Mimari:** Katmanlı Mimari (Controllers, Services, Models, Data)
* **İlişki Yapıları:** One-to-One, One-to-Many ve Many-to-Many

## Geliştirme Süreci

Proje geliştirilirken öğrencilerin ve akademisyenlerin yönetilebildiği, öğrencilerin ders seçebildiği, sınavların oluşturulup sonuçlarının sisteme kaydedilebildiği ve ders bazlı duyuruların paylaşılabildiği kapsamlı bir yapı oluşturuldu.

Veritabanı tasarımında gerçek bir üniversite bilgi sistemine uygun ilişkiler kurularak farklı senaryolar desteklendi. Entity Framework Core Migration sistemi kullanılarak veritabanı şeması kolayca yönetilebilir hale getirildi.

API'nin geliştirme ve test süreçlerini kolaylaştırmak amacıyla Swagger UI entegre edildi. Böylece tüm uç noktalar detaylı açıklamalarıyla birlikte görüntülenebilir ve doğrudan test edilebilir hale getirildi.

Sistemde gerçekleştirilen tüm kritik işlemler (POST, PUT ve DELETE) merkezi loglama sistemi tarafından otomatik olarak kayıt altına alınmaktadır. Bu sayede kullanıcı hareketleri izlenebilir hale getirilmiş ve sistemin şeffaflığı artırılmıştır.

## Bu Proje ile Kazandıklarım

Bu proje bana aşağıdaki konularda önemli deneyimler kazandırdı:

* REST API geliştirme
* ASP.NET Core
* Entity Framework Core
* Veritabanı modelleme
* Katmanlı mimari tasarımı
* CRUD operasyonları
* Rol tabanlı yetkilendirme
* Merkezi loglama sistemleri
* Swagger ile API dokümantasyonu
* Migration yönetimi
* Temiz, sürdürülebilir ve ölçeklenebilir backend geliştirme

## Projeyi İndir

Projeyi incelemek veya çalıştırmak isterseniz aşağıdaki bağlantıyı kullanabilirsiniz.

**https://www.mediafire.com/file/0y58rtnjp2ulrgk/Apisistem.rar/file**


EN


# University Management System

A comprehensive **REST API** developed with **ASP.NET Core** and **Entity Framework Core** to digitize and manage the core academic processes of a university. This project was built as my **30-day internship project at Sentos Software**, providing hands-on experience in backend development, database design, API architecture, authentication, logging, and software engineering best practices.

## Overview

The system centralizes the management of students, lecturers, departments, courses, exams, exam results, announcements, users, and roles through a scalable and maintainable RESTful API. Designed using a layered architecture, the project follows modern backend development principles and demonstrates how a real-world university information system can be structured.

Throughout the development process, I implemented complete CRUD operations, role-based authorization, database relationships, centralized logging, and interactive API documentation, resulting in a production-style backend application.

## Features

* User management (Students, Lecturers, Administrators)
* Role-based authorization
* Department and course management
* Student course registration
* Exam creation and exam result management
* Course-specific announcement system
* Complete CRUD endpoints for all major entities
* Automatic centralized logging for POST, PUT, and DELETE operations
* Interactive API documentation with Swagger UI
* SQLite database managed through Entity Framework Core
* Database migrations for schema versioning and maintenance

## Technical Stack

* **Backend:** ASP.NET Core (C#)
* **ORM:** Entity Framework Core
* **Database:** SQLite
* **API Documentation:** Swagger UI
* **Architecture:** Layered Architecture (Controllers, Services, Models, Data)
* **Database Design:** One-to-One, One-to-Many, and Many-to-Many relationships

## Project Highlights

During development, I designed a system where students and lecturers can be managed efficiently, students can enroll in courses, exams can be created and graded, and course-specific announcements can be published.

To improve maintainability and traceability, every critical action performed through the API (POST, PUT, DELETE) is automatically recorded by a centralized logging system, making the application transparent and easier to monitor.

Swagger UI was integrated to simplify API testing and documentation, allowing every endpoint to be explored interactively. Entity Framework Core migrations were used to keep the database schema organized and easily maintainable throughout development.

## Learning Outcomes

This project significantly strengthened my experience in:

* REST API development
* ASP.NET Core
* Entity Framework Core
* Database modeling and normalization
* Authentication and authorization
* Layered software architecture
* Logging and monitoring
* API documentation
* Database migrations
* Clean and maintainable backend development

## Download

If you would like to explore the project locally, you can download it here:

**https://www.mediafire.com/file/0y58rtnjp2ulrgk/Apisistem.rar/file**

