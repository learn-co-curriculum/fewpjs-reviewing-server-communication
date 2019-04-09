## Quiz: Reviewing Server Communication

???

# Reviewing Server Communication

?: Choose which of the following are parts of the process of programming "favoriting" a social media post.

[X] A click event on a heart icon triggers when the icon is clicked by an user.
[] The source HTML file is updated to display a full heart icon.
[X] The DOM is updated to display a full heart icon.
[X] A message is sent to the server when the click event runs.

?: AJAX refers to:

[] another name for `fetch()`.
[] a specific technology for asynchronous web programming.
[X] the technique we use for sending and receiving data behind the scenes of a rendered web page.
[] a way to render HTML pages.

?: Choose the correct code sample for creating an event that uses `fetch()` to receive data and update the DOM.

()
```javascript
fetch('http://api.open-notify.org/astros.json')
.then(function(response) {
  return response.json();
})
```
(X)
```javascript
fetch('http://api.open-notify.org/astros.json')
.then(function(response) {
  return response.json();
})
.then(function(json) {
  console.log(json)
});
```
()
```javascript
fetch('http://api.open-notify.org/astros.json')
.then(function(json) {
  console.log(json)
});
```
()
```javascript
fetch('http://api.open-notify.org/astros.json')
```

?: The following code is a correct way to make a web request using `fetch()`:

```javascript
fetch('https://anapioficeandfire.com/api/books')
.then(resp => resp.json())
.then(json => console.log(json));
```

(X) True
() False

?: Choose which of the following are technologies involved in using AJAX.

[X] JSON
[X] the JavaScript event loop
[] CSS
[X] Promises

?: Since `fetch()` is a relatively new arrival, what are some of the other techniques you might see in older code is involved in performing a similar function?

[X] `$.ajax`
[] a pull request
[X] `XMLHttpRequestObject`
[] a push request

?: Browsers are able to run many different applications and tasks at what seems like the same time to the user by utilizing a:

(X) asynchronous execution model
() synchronous execution model

?: The following code represents a synchronous block of code:

```javascript
let tooMuchData = oneFetch("http://genome.example.com/...");
let lis = document.querySelectorAll("li");
console.log(tooMuchData);
```

() False
(X) True

?: The following code represents an asynchronous block of code:

```javascript
oneFetch("http://genome.example.com/...", tonOfGeneticData => sequenceClone(tonOfGeneticData));
let lis = document.querySelectorAll("li");
```

(X) True
() False

?: If something goes wrong in a `fetch()` request, JavaScript will look through the calls for:

() the first `then()`
() the third `then()`
(X) a `catch()`
() any `then()`

???
