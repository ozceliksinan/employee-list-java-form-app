<div align="center">
  <img src="img/icon.png" alt="Employee List Application" width="100" height="100">
</div>

## <img src="img/visual-studio.gif" width="30" style="margin-bottom: -5px;"> Employee List Application

For the application to work, the file calisanlardb.sql located in the root directory must be included in phpMyAdmin.

Enter phpMyAdmin and create a new database. Let's name the database we have created as calisanlarprojesidb.

![sinanozcelik.com](img/1.jpg)

Then, let's import the calisanlarprojesidb.sql file in our project file into the database we have created.

![sinanozcelik.com](img/2.jpg)

As the last step, let's open the /src/database.java file in edit mode and fill in the necessary information for the database according to you.

```java
public class Database {

  public static final String kullanici_adi = "root";           // PhpMyAdmin username
  public static final String parola = "sinan123";              // PhpMyAdmin password
  public static final String db_ismi = "calisanlarprojesidb";  // Database Name
  public static final String host = "localhost";               // Server Name
  public static final int port = 3306;                         // Server Port
}
```

Authentication Informations:

```
Username: admin
Password: admin
```

## <img src="img/code.webp" width ="25" style="margin-bottom: -5px;"> Build With

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![NetBeans IDE](https://img.shields.io/badge/NetBeansIDE-1B6AC6.svg?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

## <img src="img/whatsapp.gif" width="30" style="margin-bottom: -5px;"> Contact Information

You can reach out to me using the following contact details:

[![Email](https://img.shields.io/badge/Email-info%40sinanozcelik.com-brightgreen)](mailto:info@sinanozcelik.com)

[![Website](https://img.shields.io/badge/Website-sinanozcelik.com-blue)](https://sinanozcelik.com)

I'm always open to development and collaboration. Feel free to reach out to me!