---
layout: post
title:      "Sinatra: has_secure_password"
date:       2019-01-05 02:48:18 +0000
permalink:  sinatra_has_secure_password
---


* What is has_secure_password and where it comes from

Has_secure_password adds methods to set and authenticate aganist a Bcrypt password. This method requires your class to have a password_digest attribute. However, your forms and controller should still refer to :password rather than password_digest. Has_secure_password is made available to use by adding BCrypt to the gemfile and running bundle install.

* Bcrypt and the role it plays in has_secure_password

Before the has_secure_password method can be used, the bcrypt gem must be added to the gemfile. Bcrypt is a hasing  algorithm that also salts users' passwords. This means that the password will be encrypted, or hashed, in such a way that if someone were to get a hold of the encrypted version of the password, they would have no way to to decypt it. This is much more secure than directly storing user passwords in a database.

* the methods provided by has_secure_password

Has_sure_password provides the following three methods:
   1. authenticate: Returns self if the password is correct, otherwise it returns false.
   2. password=: Encrypts the password into the password_digest attribute, only if the new password is not empty.
   3. password_confirmation=:  Provides password confirmation by allowing you to compare the unencrypted password with the encrypted version. 


