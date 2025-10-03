[README.md](https://github.com/user-attachments/files/22672821/README.md)
# Chris Sizemore Campaign Website

This is the official campaign website for **Chris Sizemore, Candidate for Rabun County Commissioner District 2**.  
It is a static site built with HTML/CSS/JS and hosted for free on **GitHub Pages**.

---

## 🚀 How to View the Site
Once GitHub Pages is enabled, the site will be live at:

```
https://<your-username>.github.io/chris-sizemore-campaign/
```

Replace `<your-username>` with your GitHub username.

---

## 🛠️ How to Update Content
All text, colors, and links are controlled in the `CONFIG` object inside **index.html** near the top of the file.

### Example CONFIG Section
```js
const CONFIG = {
  name: "Chris Sizemore",
  role: "Candidate — District 2 County Commissioner",
  slogan: "Community First, Always",
  heroImage: "/assets/headshot.jpg",
  bio: "Chris Sizemore is a dedicated public servant...",
  issues: [
    {title:"Transparency", desc:"Building trust by ensuring open communication and clear decision-making."},
    {title:"Accountability", desc:"Holding county leadership to the highest standards."},
    {title:"Economic Growth", desc:"Encouraging sustainable development and supporting local businesses."}
  ],
  contactEmail: "Vote4Sizemore@gmail.com",
  phone: "(706) 406-8407",
  social: {
    facebook: "https://facebook.com/yourpage",
    twitter: "",
    instagram: ""
  }
};
```

### To Update:
1. Go to your GitHub repo.  
2. Click **index.html** → **Edit**.  
3. Update the `CONFIG` fields (bio, slogan, issues, contact info, links).  
4. Scroll down and click **Commit changes**.  
5. Your site updates automatically within 1–2 minutes.

---

## 📸 Updating Images
- Place your images in the `/assets` folder.  
- For your headshot, use: `/assets/headshot.jpg`  
- To replace, upload a new image with the same filename or update the `heroImage` field in CONFIG.

---

## ✉️ Volunteer/Contact Form
By default, the volunteer form opens the user’s email client with a pre-filled message.  
If you want submissions saved online, replace the form action with a **Google Form** or **Formspree** endpoint.

---

## ⚙️ Local Testing (Optional)
If you want to preview changes before pushing:
```bash
# In the repo folder
open index.html
```
(or double-click the file to open in your browser).

---

## 📌 Notes
- This site is **fully static** (no database, no server).  
- GitHub Pages automatically rebuilds the site after each commit.  
- Only repository collaborators can update the site.  

---

✅ Paid for by the Chris Sizemore Campaign.  
