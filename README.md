## What is Wall Street?
Wall Street is a virtual stock trading web application made using React. This application intends to help future investors learn the ups and downs of the stock market and build a portfolio of stocks for themselves. Beginning with a sum of **$10,000** you get a chance to get accustomed to the buying and selling of stocks, track your progress over a period of time and make yourself ready to conquer the stock market.

## Why Wall Street?

The stock market has always been considered a risky business, infact, some might even go to the extents of calling these investments as gambles. Wall Street is a Web Application that will prove otherwise. With access to virtual money and a starting sum of **$10,000**, Wall Street will enable you to build your very own portfolio from scratch. Here, you get a chance to learn about how the stock market operates in the real world, find your way through profits and losses and gain a practical hand on experience of this trade business without the risk of stepping into the real stock exchange.  


## Installation

You need to have Node installed on your local machine. [Node](https://nodejs.org/en/)

NPM(Node Package Manager is already bundled with Node). You can use yarn as well. Install Yarn from [here](https://yarnpkg.com/lang/en/docs/install/)

To run the project

```
cd v2/
yarn install
yarn start
```

Yarn can be replaced by npm. 

The above command will start the frontend

To start the backend
```
cd v2/backend
yarn install
yarn start
```

The App uses a [Mongo database](https://docs.mongodb.com/v3.2/administration/install-community/) so you will need to start a mongo service first on your local machine or if you don't want local mongo instance you can use [mLab](http://mlab.com). Replace your mLabURI with the local one in v2/backend/models/mongoose-setup.js and put your username and password in a .env file. Sample env file is given backend/.env.sample. Just replace it with your mLab credentials and rename the file to .env

To add a feature request just create an issue.

The v1 of this project was made when I just started out learning React, so it has lots of bugs and some core features didn't work properly(blame decimal alegbra in JavaScript)

To improve on all of it, I have made a v2 which is just more stable and better and with good practices. I have used TypeScript in React for the first time and really liked it, having static checking goes a long way in development process.

**For all the participants of OpenCode, I just want to tell you that this project might be a litle daunting given your experience level. You may face many problems in the setup itself, don't get disheartned and leave it in the middle. You may contact me anytime on [Facebook](https://www.facebook.com/jsc3998) and resolve your doubts. If you get stuck or don't know how to solve a particular issue or need some suggestions always feel free to ask me or anyone. Feel free to comment on any issues to get clarification, hint or any doubt you might have.**

Enjoy!!


