# Complete Jenkins Setup Guide for Windows

This guide provides step-by-step instructions to install and set up Jenkins on Windows.

## 1. Download Jenkins

- Go to the official Jenkins download page: [https://www.jenkins.io/download/](https://www.jenkins.io/download/)
- In the **Windows** section, download the **LTS** (Long-Term Support) release installer.

<img src="1.png" alt="Jenkins Download Page" width="600">
<img src="2.png" alt="Jenkins Installer" width="600">

## 2. Install Jenkins

- Run the downloaded installer and follow the prompts.

<img src="2a.PNG" alt="Jenkins Installer" width="600">

- When asked, specify the path to your JDK 17 or 21 installation (Jenkins requires one of these versions).

<img src="3.PNG" alt="JDK Selection" width="600">

- Choose **Run service as LocalSystem**.

<img src="4.PNG" alt="Service Account Selection" width="600">

- Set the port for Jenkins (default is 8080).

<img src="5.PNG" alt="Port Selection" width="600">

## 3. Initial Jenkins Setup

- After installation, open your browser and go to [http://localhost:8080](http://localhost:8080).

<img src="6.png" alt="Jenkins Welcome Page" width="600">

- On the Jenkins welcome page, you will be prompted to unlock Jenkins.
- Locate the initial admin password in the file specified on the screen (usually at `C:\Program Files\Jenkins\secrets\initialAdminPassword`).
- Copy and paste this password into the input box to proceed.

<img src="7.png" alt="Unlock Jenkins" width="600">

## 4. Install Plugins

- Follow the prompts to install recommended plugins.

<img src="8.png" alt="Plugin Installation" width="600">
<img src="9.png" alt="Plugin Installation Progress" width="600">

## 5. Create Admin User

- Set up your first admin user.

<img src="10.png" alt="Create Admin User" width="600">

- Sign in with your new admin credentials.

<img src="10a.png" alt="Sign In" width="600">

## 6. Jenkins Home Page

- You will be redirected to the Jenkins home page.

<img src="11.png" alt="Jenkins Home Page" width="600">

## 7. Create a Demo Job

- Create a new job to test your Jenkins setup.

<img src="12.png" alt="Create Job" width="600">
<img src="13.png" alt="Job Configuration" width="600">
<img src="14.png" alt="Job Build" width="600">
<img src="15.png" alt="Job Success" width="600">

---

You have now completed the Jenkins installation and initial setup on Windows.