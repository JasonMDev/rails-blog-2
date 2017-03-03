# Rails Commands
This is the summary of the Rails Command used to generate the web page.

        $ rails _5.0.1_ new rails-blog-2
        $ rails g controller posts
        $ rails g model Post title:string body:text
        $ rails db:migrate
        $ rails g model Comment name:string body:text post:references
        $ rails db:migrate
        $ rails g controller comments
        $ rails g controller pages
        $ bundle install --without production
        $ rails g devise:install
        $ rails g devise:views
        $ rails g devise User
        $ rails db:migrate
