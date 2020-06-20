This guide assumes no prior programming experience and is just one example of how to go about it.

# Table of Contents

[Terminal/Shell Resources](#terminal-shell-resources)
[Text Editors](#text-editors)
[Git and Github](#git-and-github)
[Vagrant](#vagrant)
[HTML](#html)
[CSS and SASS/SCSS](#css-and-sass-scss)
[JavaScript](#javascript)
[SQL](#sql)
[Ruby](#ruby)
[Ruby on Rails](#ruby-on-rails)
[Deploying Your App](#deploying-your-app)


## Terminal/Shell Resources

When running Catalina, stick with the default zsh shell that the terminal comes with, instead of bash. However, it seems like a lot of the commands used in the zsh shell are similar to bash, so here are some bash resources.

- https://www.makeuseof.com/tag/beginners-guide-mac-terminal/ (upto sudo section)
- https://ss64.com/osx/ (Reference, not a tutorial)
- http://linuxcommand.org/lc3_learning_the_shell.php (No need to look at the whole shell scripting section, as scripting is much easier in Ruby for beginners)
- https://www.learnenough.com/command-line (This whole thing looks pretty good)
- https://en.wikipedia.org/wiki/Man_page (Important when you don’t know how to use certain commands)
- https://vitux.com/get-help-on-linux-shell/ (More on how to get help)
- https://medium.com/@vietkieutie/what-happens-when-you-type-ls-c-into-your-shell-e2faf1ad2dbd (Advanced explanation as to what actually happens under the hood)
- https://medium.com/@jalendport/what-exactly-is-your-shell-path-2f076f02deb4 ($PATH is super important)
- https://www.digitalocean.com/community/tutorials/how-to-read-and-set-environmental-and-shell-variables-on-a-linux-vps (Good primer on environment variables)

## Text Editors 

Use Visual Studio Code and either vi or emacs for a terminal-based text editor

- https://flaviocopes.com/vscode/ (Nice VSCode tutorial)
- https://www.cs.colostate.edu/helpdocs/vi.html (vi commands)
- https://www.gnu.org/software/emacs/tour/ (Guided emacs tour)


## Git and Github

Git is super important for managing the state of your code

- https://try.github.io/ (This looks especially good)
- https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes (READMEs are important for anyone else who’s looking at your code)
- https://guides.github.com/activities/hello-world/ (Intro to Github)
- https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners (Pretty solid)
- https://git-scm.com/book/en/v2 (More in-depth dive about git concepts)
- https://git-scm.com/docs (Reference only, not a tutorial)

## Vagrant

Vagrant helps you create a development environment that simulates your production environment. Locally, you’re using MacOS, but a lot of servers out there to deploy your code mostly use Linux. As a result, you’ll be working within a Linux virtual machine environment most of the time.

- https://www.vagrantup.com/intro (Intro to Vagrant)
- https://www.vagrantup.com/downloads (Download Vagrant)
- https://www.virtualbox.org/wiki/Downloads (Install Virtualbox)
- https://www.vagrantup.com/intro/getting-started/project_setup (Project Setup)
- https://www.vagrantup.com/docs/vagrantfile (What is a Vagrantfile?)
- https://www.vagrantup.com/intro/getting-started/boxes (What is a Vagrant box?)
- https://app.vagrantup.com/bento/boxes/amazonlinux-2 (Use a Vagrant box similar to your production environment)
- https://www.vagrantup.com/intro/getting-started/up (Starting your Vagrant box)
- https://www.vagrantup.com/intro/getting-started/synced_folders (cd into /vagrant to access the project located on your host machine)
- https://www.vagrantup.com/intro/getting-started/networking (In your Vagrantfile, forward a specific port on your home machine to a port within the box. Common configuration for web server in Rails is host: 4000 and guest: 3000)

## HTML

HTML is text that the browser parses with its own code behind-the-scenes to create a webpage

- https://learn.shayhowe.com/html-css/ (Super good for both HTML and CSS)
- https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML (You’ll find out that Mozilla is one of the best when it comes to web-related resources)
- https://developer.mozilla.org/en-US/ (Reference for all things web, no need to read it all at once)

## CSS and SASS/SCSS

CSS is text that the browser parses with its own code behind-the-scenes to style a webpage

- https://learn.shayhowe.com/html-css/ (Super good for both HTML and CSS)
- https://learnlayout.com/ (Layout is the hardest part about CSS)
- https://css-tricks.com/specifics-on-css-specificity/ (CSS Specificity, CSS Tricks in general is a really good CSS resource)
- http://www.standardista.com/wp-content/uploads/2012/01/specificity3.pdf (CSS Specificity Examples)
- https://developer.mozilla.org/en-US/docs/Learn/CSS (Mozilla CSS reference)
- https://developer.mozilla.org/en-US/docs/Web/CSS/Reference (CSS Properties to use as a reference)
- https://sass-lang.com/ (SASS/SCSS is the primary CSS preprocessor in Rails)

## JavaScript

JavaScript is a language that was initially made for the browser, but is now commonly used in a general programming context as well.

- https://javascript.info/ (Super good modern JavaScript tutorial)
- https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics (JS basics)
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Variables (Variables in JS)
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures (Data types in JS)
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence (Operator Precedence)
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling (Control flow and error handling)
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions (Functions)
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects (Objects)
- https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q/playlists (Fun Fun Function is my favorite JavaScript Youtuber)
- https://github.com/mbeaudru/modern-js-cheatsheet (Modern JS Cheatsheet)

## SQL

Rails allows you to use a relational database to manage all of your data. When it comes to a particular database in question, I highly recommend using PostgreSQL.

- https://www.youtube.com/watch?v=FR4QIeZaPeM (What is a database and SQL?)
- https://web.csulb.edu/colleges/coe/cecs/dbdesign/dbdesign.php?page=sql/ddldml.php (Data definition and data manipulation)
- https://www.codecademy.com/learn/learn-sql (Good SQL tutorial)
- https://guides.rubyonrails.org/active_record_basics.html (Interfacing with your db in Rails through Active Record, go through all of the other ActiveRecord sections in the Rails Guides as well)
- https://guides.rubyonrails.org/active_record_migrations.html
- https://guides.rubyonrails.org/active_record_validations.html
- https://guides.rubyonrails.org/active_record_callbacks.html
- https://guides.rubyonrails.org/association_basics.html
- https://guides.rubyonrails.org/active_record_querying.html
- https://www.postgresqltutorial.com/ (This tutorial on Postgresql Looks pretty good)
- https://www.postgresql.org/docs/12/index.html (Use as a reference)

## Ruby

Ruby is a great general programming language and it’s currently most famous for being used in Ruby on Rails (or Rails for short)

- https://www.codecademy.com/learn/learn-ruby (Covers all of the basic types)
- http://www.r-5.org/files/books/computers/dev-teams/diagrams/Sandi_Metz-Practical_Object-Oriented_Design_in_Ruby-EN.pdf (How to write great Ruby code)
- https://ruby-doc.org/core-2.7.1/ (Use as a reference and not read all at once when you want information on certain types)
- https://en.wikipedia.org/wiki/RubyGems (What is a gem?)
- https://guides.rubygems.org/rubygems-basics/ (RubyGems basics)
- https://guides.rubygems.org/command-reference/ (Use as a reference)
- https://en.wikipedia.org/wiki/Shebang_(Unix) (Applicable when you want to write your own scripting)

## Ruby on Rails

One of the most popular web frameworks and most approachable in my opinion.

- https://guides.rubyonrails.org/getting_started.html (Start here)
- https://guides.rubyonrails.org/index.html (Scope out the entire site over time and you’ll eventually become a pro when it comes to concepts)
- https://www.railstutorial.org/book (This whole thing is really good)
- https://bundler.io/gemfile.html (What is a Gemfile?)


## Deploying Your App

Make your application available to the world! I’m going to go into AWS resources when it comes to deploying, as it is a cost-effective way to do so, albeit a little tedious.

- https://portal.aws.amazon.com/billing/signup#/start (Since AWS has a 12-month free tier, only create a new AWS account only when you’re ready to deploy your code for the world to see. I made a mistake creating an AWS account a long time ago and don’t have much of my free tier left.)
- https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/ruby-rails-tutorial.html (Deploy a Rails app to AWS with Elastic Beanstalk)
- https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html (Read through all of the AWS Elastic Beanstalk guides for more advanced usage)
