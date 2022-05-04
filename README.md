# Hello Rails Back-End

> An API that provides random greetings.
# Front-End Repo

[Link][(https://github.com/gemmen29/hello-react-front-end](https://github.com/Lucas-Masaba/hello-react-front-end))

## Built With

- Ruby
- Ruby on Rails
- OOP
- SQL Postgres
- CORS

## Getting Started

To get a local copy up and running follow these simple example steps.

- Click on the top right green "code" button.
- On the dropdown menu, choose "download with zip" button.
- After download, extract the zip file and you have the project on your machine.
- Make sure that your PostgreSQL server is running and you have the ability to establish connection with the database.
- Create a new file called `local_env.yml` in the folder `config/` and paste the following code in it:
  > `PG_USERNAME: "YourPostgresUsername"`<br> `PG_PASSWORD: "YourPostgresPassword"` <br> `GMAIL_USERNAME: "YourGmailSenderUsername"`<br> `GMAIL_PASS: "YourGmailSenderPassword"`<br>
  > Note:<br> You can use your own gmail account to send emails but first you have to configure 2-Step Authorization and after that you have to configure
  > an APP Password for this specific application. If you want more information about this, GOOGLE IT.
- Execute `rails db:create` to create the database.
- Execute `rails db:seed` to put the five different messages in greeting table.
- Run `rails s` to run the application on port `3000`.
## Tests

- If you want to run some unit tests, all you need to do is:
- On your terminal execute:
  > `gem install rspec`
- Run the `rspec` command in this case over the path of `spec/`, the resulting command will look like this:
  > `rspec spec/`
- If you want to run the tests over the entire project, you can execute the following command:
  > `rspec`
## Author

👤 **Khusiima Luke Masaba**

- GitHub: [@Lucas-Masaba](https://github.com/Lucas-Masaba)
- Twitter: [@MasabaLuke](https://twitter.com/MasabaLuke)
- LinkedIn: [Khusiima Luke Masaba](https://linkedin.com/in/khusiima-luke-masaba)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./MIT.md) licensed.