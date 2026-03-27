# FoxCMS SQL Injection Vulnerability

foxcms<=1.2.6 has an SQL injection vulnerability in the executeCommand() method in app/admin/controller/DataBackup.php in the backend



$command passed by $param ['command '];

<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/dcfee5f8-238c-481b-b370-e607db2e5192" />

Follow up param method

<img width="1131" height="598" alt="image" src="https://github.com/user-attachments/assets/d9b5b6a8-492d-45df-a7d5-b01c3c750b6c" />

Post here for reference.

Click on a feature and grab a package.

<img width="1901" height="830" alt="image" src="https://github.com/user-attachments/assets/49a6fa1b-f42f-4a27-b9b8-6fdf2f92f128" />

Change the path to the package to executeCommand

<img width="1506" height="663" alt="image" src="https://github.com/user-attachments/assets/5cb06cf3-6b75-4c91-a553-355df53caaf1" />

Modify the parameters to:`SELECT DATABASE() AS db,USER() AS user,VERSION() AS ver` And perform URL encoding

<img width="1508" height="692" alt="image" src="https://github.com/user-attachments/assets/ec3de3c7-cec4-4074-8d43-b801458c7f17" />

Query database name, username, and version

<img width="1904" height="925" alt="image" src="https://github.com/user-attachments/assets/bcb76ca9-1fde-4d68-a5f9-4f0294c25bdf" />
<img width="1051" height="806" alt="image" src="https://github.com/user-attachments/assets/0fb9d53c-8ae8-4fdd-b1b4-6bed7e60db9c" />
