# HOWTO insert pictures and other media into Markup file

Hi,
My name is Olesya. I like new technologies and would like to learn how to code to create something useful.

My HOWTO notes for a Markup file in Github:
example of uses can be to create more interesting README file

### 1. to add a code snippet, add three tildes \~~~ on the line above and below the desired code.
  
   for example, write this in Markdown:

   \~~~

   print("Hello World!")

   \~~~

   it will look like this when implemented:
   ~~~
   print("Hello World!")
   ~~~

### 2. inserting images template:
   ~~~
   ![alt text](http://url/to/img.png)
   ~~~
You can link to image URL from external source or directly from your repository

Image referenced from external source, tec-science in this case
![Image referenced from tec-science website](https://www.tec-science.com/wp-content/uploads/2021/03/en-worm-gear-globoid-worm-helical-gear-768x432.jpg)


### 3. To resize the image is better to use HTML (I am doing 50% of original size here)


\<img src="https://www.tec-science.com/wp-content/uploads/2021/03/en-worm-gear-globoid-worm-helical-gear-768x432.jpg" width="50%" height="50%"/>

<img src="https://www.tec-science.com/wp-content/uploads/2021/03/en-worm-gear-globoid-worm-helical-gear-768x432.jpg" width="50%" height="50%"/>


### 4. For side by side image display, place HTML code ritght next to the the previous image code and it will appear side by side
<img src="https://www.tec-science.com/wp-content/uploads/2021/03/en-worm-gear-globoid-worm-helical-gear-768x432.jpg" width="50%" height="50%"/><img src="https://www.tec-science.com/wp-content/uploads/2021/03/en-worm-gear-globoid-worm-helical-gear-768x432.jpg" width="50%" height="50%"/>
