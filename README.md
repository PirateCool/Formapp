# A rails app

Don't forget to run `bundle install`

You can create a user, edit informations and see all users.
You cannot login !

Model, controller, forms, routes generated with

```
rails g scaffold Users username:string email:string bio:text
```

# Routing, views

| routes | URL |
| --- | --- |
| new_user_path | Views/User/New.html.erb  |
| edit_user_path | Views/User/Edit.html.erb  |
| users_path | Views/User/Index.html.erb |
| root_path | Views/Pages/Home.html.erb|

## You can check The Form App on Heroku!!
https://theformapp.herokuapp.com/

### Call me for corrections 
`appear.in/dev-ugo` or in THP slack `/appear dev-ugo`
