### Send an e-mail using barebone ActionMailer from console
```ruby
ActionMailer::Base.mail(from: 'me@gmail.com', to: u.email).deliver
```
