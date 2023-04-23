# How to contribute to CrazyCss

To get started you can find an [issue to work on](https://github.com/EzpieCo/CrazyCss/issues).

## Feature request?

If you have any requests you can create an issue for that, but make sure that there's no similar issue already.

## Bug found

Thought the entire css library is made with pure css and can't produce any errors, but still if you encounter one you can report it by creating an issue.

## Add some code

If you wish to help me out in making crazycss bitter you can add some code by following these steps:

1. Open the `src/utilities` folder and create a new folder with any name.

2. Create a `main.css` file that is going to import all other css files you make need. For example your directory structure can be like this:

   ```
   crazycss/
        src/
            utilities/
                {Your utility}/
                    main.css
                    // other files
   ```

3. In the `src/crazy.css` file import your main.css file and your all done.
