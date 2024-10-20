<a id="top"></a>
<h1 align="center">🧭 DFS-BFS Graph Traversal</h1>

This project implements **Depth-First Search (DFS)** and **Breadth-First Search (BFS)** algorithms for graph traversal. The backend includes user authentication functionality with a **Login** and **Signup** page. The project currently stores user data in **local storage**.

<hr>

 <details>
   <summary><h2>📑 Table of Contents</h2></summary>

### 🔮 Future Upgrades Await
This is just the beginning! With plans to incorporate advanced algorithms (Dijkstra's, A*) 🧠, user dashboards 📊, and mobile-friendly features 📱, we’re on the path to making this project an indispensable tool for graph lovers everywhere.

<img src="https://raw.githubusercontent.com/alo7lika/DFS-BFS-Graph-Travers/refs/heads/master/Images/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

### This project is now OFFICIALLY accepted for

<div align="center">
  <img src="https://raw.githubusercontent.com/alo7lika/DFS-BFS-Graph-Travers/refs/heads/master/Images/329829127-e79eb6de-81b1-4ffb-b6ed-f018bb977e88.png" alt="GSSoC 2024 Extd" width="80%">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/alo7lika/DFS-BFS-Graph-Travers/refs/heads/master/Images/hacktober.png" alt="Hacktober fest 2024" width="80%">
</div>

<br>

<!--Line-->
<img src="https://raw.githubusercontent.com/alo7lika/DFS-BFS-Graph-Travers/refs/heads/master/Images/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">


## 📑 Table of Contents


1. 🌟 [Features](#-features)
2. 🛠️ [Technical Stack](#-technical-stack)
3. 📝 [Changelog](#-changelog)
4. 📂 [Project Structure](#-project-structure)
5. ⚙️ [Prerequisites](#-prerequisites)
6. 🚀 [How to Set Up and Run the Project](#-how-to-set-up-and-run-the-project)
7. 🧪 [Testing Instructions](#-testing-instructions)
8. 🔐 [Login and Signup Pages](#-login-and-signup-pages)
9. 🖥️ [How the Server Works](#-how-the-server-works)
10. 📊 [Graph Feature](#-how-the-graph-feature-works)
11. 🗺️ [Roadmap](#-roadmap)
12. 🤝 [Contributing](#-contributing)
13. 👥 [Contributors](#-our-contributors)

</details>

<hr>

## 🌟 Features

- 🔑 User **Login** and **Signup** system
- 🔍 DFS and BFS graph traversal algorithms
- 💾 Data persistence using **LocalStorage**
- 🖥️ Frontend built with **Angular**
- 🔧 Backend using **Node.js** with **Express.js**

---
## 🛠️ Technical Stack

| **Component**        | **Technology**                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Frontend**         | Angular 🅰️                                                                    |
| **Backend**          | Node.js 🟢, Express.js ⚙️                                                    |
| **Authentication**   | LocalStorage 🔒 (with plans to integrate OAuth 🔑)                            |
| **Database**         | LocalStorage for user data 💾 (future plans for database integration 📊)      |
| **Graph Algorithms** | DFS and BFS implemented for traversal 📈                                      |
| **Deployment**       | Netlify configuration for frontend 🌐 
---

## 📝 Changelog

### Version 1.0.0 (Initial Release)
- Implemented **DFS** and **BFS** graph traversal algorithms. 🔍
- Added **Login** and **Signup** pages with user data stored in **LocalStorage**. 🔑
- Basic project structure setup with Angular for the frontend and Node.js/Express.js for the backend. 🏗️


---

## 📂 Project Structure

```bash
.vscode/                    # Contains workspace settings for VSCode
backend/                    # Backend directory (Node.js/Express)
public/                     # Public assets like images, logos, etc.
src/                        # Angular application source code
.editorconfig               # Editor configuration for consistent coding style
.gitignore                  # Git ignore file to exclude certain files from being committed
CODE_OF_CONDUCT.md          # Code of conduct for contributors
CONTRIBUTING.md             # Guidelines for contributing to the project
README.md                   # Project documentation file
angular.json                # Angular workspace configuration
netlify.toml                # Configuration for deploying to Netlify
package-lock.json           # Locked versions of installed npm dependencies
package.json                # Project metadata and npm dependencies
tsconfig.app.json           # TypeScript configuration for the app
tsconfig.json               # General TypeScript configuration
tsconfig.spec.json          # TypeScript configuration for testing
```

---

## ⚙️ Prerequisites

Make sure you have the following installed before running the project:

- 🟢 [Node.js](https://nodejs.org/en/download/) (v14 or above)
- 📦 npm (comes with Node.js)
- 🅰️ [Angular CLI](https://angular.io/cli) (globally installed)

---


 <details>
   <summary><h2>🚀 How to Set Up and Run the Project</h2></summary>

### 🛠️ Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/dfs-bfs-graph-traversal.git
cd GRAPH-TRAVERSAL
```

### 🛠️ Step 2: Install Frontend Dependencies

```bash
npm install
```

### 🛠️ Step 3: Navigate to Backend Directory and Install Backend Dependencies

```bash
cd backend
npm install
```

### 🛠️ Step 4: Run the Backend Server

From the `backend` directory, start the backend:

```bash
node server.js
```

Alternatively, you can use **nodemon** for automatic restarts:

```bash
npm install -g nodemon
nodemon server.js
```

### 🛠️ Step 5: Start the Frontend Server

Go back to the project root (`GRAPH-TRAVERSAL`) and run the Angular development server:

```bash
ng serve
```

Your frontend will be running at `http://localhost:5000` 🌐.


</details>

<hr>

<details>
   <summary><h2>🧪 Testing Instructions</h2></summary>


To ensure the reliability and functionality of the project, follow these testing instructions:

### Unit Testing

1. **Navigate to the frontend directory**:
   ```bash
   cd src
   ```
2. **Run the unit tests:**
   ```bash
   ng test
   ```
### End-to-End Testing

1. **Install Protractor (if not already installed)**:
   ```bash
   npm install -g protractor
   ```
2. **Start the Protractor server**:
   ```bash
   webdriver-manager update
   webdriver-manager start
   ```
3. **Run the end-to-end tests**:
   ```bash
   ng e2e
   ```
### Manual Testing

- After running the application, perform manual testing by interacting with the **Login** and **Signup** pages to ensure functionality.
- Test the **graph traversal features** by creating graphs with various nodes and edges, checking for expected behavior.



</details>

<hr>

## 🔐 Login and Signup Pages

- The **Signup Page** allows users to register by entering a username and password, which is stored in **LocalStorage**.
- The **Login Page** checks credentials against the data stored in LocalStorage.

### 🛠️ How to Access Signup Details from LocalStorage

1. 🖱️ Right-click on the **Signup page** and select **Inspect**.
2. 🧰 Navigate to the **Application** tab in the developer tools.
3. 📂 Under **Storage**, expand **LocalStorage**.
4. 🔍 You’ll find the stored signup details there.

---

## 🖥️ How the Server Works

The backend server, built with **Node.js** and **Express.js**, handles:

- 🛡️ **User Authentication**: A basic registration and login system.
- 🔄 **Graph Traversal**: Provides APIs for DFS and BFS traversals.

## 📊 How the Graph Feature Works

- Input your nodes. **Make sure it is in A,B,... format. Comma is necessary**
- Input your edges. **Make sure it is in the [to]-[from] format. Eg: 0-1**
- Click on **create custom graph** button 🔵
- See how the magic happens
 

<details>
   <summary><h3>Example: </h3></summary>

![alt text](image.png)

Output:

![alt text](image-1.png)

</details>

<hr>

## 🗺️ Roadmap

| **Timeline**   | **Milestone**                  | **Description**                                                                                         |
|----------------|--------------------------------|---------------------------------------------------------------------------------------------------------|
| **2024**       | **Q4 2024**                    | 🔍 **Enhanced User Authentication**: Implement OAuth for third-party authentication (Google, Facebook) and improve security measures for password storage. |
| **2025**       | **Q1 2025**                    | 📈 **Advanced Graph Algorithms**: Integrate additional graph traversal algorithms (e.g., Dijkstra's and A*) and provide visualizations for different traversal methods. |
|                | **Q2 2025**                    | 🖥️ **User Dashboard**: Develop a dashboard for users to view their traversal history and saved graphs. Enable features for users to share their graphs with others. |
|                | **Q3 2025**                    | 📱 **Mobile-Friendly Version**: Ensure the application is responsive and works well on mobile devices. Create a mobile application version for iOS and Android. |
|                | **Q4 2025**                    | 🌐 **Multilingual Support**: Add support for multiple languages to enhance accessibility. Enable user-selectable language options in the application settings. |


## Contributing

We welcome contributions from developers of all experience levels. Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

<hr>

<h2 align = "center">Our Contributors ❤️</h2>

- We extend our heartfelt gratitude for your invaluable contribution to our project! Your efforts play a pivotal role in elevating this project to greater heights.
- Make sure you show some love by giving ⭐ to our repository.

<div align="center">

| Contributor          | Contributor          | Contributor          | Contributor          |
|----------------------|----------------------|----------------------|----------------------|
| <img src="https://github.com/shubhagarwal1.png" alt="Shubham Agarwal" width="100" height="100"> <br> <div align="center">[Shubham Agarwal](https://github.com/shubhagarwal1)</div>  | <img src="https://github.com/mehul-m-prajapati.png" alt="Mehul Prajapati" width="100" height="100"> <br> <div align="center">[Mehul Prajapati](https://github.com/mehul-m-prajapati)</div>  | <img src="https://github.com/sakeel-103.png" alt="Sakeel" width="100" height="100"> <br> <div align="center">[Sakeel](https://github.com/sakeel-103)</div>           | <img src="https://github.com/Jashwanth-rit.png" alt="Jashwanth R" width="100" height="100"> <br> <div align="center">[Jashwanth R](https://github.com/Jashwanth-rit)</div>      |
| <img src="https://github.com/ananyag309.png" alt="Ananya Gupta" width="100" height="100"> <br> <div align="center">[Ananya Gupta](https://github.com/ananyag309)</div>        | <img src="https://github.com/alo7lika.png" alt="Alolika Bhowmik" width="100" height="100"> <br> <div align="center">[Alolika Bhowmik](https://github.com/alo7lika)</div>        | <img src="https://github.com/muskan171105.png" alt="Muskan Sharma" width="100" height="100"> <br> <div align="center">[Muskan Sharma](https://github.com/muskan171105)</div>   | <img src="https://github.com/adityakalburgi.png" alt="Aditya Kalburgi" width="100" height="100"> <br> <div align="center">[Aditya Kalburgi](https://github.com/adityakalburgi)</div> |
| <img src="https://github.com/LifeHashed.png" alt="Life Hashed" width="100" height="100"> <br> <div align="center">[Life Hashed](https://github.com/LifeHashed)</div>        | <img src="https://github.com/Varsha567.png" alt="Varsha" width="100" height="100"> <br> <div align="center">[Varsha](https://github.com/Varsha567)</div>               | <img src="https://github.com/09viv.png" alt="Viv" width="100" height="100"> <br> <div align="center">[Viv](https://github.com/09viv)</div>                     | <img src="https://github.com/Shariq2003.png" alt="Shariq" width="100" height="100"> <br> <div align="center">[Shariq](https://github.com/Shariq2003)</div>              |
| <img src="https://github.com/Himanshu-kumar025.png" alt="Himanshu Kumar" width="100" height="100"> <br> <div align="center">[Himanshu Kumar](https://github.com/Himanshu-kumar025)</div> | <img src="https://github.com/avisha191.png" alt="Avisha" width="100" height="100"> <br> <div align="center">[Avisha](https://github.com/avisha191)</div>              | <img src="https://github.com/Mausumi134.png" alt="Mausumi" width="100" height="100"> <br> <div align="center">[Mausumi](https://github.com/Mausumi134)</div>          | <img src="https://github.com/itbindu.png" alt="Bindu" width="100" height="100"> <br> <div align="center">[Bindu](https://github.com/itbindu)</div>                  |
| <img src="https://github.com/dipkulkhandelwal21.png" alt="Dipesh Kulkhandewal" width="100" height="100"> <br> <div align="center">[Dipesh Kulkhandewal](https://github.com/dipkulkhandelwal21)</div> | <img src="https://github.com/mahaveergurjar.png" alt="Mahaveer Gurjar" width="100" height="100"> <br> <div align="center">[Mahaveer Gurjar](https://github.com/mahaveergurjar)</div>            | <img src="https://github.com/rudrapratap63.png" alt="Rudra Pratap" width="100" height="100"> <br> <div align="center">[Rudra Pratap](https://github.com/rudrapratap63)</div>        | <img src="https://github.com/Sawan-Kushwah.png" alt="Sawan Kushwah" width="100" height="100"> <br> <div align="center">[Sawan Kushwah](https://github.com/Sawan-Kushwah)</div>     |
| <img src="https://github.com/T-Rahul-prabhu-38.png" alt="T Rahul Prabhu" width="100" height="100"> <br> <div align="center">[T Rahul Prabhu](https://github.com/T-Rahul-prabhu-38)</div> | <img src="https://github.com/Aditijainnn.png" alt="Aditi Jain" width="100" height="100"> <br> <div align="center">[Aditi Jain](https://github.com/Aditijainnn)</div>         | <img src="https://github.com/saurabh-dev-vns.png" alt="Saurabh" width="100" height="100"> <br> <div align="center">[Saurabh](https://github.com/saurabh-dev-vns)</div>             | <img src="https://github.com/smog-root.png" alt="Smog Root" width="100" height="100"> <br> <div align="center">[Smog Root](https://github.com/smog-root)</div>            |
| <img src="https://github.com/iamendless10.png" alt="I Am Endless" width="100" height="100"> <br> <div align="center">[I Am Endless](https://github.com/iamendless10)</div>       | <img src="https://github.com/AswaniBolisetti.png" alt="Aswani Bolisetti" width="100" height="100"> <br> <div align="center">[Aswani Bolisetti](https://github.com/AswaniBolisetti)</div> | <img src="https://github.com/SupratitDatta.png" alt="Supratit Datta" width="100" height="100"> <br> <div align="center">[Supratit Datta](https://github.com/SupratitDatta)</div>   | <img src="https://github.com/khurshed07.png" alt="Khurshed" width="100" height="100"> <br> <div align="center">[Khurshed](https://github.com/khurshed07)</div>              |
| <img src="https://github.com/devxMani.png" alt="Devx Mani" width="100" height="100"> <br> <div align="center">[Devx Mani](https://github.com/devxMani)</div>               | <img src="https://github.com/Dipu2552003.png" alt="Dipu" width="100" height="100"> <br> <div align="center">[Dipu](https://github.com/Dipu2552003)</div>                     | <img src="https://github.com/Sandigupta.png" alt="Sandi Gupta" width="100" height="100"> <br> <div align="center">[Sandi Gupta](https://github.com/Sandigupta)</div>        | <img src="https://github.com/ThunderShadows.png" alt="Thunder Shadows" width="100" height="100"> <br> <div align="center">[Thunder Shadows](https://github.com/ThunderShadows)</div>  |

</div>


---

### 📬 Feel free to contribute or open issues if you find any bugs!


<hr>
<div>
  <h2><img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f64f_1f3fb/512.webp" width="35" height="35"> Support </h2>
</div>

<div>
  Don't forget to leave a star<img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" width="35" height="30"> for this project!
</div> 
<hr>

<a href="#top" style="position: fixed; bottom: 20px; right: 20px; background-color: black ; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; border-radius: 5px; font-family: Arial; font-size: 16px;">Go to Top</a>

