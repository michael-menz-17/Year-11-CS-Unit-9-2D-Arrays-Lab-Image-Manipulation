# Year-11-CS-Unit-8-2D-Arrays-Lab-Image-Manipulation

This lab includes two packages within the src folder: code and image. If you open the code package, you will see a single class called <b>ImageManipulation</b>. <b>This is the only class that you will be writing code in</b>. If you open the image package, you will see four classes within it: APImage, ImageFileFilter, ImagePanel, and Pixel. The only two classes that you will directly use within your program are <b>APImage</b> and <b>Pixel</b>. The <b>APImage</b> class represents an image as a two-dimensional grid of <b>Pixel</b> objects. You will use the constructors and methods in the <b>APImage</b> class and <b>Pixel</b> class in order to complete this lab. The methods for the <b>APImage</b> and <b>Pixel</b> class are listed below.

# APImage class

| <b>APImage CONSTRUCTORS</b> | <b>WHAT IT DOES</b> |
| -------------------- | ------------ |
| APImage()            | Creates an image from a file dialog selection, or creates a blank, 200 by 200, black image if the user cancels the dialog. |
| APImage (String filename) | Creates an image from the given file; throws an exception if the file does not exist or the file is not in JPEG format. |
| APImage (int width, int height) | Creates a blank image of the given width and height, with a color of black. |

| <b>APImage METHODS</b> | <b>WHAT IT DOES</b> |
| ---------------------- | ------------------- |
| int getWidth() | Returns the images width in pixels |
| int getHeight() | Returns the images height in pixels |
| Pixel getPixel(int x, int y) | Returns the pixel at the given position, where x is the column and y is the row |
| void setPixel(int x, int y, Pixel p) | Resets the pixel at the given position, where x is the column and y is the row |
| void draw() | Makes the image’s window visible and draws the image in it |
| APImage clone() | Returns a new instance of APImage that is a copy of this image |
| String toString() | Returns the string representation of the image containing the information (filename, width, and height) |

# Pixel class

| Pixel CONSTRUCTOR | WHAT IT DOES |
| ----------------- | ------------ |
| Pixel(int red, int green, int blue) | Creates a pixel with the given RGB values |

| Pixel METHOD | WHAT IT DOES |
| ------------ | ------------ |
| int getRed() | Returns the pixel’s red value |
| int getGreen() | Returns the pixel’s green value |
| int getBlue() | Returns the pixel’s blue value |
| void setRed(int red) | Resets the pixel’s red value to red |
| void setGreen(int green) | Resets the pixel’s green value to green |
| void setBlue(int blue) | Resets the pixel’s blue value to blue |
| Pixel clone() | Returns a copy of this pixel |
| String toString() | Returns the string representation of the pixel (red, green, and blue values) |

There are six challenges in this lab (challenge 0, challenge 1, challenge 2, challenge 3, challenge 4, and challenge 5). To complete this lab, you will need to complete challenges 0, 1, 2, 3, 4 and 5. Each challenge involves manipulating an image. The image that you will be manipulating is located in your project and is called <b>cyberpunk2077.jpg</b>.

Below are examples of what your output should look like after calling each method.

Challenge 0:

<img width="1390" alt="Screen Shot 2023-03-07 at 3 58 18 PM" src="https://user-images.githubusercontent.com/57818506/223359976-45942c39-3bda-479b-99b0-d366602b0af1.png">

Challenge 1:

<img width="1390" alt="Screen Shot 2023-03-07 at 3 48 09 PM" src="https://user-images.githubusercontent.com/57818506/223360010-588bbbcf-881a-43d7-8f9a-3573f85bfa73.png">

Challenge 2:

<img width="1385" alt="Screen Shot 2023-03-07 at 3 50 15 PM" src="https://user-images.githubusercontent.com/57818506/223360051-d327d84c-5e01-4d90-8793-1995d7380335.png">

Challenge 3 (threshold 20):

<img width="1387" alt="Screen Shot 2023-03-07 at 3 49 41 PM" src="https://user-images.githubusercontent.com/57818506/223360081-f03b02c0-ad01-40a5-912a-4d6a027effac.png">

Challenge 4:

<img width="1387" alt="Screen Shot 2023-03-07 at 4 14 01 PM" src="https://user-images.githubusercontent.com/57818506/223363205-7bdd7c36-1bc1-421d-9678-9cbe97d1d22b.png">

Challenge 5:

<img width="879" alt="Screen Shot 2023-03-07 at 3 48 36 PM" src="https://user-images.githubusercontent.com/57818506/223360180-d77d51cb-9074-48c8-ba63-43e8396812d6.png">

As always, good luck, have fun! =)
