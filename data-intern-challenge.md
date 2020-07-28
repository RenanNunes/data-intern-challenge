# Data Intern Challenge

This is Conta Stone's data challenge for intern applicants. The objective is to extract and analyze data from a database.

## Instructions

The solution can be developed using Python, SQL scripts, a BI tool or a combination of those. 
It must be sent as a compressed `.zip` folder including all the necessary files or hosted in a public code repository, such as **GitHub** or **GitLab**.

Access the PostgreSQL database using the following credentials:

```
host: db-stone.cjepwwjnksng.us-east-1.rds.amazonaws.com
port: 5432
database name: postgres
user: read_only_user
password: banking123
```

The database contains credit card transactional data in 4 tables:

- `customers`
- `cards`
- `transactions`
- `frauds`

1. Extract and analyze the data in the database in order to answer the following questions. Provide a description and/or comments for each solution.

- What is the average `age` of the customers in the database?
- How is the `card_family` ranked based on the `credit_limit` given to each card?
- For the transactions flagged as fraud, what are the `id`s of the transactions with the highest value?

2. Analysis:

- Analyze whether or not the fraudulent transactions are somehow associated to the other features of the dataset. Explain your results.

**It is not necessary to answer all questions.**