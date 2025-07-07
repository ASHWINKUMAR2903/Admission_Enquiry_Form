# Admission_Enquiry_Form
## Date: 07.07.2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Enquiry Form</title>
</head>
<body>
    <h1 align="center"> Admission Enquiry </h1>
    <form align="center">
        <label>Full Name</label>
        <input type="text" placeholder="User Name" required> <br><br>

        <label>Email Address</label>
        <input type="Email" placeholder="Email" required> <br><br>

        <label>Phone Number</label>
        <input type="tel" placeholder="PhoneNumber" required> <br><br>

        <label>Gender</label>
        <input type="radio" name="Gender" title="Gender" required>Male
        <input type="radio" name="Gender" title="Gender" required>Female <br><br>
        
        <label>Date of Birth</label>
        <input type="date" placeholder="YYYY-MM-DD" required> <br><br>

        <label>Department Interested</label>
        <select title="Department Interested" required>
            <option value="">Select option</option>
            <option value="CSE">CSE</option>
            <option value="ECE">ECE</option>
            <option value="MECH">MECH</option>
            <option value="IT">IT</option>
        </select><br><br>

        <label>Academic Qualification</label>
        <input type="Text Area" placeholder="Academic details" required> <br><br>

        <label>Address</label>
        <input type="Text Area" placeholder="Address details" required> <br><br>

        <label>Preferred Mode of Contact :</label>
        <input type="Checkbox" name="contact" title="contact">PhoneNumber
        <input type="Checkbox" name="contact" title="contact">Email <br><br>

        <input type="submit" value="Submit" align="center">
        <input type="reset" value="Clear Form">
    </form>
</body>
</html>
```
## Output:
![image](https://github.com/user-attachments/assets/6cdeae32-0de2-4992-b0b2-e2f08e5b671f)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
