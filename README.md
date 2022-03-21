<h2 background-color:"DodgerBlue" align="center"> HENOSIS </h2>
<p align="center"> Plan | Organize | Track </p>
<h4 align="center"> The prime goal of  Henosis is to assist managers with their everyday project management responsibilities. Henosis allows you to plan, organize, and prioritize tasks to finish them efficiently. It also helps you to connect with other developers through a real-time chat portal. Developers can discuss issues and plan upcoming features.
</h4>

<p background="black" align="center">      
      <img src="https://miro.medium.com/max/6000/1*ZQywXQQMs32Dray68Sjptg.jpeg" alt="conference-events"  width="500px" /> </br>
</p>

- Server Code : [Henosis Server Repo](https://github.com/nrd141913/henosis-server)

- Live Site : [Henosis Live Site](henosis.vercel.app)

## Homepage

![Homepage Henosis](public/images/dashboard.png)
![Homepage Developer's Book](public/images/logo.png)

## Documentation

- [How to work with multiple branch or team collaboration](docs/team-collaboration-guide-for-github.md)

* [Next Js Documentation](https://nextjs.org/docs)
* [TypeScript Documentation ](https://www.typescriptlang.org/docs/)
* [ Express Documentation ](https://expressjs.com/en/starter/installing.html)
* [ Mongoose Documentation ](https://mongoosejs.com/docs/index.html)
* [ Vercel Documentation ](https://nextjs.org/docs/deployment)

## How to run this project

- Clone first `git clone https://github.com/mir-hussain/henosis-client.git henosis-client`
- `cd henosis-client`
- run command `npm install`
- run command `npm run dev`
- browse: http://localhost:3000 for seeing main application views

# Features

- Project Planning and scheduling.
- Collaboration with the team.
- Organize, prioritize, and assign tasks to team members.
- Board/card layout and Grand chart layout.
- Progress monitoring in real-time.
- User dashboard for maintaining personal workflow.
- Chats and discussions to stay connected.
- Channel-based chat portal.

# Technical Features

- TypeScript provides highly productive development tools for JavaScript IDEs and practices, like static checking.
- Mongoose used for flexible Database Query.
- Batch Query for optimize fetching data
- Handled token based authentication by JWT
- Authentication Header verified on both side (Client & Server Side )
- Implement Firebase Authentication
- Data managed via RestAPI
- Frontend managed via Next.js. Because a project management web application should be SEO friendly. Next.js is a good solution for this. Auto code splitting , lazy loading, image progressive loading is implemented by default.

# Used Technologies

Backend

- Language : Node.js
- Framework : Express.js
- ORM : Mongoose
- Database : MongoDB

Frontend

- Language : JavaScript & TypeScript
- UI Framework : NEXT.js
- UI Design Library: SaaS
- State Management : Redux

# Work On Team Project

- Create new branch `git checkout -b BRANCH_NAME` eg `git checkout -b henosis`
- checkout branch `git checkout master`
- Fetch Upstream `git fetch -u master`
- working on a branch. pull before start working
  - `git add .`
  - `git commit -m "Bug Fixed"`
  - `git fetch && git pull origin development`
  - `git push origin BRANCH_NAME` eg : `git push origin development`
