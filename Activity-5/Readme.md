# Activity 5

Nice work on the todos!

Now let's see your chops at working with less instructions:

## Step 1
Work together with your team member to complete all the steps from the last activity for links.

* Create a POST request with the path `'/link'`.

* Create a POST route to handle that request.

Use

```
$("#url").on('keyup', setLink);
```

to trigger the POST request function.

and send

```
var newName = {
          userName: $("#usr-name").val(),
}
```

as the data in the post request

## Step 2

Make sure that the links are being added correctly to your database. Once they are, work on creating:

* a GET request to get the todo list and display the todos on the page

* a GET route to handle those requests

Use the following code to append the todos:

```
 $("#links").append('<button type="button" class="list-group-item linkitem" data-id="' + data[i].id + '">' + data[i].linkName + '</button>');
 ```
