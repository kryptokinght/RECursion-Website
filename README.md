<div align="center">
    <a href="recursionnitd.in">
    <img width="200" height="200" src="https://scontent.fccu5-1.fna.fbcdn.net/v/t1.0-1/p200x200/15232221_726082450888403_3053108573634342595_n.jpg?_nc_cat=101&oh=01941a444fc2bb5a60aed19c56be8701&oe=5C2F6B28">
    </a>
    <br>
    <br>
    <br>
    <a href="https://github.com/RECursion-NITD/RECursion-Website/issues">
    <img src="https://img.shields.io/github/issues/RECursion-NITD/RECursion-Website.svg">
    </a>
    <a href="https://github.com/RECursion-NITD/RECursion-Website/network/members">
        <img src="https://img.shields.io/github/forks/RECursion-NITD/RECursion-Website.svg">
    </a>
	<a href="https://github.com/RECursion-NITD/RECursion-Website/stargazers">
		<img src="https://img.shields.io/github/stars/RECursion-NITD/RECursion-Website.svg">
	</a>
	<a href="https://opensource.org/licenses/MIT">
		<img src="https://img.shields.io/github/license/RECursion-NITD/RECursion-Website.svg">
	</a>
	<a href="https://github.com/RECursion-NITD/RECursion-Website/pulls">
		<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square">
	</a>
  <h1>Recursion</h1>
  <h3>Programming club of NIT Durgapur</h3>
  <p>
    RECursion NIT Durgapur is an initiative to embolden the budding coding minds through regular Code Classes, robust coding competitions and geeky sessions.
  </p>
</div>

<br>

Pioneered by a faction of enthusiasts in 2014, RECursion has continued to evolve ever since. Besides a fancy placement package, we seek to ameliorate participation in programming competitions like ACM ICPC etc.

Our dynamic panel is invariably available to sort any techie doubts and cultivate positivity in you. We intend to create an intriguing ambience where coding is more of a mental sport and after every green tick, the Coder in you gets bigger and wittier. So if you have those bits hovering over your head 24*7, RECursion is your Solution!

**Tech Stack** : 
    
*Backend*: [Ruby on Rails](https://rubyonrails.org/) 

*Frontend*: [Material Design Bootstrap](https://mdbootstrap.com/) 

*Database*: [PostgreSQL RDBMS](https://rubygems.org/gems/pg/versions/0.18.4) 

*Others*: [Moment.js](https://momentjs.com/), 

## Getting Started
* Clone this repo by running the following command in your terminal
    
    ```bash
     git clone https://github.com/RECursion-NITD/RECursion-Website.git
     ```
* Install the *Ruby on Rails* framework by following the steps mentioned in this [tutorial](https://www.tutorialspoint.com/ruby-on-rails/rails-installation.htm).

## Building

Before you start installing the gem dependencies and get the dev server running, make sure you have the lastest version of `bundler` installed. You can install it via the command `gem install bundler`.

```bash
# installs gem dependencies as specified in gemlock
bundle install

# runs (single) migrations that have not run yet.
rake db:migrate

# starts the rail server in debug mode. Goto localhost:3000 to see the website running in development mode.
rails server

```
**NOTE** : When you start the rails server, it will take a very long time(20-40s) to load the website.[Why rails server is slow?](https://stackoverflow.com/questions/16744279/rails-development-server-is-slow-and-takes-a-long-time-to-load-a-simple-page). This is because the rails server starts in debug mode. To bypass the debug mode go to the `config/environments/developemtn.rb` file and change `config.assets.debug=true` to *false*.

## Contribution
* Any suggestions for adding any features or any other functionallity to improve this site and make it more useful and user friendly would be highly appreciated.
* Please follow the contributing guidelines mentioned [here](CONTRIBUTING.md).


## License

 Resursion-website under [MIT License](https://opensource.org/licenses/MIT).


 