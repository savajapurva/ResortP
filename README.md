# React Beach Resort 

It is a resort website where user can checkout different types of rooms such as single, double, family and presidential. There is a filter in room page where user can filter rooms by room type, room capacity, price and whether pet is allowed or not.

Live link: <a href="https://my-react-resort.netlify.com/rooms" target="_blank">Click here</a>

<img src="img/aa.png">

---

## Quick Start

```bash
# clone repository
https://github.com/savajapurva/ResortP.git

# Install dependencies
cd ResortP && npm install

```
To query and get content using the APIs, client applications need to authenticate with both the Space ID and an access token. So, create account in contentful and then create an App. 

API keys of your app will be in setting -> API keys section

Now, create an .env.development file in yor project and add your keys.

```
REACT_APP_API_SPACE=YOUR_SPACE
REACT_APP_API_ACCESS_TOKEN=YOUR_ACCESS_TOKEN
```

To access your data from contentful, you need to add all your fields and data to the content model that you need to create at the dashboard. Kindly, refer to the below snapshot of my dashboard.

<img src="img/d.png">

---
<img src="img/e.png">

---
<img src="img/f.png">

---
<img src="img/g.png">

```

To run the development server:

```bash
# the development server runs on port 3000
npm run dev
```

To run production build:

```bash
# create code bundle
npm run build

# run production server
npm run prod
```

### To deploy this project to netlify see steps below:

At first push your project to Github. You will need to create an account in Netlify and link that repository.

```bash
# Guide (paste link in browser)
https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/
```

Before start deploying make sure to add the environment variables in Build and deploy sections of Netlify.

```bash
REACT_APP_API_SPACE=YOUR_SPACE
REACT_APP_API_ACCESS_TOKEN=YOUR_ACCESS_TOKEN
```

Hit the Deploy button after setting up above configuration and you are ready to go.

---

## Project Snapshots

<img src="img/b.png">

---

<img src="img/bb.png">

---

<img src="img/c.png">

---

## Main Technologies

### Client Side

- [x] **[React](https://github.com/facebook/react)**
- [x] **[styled-components](https://github.com/styled-components/styled-components)**
- [x] **[React-Router-DOM](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**

#### Libraries used in Client-side

- [x] **[contentful](https://github.com/contentful)**
- [x] **[react-icons](https://github.com/react-icons/react-icons)**
