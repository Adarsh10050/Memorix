# Memorix

**Memorix** is a modern web application that allows users to **store, manage, and organize contacts efficiently**. Each contact can have a **photo, phone number, description, and nickname**, making it easier to identify and keep track of personal and professional connections.  

---

## **Features**

- **Add Contacts**: Save new contacts with full details including photo, nickname, and description.  
- **View Contacts**: Display all your contacts in a clean and organized interface.  
- **Edit Contacts**: Update contact information at any time.  
- **Delete Contacts**: Remove unnecessary or outdated contacts.  
- **Profile Photos**: Each contact can have a profile image for easy identification.  
- **Search & Filter**: Quickly find contacts using names, nicknames, or descriptions.  

---

## **Tech Stack**

- **Backend**: Java, Spring Boot, Spring Security  
- **Frontend**: HTML, CSS, Thymeleaf  
- **Database**: MySQL  
- **Build Tool**: Maven  
- **Others**: Bootstrap, JavaScript  

---

## **Screenshots**

![Home Page] <img width="1919" height="858" alt="Screenshot 2025-10-27 010035" src="https://github.com/user-attachments/assets/f619e314-5361-4988-90ba-1c50dff22a4e" />

*Home page with navigation and quick access to features.*

![Memorix Dashboard] <img width="1912" height="867" alt="Screenshot 2025-10-27 010114" src="https://github.com/user-attachments/assets/a6d1e039-afc2-46cd-a1cf-753b36ecc6d1" />

*Form to add new contacts with photo upload.*

![Login/Signup page]<img width="1911" height="866" alt="Screenshot 2025-10-27 010045" src="https://github.com/user-attachments/assets/1e1bd90c-6f12-4236-b190-5279b779fea5" />
<img width="1919" height="867" alt="Screenshot 2025-10-27 010055" src="https://github.com/user-attachments/assets/675a4edc-3101-45df-954d-8d20bc0f7935" />

*Register and login yourself here.*

---

## **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Memorix.git
2. Open in IDE: Use Spring Tool Suite (STS) or IntelliJ IDEA.

# ==============================
# Database Configuration
# ==============================
```
spring.datasource.url=jdbc:mysql://localhost:3306/memorix?useSSL=false&allowPublicKeyRetrieval=true&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=your_password
```
# ==============================
# JPA / Hibernate Configuration
# ==============================
```
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```

# ==============================
# Server Configuration (Optional)
# ==============================
```
server.port=8181
```


