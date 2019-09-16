# Lazy-Loading-using-JQuery

Hello Guys. Today i am going to tell you how to use lazy loading in your website using JQuery. What is Lazy Loading ? Lazy Loading is a concept in which we load content of the website as per the requirement or use. On load of our website, what we generally do is that we load all the content from database, render all data on UI, create all HTML DOMs even if that is not visible to user. This is ok for small website, but it we are going with heavy data websites like eCommerce where we have lots of data to show then we use lazy loading.

In Lazy loading, what we do is we load only that content which is visible on screen at a particular time. And other data rendered when we go to that section maybe by scrolling or maybe using some tabs. This increase the speed and performance of website. I used this concept in my organization while developing web pages in Salesforce.

Here i am sharing a small example of using lazy loading using JQuery plugin in HTML. There are hundred of ways to do, will share other in other posts.

I have used JQuery’s Lazy Loading script that has a function lazyLoad() which is responsible for loading the content when that div comes in visibility. When we create data, we have to comment the code so that it will not be visible on UI and when we use lazyLoad() on parent div, it automatically make the code uncommented and make it visible on UI as soon as that div comes in the screen

To view a demo, visit - http://blog.singhtarandeep.com/lazyloading.html

For complete blog post, visit - http://blog.singhtarandeep.com/blog/2017/05/14/lazy-loading-using-jquery/
