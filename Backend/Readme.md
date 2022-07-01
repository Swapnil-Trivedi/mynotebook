# Backend readme Django

## Database and Endpoints needed
### Database models
List of tables and what they are for
- Notes : Contains all the notes for a user
    - title
    - description
    - tag
    - createdAt


- User : Store User data will use default Djanog user model
  - First name
  - Last name
  - Email

### Routes for API
Base Url : ../api/v1/

- auth for login/logout to be added once created
- /notes/
  - [GET]       :  get all the notes for a user
  - [POST]      :  to add a new note
  - [PUT]       :  to update the post 
  - [DELETE]    :  to delete the note
