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

(while deployment , no need to put NODE_ENV as environment variable)

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
