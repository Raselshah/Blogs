# How to Master React JS in No Time

##In my previous article on how to master React Js, I have already talked about the first 5 few steps that you are going to follow to get started learning React Js and how to master it in no time. But in this article, I am going to continue from where i stopped in order to keep your head up towards becoming a React Js Pro.

Guidelines

step 6: choose between Functional Components or Class Based Components
step 7: Learn Import and Export
step 8: Set up your IDE by installing the Necessary Extensions
step 9: Understading React Hooks
step 10: Work with Conditional Rendering
step 11: Learn controlled and uncontrolled Inputs
step 12: Understanding the ES6 syntax
step 13: Learn How to fetch data using React JS
step 14: Learn React PropTypes
step 15 : Build Projects
step 6 : Functional Components or Class Based Components
After you have learnt how React components works, now is the time to make the decision if you want to stick with React functional component or class based component. Now, i know that you might want to ask this question that what on earth is Functional and clased based components ?

Don't worry i got your back !😎

<img src='https://cdn.hashnode.com/res/hashnode/image/upload/v1655546194692/f29rltIjw.webp?auto=compress,format&format=webp' alt='github' width="100%" height='400'>
checkout this out !
<img src='https://cdn.hashnode.com/res/hashnode/image/upload/v1655546319705/hjbSv21Kd.png?auto=compress,format&format=webp' alt='github' width="100%" height='400'>
Now let me throw you a mind grenade. Class based component is very difficult to read because there are many this keyword that appears everytime while coding which makes it really difficult to read like i said, so I prefer Functional component to render my App which is more easier to use with React Hooks and all the new features that has been added so far.

Of course there's nothing bad in learning the two, but you can always have a preference to build your cool and amazing react App. with that being said, which one would you go for ?

step 7: Learn ES6 Import and Export in React
At this point, you can ceate multiple react components , but how do you make use of some components in other components to render your entire react App ? Well, if you are familiar with ES6 syntax, I guess you already know that import and export means and that is what we are going to use import and export out react components in another components
<img src='https://cdn.hashnode.com/res/hashnode/image/upload/v1655546944373/hc5JmteUH.gif?auto=format,compress&gif-q=60&format=webm' alt='github' width="100%" height='400'>
it's important to note that when we are creating a new component, we will have to import react from react.. see the code below

{
import React from "react"

const App = () => {
    return <h1>Hello world<h1/>
}
}
  
But if we are to make use of this component in another component, we will have to use the export keyword see the full sample code below

{
import React from 'react'

const Tutorial = () => {
  return (
    <div>Tutorial</div>
  )
}
    }

export default Tutorial

by exporting component using export default with the name of the component, we can make use of this component by importing it in another component. see the sample code below


COPY
import React from 'react'
import Tutorial from "filepath"

const App = () => {
  return (
    <div>
      <Tutorial />
    </div>
  )
}

export default App

in this example, we import the component, and render it in another component. that way we have access to that component in out App component. Try it out and see the result

step 8: Set up your IDE by installing the Necessary Extensions
As a developer, you need to set up your IDE to make your development faster and easi, so that is why there are some cool extensions out there that can help you write your code faster and speed up your development without having to worry about anything. 🎼 "Ain't worry about nothing 😎"

the steps to download these extensions are quite the same, go to your VScode and click on the extension icon, the sidebar will open for you to search for theextension you want to install, then after that, you can click on the install button to install your preffered extension

<img src='https://cdn.hashnode.com/res/hashnode/image/upload/v1655548094074/WptFlN-fn.png?auto=compress,format&format=webp' alt='github' width="100%" height='400'>
Here are some neccessary Extensions that i recommend you to have

- Prettier : This Extension will format your code and make it look good and well structured without manually formatting your code. if you were to manually format your code, it will quiet take some time to accomplish during your development. to avoid all the stress that you will go through, make use of Prettier instead.

- ES7+ React/Redux/React-Native snippets : The cool thing about this extensions is that it makes you create a simple react component within a short period of time by typing rafce command and Tada ! your new react functional component is created,

- Live Server : The Importance of this extension is to enable you to automatically preview your webpage during the development which is quite essential and helpful. in that case, you will avoid going to your webpage several times that click on refresh icon to manually see the updated features that you have added on you webpage. it gets quite frustrating at some point so use Live Server extention instead.

There are many other extensions out there that you can use, but this are quite good to start off while building your react App.

step 9: Understading React Hooks
React Hooks is used with functional Components which means it's not suppported in class based components.

There are quite a lot of React Hooks out there, I will be going through some of them to give you a head start.

The first and most common react hook out there is the useState Hook. it is very common and there is no doubt that you will surely use it in your React functional Application, so with that being said, check out the code sample below

COPY
import React, { useState } from "react"

const App = () => {
  const [count, setCount] = useState(0)

  return(
    <>
        <h1>{count}</h1>
         <button onClick={() => setCount + 1}>
            count
          </button>
    </>
  )
}

In the example above, we import useState Hook from react. This useState returns value, its accessor and is initiated at the start: const [count, setCount] = useState(initialState);. Thereby in retrospective, in contrast to class components by Constructor, and state manipulated functions such as handleIncrease which was bind to this scope.

some other React Hooks that you will have to study are listed below

Basic Hooks

useState
useEffect
useContext
Additional Hooks

useReducer
useCallback
useMemo
useRef
useImperativeHandle
useLayoutEffect
useDebugValue
useDeferredValue
useTransition
useId
In conclusion, Here comes the end of the part 2 on the step by step guide to master React JS. but have it in mind that perfect pratice makes perfect. so the more you practice what you learn, the easier you will be familar with it. so keep learning, practicing and having fun along the way.

