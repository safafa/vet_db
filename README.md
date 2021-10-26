![](https://img.shields.io/badge/microverse-blueviolet)

# Vet clinic database: database performance audit

> "Vet clinic database: database performance audit" is a database where we optimized some slow queries.

### Queries that we optimized: 
 - SELECT COUNT(*) FROM visits where animal_id = 4;
 
 `before`
![image](https://user-images.githubusercontent.com/63932912/138891748-0a0c3909-ca91-4d8a-8e8e-3af525a2e13e.png)
`after`
![image](https://user-images.githubusercontent.com/63932912/138892010-444ca0b5-bec9-469f-b227-6cc1baa3425d.png)

- SELECT * FROM visits where vet_id = 2;

`before`
![image](https://user-images.githubusercontent.com/63932912/138892211-05c1ed69-af44-4369-b7cb-32c46ec8437e.png)
`after`
![image](https://user-images.githubusercontent.com/63932912/138892268-9da2c406-76e4-41fd-882a-30764380808f.png)

- SELECT * FROM owners where email = 'owner_18327@mail.com';

`before`
![image](https://user-images.githubusercontent.com/63932912/138892657-b91cf65e-fea7-46e6-bad2-3fbf3e030cef.png)
`after`
![image](https://user-images.githubusercontent.com/63932912/138892737-5b0f6c17-b6b6-4344-ba1e-fd3d69c6558f.png)

## Getting Started

To get a local copy up and run the app, follow these simple example steps.

### Prerequisites

- Postgres 

### Setup

Clone the repository with:

```
git clone git@github.com:safafa/vet_db.git
```
or download [ZIP file](https://github.com/safafa/vet_db/archive/refs/heads/dev.zip)

Run the commands from `schema.sql` and `data.sql` to create the database locally.

## Authors

👤 **Aleksandar Ivezic**

- GitHub: [@Aleksandar Ivezic](https://github.com/ShinobiWarior)
- Twitter: [@AIvezic](https://twitter.com/AIvezic)
- LinkedIn: [Aleksandar Ivezic](https://www.linkedin.com/in/aleksandar-ivezic/)

👤 **Safa Aballagh**

- GitHub: [@Safafa](https://github.com/safafa)
- Twitter: [@safa aballagh](https://twitter.com/Aballagh_S)
- LinkedIn: [Aballagh Safa](https://www.linkedin.com/in/aballaghsafa/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/safafa/vet_db/issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- This project was inspired by [Microverse](https://www.microverse.org/?grsf=w9rx3c)
