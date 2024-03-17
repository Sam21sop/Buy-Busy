# BusyBuy E-commerce Project Documentation


## Project Overview
BusyBuy is a web application for an e-commerce business that allows customers to browse available products, add or remove them from their shopping cart, and complete the purchasing process.


## Project Structure
```
busybuy-app/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── assets/
│   │   ├── images/
│   │   └── ...
│   │
│   ├── components/
│   │   ├── Auth/
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── ...
│   │   │
│   │   ├── Cart/
│   │   │   ├── CartItem.js
│   │   │   ├── CartPage.js
│   │   │   └── ...
│   │   │
│   │   ├── Common/
│   │   │   ├── Spinner.js
│   │   │   ├── Toast.js
│   │   │   └── ...
│   │   │
│   │   ├── Home/
│   │   │   ├── FilterSidebar.js
│   │   │   ├── HomePage.js
│   │   │   ├── ProductCard.js
│   │   │   └── ...
│   │   │
│   │   ├── Order/
│   │   │   ├── OrderItem.js
│   │   │   ├── OrderPage.js
│   │   │   └── ...
│   │   │
│   │   └── ...
│   │
│   ├── contexts/
│   │   ├── AuthContext.js
│   │   ├── CartContext.js
│   │   └── ...
│   │
│   ├── services/
│   │   ├── firebase.js
│   │   └── ...
│   │
│   ├── App.js
│   ├── index.js
│   └── ...
│
├── .gitignore
├── package.json
└── README.md
```


## Technology Used

1. [React](https://react.dev/reference/react) : Frontend JavaScript library for building user interface components.
2. [React-Context API](https://react.dev/reference/react/createContext) : For managing user authentication and product state.
3. [React Router](https://reactrouter.com/en/main/start/tutorial) : For client-side routing.
4. [Firebase](https://firebase.google.com/docs) : For database management.
5. [React Toastify](https://fkhadra.github.io/react-toastify/introduction/) : For displaying toast messages.
5. [React Spinners](https://www.davidhu.io/react-spinners/) : For showing loading states.
5. [Tailwind CSS](https://tailwindui.com/documentation) : For styling application.

## Project Setup
1. Create a new React.js project with vite
    ```bash
    npm create vite@latest buybusy

2. Initialize Firebase
    - Go to the Firebase Console and create a new project.
    - Enable Firestore and Authentication services for your project.
    - Follow the instructions to set up the Firebase SDK in your React.js project.

3. Install required dependencies
    ```bash 
    npm install react-router-dom firebase react-spinners react-toastify

4. install Devdependencies
    - add tailwind CSS to project
        ```bash
        npm install -D tailwindcss postcss autoprefixer

    - initialize tailwind config file
        ```bash 
        npx tailwindcss init -p
    
    - [Further Configuration](https://tailwindcss.com/docs/guides/vite)

