# Pete's Pet Emporium!

#### This is a full stack project for educational purposes that features a variety of features explained below.


## 🚀 Getting Started - Local

### macOS Mojave 10.0+, Catalina 10.1+

```bash
# clone the repo
git clone https://github.com/Abhishek5101/petes-pet-emporium
# change into project directory
cd petes-pet-emporium

# install dependencies
npm install
# run locally 
npm run dev

Visit http://127.0.0.1:3000 to interact with the application
```

## :hammer: Built With

-   [Node.js](https://www.djangoproject.com/) - Javascript runtime environment
-   [Express.js](https://www.django-rest-framework.org/) - Node.js web application framework
-   [MongoDB](https://pypi.org/project/djoser/) - Database
-   [AWS S3](https://sqlite.org/index.html) - File hosting
-   [Stripe API](https://sqlite.org/index.html) - Accepting payments
-   [Mailgun API](https://sqlite.org/index.html) - Sending email confirmations


## 📝 License

By contributing, you agree that your contributions will be licensed under its Apache License.


## Features

### Full-text Search & Pagination
A search bar in the navbar to search for pets as well as fuzzy and full-text search on multiple criteria. Paginate the results.

### Validations
Validations to protect against unsanitary data getting into your database.

### Upload Images
Upload pictures of pets from new to AWS S3 and edit forms

### Payment Gateways
Buy pets using Stripe checkout API.

### Send Emails
An email is sent when a pet is purchased.

### Responding to JSON
This project as a full API
