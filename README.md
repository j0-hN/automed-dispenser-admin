# Automed Dispenser Admin

This repository contains the Admin Panel for Automed Dispenser.

## How to View the Admin Panel Online

To make your uploaded HTML code visible on the web, you can use GitHub Pages to publish your site:

### 1. Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click on "Settings" > "Pages" in the left sidebar.
3. Under "Source", select the branch (usually `main` or `master`) and the root (`/`) folder.
4. Click "Save".

A public URL will be generated (e.g., `https://j0-hN.github.io/automed-dispenser-admin/`).  
You can then visit `https://j0-hN.github.io/automed-dispenser-admin/admin.html` to view your Admin Panel.

### 2. Repository Structure

- `admin.html`: Main HTML file for the admin panel.
- Any other files for backend (like `admin.php`, `last_scan.php`) must be hosted on a server with PHP support. GitHub Pages only supports static files (HTML, CSS, JS).

### 3. Local Testing

To test locally, simply open `admin.html` in your browser.

### 4. Note on Backend

If your HTML uses PHP files (like `admin.php` and `last_scan.php`), these will NOT work on GitHub Pages since it does not support server-side code. For full functionality, deploy your code to a web server that supports PHP.

## Example Usage

- Go to the [GitHub Pages URL](https://j0-hN.github.io/automed-dispenser-admin/admin.html) after enabling Pages.
- Use the Admin Panel to manage users.

## Contact

For questions or support, open an issue in this repository.
