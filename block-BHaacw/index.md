- Create a responsive layout according to the design shown below.

![CSS Grid Assignment I](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/css-grid/assignment-1/card.png)

- Find the medium and small screen design in the assets folder.

- Chose your own images for the assignment.

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.

- Pay attention to the codes, your code quality matters a lot.

- Try to implement the layout as exactly as it has been provided in the design.

- Pay attention to minor things like spacing, alignment, size, etc.

- Use any font-family which suits better for the assignment.

- Once you are done with the assignment connect with the mentor and get the code reviewed.
c

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="./assets/stylesheets/style.css" />
  </head>
  <body>
    <header class="header">
      <div class="container">
        <h1 class="page-heading">card layout</h1>
        <nav class="nav">
          <ul class="nav-menu">
            <li class="nav-menu-item">home</li>
            <li class="nav-menu-item">about</li>
            <li class="nav-menu-item">gallery</li>
            <li class="nav-menu-item">blog</li>
            <li class="nav-menu-item">references</li>
            <li class="nav-menu-item">contact</li>
          </ul>
        </nav>
      </div>
    </header>
    <main>
      <section>
        <div class="container">
          <div class="grid-container one">
            <article>
              <h2>the title</h2>
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <a href="#">Learn more...</a>
            </article>
            <article>
              <h2>the title</h2>
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <img src="./assets/cat.png" alt="cat" />
              <a href="#">Learn more...</a>
            </article>
            <article>
              <h2>the title</h2>
              <img src="./assets/cat.png" alt="cat" />
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <a href="#">Leran more...</a>
            </article>
          </div>
          <div class="grid-container two">
            <article>
              <h2>the title</h2>
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <a href="#">Learn more...</a>
            </article>
            <article>
              <h2>the title</h2>
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <a href="#">Learn more...</a>
            </article>
            <article>
              <h2>the title</h2>
              <p>
                Some Text goes here, some text goes here, some text goes here,
                some text goes here.
              </p>
              <a href="#">Learn more...</a>
            </article>
          </div>
        </div>
      </section>
    </main>
  </body>
</html>
