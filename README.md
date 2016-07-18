Project learning how RESTful Routes in Node.js and Express.js work. 


| Name          | Path            | HTTP Verb  | Purpose                                             |
| ------------- |:---------------:| ------:| -------------------------------------------------------:|
| Index         | /blogs          |  GET   | List all blog posts.                                    |
| New           | /blogs/new      |  GET   | Show new blog post form.                                |
| Create        | /blogs          |  POST  | Create a new blog post, then redirect somewhere.        |
| Show          | /blogs/:id      |  GET   | Show info about one specific blog post.                 |
| Edit          | /blogs/:id/edit |  GET   | Show edit form for one blog post.                       |
| Update        | /blogs/:id      |  PUT   | Update a particular blog post, then redirect somewhere. |
| Destroy       | /blogs/:id      | DELETE | Delete a particular blog post, then redirect somewhere. |