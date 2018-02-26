# Assignment
## Requirments
- Java 1.8 
- MySQL database free of choice
- Postman or anything free of choice

To run this project all you need to do is to import as Maven project, create MySQL database (localhost:3306), and call it 'notes_app', and run DemoApplication class

## Avalible end-points:
localhost:8080/
- Get     api/notes
- Get     api/notes/{id}
- Post    api/notes
- Put     api/notes/{id}
- Delete  api/notes/{id})
  
I.E. Send to api call post (localhost:8080/api/notes) with {"title": "trolo", "content":"trolo2"}
