Date:19-04-2026
Day: 1
Topic:Creating class and object
Video link: https://youtu.be/lWFzm8qIR1c?si=Vc-Fj2kYjAw31AKB

Example-1:Student.java

public class Student {
    String name;
    int age;

    void display() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}

public class Main {
    public static void main(String[] args) {
        Student s1 = new Student();
        s1.name = "Rahim";
        s1.age = 20;
        s1.display();
    }
}


Example-2: Mobile.java
public class Mobile {
    String brand;
    void showBrand() {
        System.out.println("Mobile Brand: " + brand);
    }
}
public class Main {
    public static void main(String[] args) {
        Mobile m1 = new Mobile();
        m1.brand = "Samsung";
        m1.showBrand();
    }
}
