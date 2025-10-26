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

![Home Page](screenshots/home.png)  
*Home page with navigation and quick access to features.*

![Add Contact](screenshots/add_contact.png)  
*Form to add new contacts with photo upload.*

![Contact List](screenshots/contact_list.png)  
*View all saved contacts with search and filter functionality.*

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


