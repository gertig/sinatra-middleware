About
=====
sinatra-middleware is a very basic example of a modular Sinatra application.

How to setup in Development
===========================

`$ git clone git://github.com/AndrewGertig/sinatra-middleware.git myapp_dir`

`$ mate myapp_dir/.rvmrc`

Change this line: 

  rvm use 1.9.2-p290@sinatra-middleware --create
  
To:

  rvm use 1.9.2-p290@myapp_dir --create
  
Note: You can also change the rubie that you are using.

`$ cd myapp_dir`

Accept the .rvmrc file

`$ gem install bundler`

`$ bundle install`

`$ shotgun`

Then browse to:

`http://localhost:9393/`