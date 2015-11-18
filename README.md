Welcome to Blog Rails!
===================


This is the blog done in Ruby on Rails with the goal to learn and practice Ruby on Rails.

Is hosted in url below:

http://blog-wtrindades.herokuapp.com/

----------


How to install project in localhost:
-------------

First you need have installed in your system:

> 

> - Ruby 2.2.3
> - Ruby on Rails 4
> - Postgres 9.5
> - Git

### Steps:
#### Make git clone

```
$ git clone https://github.com/wtrindades/blogRails.git
```

#### Install gems in project

```
$ cd blog/
$ bundle install
```

#### Create and migrate database

```
$ rake db:create
$ rake db:migrate
```

#### Start server

```
$ rails s
```
And access in your browser http://localhost:3000
