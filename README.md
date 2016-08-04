# 1. Gems
    Ruby Gems are libraries that contain specific pieces of functionality that can be reused in different applications.

    -capybara: Capybara helps you test web applications by simulating how a real user would interact with your app.

    -launchy: helps you open your application when you start it

    -rspec: BDD (Behaviour Driven Development) for ruby. Is what we used in the fizz-buzz challange if im not mistaken? We defined a test, made it fail on purpose, implemented the unit and verified that the implementaion of that unit made the test succeed.

    -shotgun: auto-reloads application after making any changes

    -rack-test: testing API library for rack apps


# 2. HTML 5 minimum requirements

    Every HTML-5 page should start with <!DOCTYPE html>
    As far as I know that is all you need to make a HTML file.

    you usually have a opening html tag that specifies the language for the documents content, that can look like this <html lang="en">

    then you want your head tag where u specify the character encoding for the HTML document (not entirely sure what that does) and link your stylesheets and css. It will look something like this:

    <head>
    <meta charset="utf-8">
    <title>title</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
  </head>

    After that you just have your body tags with the page content!

    All together it will look like this:

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <title>title</title>
        <link rel="stylesheet" href="style.css">
        <script src="script.js"></script>
      </head>
      <body>
        <!-- page content goes here -->
      </body>
    </html>

# 3. Assets

  When we speak about assets, what do we mean?

  Assets are the front-end material, css files, javascript, images etc.
