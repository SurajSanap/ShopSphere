<script src="https://unpkg.com/@dotlottie/player-component@2.7.12/dist/dotlottie-player.mjs" type="module"></script>
<dotlottie-player src="https://lottie.host/e760c2af-9fc3-4346-a285-cc89a1a9b169/TjQvn2kUaA.lottie" background="transparent" speed="1" style="width: 300px; height: 300px" loop autoplay></dotlottie-player>

# ShopSphere

## **Overview**
A **scalable, modular, and secure** e-commerce platform built with **Spring Boot, Hibernate, and MySQL**. Designed to provide a seamless online shopping experience, it includes user authentication, product management, cart functionality, and admin controls. The system follows **MVC architecture** and utilizes **RESTful APIs** for efficient client-server communication.

## **Key Features**
- **User Authentication & Role-Based Access Control** (Admin, Customer)
- **Product Management** (Add, Edit, Delete, View Products)
- **Shopping Cart & Order Management**
- **Secure Payments Integration (Planned Feature)**
- **Admin Dashboard for Managing Users & Orders**
- **Spring Security Implementation** for Enhanced Security
- **Automated Database Table Creation with Hibernate**
- **Multi-IDE Compatibility (Eclipse, IntelliJ, VS Code)**

## **Tech Stack**
- **Backend:** Spring Boot, Hibernate ORM, Spring Security
- **Database:** MySQL
- **Frontend:** JSP, Bootstrap (for UI improvements)
- **Build Tool:** Maven
- **Server:** Apache Tomcat

## **Installation & Setup**
### **Prerequisites**
- Java 17 or later
- MySQL Database
- Maven
- An IDE (IntelliJ IDEA, Eclipse, or VS Code)

### **Step-by-Step Guide**
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/suraj/E-commerce-platform.git
   cd E-commerce-platform
   ```

2. **Configure the Database:**
   Update `src/main/resources/application.properties` with your database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommjava?createDatabaseIfNotExist=true
   spring.datasource.username=root
   spring.datasource.password=your_password
   ```

3. **Build the Project:**
   ```sh
   mvn clean install
   ```

4. **Run the Application:**
   ```sh
   mvn spring-boot:run
   ```

5. **Access the Web Application:**
   - Open your browser and go to `http://localhost:8080/`

## **API Endpoints**
| HTTP Method | Endpoint                  | Description                 |
|------------|--------------------------|-----------------------------|
| GET        | `/`                        | Home Page                   |
| POST       | `/login`                   | User Login                  |
| GET        | `/register`                | User Registration           |
| GET        | `/admin/products`          | View Products (Admin)       |
| POST       | `/admin/products/add`      | Add New Product             |
| GET        | `/cart`                     | View Shopping Cart          |
| POST       | `/cart/add`                 | Add Item to Cart            |

## **Project Structure**
```
E-commerce-platform/
├── src/
│   ├── main/
│   │   ├── java/com/suraj/ecommerce/
│   │   │   ├── controllers/
│   │   │   ├── models/
│   │   │   ├── repositories/
│   │   │   ├── services/
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   ├── templates/
│   │   │   ├── static/
│   ├── test/
├── pom.xml
├── README.md
```

## **Future Enhancements**
- **Payment Gateway Integration**
- **Order Tracking System**
- **Product Reviews & Ratings**
- **AI-Based Product Recommendations**

## **Contributing**
Contributions are welcome! Please fork the repository and submit a pull request.

## **License**
This project is licensed under the MIT License.

## **Author**
**Suraj** - Developer & Maintainer

