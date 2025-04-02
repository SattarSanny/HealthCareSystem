## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 🕸️ [Snippets (Code to Copy)](#snippets)  
6. 🔗 [Assets](#links)  
7. 🚀 [More](#more)

## 🤖 Introduction

A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors. It includes administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications — all built using Next.js.

## ⚙️ Tech Stack

- Next.js  
- Appwrite  
- TypeScript  
- TailwindCSS  
- ShadCN  
- Twilio  

## 🔋 Features

👉 **Register as a Patient**: Users can sign up and create a personal profile as a patient.  
👉 **Book a New Appointment with Doctor**: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.  
👉 **Manage Appointments on Admin Side**: Administrators can efficiently view and handle all scheduled appointments.  
👉 **Confirm/Schedule Appointment from Admin Side**: Admins can confirm and set appointment times to ensure they are properly scheduled.  
👉 **Cancel Appointment from Admin Side**: Administrators have the ability to cancel any appointment as needed.  
👉 **Send SMS on Appointment Confirmation**: Patients receive SMS notifications to confirm their appointment details.  
👉 **Complete Responsiveness**: The application works seamlessly on all device types and screen sizes.  
👉 **File Upload Using Appwrite Storage**: Users can upload and store files securely within the app using Appwrite storage services.  
👉 **Manage and Track Application Performance Using Sentry**: The application uses Sentry to monitor and track its performance and detect any errors.  

...and many more, including code architecture and reusability.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:

- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/en)  
- [npm](https://www.npmjs.com/)  

### Cloning the Repository

```bash
git clone https://github.com/adrianhajdin/healthcare.git
cd healthcare
```

### Installation

```bash
npm install
```
 Or
```
npm i next@latest
```


### Set Up Environment Variables

Create a `.env.local` file in the root of your project and add:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

> Replace placeholders with your actual Appwrite credentials. Sign up on [Appwrite](https://appwrite.io/) to get them.

### Running the Project

```bash
npm run dev
```

Go to [http://localhost:3000](http://localhost:3000) in your browser.

## 🕸️ Snippets

You can find useful configuration and styling snippets in the corresponding files such as:

- `tailwind.config.ts`  
- `app/globals.css`  
- `types/index.d.ts`  
- `types/appwrite.types.ts`  
- `lib/utils.ts`  
- `lib/validation.ts`  
- `constants/index.ts`

## 🔗 Assets

Public assets used in the project can be downloaded from:  
[Google Drive Link](https://drive.google.com/file/d/1yGvWFeSaH1_-aiQ1gejT23lqz5979RKB/view?usp=sharing)

## 🚀 More

Advance your skills by exploring deeper into the technologies used here. Whether it's Appwrite, Twilio, or building scalable systems in Next.js — this project is a great foundation to build on.
