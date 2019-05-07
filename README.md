## Quiz: Reviewing Server Communication

???

# Reviewing Server Communication

?: Choose which of the following IS NOT part of the process of programming "favoriting" a social media post.

( ) A click event on a heart icon triggers when the icon is clicked by an user.
(X) The source HTML file is updated to display a full heart icon.
( ) The DOM is updated to display a full heart icon.
( ) A message is sent to the server when the click event runs.

?: AJAX refers to:

( ) another name for `fetch()`.
( ) a specific technology for asynchronous web programming.
(X) the technique we use for sending and receiving data behind the scenes of a rendered web page.
( ) a way to render HTML pages.

?: Choose the correct code sample for creating an event that uses `fetch()` to receive data and update the DOM.

( )

```javascript
fetch("http://api.open-notify.org/astros.json").then(function(response) {
  return response.json();
});
```

(X)

```javascript
fetch("http://api.open-notify.org/astros.json")
  .then(function(response) {
    return response.json();
  })
  .then(function(json) {
    console.log(json);
  });
```

( )

```javascript
fetch("http://api.open-notify.org/astros.json").then(function(json) {
  console.log(json);
});
```

( )

```javascript
fetch("http://api.open-notify.org/astros.json");
```

?: The following code is a correct way to make a web request using `fetch()`:

```javascript
fetch("https://anapioficeandfire.com/api/books")
  .then(resp => resp.json())
  .then(json => console.log(json));
```

(X) True ( ) False

?: Which of the following technologies ARE NOT involved in using AJAX?

( ) JSON
( ) the JavaScript event loop
(X) CSS
( ) Promises

?: Browsers are able to run many different applications and tasks at what seems like the same time by utilizing a(n):

(X) asynchronous execution model ( ) synchronous execution model

?: The following snippet represents a synchronous block of code:

```javascript
let tooMuchData = oneFetch("http://genome.example.com/...");
let lis = document.querySelectorAll("li");
console.log(tooMuchData);
```

( ) False (X) True

?: The following code represents an asynchronous block of code:

```javascript
oneFetch("http://genome.example.com/...", tonOfGeneticData =>
  sequenceClone(tonOfGeneticData)
);
let lis = document.querySelectorAll("li");
```

(X) True ( ) False

???
