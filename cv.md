 
## **Gladky Konstantin** 
-------------------------------------------------------------------------------------


## **My Contact Info:**

+ **Phone:** +7 (798) 793-03-63
+ **E-mail:** gr1nch2@yandex.ru
+ **GitHub:** [Dexmor096](https://github.com/Dexmor096)
+ **Telegram** [Konstantin Gladky](Dexter096)
+ **Discord Chat** Gladkiy Konstantin (@Dexmor096)
-------------------------------------------------------------------------------------
## **About Me**

 I am 33 years old. I'm working. in the field of sales. I have been studying programming since 2021. Studying has already become a habit, I like to improve my skills and develop.
-------------------------------------------------------------------------------------
## My Skills 

+ HTML
+ CSS (Ant Design, SCSS, BEM)
+ JavaScript
+ React
+ Redux (Redux Toolkit)
+ Git (GitHub, GitLab)
+ TypeScript (in process)
-------------------------------------------------------------------------------------
## Code Examples

fetch function to get Hearthstone cards data
```
const getClass = async (race) => {
    try {
        const response = await fetch(`https://omgvamp-hearthstone-v1.p.rapidapi.com/cards/races/${race}`, options)
        const data = await response.json()
            .catch()
        const createImg = document.createElement('img');
        const dataImage = data.flatMap(obj => obj.img)
        const random = Math.round(Math.random() * 100);
        createImg.src = dataImage[random] !== undefined ? dataImage[random] : dataImage[5]
        image.append(createImg)
    } catch (error) {
        console.error(`${error.message}`)
    }
}
```
## Education
+ Sevastopol National Technical University
  - Physics of biological systems
+ Udemy
  - [Современный JavaScript](https://www.udemy.com/course/javascript-zero-to-junior-developer/)
  - [React](https://www.udemy.com/course/react-from-scratch/)
  - [Redux](https://www.udemy.com/course/redux-react/)
  - [TypeScript](https://www.udemy.com/course/modern_typescript/)
-------------------------------------------------------------------------------------
## Work experience
 
 + [Gordon Ramsay's menu](https://dexmor096.github.io/SPA-practice/) (React/ Materialize CSS)
 + [REST Countries](https://rest-countries-five-eta.vercel.app/) (React/Redux Toolkit)
 + [Job listings](https://dashboard-react-redux-two.vercel.app/) (React/Redux Toolkit)

## Languages

+ **Russian** - native speaker. 
+ **English** - A1-A2 (in process)
