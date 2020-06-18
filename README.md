# :notebook: Task Manager API
The **Task Manager** is an API that manages users and their daily tasks.

# :hammer: Dependencies
- [node.js](https://nodejs.org/)
- [@sendgrid/mail](https://www.npmjs.com/package/@sendgrid/mail)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [express](https://www.npmjs.com/package/express)
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [mongodb](https://www.npmjs.com/package/mongodb)
- [mongoose](https://www.npmjs.com/package/mongoose)
- [multer](https://www.npmjs.com/package/multer)
- [sharp](https://www.npmjs.com/package/sharp)
- [validator](https://www.npmjs.com/package/validator)

# :link: Dev Dependencies
- [env-cmd](https://www.npmjs.com/package/env-cmd)
- [jest](https://www.npmjs.com/package/jest)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [supertest](https://www.npmjs.com/package/supertest)

# :gear: APIs
- [SendGrid](https://sendgrid.com/)

# :checkered_flag: Getting started
Create `config/dev.env` and paste the code below to run the project in dev mode:
```
PORT=YOUR ENVIRONMENT PORT
SENDGRID_API_KEY=YOUR SENDGRID API KEY
SENDGRID_EMAIL=YOUR SENDGRID E-MAIL
MONGODB_URL=YOUR MONGODB URL
JWT_SECRET=YOUR JWT SECRET PHRASE
```

---

Create `config/test.env` and paste the code below to run the project in test mode:
```
PORT=YOUR ENVIRONMENT PORT
SENDGRID_API_KEY=YOUR SENDGRID API KEY
SENDGRID_EMAIL=YOUR SENDGRID E-MAIL
MONGODB_URL=YOUR MONGODB URL
JWT_SECRET=YOUR JWT SECRET PHRASE
```

# :memo: License
- [MIT license](https://opensource.org/licenses/MIT)