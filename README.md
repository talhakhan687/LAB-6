PROBLEM 1


public class Person {
    private String name;
    private int age;
    private String gender;
    private String address;

    public Person(String name, int age, String gender, String address) {
        this.name = name;
        this.age = age;
        this.gender = gender;
        this.address = address;
    }

    public Person() {
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public String getGender() {
        return gender;
    }

    public void setGender(String gender) {
        this.gender = gender;A
    }
    
    public String getAddress() {
        return address;
    }

    public void setAddress(String address) {
        this.address = address;
    }

    public void displayPersonInfo() {
        System.out.println("Name: " + getName());
        System.out.println("Age: " + getAge());
        System.out.println("Gender: " + getGender());
        System.out.println("Address: " + getAddress());
    }

    public static void main(String[] args) {
     
        Person person1 = new Person("Roza", 21, "Male", "dhaka");
        
        System.out.println("Details of person1:");
        person1.displayPersonInfo();

        Person person2 = new Person();
        
        person2.setName("Ahona");
        person2.setAge(19);
        person2.setGender("Female");
        person2.setAddress("DMD");

        System.out.println("\nDetails of person2:");
        person2.displayPersonInfo();
    }
}






PROBLEM 2

public class Employee {
    
    private String name;
    private int id;
    private double salary;
    private String designation;

    public Employee(String name, int id, double salary, String designation) {
        this.name = name;
        this.id = id;
        this.salary = salary;
        this.designation = designation;
    }

    public Employee() {
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public double getSalary() {
        return salary;
    }
    public void setSalary(double salary) {
        this.salary = salary;
    }

    public String getDesignation() {
        return designation;
    }

    public void setDesignation(String designation) {
        this.designation = designation;
    }

    public void displayEmployeeInfo() {
        System.out.println("Employee ID: " + getId());
        System.out.println("Name: " + getName());
        System.out.println("Salary: $" + getSalary());
        System.out.println("Designation: " + getDesignation());
    }

    public static void main(String[] args) {
       
        Employee emp1 = new Employee("lim", 011, 6700.50, "mac eng");

        System.out.println("Details of emp1:");
        emp1.displayEmployeeInfo();

        Employee emp2 = new Employee();
        
        emp2.setName("telha");
        emp2.setId(222);
        emp2.setSalary(6000);
        emp2.setDesignation("Data scientist");

        System.out.println("\nDetails of emp2:");
        emp2.displayEmployeeInfo();
   }
}
