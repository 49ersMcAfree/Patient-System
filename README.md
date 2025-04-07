# iCARE System

**Course**: CS4320-7320: Software Engineering I  
**Authors**: Group 14  
**Semester**: Fall 2024  

## Introduction

The iCARE System is a healthcare application designed to assist healthcare providers by managing patient records, automating documentation processes, and enabling easy access to patient data. This project applies core software engineering principles to create an efficient and user-friendly healthcare management system.

## Features

- **User Authentication**: Secure login using digital ink or text entry.
- **Patient Management**: Allows workers to view and assign themselves to patients.
- **Account Management**: Administrators can create and manage user accounts with role-based permissions.
- **Document Management**: Enables workers to create and edit PDF documents attached to patient records.
- **Image Importing**: Provides tools to import and convert images into PDFs for patient files.

#Here is an in depth description in how each component of this application works
- My Palette
  - When the user lands on this page, they will be prompted with 2 options. They can either lookup documents, or add a document. When selecting "View Documents", the user will be redirected to a page where they can lookup all the available documents underneath a patient's name. The User will have to type in a patient's name and press the "Submit" button to display the documents that belong to that patient. When selecting "Add Documents", the user will be redirected towards a page where they can add documents to a specific patient. When on this page, the user will have to type in the name of the patient, the type of document they want to add, the name of the document, and finally drop the document file itself. After all of these fields are filled, the user will press the submit button to add this document to the system's file system. 
