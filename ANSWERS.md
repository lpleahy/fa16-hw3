## Questions

Go to `localhost:3000/teachers` in your browser; why does this not work?
We are sending a GET request to this endpoint, which is not routed.

What type of request did your browser just perform?
GET

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
Because we sent a POST request instead, which is routed. 
