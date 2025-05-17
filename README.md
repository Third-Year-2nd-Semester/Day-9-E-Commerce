### 📁 Repository Package (`repo`)

The **repository package** contains interfaces that handle **data access operations**. These interfaces typically extend Spring Data JPA interfaces like `JpaRepository`, which allows you to:

* Perform **CRUD operations** (Create, Read, Update, Delete)
* Execute **custom queries** using method naming conventions
* Eliminate boilerplate code for database interactions

Spring Boot automatically provides the implementation at runtime, so no manual implementation is needed.



### 📁 Service Package (`service`)

The **service package** contains classes that handle the **business logic** of the application. It acts as an intermediate layer between the **controller** and the **repository**.

Responsibilities include:

* Processing or validating data before saving/fetching
* Handling business rules
* Making the application more modular and testable



![Screenshot 2025-05-17 205716](https://github.com/user-attachments/assets/038a65a1-b577-4796-b18a-624dc23daa6e)

![Screenshot 2025-05-17 205743](https://github.com/user-attachments/assets/d24ee8aa-d90c-45d7-9a91-9c2b92a650ca)
