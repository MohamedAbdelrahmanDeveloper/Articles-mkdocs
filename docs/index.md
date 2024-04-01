# Welcome to index

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project hhhh

    mkdocs.yml    # The hamo file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

<p>hello<p>
<script>
        async function logMovies() {
        const response = await fetch("http://localhost:3000/api/auth/register", {
                method: "POST", // *GET, POST, PUT, DELETE, etc.
                mode: "cors", // no-cors, *cors, same-origin
                cache: "no-cache", // *default, no-cache, reload, force-cache, only-if-cached
                credentials: "same-origin", // include, *same-origin, omit
                headers: {
                "Content-Type": "application/json",
                // 'Content-Type': 'application/x-www-form-urlencoded',
                },
                redirect: "follow", // manual, *follow, error
                referrerPolicy: "no-referrer", // no-referrer, *no-referrer-when-downgrade, origin, origin-when-cross-origin, same-origin, strict-origin, strict-origin-when-cross-origin, unsafe-url
                body: JSON.stringify({
                    "username": "hadmdo",
                    "email": "hamdo@hddamo.com",
                    "password": "123456789"
                }), // body data type must match "Content-Type" header
        });
        const movies = await response.json();
        console.log(movies);
        }
</script>
<form onclick="logMovies()" action="https://github.com/MohamedAbdelrahmanDeveloper/Articles-mkdocs.git" method="GET">
    <input name="hello"/>
</form>

```html
<p>hello<p>
    <input />
```

```js
alert()
let a = "string"
```