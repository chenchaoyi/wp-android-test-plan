# 09 - Publish option enabled for account that hasn't confirmed email yet
----
- **Severity:** high
- **Category:** Product bug

Sign up a new user **from desktop browser** (Note this has to be from desktop, Sign up from mobile devices doesn't seem to require email confirmation). Do NOT confirm the email address from your email inbox. 

Notice the Publish is disabled from desktop browser and there is a hint to ask for email confirmation first:

![](/assets/Screen Shot 2017-03-12 at 11.11.12 PM.png)

Log in from **Android app**, create a new post, and notice the **Publish** button is enabled as usual. After click on it, the post will be only saved to draft, instead of published. 

This is very misleading. The user has to log in from desktop browser to find out what was the reason that the "published" posts are all just saved to draft.
