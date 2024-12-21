# 🐾 Adopt a Pet!

*The **Adopt a Pet!** project is a `React` application that demonstrates the use of **`React Router`** to implement client-side routing.*

---

## 🎯 Project Goal

*This project aims to provide hands-on experience with **`React Router`** to build a fully functional and interactive **pet adoption website**.*

### Objectives:
*1. Display all adoptable pets on the **HomePage**.*  
*2. Filter pets by species and display specific pet profiles.*  
*3. Enable navigation based on the browser's current URL.*  
*4. Handle invalid pet details by redirecting users to a **PetNotFoundPage**.*  
*5. Allow search functionality that redirects users to a **SearchPage**, filtering pets by name.*  

---

## 🔍 Features

*- **Client-Side Routing**: Navigate between pages using **`React Router`** for a seamless user experience.*  
*- **Dynamic Routing**: Routes respond to **URL parameters** and **query parameters** to filter and display pets.*  
*- **Search Functionality**: Search for pets by name and display results dynamically.*  
*- **Error Handling**: Redirect users to a **PetNotFoundPage** when an invalid pet is requested.*  
*- **Navigation**: Users can navigate back to the homepage from any page.*  

---

## 🛠️ Technologies Used

*- **React**: For building dynamic and interactive user interfaces.*  
*- **React Router**: For implementing client-side routing.*  
*- **JSX**: To structure and style UI components.*  
*- **Mock Service Worker (MSW)**: To replicate external API functionality.*  
*- **HTML/CSS**: For additional structure and styling.*  

---

## 🔑 Key Achievements

*I completed the following tasks as part of this project:*

### . Installation of `React Router` and Initial Setup:

*1. Installed `react-router-dom@6` for `React Router` functionality.*  
*2. Set up the **`RouterProvider`** at the root level to enable app-wide communication with React Router.*  
*3. Configured `appRouter` using **`createBrowserRouter`**, **`createRoutesFromElements`**, and **`Route`** utilities.*  

### . Created and Configured Routes:

*- Defined a **`root route`** to render the `Root` component.*  
*- Added a nested **`index route`** to render the `HomePage` component alongside the navigation bar.*  

### . Implemented Dynamic Behavior Using URL Parameters:

*1. Filtered pets by species on the HomePage using the browser’s URL.*  
*2. Configured the **PetDetailsPage** to display data for specific pets based on `id` in the URL parameters.*  

### . Search Functionality:

*- Configured the **SearchPage** to filter pets by name using a query parameter (`name`).*  
*- Ensured that the app redirects users to the search results dynamically.*  

### . Error Handling and Navigation:

*- Redirected invalid pet requests to a **PetNotFoundPage**.*  
*- Implemented a "Go Home" button on the **PetNotFoundPage** to navigate users back to the homepage.*  

---

## 📂 Project Structure

### 📁 Folder Organization:

*- **src/App.js**: Main application logic and route configuration.*  
*- **src/pages/home/index.js**: Displays all adoptable pets.*  
*- **src/pages/detail/index.js**: Displays pet details.*  
*- **src/pages/search/index.js**: Filters pets based on search criteria.*  
*- **src/pages/petNotFound/index.js**: Error page for invalid pet details.*  
*- **src/components/root/index.js**: Includes navigation and defines where nested routes render.*  

### 🖥️ Dynamic Routing Setup:

*1. Configured **`nested routes`** for displaying HomePage under the `Root` component.*  
*2. Used **`Outlet`** to render nested routes.*  
*3. Dynamically fetched pet details based on URL parameters in `PetDetailsPage`.*  
*4. Implemented error handling routes for invalid pets.*  

---
## 🤝 Collaboration:
## 🚀 How to Run the Project Locally

### 1. Download the Project

*- Fork the repository on GitHub.*  
*- Clone the repository:*  
```bash
*git clone https://github.com/your-username/adopt-a-pet.git*
```
*Alternatively, download the ZIP file and extract it.*  

### 2. Install Dependencies

*Navigate to the project folder and install the required dependencies:*  
```bash
npm install
```

### 3. Start the Development Server

*Run the following command:*  
```bash
npm start
```
*Open the app in your browser at http://localhost:3000.*  

---

*Feel free to fork the project, create issues, or submit pull requests to enhance functionality.*

*Enjoy exploring the Adopt a Pet! project. Your feedback and contributions are highly appreciated!🎉*  


## ✨ Highlights of This Project

*Through this project, you acquire practical experience in using` React Router` for `client-side routing`. You learn how to:*

*- Manage `nested` and `dynamic routes`.*  
*- Use URL parameters and query strings for dynamic behavior.*  
*- Implement error handling in a React app.*  
*- Provide a seamless user experience with navigation and search features.*  


