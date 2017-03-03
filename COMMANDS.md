# Rails Commands
This is the summary of the Rails Command used to generate the web page.

        $ rails _5.0.1_ new rails-blog-2
        $ rails g controller posts
        $ rails g model Post title:string body:text
        $ rails db:migrate
        $ rails g model Comment name:string body:text post:references

        $ rails g scaffold Link title:string url:string
        $ rails g devise:install
        $ rails g devise:views
        $ rails g devise User
        $ rails g migration add_user_id_to_links user_id:integer:index
        $ rails g acts_as_votable:migration
        $ rails g scaffold Comment link_id:integer:index body:text user:references --skip-stylesheets
        $ rails g migration add_name_to_users name:string
