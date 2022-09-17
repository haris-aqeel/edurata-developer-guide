---
title: Getting started
date: 2018-09-15T07:42:34.000+00:00
slug: getting-started

---
## What is Edurata

Edurata offers a time-efficient way to document and implement standardized workflows in your company.  
Whether you need to document the onboarding process for new employees or a technical step-by-step walkthrough, we got you covered.

## Local installation

Even though Edurata is simple, we will guide you through setting it up locally.

There are mainly two repositories that are related to Edurata.

1. Edurata Frontend
2. Edurata Backend

Both repositories of Edurata are present on Gitlab. You need the owner to assign you the permissions in order to view, edit and write on the repositories.

### **Frontend Repository Steps:**

```bash
git clone https://gitlab.com/juliandm/edurata.git
cd edurata
yarn install OR npm install
yarn run dev OR npm run dev
```

These steps will clone the frontend repository, install all the packages from package.json, and will start a live server at [http://localhost:8080/](http://localhost:8080/).

When you open this link in your browser, you may see a screen as shown below.

![](/edurata-main.png)

When you go through the sign-in options, you need credentials in order to sign in. As far as **developers** are concerned. They **should NOT signup** instead they should ask for the **credentials from their contractor**.

After they signed up, you will be redirected to the dashboard and other workflow pages. As far as the frontend process is concerned, you are good to start your **development stuff according** to the instructions.

### **Backend Repository Steps:**

As far as backend setup is concerned, it is a little bit tricky as compared to the frontend stuff. You need to proceed with the following steps with special care in order to make everything right.