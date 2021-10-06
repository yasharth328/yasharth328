function getUsers() {
  fetch("http://jsonplaceholder.typicode.com/users")
    .then(res => res.json())
    .then(data => console.log(data));
}
