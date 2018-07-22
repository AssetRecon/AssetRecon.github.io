---
layout: post
title:      "CLI Data Gem Project""
date:       2018-07-22 09:42:31 +0000
permalink:  cli_data_gem_project
---


For my Ruby Data Gem Project I decided to write a a command line application that scrapes data from a website that provides live updates to cryptocurrency prices on cryptocurrency exchanges all around the world. 

The requirements for the project were as follows;

1. Provide a command line interface.
2. The command line interface must provide data from an external website.
3. The data provided must go at least one level deep.
4. The application must use good object orientation design patterns.

With these requirements in mind i mapped out my approach by first deciding on what data the application would be scraping. Next, i found some [documentation](http://https://bundler.io/v1.12/guides/creating_gem.html
) that  explained how to develop a RubyGem using Bundler. By simply running bundle gem gem_name, Bundler quickly set up the structure of the soon to be data gem and allowed me to quickly get to work. 

After the project structure was created I headed to github to create a new repository to git push to and with that I was finally ready to actually begin writing some code. 

I decided to first code the CLI logic. This way I would have a pretty good idea about what kind of classes I needed and also what kind of functionality i needed in order to get the data being requested from the CLI. In a way it was almost like writing my own tests. When you want to check if your methods are working correctly, just return to the CLI and verify your commands are returning the results you expected. 

While coding the CLI logic i found it useful to use harded coded data to test my logic. Once I completed the the CLI, I began to replace every hard coded string with the appropriate functionality handled by the appropriate class. For this project I created 3 classes: one that controlled the CLI entirely, one for scraping data, and then one for taking in the scraped data and providing the CLI class with the information requested by the user. 

Overall I would say that once you get through the initial set up and planning, the coding part may go faster than expected as long as you havee already got the general strategy of what you intend to code either written down in pseudocode or outlined in whatever way fits you best. 
