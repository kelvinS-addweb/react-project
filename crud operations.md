# requirements
-  setup a json-server as described here: https://www.youtube.com/watch?v=1zkgdLZEdwM or here: https://www.npmjs.com/package/json-server#links
-  user port 3005 for api end points
-  db.json file should have these two things: Users and Posts 
    - get list of users from here: https://jsonplaceholder.typicode.com/users and add it into db.json
    - get list of posts from here: https://jsonplaceholder.typicode.com/posts and add it into db.json
- Homepage - localhost:3000/
  - show two links: Users, Posts
  - When I click on Users I want to go to localhost:3000/users and load Users.jsx component
  - When I click on Posts I want to go to localhost:3000/users and load Posts.jsx component
 
- Users.jsx - localhost:3000/users
    - fetch the data from api path "localhost:3005/users" and show it as a list ( a simple HTML <ul> )
    - add a form that will add the user to the above users list. All fields in a User are mandetory. So can't add a user without any field empty. New user added should be reflected in db.json file.
    - each list item should have edit and delete button to edit and delete that user entry from the list
    - For Edit:
        - you can only edit name, and email. Implementation deatils are upto you.
        - when you save the edited data user list dislayed should immediately get updated. You also have to do update the data in backend as well doing the appropriate API calls. All changes should reflect in db.json file.
    - For Delete: 
        - deleted user should be removed from the user list. Also it should be removed from backend in db.json.
  
- Posts.jsx -localhosts:3000/posts
    - fetch the data from api path "localhost:3005/posts" and show it as a list ( a simple HTML <ul> )
    - add a form that will add the post to the above posts list. All fields of a Post are mandetory. So can't add a post without any field empty. New user added should be reflected in db.json file.
    - each list item should have edit and delete button to edit and delete that post entry from the list
    - For Edit:
        - you can only edit name, and email. Implementation deatils are upto you.
        - when you save the edited data post list dislayed should immediately get updated. You also have to do update the data in backend as well doing the appropriate API calls. All changes should reflect in db.json file.
    - For Delete: 
        - deleted post should be removed from the post list. Also it should be removed from backend in db.json.
  
       
