# Rails Swagger Example

> This is a simple example of how to write a Ruby on Rails REST API that includes Swagger documentation.

**This was written based on [this article](https://medium.com/@sushildamdhere/how-to-document-rest-apis-with-swagger-and-ruby-on-rails-ae4e13177f5d).**

## How to Run

> This assumes that you have Ruby and Rails installed, and if you are on Windows, that you have `wsl` setup properly.

Navigate to the project directory, and run the following:
```bash
bundle install
```
```bash
rake db:migrate
```
```bash
rake rswag:specs:swaggerize
```
```bash
rails s
```

Then, in your browser, navigate to the [Swagger documentation](http://localhost:3000/api-docs).