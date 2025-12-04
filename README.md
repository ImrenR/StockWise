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


---

##  Features

###  Authentication
- Register & Login functionality
- Form validation using Yup
- Password requirements enforced
- Auth state stored using Redux Toolkit

###  Form Handling
- Inputs managed via Formik
- Field-level and schema-level error handling
- Real-time error messages

###  Protected Routes
- Only authenticated users access dashboard
- Implemented through `PrivateRouter`

###  Redux State Flow
- Auth state inside `authSlice.jsx`
- Dispatch actions from form components
- Access state in `AppRouter.jsx`

---

##  Pages

| Page | Description |
|--------|-------------|
| `Register.jsx` | New user registration with Yup validation |
| `Login.jsx` | User authentication |
| `Dashboard.jsx` | Protected area after login |

---

##  How to Run


pnpm install
pnpm run dev


---

## Future Enhancements

- Add API integration for product CRUD

- Add stock listing page

- Add search & filter options

- Add user roles