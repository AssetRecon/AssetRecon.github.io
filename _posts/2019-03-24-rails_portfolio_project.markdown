---
layout: post
title:      "Rails Portfolio Project"
date:       2019-03-25 03:36:11 +0000
permalink:  rails_portfolio_project
---


For my rails portfolio project i decided to create an app that allows you to share your travel experiences with other users and by doing so everyone can share travel experiences and give out travel suggestions.

Compared to previous projects this one was initially easier to get started on, however I still felt like this project was the most difficult. Some of the challenges I faced was understanding nested resources, implementing signing up through Github and working through ActiveRecord Scope methods. 

Initially all these things seemed duanting, but after finding some helpful resources and answers on slack it turns out that none of it is nearly as intimidating as it seems. I believe it is worth sharing some of these resources in hopes that it will be beneficial to others who may have struggled in the same areas that I did:

* [Nested Resources](https://medium.com/@jaredrayjohnson1/4-things-i-learned-toying-around-with-nested-resources-in-rails-fed6d761e924). Forgetting to pass in the additional arguments in the link helpers is what tripped me up with Nested Routes.

* [OAuth with GIthub](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/). The walkthrough video in the learn.co curriculum was immensly helpful when it came to OAuth.

[ ActiveRecord Scope Methods](https://stackoverflow.com/questions/4869994/what-is-scope-named-scope-in-rails). This is probably the easiest out of the three. As the answers from slack say, creating an scope method this way enables you to do so with only one simple line of code that is chainable. Still, you can create your own class method that can get the job done all the same. From what I understand it is a matter of preference.


