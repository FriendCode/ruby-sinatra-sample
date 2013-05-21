Sample Web Application using Ruby and Sinatra
=============

[![Code Now](https://friendco.de/widgets/image/codenow?url=https%3A%2F%2Fgithub.com%2FFriendCode%2Fruby-sinatra-sample.git)](https://friendco.de/widgets/url/codenow?url=https%3A%2F%2Fgithub.com%2FFriendCode%2Fruby-sinatra-sample.git)


A complete sample application in ruby using sinatra which 
can run on FriendCode and Heroku.

## Important
 * Requires a **Procfile** to run on **FriendCode** and **Heroku**
 * Like Heroku the port must be fetch from an environment variable called **PORT** (`process.env.PORT` in NodeJs)
 * FriendCode's runtime is in many ways similar to (and compatible with) Heroku's, so be aware of that

## Example :

    require 'sinatra'

    get '/' do
      "Hello, world"
    end

Happy coding !