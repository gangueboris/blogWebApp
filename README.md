## 🤖 Introduction
This is a fully fonctionnal blog app that I made to learn more about php and mysql. this is my first project made with WAMP stack. I hope you will have fun in testing.

![image](https://github.com/user-attachments/assets/cbc77310-9f91-414c-8fb3-f2bb831e1860)

![image](https://github.com/user-attachments/assets/1af69555-4c4d-4280-8668-842cd51f732c)

![image](https://github.com/user-attachments/assets/fd3f8617-9828-4712-a0a5-ea39d3933903)


## ⚙️ Tech Stack

### Frontend
- HTML: Structure and content
- CSS:  Styling and layout
- JavaScript: Interactivity and dynamic content

### Backend:
- PHP: Server-side scripting and backend logic
  
### Database:
- MySQL: Data storage and management

## 🔋 Features
### 1. Core Features
- Create, read, update, and delete (CRUD) blog posts
- User authentication (login/register)
- Post categories
- Post search functionality
- Featured posts section

  
### 2. User Management
- User profiles (bio, avatar)
- Author pages with listed posts
- Role-based access control (admin, guest)
  
### 3. Post Management
- Edit post


## 🤸 Quick Start
#### 1. Move the Folder to WAMP Directory
- Copy the entire project folder and paste it into WAMP's www directory : ```C:\wamp64\www\your_project_folder```

#### 2. Set Up the Database
- Open your web browser and go to: ```http://localhost/phpmyadmin```
- Login with user : ```Boris``` and password: ```admin1234```
- Create a database 'blog', and upload the SQL dump (blog-tables.sql) found in the extracted folder
  
#### 3. Configure Project Files
- Open the ```httpd-vhosts.conf``` file from ```C:\wamp64\bin\apache\apache2.4.51\conf\extra\``` and append this
 ```
  <VirtualHost *:80>
      ServerName blogApp
      DocumentRoot "c:/wamp64/www/blog-web-app"
</VirtualHost>
```
- Open the ```hosts``` file from ```C:\Windows\System32\drivers\etc\``` and append ```127.0.0.1 blogApp```

#### 4. Run the project locally
- Open your browser and enter the project’s local URL: ```http://localhost/blog```





Note:  The credentials of all users registered can be found in the zip file (registered-user-credentials.txt). Use any to log in to the application, and have fun!
