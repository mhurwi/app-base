App Base
===

trying to get a template running to base an application off.

From Daniel Kehoe's tutorial [rails-mongoid-devise](http://railsapps.github.com/tutorial-rails-mongoid-devise.html)

for bootstrap and cancan, [see this tutorial](http://railsapps.github.com/tutorial-rails-bootstrap-devise-cancan.html)

Mongoid
Devise
CanCan
Rolify
Cucumber
RSpec
Bootstrap-sass
Rails Admin
Backbone-on-rails

Backbone-App
===
The actual backbone code is started by visiting backbone_app/index.  This route can be changed, but it's good to start with. 

The basic public website uses the home_controller, and the home views.  

Visiting /backbone_app/index will load the $(document).ready... code, which will initialize a new App Base backbone app.  That app initializer code is in app_base.js.coffee.  




<code>
ActionMailer:
configure email host in production and test,
to use gmail:
	config.action_mailer.smtp_settings = {
  	address: "smtp.gmail.com",
  	port: 587,
  	domain: "example.com",
  	authentication: "plain",
  	enable_starttls_auto: true,
  	user_name: ENV["GMAIL_USERNAME"],
  	password: ENV["GMAIL_PASSWORD"]
	}
</code>

TODO:
* setup backbone-on-rails to load with seperate controller
* simplform --bootstrap
* setup devise authentication so only authenticated users can access backbone app