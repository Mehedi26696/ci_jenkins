# GitHub Connection with Jenkins

## 1. Create a Fine-Grained PAT Token

Set the required permissions and grant repository access.

![Create PAT Token](2.png)

![Set Permissions](2a.png)

Copy and save the generated PAT token.

![PAT Token](3.png)

---

## 2. Add Credentials in Jenkins

Navigate to Jenkins and add a new credential using the PAT token.

![Add Credential](4.png)

![Credential Details](4a.png)

---

## 3. Configure GitHub Repository in Jenkins

Copy the repository HTTPS URL.

![Copy HTTPS URL](5.png)

---

## 4. Create a New Freestyle Job

Set up a new Freestyle project in Jenkins.

![Create Freestyle Job](6.png)

---

## 5. Configure Source Code Management and Build Steps

Set up credentials in the Source Code Management section and configure the build command.

![Configure Source and Build](6a.png)

---

## 6. Build the Job

Trigger the build.

![Build Job](7.png)
![Build Progress](8.png)

---

## 7. Check Console Output

Review the console output for build logs and results.

![Console Output 1](9.png)
![Console Output 2](10.png)