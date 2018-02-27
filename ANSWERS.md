## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The nil argument represents the "value" argument that is set to nil for this function call. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
This does not work because there is no GET request associated with that link. That link only opens up with a user clicks create teacher in the /teachers/new page.

3. What type of request did your browser just perform?
The browser performed a GET request that failed. 

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
There was a POST request from /teachers that rendered the page correctly!