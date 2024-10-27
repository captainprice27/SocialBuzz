# SocialBuzz : a twitter UI inspired social web app

You can check the web-app here : [socialbuzz-live](https://socialbuzz-7cu9.onrender.com)

Some Features of the web app:

-   ⚛️ Tech Stack: React.js, MongoDB, Node.js, Express, TailwindCSS
-   🔐 User Authentication with JSONWEBTOKENS (JWT)
-   🔥 React Query for Data Fetching, Caching etc.
-   ✍️ Creating , 🗑️ Deleting , ❤️ Liking and 💬Commenting on Posts . 
-   📝 Edit Profile Info including Cover Image and Profile Image
-   👥 Follow Suggestions
-   📷 Image Uploads in a post using Cloudinary
-   🔔 Send Notifications

### Setup .env file

(while deployment , no need to put **NODE_ENV** as environment variable)
(also add a .env file in the root directory , which is ignored here along with node_modules etc)

```js
MONGO_URI=...
PORT=...
JWT_SECRET=...
NODE_ENV=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```

## Sign in Page Screenshot : 

![image](https://github.com/user-attachments/assets/9c958d37-f386-4746-a6c5-0b5da5ee16ea)

## Homepage UI Screenshot : 

![image](https://github.com/user-attachments/assets/c42c6645-f7c2-4dac-98d4-8c7b63461a6f)


