In this state you can create users, posts, and comments
They are related to each other, and you can use the console
to test how it works.

For example if you create a user, some posts and some comments,
you can then do
  $user1 = User.find_by(id: 2)
  $user1.comments
And it will output the comments of that user.
Same thing goes for its posts.
