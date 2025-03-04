
<h1 align="center">
  Loan Simulator
</h1>

<h3 align="center">
  This is a fullstack aplication that simulates a bank loan and stores it in a database.
</h3>

## 💻 Introduction


![View](https://user-images.githubusercontent.com/83431609/132618122-f43de69b-ae81-4bed-bf54-f3c601ae8464.gif)

## 📚 Database

Route to access the database: 
https://letalk-backend.herokuapp.com/database

## 🧪 Technologies

This project was developed using the following technologies:
 
- [Reactjs](https://pt-br.reactjs.org/)
- [Material-ui](https://mui.com/pt/)
- [Typescript](https://www.typescriptlang.org/)
- [Nodejs](https://nodejs.org/en/)
- [PostgreSQl](https://www.postgresql.org/)
- [Sequelize](https://sequelize.org/)


## ⚡️ Instructions

- [x] The maximum term for payment is 30 years.
- [x] The minimum loan amount is R$50,000.00.
- [x] The installment amount must be divided month by month into equal installments.
- [x] After making the simulation, allow the user to execute the loan, the information must be saved in a database or JSON, because it will be necessary to create an endpoint in the API so that we can consume this data.
- [x] After the loan is made, just show a message informing that the request was made successfully.

- [x] The business rule must be all in the backend of the application, the frontend will be only to display the information.
- [x] The application should be developed preferably in Node.js and React.

## 🛠 How it works
> The validations for this application are in the backend, so if the user does not follow the instructions below, the data will not be stored.

- Only valid CPF will be accepted.
- The user will have to send a valid "uf", the options are: MG, RJ, SP and ES.
- The minimum amount that can be sent to request a loan has to be 50,000.
- In the last field the value cannot be greater than 360 months.

## 📝 License

This project was a challenge for a full stack developer position and is under the MIT license. See the file [LICENSE](LICENSE.md) for more details.

---

