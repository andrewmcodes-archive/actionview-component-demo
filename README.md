[![Ruby Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://github.com/testdouble/standard)

# README

## Install

### Clone the repository

```shell
git clone git@github.com:andrewmcodes/rails_template.git
cd project
```

### Update app name

Navigate to `config/application.rb` and change `AndrewmcodesTemplateApp` to whatever the name of your app is.

Do the same in `config/database.yml`

### Dependencies

- Ruby 2.7
- Node 13.7.0
- Rails 6.0.2.1
- Webpacker 4.2.2
- TailwindCSS 1.2.0
- psql (PostgreSQL) 12.1

### Install dependencies

Using [Bundler](https://github.com/bundler/bundler) and [Yarn](https://github.com/yarnpkg/yarn):

```shell
bundle && yarn
```

### Initialize the database

```shell
rails db:create db:migrate db:seed
```

## Serve

```shell
rails s
```
