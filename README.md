# a Rails Todo MVC
This small rails project demonstrates the power of single page apps.

Unlike the more typical todo demos over at [todo-mvc](http://todomvc.com),
which showcase how different JavaScript frameworks handle different design patterns,
this is a demonstration of how easy something similar is to put together with rails.

The biggest benefit of using rails as a backend in this way is data persistence.
That is to say tasks actually live in a database that can be interacted with.
When you hit refresh data is still there.

This is a proof-of-concept build and a start into the world of single page apps.
Future development could include user-specific lists and the like.

##To see in the wild
As of Sept 16, 2016 you can see a version of this app [on heroku](https://todo-dan-pow.herokuapp.com/)

You can also **recreate locally** by following these steps:
1. Fork and/or clone down
2. `cd` on in and run `bundle install`
3. Create the databases using `rake db:create:all`
4. Fire up a rails server using `rails s`
5. In your favorite modern browser head to [localhost:3000](http://localhost:3000)

## Check out the brains
The jQuery brains of the operation are in [app/assets/javascripts/tasks.js](https://github.com/danielpowell4/todo/blob/master/app/assets/javascripts/tasks.js)
