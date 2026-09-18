MyBrand — One Page Website
===========================

FILES
-----
index.html         The complete website (structure, styles, and behavior are all in this one file)
images/hero.jpg     The hero section image

HOW TO REPLACE THE IMAGE
-------------------------
1. Drop your new image into the "images" folder.
2. Open index.html, find this line (near the top of the hero section):
       <img src="images/hero.jpg" alt="Hero visual" class="hero-img">
3. Change "images/hero.jpg" to your new file's name.

HOW TO HOST IT
--------------
This is a static site — no build step, no server-side code, no dependencies to install.

Option A — Netlify or Vercel:
  Drag and drop this whole folder onto their dashboard and it deploys instantly.

Option B — GitHub Pages:
  Push this folder's contents to a GitHub repository and enable Pages
  in the repo settings (Settings > Pages > Deploy from branch).

Option C — Any traditional web host (cPanel, FTP, etc.):
  Upload index.html and the images folder to your host's public/www
  directory, keeping the same folder structure.

That's it — no configuration needed.
