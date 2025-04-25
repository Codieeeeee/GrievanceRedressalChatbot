# Grievance Redressal Chatbot

The **Grievance Redressal Chatbot** is a versatile application designed to simplify the process of submitting, tracking, and resolving grievances. It combines a chatbot interface with backend processing to provide an efficient and user-friendly solution for grievance management. This project can be adapted for various platforms, including web, desktop, or even mobile applications.

---

## Features

### General Features:
- **Chatbot Interaction**: Users can interact with a chatbot to describe their grievances in natural language.
- **Complaint Submission**: Users can submit complaints with details such as name, email, address, and optional image uploads.
- **Complaint Tracking**: Users can track the status of their complaints using a unique ticket number.

### Backend Features:
- **Complaint Management**: Complaints are stored in a database and categorized for easy management.
- **Status Updates**: Complaints can be updated with statuses like Pending, In Progress, or Resolved.
- **Department Classification**: Complaints are automatically routed to the appropriate department based on their content.
- **Analytics and Reporting**: Generate reports and view statistics for better decision-making.


## Technologies Used

### Core Technologies:
- **Python**: For backend logic and chatbot processing.
- **Flask**: For API development (can be replaced with other frameworks if needed).
- **MySQL**: For database management.

### Other Tools:
- **HTML/CSS/JavaScript**: For web-based interfaces.
- **CLIP Model**: For image relevance verification.
- **Google Generative AI**: For complaint classification.
- **Geopy**: For reverse geocoding GPS data from images.
