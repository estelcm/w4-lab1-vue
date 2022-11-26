![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Hello Vue

## Introduction

Today, we've learned the basics of Vue.js and how to create a simple app using the `npm init vue@latest` package. In this exercise, we've' practice what we've just learned by creating a simple landing page (hopefully with some styles :blossom:).

## Setup

- Fork this repo
- Clone this repo
- Open the LAB and start:

  ```bash
  $ cd lab-vue-c-intro
  $ npm install
  $ npm run dev
  ```

## Submission

- Upon completion, run the following commands:

  ```
  git add .
  git commit -m "done"
  git push origin master
  ```

- Create a Pull Request so that your TAs can check your work.

## Instructions

### Iteration 1 | CreateVue app

Let's get this party started! First, you will need to create a new Vue app.

Navigate to the root folder of the LAB. When you're in the root folder, use `npm init vue@latest` in the command line to create a new Vue project. 

Once you have created the app, navigate to the root folder of the app. From here, run the app in the development mode and open it in the browser.

If you need any help, remember that you can always reference the official Vue documentation. Take a look at the Getting Started page here: [Create Vue App - Getting Started](https://vuejs.org/guide/quick-start.html).


### Iteration 2 | Prepare the app

Now that you've created the app, let's clean up the `App.Vue` file. Remove the initial content generated by the CRA to get the following structure:

```jsx
<template>
  <div id="app">
  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style>
  #app {
  }
</style>
```

<br>

### Iteration 3 | Download the assets

To create the landing page we will need few images. Inside of the `src/` folder create a new folder named `images`. The folder should be nested in the following way `src/images/`. 

Next, download the following images and save them in the `src/images/` folder. 

You can retrieve all of the images from [this Figma file](https://www.figma.com/file/2rSKMls9ZscT4VjggWpvfL/Vue-Lab---Welcome-to-Vue.js?node-id=0%3A1). Figma is a free prototyping and design tool that is very popular with designers. As a web developer, it's likely that you'll have to replicate designs built in Figma a lot. Using Figma is useful because you're able to see exactly what the size and positioning of things are, rather than just viewing an image file. 

<br>

### Iteration 4 | Landing Page

Finally, let's create our landing page. Using the assets that you downloaded from Figma in the previous iteration, recreate the following landing page:

<details>
  <summary>Click here to see the image</summary>

![web-frontend-vue/lab-vue-intro-finished](https://education-team-2020.s3.eu-west-1.amazonaws.com/web-frontend-vue/lab-vue-intro-finished.png)

</details>

For now, don't worry about creating more than one component, we will cover that in the following lessons!

<br>

Happy coding! :heart:
