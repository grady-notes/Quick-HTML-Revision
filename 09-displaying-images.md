# Displaying Images

Images & multimedia like graphics can be displayed in the browser windows with the help of the `<img/>` tag. This tag does not have a closing tag

This tag has some important yet optional attributes such as the height, width, alt & the most important one, the src attribute.

Some basic & most commonly used attributes of the `<img/>` tag are as follows,

- src - `<img src="exact_path_of_the_file">` The value of the src attribute is the exact_path_of_the_file which should point towards the location of the multimedia or the image file that is to be displyed on the web page. The file can be stored on an online location like giphy, unsplash, google wallpapers or can be stored on the local machine.
  The `<img>` tag is used as follows along with the src attribute.
  `<img src="https://placehold.it/500x500">`

- alt - `<img src="path" alt="info_about_the_image">` the value of the alt attribute is just additional ifonrmation about the media that is being displayed on the webpage. It has no visual representation on the webpaage. This attritube is most useful for websites that have a reader mode because the reader mode canno tdisplay the images, therefore this attribute can be used to display some text about the image. It can also be used when the specified value in the src attribute has moved to a new location & the browser cannt find the new value, however it is a completely optional yet a useful attribute. `<img src="" alt="an image should be displayed here">`

- height & width - `<img src="path" height="value" width="value">` The height & the width attributes are used to force the size or dimensions of the displayed image or the respective media.
