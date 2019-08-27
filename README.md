# HeartCode 2019 Web Development
 
![alt text](https://raw.githubusercontent.com/arixpsy/HeartCode/master/README/Template.png)

For the next few exercises you are required to find the correct div card sections and populate the divs with your own content. If you are using the chrome browser, you may want to use chrome's development tools(Press F12) to explore raw html of the website. View more below :point_down:

![alt text](https://raw.githubusercontent.com/arixpsy/HeartCode/master/README/DevTools.png)

Depending on where your development console open, you may view the raw code of the webpage under the elements tab. You may hover over the html code and the rendered html elements will be highlight on the page itself. This is very useful if you are borrowing a html template from a external source and want to understand how the html elements look when it is rendered on the browser.

## Exercise 1(Headers and Text):
1. Look for the div with the class of "card-section blue". Inside, you should be able to find a header tag of "Headers and Text".
    ```html
    <div class="card-section blue">
        <h1>Headers and Text</h1>
        <p>Insert anything you want here</p>
    </div>
    ```
2. For this exercise, you will have edit the contents of this div. Start of by changing the header text to "My Profile".

3. Next, using the ```<p>``` tag fill the div with your name, age and hobbies. it should look something like this.
    ```
    My Profile
    Name: Arix
    Age: 23
    Hobbies: Programming, Sleeping
    ```
4. Next, insert a separating line with ```<hr>```. After the line, insert a list of things you like using ```<ol>``` and ```<li>``` tags.

    * Feel free to experiment with text formatting tags like ```<strike>```,```<u>``` and ```<strong>```.
    * You may want to use a break line ```<br>``` tag before and after the separating line to put some spacing.
5. After completing, it should look something like this :point_down:

![alt text](https://raw.githubusercontent.com/arixpsy/HeartCode/master/README/Exercise1.png)

## Exercise 2(Images and Links):
1. Look for the div with the class of "card-section red". Inside, you should be able to find a header tag of "Images and Links".
    ```html
    <div class="card-section red">
        <h1>Images and Links</h1>
        <p>Insert anything you want here</p>
    </div>
    ```

2. For this exercise, you are tasked to include a image of your preference and a hyperlink to your favourite website.

3. Start of by searching for a image you want (Or you may choose to use the image I provided in the folder ```./assets/images```). Once you have found an image, download the image and place the file in the images folder (Filepath: ```./assets/images```).

4. Next, create a image in div with the ```<img>``` tag. To link the image you have downloaded, include the html attribute ```src``` and set its value to the local file path of the image. It should looks something like this :point_down:
    ```html
    <img src="./assets/images/sushi.jpg">
    ```

5. In other cases, you may choose to link an image without download it. In this case, you can replace the ```src``` value to the url of an image instead of a local path. :point_down:
    ```html
    <img src="https://images.unsplash.com/photo-1514190051997-0f6f39ca5cde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9">
    ```

6. Next, create a link below your image using the ```<a>``` tag. Include a ```href``` attribute and set its value to the url of your favourite website. The code should look something like this :point_down:
    ```html
    <a href="https://www.youtube.com">My Favourite Website</a>
    ```
7. After completing, it should look something like this :point_down:

![alt text](https://raw.githubusercontent.com/arixpsy/HeartCode/master/README/Exercise2.png)

Photo Used: https://unsplash.com/photos/VIv0srmK78g
From bady qb on Unsplash 