# HTML & CSS workshop: Superheroines project

Create a Superheroines page about your team using HTML and CSS!

You will have an hour to complete your superhero team page.

At the end of the exercise, you will share your superhero page on the big screen and talk about what you have learned.

# Requirements

- code editor (we recommend Visual Studio Code)
- internet browser
- teams of 3

## Page structure: HTML

1. Create a folder called `superheroines` and a file called `index.html` inside the folder.

Add the skeleton of your html file: `<html>` tag containing `<head>` and `<body>` tags.

```
<html>
    <head></head>
    <body><body>
</html>
```

Save changes to your file.

Right click on the file and choose `Open with -> Google Chrome` (or any other Internet browser you use). You will see a blank page.

Right click on the page in the browser and select `Inspect` option. You will see `<html>` tag containing empty `<head>` and `<body>` tags.

2. Let's add some elements to our blank page!

Inside the `<body>` tag, add a `<p>` tag that contains the name of the project:

```
<html>
    <head></head>
    <body>
        <p>Superheroines</p>
    <body>
</html>
```

`p` element stands for the paragraph.

3. Now let's add photos of your team members. Inside your `superheroines` folder, create a folder called `images`. Now add photos of each teammate there. Be creative! You can use someone's mobile phone to take photos and then send them to the Coding Sisterhood Slack channel so that they can be accessed from your laptop.

4. Add photos to your .html file. After the `p` element, add `<image />` tag with the corresponding information about the source of the image. For example, if the photo's name is `my-best-photo.jpeg`, you need to add

```
    <image src="./images/my-best-photo.jpeg" />
```

Save the file and refresh the page - you should see the photo now.

Add the rest of the photos after the first one using the same approach.

In case your photos are too large or differ in size, you can assign them a fixed width to mae them look better. Here is an example:

```
    <image width="200px" src="./images/my-best-photo.jpeg" />
    <image width="200px" src="./images/my-best-photo2.jpeg" />
    <image width="200px" src="./images/my-best-photo3.jpeg" />
```

5. After the images, add information about your superheroine team members' names and superpowers. Use `<p>` to structure your paragraphs. E.g.,

```
    <p>We are: Tania, Kah Men and Kateryna</p>
    <p>Our superpowers are: optimism, ReactJS and gardening skills</p>
```

6. Format your data.

Use `<h1>` (top-level header) tag instead of `<p>` (paragraph) for the project name:

```
    <h1>Superheroines</h1>
```

Refresh your browser page to see how it looks now.

Enclose `We are` and `Our superpowers are` into `<b>` (bold) tags.

```
    <p><b>We are</b>: Tania, Kah Men and Kateryna</p>
    <p><b>Our superpowers are</b>: optimism, ReactJS and gardening skills</p>
```

## Page styling: CSS

Let's prettify your page using some CSS!

1. Create `index.css` file inside your `superheroines` folder. Define your first style there:

```
    h1 {
        color: violet;
    }

```

This style overrides default black colour of the header.

2. Import your css file in .html file. Inside `<head>` tag, add:

```
    <link rel="stylesheet" href="./index.css">
```

Update your browser page and see how the color of the header changed.

3. Similar to changing the colour of the header (`h1`), add style to update the colour of the paragraphs (`p`).

4. Some extra tasks here with references to the corresponding sources?
