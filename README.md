# Photo Gallery Website  

A personal photo website where users can upload, categorize, and group images.  
The aim is to create a lightweight platform (inspired by Pinterest) for organizing visual content with custom tags, categories, and grouping features.  

---

## Features  

Users can upload images, which are stored in a Supabase bucket and referenced in an SQLite database. Uploading includes a preview function and a loading indicator. Images can be categorized by theme, color, or mood, and tagged with multiple custom keywords. The tag system is designed to handle both single and multi-word tags correctly.  

The gallery view displays all uploaded images in a grid layout where images fit together naturally. Hovering over an image shows its tags and a delete button for removing it. A scroll-to-top button improves navigation.  

Group mode allows users to select two images and pair them together. The first image becomes the profile image, while the second becomes the banner image. These grouped pairs are displayed on a separate gallery page, with the same hover-to-delete functionality.  

Navigation is kept simple with a clean navbar that includes options for adding a new photo or creating a new group.  

---

## Tech Stack  

- Frontend: HTML, CSS, JavaScript  
- Backend: ASP.NET Core Web API (C#)  
- Database: SQLite  
- Storage and Authentication: Supabase  
- Hosting: GitHub Pages  

---

## Inspiration  

This project is inspired by Pinterest’s way of organizing visual content, but it is designed on a smaller scale for personal use. The site is lightweight but still viewable by others.  

---

## Progress  

Completed so far:  
- Uploading images to Supabase and saving metadata in SQLite  
- Gallery with grid layout, hover effects, delete buttons, and tag display  
- Upload page with preview and loading indicator  
- Group mode (profile and banner pairing system)  
- Group gallery page with delete functionality  
- Basic navigation bar  

---

## Future Plans  

Planned improvements include advanced filtering by tags and categories, an improved interface for grouped images, support for multiple file uploads, and public sharing with permissions.  
