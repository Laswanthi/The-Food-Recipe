# 🍴 The Food Recipe

**The Food Recipe** is a web-based recipe management website where users can explore recipes, search and filter food items, save favorite recipes, share their own recipes, and manage their account.

The project is developed using **HTML, CSS, and JavaScript** with browser **Local Storage** for storing user-related data.

---

## 📌 Features

### 👩‍🍳 User Features

* View different food recipes
* Search recipes
* Filter recipes by category/cuisine
* View detailed recipe information
* Add recipes to Favorites ❤️
* Dark Mode 🌙
* User Login and Sign Up
* Share your own recipes
* Upload recipe images
* Add reviews/ratings
* Shopping list functionality
* Store user data using browser Local Storage

### 🔐 Admin Features

The project also contains an **Admin Dashboard**.

Admin can:

* View total registered users
* View shared recipes
* View reviews
* View website activity
* View website data
* Refresh dashboard statistics
* Export admin data
* Open the main website
* Logout from the admin panel

---

## 🛠️ Technologies Used

* **HTML5** – Structure of the website
* **CSS3** – Styling and responsive design
* **JavaScript** – Website functionality and interactions
* **Local Storage** – Stores users, recipes, favorites, reviews, shopping list and activity data
* **FileReader API** – Used for reading uploaded recipe images

---

## 📂 Project Structure

```text
The-Food-Recipe/
│
├── index.html
├── item.html
│
├── style.css
├── script.js
│
├── admin.html
├── admin.css
├── admin.js
│
└── images/
    ├── biryani.jpeg
    ├── pizza.jpeg
    ├── pasta.jpeg
    ├── burger.jpeg
    ├── cake.jpeg
    ├── dosa.jpeg
    ├── noodles.jpeg
    ├── paneer.jpeg
    └── ...
```

> Keep the image filenames exactly the same as the filenames referenced in `script.js`.

---

## 🚀 How to Run the Project

### Step 1: Download/Copy the Project

Keep all the project files inside one folder.

### Step 2: Add Images

Create an `images` folder inside the project folder.

```text
The-Food-Recipe/
└── images/
```

Place all recipe images inside this folder.

### Step 3: Open the Website

Open:

```text
index.html
```

in a web browser.

You can also use **VS Code with Live Server** to run the project.

### Step 4: Login / Sign Up

Create an account using the Sign Up option and then log in to access user features.

---

## 💾 Data Storage

This project does not use a traditional database.

It uses the browser's **Local Storage** to store information such as:

* Registered users
* Logged-in user
* User recipes
* Favorites
* Reviews
* Shopping list
* Activity information

Because Local Storage is browser-based, the data is stored locally in the user's browser.

---

## 🖼️ Recipe Images

Recipe images are stored in the `images` folder.

Example:

```javascript
image: "images/biryani.jpeg"
```

The image filename and extension must match the path used in `script.js`.

For example:

```text
images/
├── biryani.jpeg
├── pizza.jpeg
├── pasta.jpeg
└── burger.jpeg
```

---

## 👨‍💻 Admin Dashboard

The admin dashboard can be accessed through:

```text
admin.html
```

The admin page uses:

```text
admin.html
admin.css
admin.js
```

The admin JavaScript checks whether the logged-in user has the required admin role before allowing access.

---

## 📱 Responsive Design

The website is designed to work on different screen sizes, including:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile devices
* 📱 Tablets

---

## 🎯 Project Objective

The main objective of **The Food Recipe** project is to create an interactive and user-friendly recipe website where food lovers can:

1. Discover recipes.
2. Search and filter recipes.
3. Save favorite recipes.
4. Share their own recipes.
5. Upload food images.
6. Review recipes.
7. Manage their personal recipe activities.

---

## 🔮 Future Enhancements

The project can be extended with:

* Backend database integration
* Online user authentication
* Cloud image storage
* Recipe comments
* Advanced recipe search
* Ingredient-based search
* Nutritional information
* Recipe recommendations
* Social sharing
* Secure admin authentication
* Online deployment

---

## 👩‍💻 Author

**Laswanthi Torlikonda**

B.Tech – Computer Science and Engineering
KL University

---

## 📄 License

This project is created for **educational and academic purposes**.

