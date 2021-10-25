# Portfolio
This is a portfolio project done for my WEB503 class with Ali Kahwaji 

This document can be considered my technical document 

I have created this website using Jekyll. I started by following a range of videos and attempting to find something that could be followed easily to create a website using jekyll, as there is a range of commands used in the programming of jekyll to get it functioning. https://www.youtube.com/watch?v=iWowJBRMtpc&t=290s This link was the most legible but not perfect guide to beginning using Jekyll. First I installed jekyll from the website then I used the command in the terminal "jekyll new portfolio" to create a portfolio base. This provides the user the grounds for building the website and may be configured using new html or md files added as files in the main folder, once this is done the user should go into the directory and select the gemfile, add "gem 'webrick'" to the gemfile and run "bundle install" to update the gems being used. This will allow the user to configure and display websites.

The theme for each webpage must be set at the top of the document, allowing jekyll to interpret these pages and manipulate html to display them. This may be "default", "home", "page" or "post" with the minima jekyll theme. 

I have used the "_posts" folder to store posts that would normally be posted to the main landing page, configured as the layout "home", moved this configuration to the "projects.md" tab, so that these "posts" may be displayed and I may have a blurb about the website on the landing page known as "index.md" which is set to the "default" layout style. 

I have not been able to deploy this website on github pages despite multiple attempts. However it fucntions correctly when run locally. 