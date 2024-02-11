# Symfony Evaluation Form Application

This Symfony application allows you to create evaluation forms for assessing trainees at the end of their training programs. Trainees can provide feedback by filling out the evaluation form, and the data submitted will be stored in a database. Additionally, the application generates a PDF report for each evaluation, which is then archived in a designated folder.

## Features

- **Evaluation Form:** Trainees can fill out the evaluation form providing details such as name, date of evaluation, training program attended, and ratings on various aspects of the training program.
- **PDF Generation:** Upon form submission, the application generates a PDF report named "Eval-lastname-firstname-date.pdf" using DomPDF library, summarizing the evaluation details.
- **Database Storage:** Evaluation data is stored in a database, allowing for easy access and retrieval of evaluation records.
- **Archiving:** The PDF reports are archived in a designated folder for record-keeping and future reference.