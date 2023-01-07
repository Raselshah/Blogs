<h2>How to Master React JS in No Time (step by step guide part 1)</h2></br>
<h2>Introduction</h2></br>
There's no doubt that React JS is the most popular javascript libary out there and due to its popularity, a lot of aspiring developers are eager to learn how react really works and how to start using it to build their projects as well.</br>

But before we start diving into the topic of the day, what exactly is React JS ? well, like i said, it is a javascipt libary that was created by Jordan Walke a software developer at facebook. It was created for building user interfaces based on UI components. It is maintained by Meta (formerly Facebook) and a community of individual developers and companies. read the full history here</br>

But have it in mind that you can create whatever you feel like by using react and some of its frameworks to build anything you would like to, but in this article, I want to walk you through the step by step guide on how to master React JS in no time and the resources that will make your learning and development much more easier. so let's dive in 😎</br>

Guidelines</br>

step 1 : The Overview</br>
step 2: The Installation Guide</br>
step 3: Understading the syntax</br>
step 4: Render your first React App</br>
step 5: Learn React Components</br>
step 6: choose between Functional Components or Class Based Components</br>
step 7: Learn Import and Export</br>
step 8: Set up your IDE by installing the Necessary Extensions</br>
step 9: Understading React Hooks</br>
step 10: Work with Conditional Rendering</br>
step 11: Learn controlled and uncontrolled Inputs</br>
step 12: Understanding the ES6 syntax</br>
step 13: Learn How to fetch data using React JS</br>
step 14: Learn React PropTypes</br>
step 15 : Build Projects</br>
step 1 : The Overview</br>

Before you start learning a new language, the first thing that is recommended for you to do is know how powerful is the language which i categorised as overview, you need to know which crazy projects you can build with it and so on. I ask myself a lot of questions such as What can I create with this language ? Can I build a game with it ? what is the benefit of learning this language ? and so on... when you finally find the answers to your mysterious questions, it will boost your interest to start learning the language and to start building crazy projects you would like to build. With that being said, let's keep digging in ☺</br>

<h2>step 2: The Installation Guide</h2></br>
npx create-react-app my-app</br>
cd my-app</br>
npm start</br>

To create a new react App, open your terminal and cd to your desktop. The first line of code above which is npx create-react-app will create your new react app in the directory called my-app, when the download is complete, then cd to my-app or whatever you call it and spin up your web server by typing npm start</br>

you should see this on your webpage after you have succefully done that</br>
when that is done, you have created your new app 😊, but there is a lot more to do. always read the docs here if you need to.</br>

<h2>step 3: Understanding the syntax</h2></br>
Now the next step is to understand how React syntax works. because technically we have to, you can't use python or angular syntax in react, you will get a big fat error ❌. When you are new to a programming language, the first thing to do is to learn the syntax.</br>

Since React JS was created for building user interfaces based on UI components, there is no doubt that we will use HTML syntax in React JS to build the structure of our webpages, but it's not called HTML syntax just like that, it is called JSX. Check the example below</br>

import React from 'react'</br>

const practice = () => {</br>
  return (</br>
    <div></br>
        <h>Hello World ! ☺</h></br>
    </div></br>
  )</br>
}</br>

export default practice</br>

In the example above, we used the syntax below which are both HTML tags, but when it comes to React, we can't just use the HTML tags to create our webpage because it won't work. that is why we have JSX read the full introduction here .</br>

<h2>step 4: Render your first React App</h2></br>
Now is the right time to render your first react app and not the pre-made app that is available for you by using npx-create react-app</br>

The first thing that I would like you to do is to navigate to your project folder and delete all the files in the public folder except the index.html, then open the src folder and delete all the files except App.css and Index.js, we will re-create it from scratch to render your very own react app</br>
<img src='https://cdn.hashnode.com/res/hashnode/image/upload/v1654761902555/ROkT-VBdT.jpg?auto=compress,format&format=webp' alt='github' width="100%" height='400'>
After that is done, then go to your src folder and create a new file called App.js or App.jsx. bear it in mind that both of them works. then after that write the code below</br>

import React from 'react'</br>

const App = () => {</br>
  return <div>App</div></br>
}</br>

export default App</br>
in the first line of code, we import React from react, basically that is a built-in module that we will have to import for every jsx file that we create, then we have our functional component with some JSX in it and we export the file called App. If you check your index.js file, we we have already imported the file called App that is why we could see our webpage with the text App because that is what we rendered. for full Tutorial check out this video by Learn With Sumit on YouTube.</br>

<hr>step 5: Learn React Components</h2></br>
what exactly is React Components ? Well here is a simple definition of react components by w3s</br>

Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML precisely JSX.</br>

Components come in two types, Class components and Function components, in this tutorial we will concentrate on Functional components but i will also show you the second type of components and its syntax, the choice of selecting either functional components or class based components is totally up to you</br>

Now, let's say we want to create a new Navbar component which is going to contain only all our Navbar elemens, then all we have to do is to create a file called Navbar.jsx and create our functional component like so and we can add our navbar links like so</br>

import React from 'react'</br>

const Navbar = () => {</br>
  return (</br>
    <></br>
      <d>Navbar</d></br>
      <u></br>
        <l>Home</l></br>
        <l>About</l></br>
        <l>Blog</l></br>
      </u></br>
    </></br>
  )</br>
}</br>

export default Navbar</br>
With this lines of code, we have created our Navbar functional components and we can re-use it again and again</br>

I know it's getting quite busy here so that is why i will continue from where I stopped and write the part 2 of this article next week. so stay updated and don't forget to share it to your fellow programmers.</br>

but before you go, follow this advice</br>
Keep Learning
