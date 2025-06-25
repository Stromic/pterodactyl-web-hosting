# 🦖 Minimalist Pterodactyl Egg for Web Hosting

This is a simple, no-frills Pterodactyl Egg built for hosting PHP websites. It uses Apache with PHP-FPM on a lightweight Alpine Linux base. The goal? Keep things minimal, fast, and easy to use.

---

## What’s inside?

- Apache as the web server  
- PHP-FPM for handling PHP scripts  
- Alpine Linux as the base image (small and efficient)  
- A clean setup focused on just what you need — nothing more

---

## Why use this egg?

If you want a straightforward environment to run PHP sites without extra bloat, this egg’s for you. It’s perfect if you’re into keeping your containers lean and fast, and just want a reliable stack that works out of the box.

---

## Use cases

This egg works great for running PHP-based applications like:

- **WordPress**  
- **Laravel**  
- Custom PHP sites  
- Lightweight CMS or static site generators with PHP backends

---

## Getting started

1. Import the egg into your Pterodactyl panel.  
2. Create a new server using this egg.  
3. Upload your PHP application.  
4. Set up an Nginx reverse proxy on your host machine or another server to expose the app to the internet under your domain.

> ⚠️ **Note:** This egg does not handle HTTPS or domain routing on its own. You’ll need to set up an external Nginx reverse proxy with SSL (e.g., using Let's Encrypt) to serve your site securely over a domain.

---

## Notes

- This egg is minimal by design. If you need databases, caching, or other services, you’ll want to add those separately.  
- Configuration files are easy to access and tweak if you need to make changes.

---

## Contributions

If you find bugs or have ideas to improve this egg, feel free to open an issue or submit a pull request!

---
