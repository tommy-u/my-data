# my-data
This repo will define the profile specific information for your webpage.

##Instructions
1. Fork and clone this repo.
1. Add a PDF of your resume/cv to the root of this directory.
2. Place a photo of yourself in the root. 
2. Populate `my-data.json` with your profile information, not all fields are
   required, refer to the schema for details. 
2. For social -> email you can hide your email from bots using something like
   [this](https://www.google.com/recaptcha/admin#mailhide).
2. Optionally include some recent news in `news.js` that will be displayed as a
   carousel. 
2. Validate `my-data.json` with the schema to make sure it will render.

You can do this in a [number of ways](http://json-schema.org/implementations.html), with Python, install [jsonschema](https://github.com/Julian/jsonschema)

`sudo pip install jsonschema`

Validate the JSON file.

`jsonschema -i my-data.json my-data.schema`

##Styling your page, make it your own
1. Change the  color theme. Visit
   [here](https://getmdl.io/customize/index.html) to create a color theme. Once
you have chosen your colors download the file from the middle of the color
wheel. Save the file as `theme.css` to the `styles` directory.
2. Edit `styles/styles.css` to change color of icons and carousel buttons. You
   should match this to a color chosen in your theme. Additionally use this file
to add or override any styles.
3. If you dont want to the github ribbon, you can uncomment the style.

##Example

You can view an example JSON file
[here](http://cs-people.bu.edu/wfkoch/my-data/my-data.json)
