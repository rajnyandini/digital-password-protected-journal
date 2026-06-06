# Digital Password Protected Journal


go here https://rajnyandini.github.io/digital-password-protected-journal/

## Features

* Password-protected admin mode
* Create new journal entries
* Delete existing entries
* Local Storage persistence
* No frameworks required

##  Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Local Storage API

##  How It Works

All journal entries are stored directly in the browser using Local Storage.

This means:

* No database setup required
* No server required
* Posts remain available after refreshing the page
* Data stays on the device where it was created

## 🔐Admin Access (IMPORTANTTTTTT)

To access Admin Mode:

1. Open the website.
2. Type:

```text
adm
```

3. Enter the configured admin password ('CHANGE_ME') is the default

> Note: This project uses frontend-only authentication and is intended for demonstration and learning purposes.

### Change Blog Name

Edit the configuration section:

```javascript
const BLOG_CONFIG = {
  name: "Digital Password Protected Journal",
  adminPassword: "CHANGE_ME"
};
```

### Change Password

```javascript
const BLOG_CONFIG = {
  name: "Digital Password Protected Journal",
  adminPassword: "CHANGE_ME"
};
```

### Change Theme Colors

Modify the CSS variables inside:

```css
:root {
  --accent: #c8703a;
}
```

