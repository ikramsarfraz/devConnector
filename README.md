# devConnector

This is a MERN stack application from the "MERN Stack Front To Back" course on Udemy. It is a small social network app that includes authentication, profiles and forum posts.

## Quick Start

### Inside the config folder, create a file called default.json with the following:

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": ""
}
```

### Install server dependencies

```
npm install
```

### Install client dependencies

```
cd client
npm install
```

### Run both Express & React from root

```
npm run dev
```

### Build for production

```
cd client
npm run build
```

## Screenshots

### HOME

![](screenshots/devConnector_home.png)

### REGISTER

![](screenshots/devConnector_register.png)

### LOGIN

![](screenshots/devConnector_login.png)

### CREATE PROFILE

![](screenshots/devConnector_CreateProfile.png)

### ADD EXPERIENCE

![](screenshots/devConnector_AddExperience.png)

### ADD EDUCATION

![](screenshots/devConnector_AddEducation.png)

### DASHBOARD

![](screenshots/devConnector_dashboard.png)

### VIEW ALL POSTS

![](screenshots/devConnector_AllPosts.png)

### COMMENT ON A POST

![](screenshots/devConnector_CommentPost.png)

### VIEW ALL DEVELOPERS

![](screenshots/devConnector_devs.png)
