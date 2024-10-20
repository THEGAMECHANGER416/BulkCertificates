# Geek Room Certificate Sender

https://github.com/user-attachments/assets/5f6d65fc-f2bc-414d-9441-a913aee08a3a

## Instructions for Use

#### Overview
This guide will help you set up and use a Streamlit application to send personalized emails with Google Slides presentations. Each presentation will be customized with the recipient's full name.

#### Step 1: Create Google Slides Presentation
1. Go to [Google Slides](https://slides.google.com).
2. Create a new presentation. Adjust the aspect ratio from `File > Page Setup`.
3. Set the certificate image as the presentation background.
4. Add a text box where you want the full name to appear.
5. In the text box, add the placeholder `{{Full_Name}}` where you want the name to be replaced.
6. Save the presentation and copy presentation URL (it looks like `https://docs.google.com/presentation/d/<presentation_id>/edit`).
7. Ensure that the email `geekroom-cerificates@bulkcertificates.iam.gserviceaccount.com` has been given "Editor" access to the Google Slides presentation.

#### Step 2: Prepare Your CSV File
1. Open a text editor or spreadsheet application (like Excel or Google Sheets).
2. Create a new file and add the following headers in the first row:
   ```
   Full Name,Email
   ```
3. Fill in the rows with the recipients' full names and email addresses. For example:
   ```
   John Doe,johndoe@example.com
   Jane Smith,janesmith@example.com
   ```
4. Save and upload the file.

#### Step 3: Generate Preview
1. Click on "Edit Mail" and Customize the subject and body.
2. Generate a preview

#### Step 4: Start Sending Emails
1. Click the button to start the email sending process.
2. Monitor the progress as emails are sent out with the personalized presentations.
