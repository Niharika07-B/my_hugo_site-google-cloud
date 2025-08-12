# 📄 My Hugo Site — Google Cloud

A simple **static website** built with [Hugo](https://gohugo.io/) and the **Hello Friend NG** theme, deployed using **Google Cloud Build** and optionally **Firebase Hosting**.

---

# 📂 Structure

```
my_hugo_site-google-cloud/
├── archetypes/            # 📝 Hugo content templates
├── public/                # 🌐 Generated static files
├── themes/hello-friend-ng # 🎨 Theme files
├── .firebaserc            # 🔥 Firebase config
├── .gitignore             # 🚫 Git ignored files
├── .hugo_build.lock       # 🔒 Hugo build lock
├── cloudbuild.yaml        # ☁️ Google Cloud Build config
├── config.toml            # ⚙️ Site settings
├── firebase.json          # 📄 Firebase hosting config
```

---

# 🚀 Deployment

**Google Cloud Build**

1. Link repo to Google Cloud Build.
2. Confirm `cloudbuild.yaml` is correct.
3. Deploy to Cloud Storage or Firebase.

**Firebase Hosting**

```bash
firebase login
firebase init
firebase deploy
```

---

# 🛠️ Tech Used

* Hugo
* Hello Friend NG theme
* Google Cloud Build
* Firebase Hosting

---

# 📊 Workflow Diagram

<div align="center">

      [Write Content & Code]  
            ⬇  
         Hugo Static Site  
            ⬇  
       Google Cloud Build ☁️  
            ⬇  
     +---------------------+  
     | Google Cloud Storage |  
     |   or Firebase Host   |  
     +---------------------+  
            ⬇  
        🌍 Live Website  

</div>


---

# ⭐ Support

If you like this project, **star ⭐ the repo** and follow for more!

---

