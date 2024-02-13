## Employee List Application

For the application to work, the file calisanlardb.sql located in the root directory must be included in phpMyAdmin.

Enter phpMyAdmin and create a new database. Let's name the database we have created as calisanlarprojesidb.

![sinanozcelik.com](img/1.jpg)

Then, let's import the calisanlarprojesidb.sql file in our project file into the database we have created.

![sinanozcelik.com](img/2.jpg)

As the last step, let's open the /src/database.java file in edit mode and fill in the necessary information for the database according to you.

```java
public class Database {

  public static final String kullanici_adi = "root";    // Your phpMyAdmin username
  public static final String parola = "sinan123";       // Your phpMyAdmin password

  public static final String db_ismi = "calisanlarprojesidb";   // Database name

  public static final String host = "localhost";

  public static final int port = 3306;
}

```

Username to login to the application: admin

User password to login to the application: admin

## <img src="https://user-images.githubusercontent.com/74038190/235294019-40007353-6219-4ec5-b661-b3c35136dd0b.gif" width="30" style="margin-bottom: -5px;"> Contact Information

You can reach out to me using the following contact details:

[![Email](https://img.shields.io/badge/Email-sinanozcelik%40yaani.com-brightgreen)](mailto:sinanozcelik@yaani.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sinan--ozcelik-blue)](https://www.linkedin.com/in/sinan-ozcelik/)

I'm always open to development and collaboration. Feel free to reach out to me!
