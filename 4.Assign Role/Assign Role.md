# Assigning Roles to a User in Jenkins

This guide walks you through assigning roles to users in Jenkins using the Role-Based Authorization Strategy plugin.

---

## 1. Install the Role-Based Authorization Strategy Plugin

Go to **Manage Jenkins** → **Manage Plugins** and install the **Role-Based Authorization Strategy** plugin.

![Install Plugin](1.png)

---

## 2. Configure Security Settings

Navigate to **Manage Jenkins** → **Configure Global Security**.  
Set **Authorization** to **Role-Based Strategy**.

![Set Authorization](2.png)

---

## 3. Create a Global Role

Go to **Manage Jenkins** → **Manage and Assign Roles** → **Manage Roles**.  
Create a global role named `Developer` and assign the desired permissions.

![Create Role](3.png)
![Set Permissions](4.png)

---

## 4. Create a User

Navigate to **Manage Jenkins** → **Manage Users** → **Create User**.  
Create a user named `developer1` with appropriate credentials.

![Create User](5.png)
![User Details](6.png)
![User Created](7.png)

---

## 5. Assign Role to User

Go to **Manage Jenkins** → **Manage and Assign Roles** → **Assign Roles**.  
Assign the `Developer` role to the user `developer1`.

![Assign Role](8.png)
![Role Assigned](9.png)

---

## 6. Verify User Permissions

Log in as `developer1`.  
You will notice that the user has limited access based on the assigned role.

![Login as Developer1](10.png)
![Limited Features](11.png)
![Restricted Access](12.png)

---

**Note:**  
Assigning roles helps enforce security and restricts users to only the permissions they need.