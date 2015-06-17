#Group Practice for Launch Challenge

Answer the following questions:

- How would you return all the recipes in your database?
- Recipe.all
- How would you return all the comments in your database?
- Comment.all
- How would you return the most recent recipe posted in your database?
- Recipe.all.last
- How would you return all the comments of the most recent recipe in your database?
- Recipe.all.last.comments
- How would you return the most recent comment of all your comments?
- Comment.all.last
- How would you return the recipe associated with the most recent comment in your database?
- Comment.all.last.recipe
- How would you return all comments that include the string brussels in them?
- Comment.where("comments.body LIKE ?", '%brussels%')
- Comment.where("body LIKE ?", '%brussels%')
