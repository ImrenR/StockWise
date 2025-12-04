#  Stock Management App - StockWise

A full-featured Stock Management application built with React, Redux Toolkit, Formik, and Yup.  
This project demonstrates authentication, form validation, protected routes, reusable components, and state management in a clean folder structure.

---

##  Tech Stack

### Frontend
-  React + Vite
-  Redux Toolkit (authSlice)
-  Formik for form control
-  Yup for validation schema
-  Toastify for notifications
-  Private route protection

---

##  Project Structure Overview

```
src
├─ app/
│ └─ store.jsx
├─ assets/
├─ components/
│ ├─ AuthHeader.jsx
│ ├─ AuthImage.jsx
│ ├─ ErrorBoundary.jsx
│ └─ RegisterForm.jsx
├─ features/
│ └─ authSlice.jsx
├─ helper/
│ └─ ToastNotify.js
├─ pages/
│ ├─ Dashboard.jsx
│ ├─ Login.jsx
│ └─ Register.jsx
└─ router/
├─ AppRouter.jsx
└─ PrivateRouter.jsx
```
