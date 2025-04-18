# TASK-8 DAY-8
# TASK 8: Java Maven Build Job using Jenkins

## Tools & Technologies Used

- Jenkins
- Java JDK 8 or 11
- Apache Maven
- Git & GitHub
- Ubuntu/Linux

## Source Code

### Hello.java
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Jenkins + Maven!");
    }
}
```
### pom.xml
```xml
<project>
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.example</groupId>
  <artifactId>hello</artifactId>
  <version>1.0</version>
  <build>
    <plugins>
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-compiler-plugin</artifactId>
        <version>3.8.1</version>
        <configuration>
          <source>1.8</source>
          <target>1.8</target>
        </configuration>
      </plugin>
    </plugins>
  </build>
</project>
```
## Jenkins Configuration

- Go to **Manage Jenkins** → **Global Tool Configuration**
- Add Maven (e.g., **Maven 3.8.6**)
- Add JDK (e.g., **Java 8 or 11**)

---

## Freestyle Job Setup

- **Project Name**: `hello-java-maven-task`

### Source Code Management

- **Git**
- **Repository URL**:  
  `https://github.com/Srireddy88/hello-java-maven.git`
  ![Screenshot 2025-04-18 161242](https://github.com/user-attachments/assets/546c52de-25bf-4bc1-9b5b-61c06ad88096)


![Screenshot 2025-04-18 151110](https://github.com/user-attachments/assets/7406660f-b532-4a1d-8ee0-cbe8f06f4d11)

![Screenshot 2025-04-18 154935](https://github.com/user-attachments/assets/15bcc3b6-7a48-45db-b05e-8029e1c2752d)
![Screenshot 2025-04-18 154944](https://github.com/user-attachments/assets/ec5d1198-ad15-40c7-8f68-1d742290b88a)
![Screenshot 2025-04-18 155003](https://github.com/user-attachments/assets/045774c1-f686-41af-929b-384610108a5d)
## After making chages to the Hello.java file 
![Screenshot 2025-04-18 160904](https://github.com/user-attachments/assets/7364d4ea-02f3-4bf1-8868-b30b0eedee5a)
![Screenshot 2025-04-18 160919](https://github.com/user-attachments/assets/d504e95c-ba1c-4bd6-909d-9ca0194a8166)


