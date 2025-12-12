This project is a solution to the API Integration Internship, Where I uses JSONPlaceholder API.

Setup:

pip install -r requirements.txt

uvicorn app.main:app --reload

After Running Server:
Endpoints through which you can see find data.
http://127.0.0.1:8000/docs - Using this URL you can visit to Swagger UI Where you can check all enpoints using Postman Api.

Or Directly,
you can see Endpoints using URL.
http://127.0.0.1:8000/posts
http://127.0.0.1:8000/posts{post_id}
http://127.0.0.1:8000/users
http://127.0.0.1:8000/todos
