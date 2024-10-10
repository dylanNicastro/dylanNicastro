```java
public class DylanNicastro {
    String name;
    int age;
    String university;
    boolean lookingForInternship;
    String[] learned;
    String[] currentlyLearning;

    public DylanNicastro() {
        this.name = "Dylan Nicastro";
        this.age = 19;
        this.university = "Stony Brook University";
        this.lookingForInternship = true;

        this.learned = new String[] {"C", "Java", "Python", "Javascript", "HTML", "CSS"};
        this.currentlyLearning = new String[] {"React", "Node.js", "MongoDB", "Express"};
    }

    @Override
    public String toString() {
        return "Welcome to my GitHub profile! I'm a student who enjoys writing code, playing videogames, and learning new things.";
    }
}
```