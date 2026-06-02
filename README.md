                       # Java-Upskilling--CTS-
# Bootstrap 5 Lab Exercises – README

## Overview

This project contains Bootstrap 5 exercises covering the fundamentals of responsive web design, grid systems, typography, forms, buttons, navigation, and Flexbox utilities.

The exercises demonstrate how Bootstrap's predefined classes can be used to create responsive and visually appealing web pages with minimal custom CSS.


# Prerequisites

Before running the exercises, ensure that:

* Bootstrap 5 CSS and JavaScript files are included.
* A modern web browser is installed.
* Basic knowledge of HTML and CSS is available.

### Bootstrap CDN

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
```

---

# Exercises Covered

## 1. Setting Up Bootstrap 5

### Exercise 1.1

* Create a basic HTML page.
* Link Bootstrap using CDN.

### Exercise 1.2

* Set up Bootstrap using downloaded files or npm.
* Include Bootstrap CSS and JavaScript locally.

---

## 2. Bootstrap Structure and Files

### Exercise 2.1

Explore Bootstrap directory structure:

* CSS folder
* JS folder
* Icons folder

### Exercise 2.2

Use `bootstrap.bundle.min.js` to enable:

* Collapse
* Dropdowns
* Modals
* Tooltips
* Carousels

---

## 3. Fundamentals of Responsive Grid Layout

### Exercise 3.1

Responsive layout:

* Mobile → 1 column
* Tablet → 2 columns
* Desktop → 3 columns

Classes used:

```html
col-12 col-md-6 col-lg-4
```

### Exercise 3.2

Use:

* `.container`
* `.row`
* `.col-*`

to create responsive page layouts.

---

## 4. Column Layouts and Grid Classes

### Exercise 4.1

Two-column layout:

```html
col-md-3
col-md-9
```

Used for:

* Sidebar
* Main content

### Exercise 4.2

Four equal columns:

```html
col-sm-3
```

Each column occupies 25% width.

---

## 5. Alignment and Reordering in Grid

### Exercise 5.1

Center content using:

```html
justify-content-center
align-items-center
```

### Exercise 5.2

Reorder columns using:

```html
order-md-1
order-md-2
```

Allows different layouts on mobile and desktop.

---

## 6. Responsive Flexbox Utilities

### Exercise 6.1

Responsive Navbar:

```html
d-flex
flex-column
flex-md-row
```

### Exercise 6.2

Card layout using:

```html
justify-content-between
align-items-center
```

for proper spacing and alignment.

---

## 7. Typography

### Exercise 7.1

Bootstrap typography classes:

```html
display-1
lead
text-muted
fw-bold
fw-light
fst-italic
```

### Exercise 7.2

Text transformation utilities:

```html
text-uppercase
text-lowercase
text-capitalize
```

---

## 8. Forms

### Exercise 8.1

Registration form using:

```html
form-control
form-check
input-group
```

Features:

* Name field
* Email field
* Username field
* Terms and Conditions checkbox

### Exercise 8.2

Login form using:

```html
form-floating
```

Creates floating labels for form inputs.

---

## 9. Buttons

### Exercise 9.1

Contextual buttons:

```html
btn-primary
btn-secondary
btn-success
btn-danger
btn-warning
btn-info
btn-dark
```

Outline buttons:

html
btn-outline-*


### Exercise 9.2

Button groups:

```html
btn-group
```

Toggle buttons:

```html
btn-check
```

---

## 10. Navbars and Navigation

### Exercise 10.1

Responsive Navbar containing:

* Logo
* Navigation links
* Search form

Classes used:

```html
navbar
navbar-expand-lg
navbar-dark
bg-dark
```

### Exercise 10.2

Navigation styles:

#### Basic Navigation

```html
nav
```

#### Tab Navigation

```html
nav-tabs
```

#### Pill Navigation

```html
nav-pills
```

---

# Bootstrap Concepts Learned

* Bootstrap Installation
* Grid System
* Responsive Design
* Flexbox Utilities
* Typography Utilities
* Form Components
* Buttons and Button Groups
* Navigation Bars
* Tab Navigation
* Responsive Layout Design


