```
Git workflow
```

    https://cloud.github.com/downloads/GArik/progit/progit.ru.pdf

    ![](/assets/git.png)

    What to do:
    # Defining Methods

    Methods allow you to smoothly display code examples in different languages.

    {% method %}
    ## My first method$$
    $$

    My first method exposes how to print a message in JavaScript and Go.

    {% sample lang="js" %}
    Here is how to print a message to `stdout` using JavaScript.

    ```js
    console.log('My first method');
    ```

    {% sample lang="go" %}
    Here is how to print a message to `stdout` using Go.

    ```go
    fmt``.Println("My first method")
    ```

    {% common %}
    Whatever language you are using, the result will be the same.

    ```bash
    $ My first method
    ```
    {% endmethod %}


    1. Create account [https://github.com/](https://github.com/)
    2. Create repository on github 
    3. Download Git client for your OS \( Desktop client for Windows [https://desktop.github.com/\](https://desktop.github.com/%29\) or package git for Linux
    4. Create 



    ### create a new repository on the command line

    ```
    echo "# JavaBaseBook" >>README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/tomkaX/JavaBaseBook.git
    git push -u origin master
    ```

    ### push an existing repository from the command line

    ```
    git remote add origin 
    https://github.com/tomkaX/JavaBaseBook.git
    git push -u origin master
    ```

    ```

    ```







