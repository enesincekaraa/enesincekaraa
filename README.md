<h1 align="center">Enes İncekara</h1>
<h3 align="center">Software Engineer | Backend Architecture & System Design</h3>

<p align="center">
<a href="https://www.linkedin.com/in/enes-incekara/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/enesincekaraa"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:enesincekara61@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://medium.com/@enesincekaradev"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white"/></a>
</p>

---

## 💡 Mühendislik Felsefem

Kalite odaklı ve test edilebilir bir mühendislik disiplinini merkeze alarak, **ölçeklenebilir, dayanıklı (resilient) ve yüksek performanslı backend sistemleri** tasarlıyorum. 

Sadece kod yazmakla yetinmiyor; **Domain-Driven Design (DDD)**, **Event-Driven Architecture (EDA)** ve **Çok Kiracılı (Multi-tenant)** sistemler üzerine mimari kararlar alıyorum. Son dönemde geleneksel mikroservis mimarilerini, yerel yapay zeka (LLM/RAG) entegrasyonlarıyla birleştirerek modern sınırları zorluyor ve doğrudan gerçek dünya problemlerini çözen production-ready projeler üretiyorum.

---

## 🧠 Teknoloji Yığını & Uzmanlık

*   **Backend & Frameworks:** Java, Spring Boot, C#, .NET, REST API Design
*   **Architecture & Patterns:** Microservices, Event-Driven Systems, Clean Architecture, Transactional Outbox Pattern
*   **Message Brokers:** Apache Kafka, RabbitMQ (Dead-Letter Queues, Async Processing)
*   **Data & Caching:** PostgreSQL, MySQL, Redis (Rate Limiting, In-memory caching)
*   **AI Integration:** Ollama, Qwen 2.5 (Local LLM), RAG Systems
*   **DevOps & Observability:** Docker, Docker Compose, GitHub Actions, Actuator, Micrometer

---

## 🚀 Öne Çıkan Mühendislik Projeleri

### 🤖 DocuMind AI | *Multi-Tenant RAG System*
Kullanıcıların belgeleri üzerinde izole bir şekilde yapay zeka tabanlı soru-cevap yapmasını sağlayan sistem.
*   **Mimari:** Thread-bound `TenantContext` ile yönetilen Multi-tenant yapı.
*   **AI & Resilience:** Yerel Ollama (Qwen 2.5) entegrasyonu, **Circuit Breaker** ve **Retry** (Resilience4j) ile korunan dayanıklı (resilient) çağrılar.
*   **Async Processing:** MinIO ve RabbitMQ üzerinden arka planda asenkron belge işleme ve vektörizasyon.
*   **Security:** Bucket4j ile kiracı bazlı API Rate Limiting ve RFC 7807 standartlarında Exception Handling.

### ⚡ EventHub Platform | *Event-Driven Microservices*
Dağıtık sistemlerde veri tutarlılığını sağlayan gelişmiş event-driven altyapısı.
*   **Patterns:** Domain Events ve **Transactional Outbox Pattern** implementasyonu.
*   **Messaging:** Spring Kafka ile yüksek hacimli producer & consumer yönetimi.
*   **Focus:** Gerçek sistemlerde kullanılan advanced mesajlaşma garantileri (at-least-once delivery).

### ⚖️ Lexiflow & InvoiceGuard | *Asynchronous Microservices*
Sözleşme analizi ve fatura güvenliği süreçlerini yöneten dağıtık servisler.
*   **Messaging:** RabbitMQ ile asenkron iletişim ve **Dead-Letter Queue (DLQ)** yapılandırmaları.
*   **Focus:** Hata toleransı (fault tolerance) ve kayıpsız veri işleme.

### 🔥 BitPath | *High-Performance URL Shortener*
Yüksek trafikli link kısaltma ve analiz platformu.
*   **Performance:** Redis cache ve Rate limiting ile optimize edilmiş yanıt süreleri.
*   **Analytics:** Kafka üzerinden asenkron "click event tracking" mekanizması.
*   **Storage:** PostgreSQL persistence.

---

## 🎯 Şu Anda Neler Yapıyorum?

*   Production-ready, hata toleransı yüksek (fault-tolerant) dağıtık sistemler inşa ediyorum.
*   Yerel yapay zeka modellerini (Local LLMs) mikroservis ekosistemlerine asenkron olarak entegre etme üzerine çalışıyorum.
*   Backend mimarilerinde performans optimizasyonu ve "System Design" konularında derinleşiyorum.

---

> *"Good architecture is not about making the right decisions early, but making decisions easy to change later."*
