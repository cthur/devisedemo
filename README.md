# README

Ruby version: 2.3.1
Rails version: 5

Purpose of this Demo:

I want to learn more about the Devise gem and all the features I might be able to incorporate in future websites. 


Topics to Learn:
- Setting up User's database
- Setting up Admin login
- Sessions and cookies
- Creating a preferences page for users
- Setting up email confirmations


Starting a New Project:
- Creating the initial rails app
    rails new devisedemo
- Setting up git
    git init
    git add .
    git commit -m "Message"


Getting the Devise gem installed
- Add the Devise gem to the Gemfile (devisedemo > Gemfile)
    gem 'devise'
- Run the bundle command to install the new gem
    bundle install
- Run the generator
    rails generate devise:install

