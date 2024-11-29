# Animal Tables Web App 🐱🐶🐟

## Overview

Hey there! Welcome to the *Animal Tables Web App* 🐾. This is a simple and fun web application where you can view, add, edit, and delete animal records across three tables. We have *Big Cats, **Dogs, and **Big Fish* — each with details like name, size, and location. 🐯🐶🐋

The app is super interactive:
- You can *sort* the tables.
- *Add new animals* with images (currently using some cute placeholder images).
- *Edit* animal details or *remove* them when needed.
- *Hover over animal images* to enlarge them — no need for pop-ups!

Designed to be simple and clean, the app uses *Bootstrap* for the responsive layout, and *JavaScript* for the interactivity.

## Features
- *Sorting*: 
  - Big Cats: Sort by name, size, or location (except the image column).
  - Dogs: Sort by *Name* or *Location*.
  - Big Fish: Sort by *Size*.
- *Add*: Add new animals with a modal form.
- *Edit*: Edit animal details via modals.
- *Delete*: Remove animals with a delete button.
- *Image Enlarging*: Hover over images to view them in a larger size — no need for a pop-up.

## Design Approach

### 1. *HTML Structure*:
I kept the HTML structure simple and straightforward. Everything resides in one file, index.html. The file contains three tables, one for each animal category (Big Cats, Dogs, Big Fish). There’s also a modal form for adding new animals and editing existing ones.

### 2. *JavaScript Logic*:
Here's the magic that makes it all come to life:
- *Data Management*: The animals are stored in JavaScript arrays. Each animal is an object with properties like species, name, size, location, and image. 🐱🦈
- *Sorting*: You can click on column headers to sort the data:
  - *Big Cats: Sort by **Name, **Size, or **Location*.
  - *Dogs: Sort by **Name* or *Location*.
  - *Big Fish: Sort by **Size*.
- *CRUD Operations*: 
  - *Add*: A modal lets you add new animals by inputting details and uploading an image.
  - *Edit*: Easily edit an animal's details through the edit modal.
  - *Delete*: Remove an animal from the list with the delete button.
- *Image Enlarging*: Hovering over an animal image will enlarge it for a better view. 🧐

### 3. *UI/UX Design*:
I wanted the app to be as easy to use as possible:
- *Responsive Design: Thanks to **Bootstrap*, the app is mobile-first and adapts to all screen sizes.
- *Modals: I used **Bootstrap modals* for adding and editing animals. They're clean and user-friendly.
- *Hover Effect*: The image hover effect enlarges the image — no complicated pop-ups, just a smooth experience.
- *Sorting*: Sorting by clicking on column headers is a simple, yet powerful feature.

### 4. *Code Organization*:
I focused on keeping the code clean, human-readable, and maintainable:
- *Modular Functions*: The logic is split into small, reusable functions. Each function does one thing well — adding, editing, or deleting animals.
- *Plain Variable Names*: I used simple and understandable variable names like cats, dogs, and fishies to keep things clear.

---

## How to Run

### Prerequisites:
No special setup needed! Just open the index.html file in any browser.

### Steps to Run:
1. Clone or download this repository.
2. Open the index.html file in your browser.
3. Enjoy the app! 🎉