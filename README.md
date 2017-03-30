# Let's Learn JQuery!

## Learning Competencies

* DOM manipulation.
* DOM Traversal.
* Event binding.

## Summary
We will be using JQuery in place of vanilla JavaScript to select elements from the DOM, manipulate those element, and bind events to those elements.

[JQuery](http://jquery.com/) is a very popular library that allows us to use JavaScript with a friendly syntax. JQuery uses CSS selectors to find elements within the dom. We reference JQuery with a $ and then pass the selector for the element we are looking for in as an argument

```
 $(".myelement")
```

We can use the [JQuery Documentation](http://api.jquery.com/) to help us find the functions we need to complete the releases.

## Releases

### Release 0: Traversing and manipulating the DOM
The DOM refers to document object model. This is the representation of the document (a webpage) as a tree structure that we navigate through.

Open up the traverse.html file and use JQuery to access the following elements.

- return the content of the h1 tag
- update the last name to be "Eich" with a capital E
- return all of the list items
- ???


### Release 1: Event Binding
Every time we interact with the DOM events are emitted. We can hook into these events using JavaScript to perform actions when the events occur. For example when we click a button, a click event is fired. We can tap into that event and excecute some code when the button is clicked. 

The JQuery "on" function gives us a friendly syntax to bind to events. Here's the [documentation](http://api.jquery.com/on/) for "on".

A list of events can be found [here](https://developer.mozilla.org/en-US/docs/Web/Events)

Let's add a click handler that displays an alert with a list item's text when clicked.

Now let toggle the visibility of the ul list when the h1 is clicked.

### Release 2: Make a functioning counter
Let's open the counter.html file. We have a nice looking counter but it doesn't do anything yet.

- _ content about adding counter functionality_
- _ content about addind and removing styling with set timeout_
 

### Release 3: Count by numbers other than one
Now let's make our counter increment by five. What updates do we need to make to our code to facilitate that change?

### Release 4: Add multiple counters
What if we wanted to add multiple counters? Will this cause issues with the way our code is currently set up?

Let's add a second counter that increments by 10. Does everything behave as we'd expect?
