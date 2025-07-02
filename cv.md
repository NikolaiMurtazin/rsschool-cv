# Nikolai Murtazin

<img src="assets/img/NikolaiMurtazin.jpg" width="150" alt="Nikolai Murtazin">

---

## Contact Information

* **Email:** murtazinnikolai@gmail.com
* **GitHub:** [github.com/NikolaiMurtazin](https://github.com/NikolaiMurtazin)
* **LinkedIn:** [linkedin.com/in/NikolaiMurtazin](https://www.linkedin.com/in/nikolai-murtazin)
* **Discord:** nikolaimurtazin
* **Telegram:** @NikolaiMurtazin

---

## About Me

Highly motivated and results-driven aspiring Software Developer with a solid foundation in backend development 
(Java, Spring Boot, Microservices) and a keen interest in expanding into frontend technologies. My goal is to leverage 
analytical skills and a strong passion for continuous learning to build robust, scalable, and user-friendly applications. 
I am a proactive problem-solver, committed to writing clean, efficient code, and thrive in collaborative environments. 
Eager to apply my existing knowledge and quickly master new tools and frameworks to contribute effectively to innovative 
projects.

---

## Skills

* **Languages:** Java, HTML5, CSS3
* **Backend Technologies:** Spring, Hibernate, SQL, Maven, Rest, gRPC, Microservices
* **Version Control:** Git, GitHub
* **Tools & Environment:** VS Code, IntelliJIdea, WebStorm, Postman, Docker
* **Methodologies:** Agile principles, Scrum
* **Soft Skills:** Problem-Solving, Teamwork, Adaptability, Fast Learner, Attention to Detail

---

## Code Examples

### Codewars Task: Find The Parity Outlier

You are given an array (which will have a length of at least 3, but could be very large) containing integers. 
The array is either entirely comprised of odd integers or entirely comprised of even integers except for a single 
integer N. Write a method that takes the array as an argument and returns this "outlier" N.

```java
public class FindOutlier {
  static int find(int[] integers) {
    int evenCount = 0;
    
    for (int i = 0; i < 3; i++) {
      if (integers[i] % 2 == 0) evenCount++;
    }
    boolean majorityEven = evenCount >= 2;

    for (int num : integers) {
      if ((num % 2 == 0) != majorityEven) {
        return num;
      }
    }
    
    throw new IllegalArgumentException("No outlier found");
  }
}
```
Example Usage:

[2, 4, 0, 100, 4, 11, 2602, 36] --> 11 (the only odd number)

[160, 3, 1719, 19, 11, 13, -21] --> 160 (the only even number)

---

## Work Experience / Projects:

### 1. ExploreWithMe (EWM) Platform"

* **Description:** Developed a highly scalable event organization and discovery platform using a microservice architecture. This project modernized an existing monolithic application, preparing it for high loads and enhanced scalability. Key features include event search, organization, request management, user ratings, and analytics.
* **Skills Used:** Java, Spring Boot, Microservices, RESTful API, PostgreSQL, Docker, Git, Maven/Gradle, Unit/Integration Testing.
* **Repository:** [https://github.com/NikolaiMurtazin/java-plus-graduation](https://github.com/NikolaiMurtazin/java-plus-graduation)

### 2. Explore With Me (Microservices Version)

* **Description:** Implemented an event sharing and community-building application designed to connect users for various events. The project is structured as two distinct microservices, each with its own database: one for core business logic (event management, user interaction) and another for statistics and analytics, ensuring modularity and performance.
* **Skills Used:** Java, Spring Boot, Microservices, RESTful API, PostgreSQL, JUnit, Maven/Gradle, Git.
* **Repository:** [https://github.com/NikolaiMurtazin/java-explore-with-me-plus](https://github.com/NikolaiMurtazin/java-explore-with-me-plus)

### 3. Sharing Service (ShareIt)

* **Description:** Developed a backend service for a collaborative sharing application, enabling users to list, search for, and rent items. The service supports functionalities like item requests, user reviews, and managing item availability, facilitating a community-driven sharing economy.
* **Skills Used:** Java, Spring Boot, RESTful API, Hibernate, JPA, PostgreSQL, Docker, Lombok, JUnit, Git.
* **Repository:** [https://github.com/NikolaiMurtazin/java-shareit](https://github.com/NikolaiMurtazin/java-shareit)

### 4. Film Rate Service (Filmorate)

* **Description:** Created a RESTful API for a film rating social network. Users can register, add films to their libraries, rate films, add friends, and interact with other users' ratings. The service handles user management, film data, and social interactions, providing a backend for a rich user experience.
* **Skills Used:** Java, Spring Boot, RESTful API, Data Validation, JUnit, Git, Maven.
* **Repository:** [https://github.com/NikolaiMurtazin/java-filmorate](https://github.com/NikolaiMurtazin/java-filmorate)

---

## Education:

* **Moscow Aviation Institute / Technology and automation of material processing**
* **Moscow University of Finance and Law / State and municipal service**
* **Yandex Practicum Advanced Java Course**
* **Retraining of IT specialists Application development in Germany**

---

## Languages:

* **Russian:** native
* **German:** B2 (actively learning)
* **English:** A2–B1 (actively learning)
