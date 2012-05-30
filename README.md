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

Can implement:
Backbone-on-rails

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
