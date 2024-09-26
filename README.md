A Fullstack MERN Support Ticket System
# Built With :
[MongoDB Atlas](https://www.mongodb.com/atlas/database)
[Express.js](https://expressjs.com/)
[React.js](https://reactjs.org/)
[Node.js](https://nodejs.org/en/)




# Installation :
Lets create a `.env` file in the root of the project:
Then put the following code in that `.env` except you should add your details.


NODE_ENV = development
PORT = 5000
MONGODB_URL=<your_mongodb_connection_string>
JWT_SECRET=<your_secret_key>




# Folder Structure

```
├── README.md
├── backend
│   ├── config
│   │   └── db.js
│   ├── controllers
│   │   ├── noteController.js
│   │   ├── ticketController.js
│   │   └── userController.js
│   ├── middleware
│   │   ├── authMiddleware.js
│   │   └── errorMiddleware.js
│   ├── models
│   │   ├── noteModel.js
│   │   ├── ticketModel.js
│   │   └── userModel.js
│   ├── routes
│   │   ├── noteRoutes.js
│   │   ├── ticketRoutes.js
│   │   └── userRoutes.js
│   └── server.js
├── frontend
│   ├── README.md
│   ├── package-lock.json
│   ├── package.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   └── src
│       ├── App.js
│       ├── app
│       │   └── store.js
│       ├── components
│       │   ├── BackButton.jsx
│       │   ├── Header.jsx
│       │   ├── NoteItem.jsx
│       │   ├── PrivateRoute.jsx
│       │   ├── Spinner.jsx
│       │   └── TicketItem.jsx
│       ├── features
│       │   ├── auth
│       │   │   ├── authService.js
│       │   │   └── authSlice.js
│       │   ├── notes
│       │   │   ├── noteService.js
│       │   │   └── noteSlice.js
│       │   └── tickets
│       │       ├── ticketService.js
│       │       └── ticketSlice.js
│       ├── hooks
│       │   └── useAuthStatus.js
│       ├── index.css
│       ├── index.js
│       ├── pages
│       │   ├── Home.jsx
│       │   ├── Login.jsx
│       │   ├── NewTicket.jsx
│       │   ├── Register.jsx
│       │   ├── Ticket.jsx
│       │   └── Tickets.jsx
│       └── serviceWorker.js
├── node_modules
├── package-lock.json
└── package.json






# Run backend & frontend servers concurrently : npm run dev





Inside of `/backend/controllers/ticketController.js` are a collection of.

  getTickets, [done]
  getTicket, [done]
  createTicket, [done]
  updateTicket
  deleteTicket,





# Build an application

In order to make a production build of your application: npm run build





# Deploy your application

In order to produce a ready-to-deploy version of your application : npm run deploy






Available Scripts : Terminal
# `npm start`
# `npm test`
# `npm run build`
# `npm run eject`                ::             "this is a one-way operation. Once you `eject`, you can’t go back"
