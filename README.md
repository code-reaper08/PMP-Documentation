# The Project Management Portal of Sathyabama Institute of Science and Technology

This makes the process of managing and tracking projects much simple and easy. This also encourages the use of GitHub to leverage project tracking potentials without reinventing the wheel. Project Management Portal will be a one stop point, where faculties can be assigned and they can track the student's projects. The application follows a top-down role heirarchy structure to allow controlled access. This makes the application error prone and safe.

The Portal is divided into three parts,

```
1. Admin side
2. Faculty side
3. Student side
```

## Admin side
Admin side is the most powerful part of the application. This has the provisions to CRUD on every entity using a Single Login Credentials. The Admin side is built with completely Open-Source techstack and it's stable. The admin side also has a intuituve UI to handle complex tasks. Admin side is used to create next level hierarchic entities such as faculties. Usually handled by a tech-team.

## Faculty side
Faculty side contains a dashboard, where faculties can track and manage all the projects they are involved in. This also include abilities such as,

```
a) add a student to the portal
b) remove a student from a portal
c) edit project details and team
d) edit student details
e) set deadline for the projects
f) delete a project from the portal
```

## Student side
Student side is the least of the heirarchical access control, the student side will also contain a respective dashboard to view and manage the projects.

Operations available when typing,

```
a) Create a new project
b) Choose faculty-in-charge
```

Operations after creating a project

```
a) Update the project description
b) Update GitHub link
c) Update Completion status
```

## Faculty side FAQ's

### **How to Access**
Navigate to the `Login` page using the navbar at top.

![Login page](https://user-images.githubusercontent.com/64256342/179232015-a08d8383-025d-40b8-9e27-73fa9133f3b2.png)

Fill in the credentials and you access the dashboard.

### **How to add a new student to the portal**
Click on the `control dock` on the top-right corner. Click on `Add a new student to the Portal` button.

![image](https://user-images.githubusercontent.com/64256342/179233287-64260d5f-dbb2-416f-be5a-4d26251bd391.png)

Fill the student creation form and create a password for that student. Share the password to that particular student, so that they can access the portal at their end.

### **How to delete/permanently remove a student from the portal**

To delete a student from the portal, click on `control dock`. Click on `Remove a student from the portal` button

![image](https://user-images.githubusercontent.com/64256342/179234248-44790ddf-927e-4ffa-a105-0cafc4e05c8f.png)

In the dropdown select the student whom you want to be deleted/removed, and click on the `Remove this student from the portal` button to confirm.

### **How to edit student details**

The student data can be edited by the faculty at any point of time. This makes it easy to update username and email address.
Click on `Edit student detail` from the `control dock`. Select the student whose data to be updated. Fill in the new details and press `Save student details`.

![image](https://user-images.githubusercontent.com/64256342/179235130-30de1270-ec51-4722-81e3-331616aea187.png)

### **Setting deadline for the project**
Click on the `Set Deadline` button the project item, click on a specific date using the date-picker and click on `set deadline` button to confirm the date. One can use the same flow as this to update deadline, once it is set using the `Update Deadline` button.

![image](https://user-images.githubusercontent.com/64256342/179235877-db27d106-5a62-4672-bb34-6d07508dc8b5.png)
![image](https://user-images.githubusercontent.com/64256342/179235996-8828ef30-15db-41a0-b814-bff7e1517490.png)
