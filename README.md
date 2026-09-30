# README

T# Blog App — Ruby on Rails

A simple blog application built while learning Ruby on Rails.

## Features
- Create and view blog posts
- Add comments to posts
- Post and Comment association using has_many / belongs_to
- Nested routes (/posts/:post_id/comments)
- Strong parameters for security
- ActiveRecord ORM (no raw SQL)

## What I learned
- MVC architecture in Rails
- ActiveRecord associations and migrations
- Nested resources and routing
- ERB templating and partials
- Debugging NoMethodError in views

## Tech Stack
- Ruby 3.4.11
- Rails 8.1.4
- SQLite (development)

## Setup
```bash
git clone <repo-url>
cd blog_app
bundle install
rails db:migrate
rails server
```