# Blood Bank System Installation Guide  

Follow the steps below to set up and run the **Blood Bank System** on your local machine:  

## Prerequisites  
Before proceeding, ensure you have the following installed:  
1. [XAMPP](https://www.apachefriends.org/index.html)  
2. A text editor like [Notepad++](https://notepad-plus-plus.org/) or [Sublime Text 3](https://www.sublimetext.com/).  

## Installation Steps  
1. **Download the Blood Bank System:**  
   - Download the project zip file.  
   - If not already installed, download and install [WinRAR](https://www.win-rar.com/start.html?&L=0) or a similar tool to extract files.  

2. **Extract Files:**  
   - Extract the downloaded zip file.  
   - Copy the extracted folder named `Blood Bank System`.  

3. **Set Up the Root Directory:**  
   - Navigate to your XAMPP installation directory (e.g., `C:\xampp\htdocs`).  
   - Paste the `Blood Bank System` folder inside the `htdocs` directory.  

4. **Set Up the Database:**  
   - Open [phpMyAdmin](http://localhost/phpmyadmin) in your browser.  
   - Create a new database with the name `bloodbank_db`.  
   - Import the `bloodbank_db.sql` file:  
     - Locate this file inside the extracted project folder under `SQL File`.  
     - Use the **Import** option in phpMyAdmin to upload the `.sql` file.  

5. **Run the Application:**  
   - Open your browser and navigate to `http://localhost/bloodbank`.  

## Login Credentials  

Use the following credentials to access the system:  

**Admin**  
- **Username:** `admin`  
- **Password:** `admin123`  
