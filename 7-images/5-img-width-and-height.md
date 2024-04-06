# Image Width & Height 📏

You can use the width and height attributes to tell the browser how big your image is.
You just need to write the number of pixels for the width and the height, without any units. For example:

```htm
<img src="images/sky.jpg" width="300" height="200" alt="A blue sky with white clouds and a rainbow" />
```

This means that the image is 300 pixels wide and 200 pixels high. 🌈

The browser needs to download the HTML and the image separately, using HTTP(S) requests.
The HTML is usually smaller and faster to download than the image.
So the browser will show the HTML first, and then the image when it is ready. 🚀

If you don't tell the browser the size of your image, it will have to guess how much space to leave for it.
This can make your web page look messy or jumpy when the image finally appears. 😕

But if you do tell the browser the size of your image, it will know how much space to leave for it from the start.
This will make your web page look smoother and more professional. 😎
