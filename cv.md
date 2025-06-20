# Nikolai Murtazin

<img src="images/NikolaiMurtazin.jpg" width="150" alt="Nikolai Murtazin">

---

## Contact Information

* **Email:** murtazinnikolai@gmail.com
* **GitHub:** [github.com/NikolaiMurtazin](https://github.com/NikolaiMurtazin)
* **LinkedIn:** [linkedin.com/in/NikolaiMurtazin](https://www.linkedin.com/in/nikolai-murtazin)
* **Discord:** nikolaimurtazin
* **Telegram:** @NikolaiMurtazin

---

## About Me


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