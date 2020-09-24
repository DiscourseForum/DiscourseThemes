---
title: Banner themes (and instructions for customizing them)
author: Daniela
homepage: https://github.com/discourse/discourse-three-columns-banner
download: https://github.com/discourse/discourse-three-columns-banner
demo: 
thumbnail: /images/82368/thumbnail.png
license: MIT License
license_link: https://github.com/discourse/discourse-three-columns-banner/blob/master/LICENSE
category: Theme Components
meta_topic_id: 82368

---
> :loudspeaker: :warning: A new theme component based on this theme has been released, see https://meta.discourse.org/t/versatile-banner/109133. It will be much simpler to configure and maintain because it uses the theme settings introduced immediately after the release of this theme. I invite you to update your banners using the new component. :warning: :loudspeaker:

A good banner:
- should not be invasive. Scrolling the page over and over again to get to site content is never a good thing.
- must be clear and explicit, displaying only the essential information. The fewer lines there are to read, the easier it is for even a distracted user to read them! No one likes walls of text.
- uses colors that recall your brand.
- gives a clear call-to-action. Add only strictly necessary links and make the most important one a button to click.

Also consider these points:
- a picture is worth a thousand words. You can also use a gif, as long as it is not psychedelic!
- do you really need a visible banner even on mobile devices? Often the banners on smartphones are boring, they load with difficulty if they have very heavy images (reduce the weight as much as possible!) and the page must be scrolled over and over again to make it disappear. Consider adding a close button or not putting the banner on mobile devices at all!

_If you are not technical follow the Automatic Installation instructions_

---------

# A three-column Discourse banner

A three column banner that will be responsive and therefore can also be enabled on mobile devices.  

**Automatic installation**: _https://github.com/discourse/discourse-three-columns-banner_  
- Follow this guide https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682. 
- After installing the banner, you have to add it as a component of the main theme (or the main themes if you have more than one selectable by users)
   [details="More details here"]
   ![firefox_2018-03-06_23-16-29: 617x500,50%](/images/82368/h7nwkx5ZMWfxp7eUytRySviFPQ2.png)
   Select the theme component and click Add
   ![firefox_2018-03-06_23-22-59: 622x241,50%](/images/82368/pIHOEfl9Tk4Aj9V7rEZ2GVBbAB5.png)
   
   
   [/details]


**Manual Installation:**

[details="Add the following code in the Common > After Header tab"]

```
<!--SECTION BANNER BOX-->

<section class="banner-box">

	<!--ADD A "CLOSE BANNER" BUTTON ON THE TOP RIGHT-->
	<!--To disable this button, comment the <button> </button> tag-->
	
	<button type="button" class="close">
             <svg class="fa d-icon d-icon-times svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#times"></use></svg>
        </button>

        <div class="container">
	
            <!--SECTION HEADER-->
	        <div class="section-header ">
		
		        <!--TITLE-->
		        <h2 class="x-title"> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h2>

		            <div class="colored-line"></div>

		            <div class="description"><p>
		            Nulla ullamcorper augue vel sodales pellentesque. 
		            Sed vitae sapien sit amet mauris consequat malesuada. Vestibulum vitae iaculis nisl, vel aliquet velit. 
		            Fusce venenatis laoreet diam, non dictum nisl vestibulum non.</p>
		            </div>
		            <div class="colored-line"></div>
	        </div>
	        <!--/END SECTION HEADER-->
	
	            <div class="row">
		

                    <!--SINGLE BOX-->
		            <div class="col3 single-box">
			
			            <!--ICON-->
			            <div class="x-icon"><svg class="fa d-icon d-icon-cog svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#cog"></use></svg></div>
			
			            <!--HEADING-->
			            <h3>A simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est. </p>
			
                	    <!--LIST-->
			            <div>
            		        <ul class="feature-list">
            			        <li><svg class="fa d-icon d-icon-twitter svg-icon svg-node" aria-hidden="true"><use xlink:href="#fab-twitter"></use></svg><a href="your-url"> A tweet</a> to wake up my friends</li>
            			        <li><svg class="fa d-icon d-icon-picture-o svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#far-image"></use></svg> Put the photos in the bag</li>
            			        <li><svg class="fa d-icon d-icon-list svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#list"></use></svg> Rearrange books in the study</li>
            			        <li><svg class="fa d-icon d-icon-thumbtack svg-icon pinned svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#thumbtack"></use></svg> And the notes?</a></li>
            		        </ul>
                        </div>
			
                    </div>
		            <!--/END SINGLE BOX-->
		

                    <!--SINGLE BOX-->
		            <div class="col3 single-box">
			
			            <!--ICON-->
			            <div class="x-icon"><svg class="fa d-icon d-icon-search svg-icon svg-node" aria-hidden="true"><use xlink:href="#search"></use></svg></div>
			
			            <!--HEADING-->
			            <h3>Another simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Integer velit ante, <a href="www.discourse.org">DISCOURSE</a> amet tristique in, gravida at ligula. 
			            Sed gravida mauris id neque vestibulum semper. Suspendisse potenti. Nam nec maximus ligula. 
			            Ut eget semper est. Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum. </p>

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>			
			
		            </div>
		            <!--/END SINGLE BOX-->
		

 
                    <!--SINGLE BOX-->
		            <div class="col3 single-box">
			
			            <!--ICON-->
			            <div class="x-icon"><svg class="fa d-icon d-icon-wrench svg-icon svg-node" aria-hidden="true"><use xlink:href="#wrench"></use></svg></div>
			
			            <!--HEADING-->
			            <h3>Yet another simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Pellentesque ut lacinia nunc, eu molestie nulla. 
			            Pellentesque viverra nisi urna, at hendrerit nisl sodales in. 
			            Morbi auctor sodales nisi, eget aliquam justo maximus in. 
			            Suspendisse a felis a massa elementum pellentesque quis eget dolor. 
			            Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. </p>
			
		            </div>
		            <!--/END SINGLE BOX-->

	            </div>
	            <!--/END ROW-->
  
        </div>
        <!--/END CONTAINER-->

</section>
<!--/END SECTION BANNER BOX-->
```
[/details]


[details="Add the following code  in the Common > Body tab"]
```
<script>

$('#main').on('click', '.banner-box .close', function(e) {

$(e.target).parent().remove();

});

</script>
```
[/details]


[details=" Add the following code in the Common > CSS tab"]

```
/*-------------------------------------------------
   VARIABLES: choose the colors of your banner
-------------------------------------------------*/

$main-color: #FF6C00;
$background-color: #FBDE9C;

/*-------------------------------------------------
   SECTION:  BOXES
-------------------------------------------------*/

.section-header {
    padding-bottom: 20px;
    h2 {
        margin-bottom: 20px;
    }
}

.banner-box {
    margin-bottom: 20px;
    background-image: url("https://i.imgur.com/k7SnZth.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-color: $background-color; /* to be sure that even if the image above will not be loaded there will be at least a colored background */
}

.x-title {
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 15px;
    text-align: center;
    color: $main-color;
}

.description p {
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 15px;
    text-align: center;
}

.banner-box .single-box {
    padding-bottom: 20px;
        .x-icon {
        font-size: 70px;
    }
}

//COLUMNS MANAGEMENT

.col3 {
    width: 30%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col2 {
    width: 45%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col4 {
    width: 22,5%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.container::after, .row::after {
    clear: both;
}

.col2, .col3, .col4 {
    text-align: center;
}

.row::after {
    content: " ";
    display: table;
}

//ICON AND BOX HEADING COLOR

.banner-box .single-box .x-icon, .single-box h3 {
    color: $main-color;
}

//BOX HEADING POSITIONING

.banner-box .single-box h3 {
    margin-top: 20px;
    text-align: center;
}

//COLORED LINE

.colored-line {
    margin: auto;
    width: 165px;
    height: 1px;
    background: $main-color;
}

//SINGLE BOX, TEXT ALIGNMENT

.box p {
    text-align: center;
}

//TEXT ALIGNMENT INSIDE BUTTONS

#my-button {
    text-align: center;
    padding-bottom: 5px;
}

//IMAGE SIZE AS ICON SIZE

.responsive-img {
    border-style: none;
    border-width: 1px;
    height: 70px;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;
}

//LIST ALIGNMENT

.feature-list {
    text-align: left;
    list-style-type: none;
}

//BUTTON BACKGROUND

.col2, .col3, .col4 {
    .btn.btn-icon-text.ember-view {
        background: $main-color;
    }
}

//CLOSE BUTTON ON THE TOP RIGHT
.banner-box .close {
    border: none;
    background: transparent;
    padding-top: 5px;
    float: right;
}
```
[/details]


[details=" Add the following code in the Mobile > CSS tab"]
```
//MOBILE DEVICES

@media only screen and (min-device-width: 320px) and (max-device-width: 800px) {
    .col2, .col3, .col4 {
        width: 90%;
    }
}
```
[/details]

#### What you have to change on this banner:

- `After Header` tab
  - You will have to edit all the text!
  - Change [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/), use your favorites
  - Remember to change the link of the button
- `Common CSS` tab
  - Change the colors of the banner, just change the values within the variables at the beginning of the stylesheet. You can use both the hexodecimal colors (e.g. `#FF6C00`) and the color name (e.g. `red`)
  - Change the `banner-box` background-image URL with the one you prefer

#### And what you can change:
 
- You can delete an item. For example, if the banner closing button is not useful for you, you can comment out or delete it. 
- You can duplicate an item. For example, if you want to add another list or button in another column, copy and paste the relevant code: 
   [details="An example of duplication"]
   ![firefox_2018-03-06_18-37-25: 690x444,60%](/images/82368/7jNIFjRAbAyhUh4P9lpkTE9nhbQ.png)
   ![firefox_2018-03-06_18-48-28: 690x147,60%](/images/82368/mJMyL8RE2IlAK9FpR9dplRWCBed.jpg)
   [/details]
- You can change the number and size of the columns.
  - In the CSS, 3 types of columns are specified:
`col2` = 2 columns banner (each column occupies 45% of the available space)
`col3` = 3 column banner (each column occupies 30% of the available space)
`col4` = 4 columns banner (each column occupies 22.5% of available space)
In the `After Header` tab all I've changed is the name of the columns. Instead of three `col3` columns, in every `Single Box` I changed `col3` to  a `colx`, a `colx` and another `colx`(where x is the number above). It is possible to change the number of columns, for example using 2 Single Box with `col2` (one of the Single Box will be commented), or 4 Single Box with 4 `col4` (the missing Single Box will be duplicated). **The important thing not to break the banner layout (especially on mobile) is that the sum of the columns must always be of width `90%` in total**

   [details="An example of a new layout"]
   All I've changed is the name of the columns. Instead of three `col3` columns, in every `Single Box` I changed `col3` to a `col4`, a `col2` and another `col4`.

   ![firefox_2018-03-06_19-09-05: 690x409,60%](/images/82368/ioRgpe8LScvDmruRo8ANqPM9YM5.png)

   ![firefox_2018-03-06_19-04-06: 690x331,60%](/images/82368/ioH8WifkVUueUTz2DM7lc2aKnQk.jpg)
   [/details]




### How it appears:

Desktop view:

![3col-desktop: 690x319,70%](/images/82368/azqXGDesPdIc5bqU71bzBt3jvZx.png)


Mobile view:

![3col-mobile-optimize: 276x499,50%](/images/82368/53DncdzpcOYT4RcDjvCsF8nvS6W.gif) ![3col-mobile2-optimize: 690x406,50%](/images/82368/gGyo1ie5CvLrJzB7UUASlmbb63J.gif)

-------------------

# A two-column Discourse banner

This is a responsive two column banner that can be also enabled on mobile devices.

**Automatic installation** : *https://github.com/discourse/discourse-two-columns-banner*

**Manual Installation:**


[details="Add the following code in the Common > After Header tab"]

```
<!--SECTION BANNER BOX-->

<section class="banner-box">

	<!--ADD A "CLOSE BANNER" BUTTON ON THE TOP RIGHT-->
	<!--To disable this button, comment the <button> </button> tag-->
	
	<button type="button" class="close">
             <svg class="fa d-icon d-icon-times svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#times"></use></svg>
        </button>
    
        <div class="container">
	
            <!--SECTION HEADER-->
	        <div class="section-header ">
		
		        <!--TITLE-->
		        <h2 class="x-title"> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h2>

		        <div class="colored-line"></div>

		        <div class="description"><p>
		        Nulla ullamcorper augue vel sodales pellentesque. 
		        Sed vitae sapien sit amet mauris consequat malesuada. Vestibulum vitae iaculis nisl, vel aliquet velit. 
		        Fusce venenatis laoreet diam, non dictum nisl vestibulum non.</p>
		        </div>
		        <div class="colored-line"></div>
	        </div>
	        <!--/END SECTION HEADER-->
	
	            <div class="row">
		

                    <!--SINGLE BOX-->
		            <div class="col2 single-box">
			
			            <!--IMAGE-->
                        <img src="https://i.imgur.com/oRoO3Ya.png" class="responsive-img">
			
			            <!--HEADING-->
			            <h3>A simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.
			            Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.</p>
			
                	    <!--LIST-->
			            <div>
            		        <ul class="feature-list">
            			        <li><svg class="fa d-icon d-icon-twitter svg-icon svg-node" aria-hidden="true"><use xlink:href="#fab-twitter"></use></svg><a href="your-url"> A tweet</a> to wake up my friends</li>
            			        <li><svg class="fa d-icon d-icon-picture-o svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#far-image"></use></svg> Put the photos in the bag</li>
            			        <li><svg class="fa d-icon d-icon-list svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#list"></use></svg> Rearrange books in the study</li>
            		        </ul>
                        </div>			

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>
			
		            </div>
		            <!--/END SINGLE BOX-->
		

                    <!--SINGLE BOX-->
		            <div class="col2 single-box" style="float: right">
			
			            <!--IMAGE-->
                        <img src="https://i.imgur.com/ZCXib8B.png" class="responsive-img">

			
			            <!--HEADING-->
			            <h3>Another simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Integer velit ante, <a href="www.discourse.org">DISCOURSE</a> amet tristique in, gravida at ligula. 
			            Sed gravida mauris id neque vestibulum semper. Suspendisse potenti. Nam nec maximus ligula. 
			            Ut eget semper est. Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.
			            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.</p>

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>			
			
		            </div>
		            <!--/END SINGLE BOX-->
		
	            </div>
	            <!--/END ROW-->
  
        </div>
        <!--/END CONTAINER-->

</section>
<!--/END BANNER BOX SECTION-->
```
[/details]


[details="Add the following code in the Common > Body tab"]
```
<script>

$('#main').on('click', '.banner-box .close', function(e) {

$(e.target).parent().remove();

});

</script>
[/details]



[details="Add the following code in the Common > CSS tab"]
```
/*-------------------------------------------------
   VARIABLES: choose the colors of your banner
-------------------------------------------------*/

$main-color: #5270FE;
$background-color: #BFD7FF;

/*---------------------------------------
   SECTION:  BOXES
-----------------------------------------*/

.section-header {
    padding-bottom: 20px;
    h2 {
        margin-bottom: 20px;
    }
}

.banner-box {
    margin-bottom: 20px;
    background-image: url("https://i.imgur.com/4qwhXM3.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-color: $background-color; /* to be sure that even if the image above will not be loaded there will be at least a colored background */
}

.x-title {
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 15px;
    text-align: center;
    color: $main-color;
}

.description p {
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 15px;
    text-align: center;
}

.banner-box .single-box {
    padding-bottom: 20px;
    .x-icon {
        font-size: 70px;
    }
}


//COLUMNS MANAGEMENT

.col3 {
    width: 30%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col2 {
    width: 45%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col4 {
    width: 22.5%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.container::after, .row::after {
    clear: both;
}

.col2, .col3, .col4 {
    text-align: center;
}

.row::after {
    content: " ";
    display: table;
}

//ICON AND BOX HEADING COLOR

.banner-box .single-box .x-icon, .single-box h3 {
    color: $main-color;
}

//BOX HEADING POSITIONING

.banner-box .single-box h3 {
    margin-top: 20px;
    text-align: center;
}

//COLORED LINE

.colored-line {
    margin: auto;
    width: 165px;
    height: 1px;
    background: $main-color;
}

//SINGLE BOX, TEXT ALIGNMENT

.box p {
    text-align: center;
}

//TEXT ALIGNMENT INSIDE BUTTONS

#my-button {
    text-align: center;
    padding-bottom: 5px;
}

//IMAGE SIZE AS ICON SIZE

.responsive-img {
    border-style: none;
    border-width: 1px;
    height: 70px;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}

//LIST ALIGNMENT

.feature-list {
    text-align: center;
    list-style-type: none;
}


//BUTTON BACKGROUND

.col2, .col3, .col4 {
    .btn.btn-icon-text.ember-view {
        background: $main-color;
    }
}

//CLOSE BUTTON ON THE TOP RIGHT

.banner-box .close {
    border: none;
    background: transparent;
    padding-top: 5px;
    float: right;
}
```
[/details]


[details="Add the following code in the Mobile > CSS tab"]
```
//MOBILE DEVICES

@media only screen and (min-device-width: 320px) and (max-device-width: 800px) {
    .col2, .col3, .col4 {
        width: 90%;
    }
    .feature-list {
        text-align: center;
    }
}
```
[/details]

#### What you have to change on this banner:

* `After Header` tab
  * All that is listed in the previous banner and in addition change the  `image src` in the two `Single Box`
* `Common CSS` tab
  * All that is listed in the previous banner


#### And what you can change:
 
- All that is listed in the previous banner, including the number and size of the columns!


### How it appears:

Desktop view:

![two-column-desk: 689x301,70%](/images/82368/iAShCHLJ8Di48jr7kUY4QrkT2tx.png)

Mobile view:

![two-column-mobile-gif: 275x499,50%](/images/82368/4ouhZEFjJl02mHdNNMgoxGnIiTZ.gif) ![two-column-mobile2-gif: 642x378,50%](/images/82368/CVLadGbBsOptl7pONYMwEmpXET.gif)

------------

## A full-width Discourse banner

This is a responsive full width banner that can be also enabled on mobile devices.

**Automatic installation** : *https://github.com/discourse/discourse-full-width-banner*

**Manual Installation:**

[details="Add the following code in the Common > After Header tab "]
[code]
<!--SECTION BANNER BOX-->

<section class="banner-box">

	<!--ADD A "CLOSE BANNER" BUTTON ON THE TOP RIGHT-->
	<!--To disable this button, comment the <button> </button> tag-->

	<button type="button" class="close">
             <svg class="fa d-icon d-icon-times svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#times"></use></svg>
        </button>

        <div class="container">

            <!--SECTION HEADER-->
	        <div class="section-header ">

		        <!--TITLE-->
		        <h2 class="x-title"> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h2>

		        <div class="colored-line"></div>

		        <div class="description"><p>
		        Nulla ullamcorper augue vel sodales pellentesque.
		        Sed vitae sapien sit amet mauris consequat malesuada. Vestibulum vitae iaculis nisl, vel aliquet velit.
		        Fusce venenatis laoreet diam, non dictum nisl vestibulum non.</p>
		        </div>
		        <div class="colored-line"></div>
	        </div>
	        <!--/END SECTION HEADER-->

	            <div class="row">


                    <!--SINGLE BOX-->
		            <div class="col2 single-box" style="float: left;">

			            <!--IMAGE-->
                        <img src="https://i.imgur.com/oRoO3Ya.png" class="responsive-img">

			            <!--HEADING-->
			            <h3>A simple box</h3>

			            <!--BOX DESCRIPTION-->
			            <p class="box">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.
			            Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.</p>

                	    <!--LIST-->
			            <div>
            		        <ul class="feature-list">
            			        <li><svg class="fa d-icon d-icon-twitter svg-icon svg-node" aria-hidden="true"><use xlink:href="#fab-twitter"></use></svg><a href="your-url"> A tweet</a> to wake up my friends</li>
            			        <li><svg class="fa d-icon d-icon-picture-o svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#far-image"></use></svg> Put the photos in the bag</li>
            			        <li><svg class="fa d-icon d-icon-list svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#list"></use></svg> Rearrange books in the study</li>
            		        </ul>
                        </div>

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>

		            </div>
		            <!--/END SINGLE BOX-->


                    <!--SINGLE BOX-->
		            <div class="col2 single-box" style="float: right;">

			            <!--IMAGE-->
                        <img src="https://i.imgur.com/ZCXib8B.png" class="responsive-img">


			            <!--HEADING-->
			            <h3>Another simple box</h3>

			            <!--BOX DESCRIPTION-->
			            <p class="box">Integer velit ante, <a href="www.discourse.org">DISCOURSE</a> amet tristique in, gravida at ligula.
			            Sed gravida mauris id neque vestibulum semper. Suspendisse potenti. Nam nec maximus ligula.
			            Ut eget semper est. Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.
			            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.</p>

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>

		            </div>
		            <!--/END SINGLE BOX-->

	            </div>
	            <!--/END ROW-->

        </div>
        <!--/END CONTAINER-->

</section>
<!--/END BANNER BOX SECTION-->

[/code]
[/details]


[details="Add the following code in the Common > Body tab"]
[code]
<script>
  $('#main').on('click', '.banner-box .close', function(e) {
      $(e.target).parent().remove();
  });
</script>
[/code]
[/details]


[details="Add the following code in the Common > CSS tab "]
[code]
/*-------------------------------------------------
   VARIABLES: choose the colors of your banner
-------------------------------------------------*/

$main-color: #5270FE;
$background-color: #BFD7FF;

/*---------------------------------------
   SECTION:  BOXES
-----------------------------------------*/

.section-header {
    padding-bottom: 20px;
    h2 {
        margin-bottom: 20px;
    }
}

.banner-box {
    margin-top: 18px;
    background-image: url("https://i.imgur.com/4qwhXM3.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-color: $background-color; /* to be sure that even if the image above will not be loaded there will be at least a colored background */
}

.x-title {
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 15px;
    text-align: center;
    color: $main-color;
}

.description p {
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 15px;
    text-align: center;
}

.banner-box .single-box {
    padding-bottom: 20px;
    .x-icon {
        font-size: 70px;
    }
}


//COLUMNS MANAGEMENT

.col3 {
    width: 30%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col2 {
    width: 45%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col4 {
    width: 22.5%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.container::after, .row::after {
    clear: both;
}

.col2, .col3, .col4 {
    text-align: center;
}

.row::after {
    content: " ";
    display: table;
}

//ICON AND BOX HEADING COLOR

.banner-box .single-box .x-icon, .single-box h3 {
    color: $main-color;
}

//BOX HEADING POSITIONING

.banner-box .single-box h3 {
    margin-top: 20px;
    text-align: center;
}

//COLORED LINE

.colored-line {
    margin: auto;
    width: 165px;
    height: 1px;
    background: $main-color;
}

//SINGLE BOX, TEXT ALIGNMENT

.box p {
    text-align: center;
}

//TEXT ALIGNMENT INSIDE BUTTONS

#my-button {
    text-align: center;
    padding-bottom: 5px;
}

//IMAGE SIZE AS ICON SIZE

.responsive-img {
    border-style: none;
    border-width: 1px;
    height: 70px;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}

//LIST ALIGNMENT

.feature-list {
    text-align: center;
    list-style-type: none;
}


//BUTTON BACKGROUND

.col2, .col3, .col4 {
    .btn.btn-icon-text.ember-view {
        background: $main-color;
    }
}

//CLOSE BUTTON ON THE TOP RIGHT

.banner-box .close {
    border: none;
    background: transparent;
    padding-top: 5px;
    float: right;
}

//MAKE IT A FULL WIDTH BANNER

.banner-box .container {
    max-width: 70%;
    margin: 0 auto;
}
.banner-box {
    margin-left: calc(-50vw + 50%);
    margin-right: calc(-50vw + 50%);
    
}
#main-outlet {
    padding-top: 64px; /*this value must be changed if the height of the header has been changed*/
}
.navigation-container, 
.alert.alert-info {
    margin-top: 18px;
    margin-bottom: 0px;
}
[/code]
[/details]


[details="Add the following code in the Mobile > CSS tab"]
[code]
//MOBILE DEVICES

@media only screen and (min-device-width: 320px) and (max-device-width: 800px) {
    .col2, .col3, .col4 {
        width: 90%;
    }
    .feature-list {
        text-align: center;
    }
    .banner-box .container {
        max-width: 90%;
    }    
}

[/code]
[/details]

#### What you have to change on this banner:

* `After Header` tab
  * All that is listed in the previous banner and in addition change the `image src` in the two `Single Box`
* `Common CSS` tab
  * All that is listed in the previous banner

#### And what you can change:

* All that is listed in the previous banner, including the number and size of the columns!

### How it appears:

Desktop view:
![firefox_2018-03-14_20-29-06: 690x306,70%](/images/82368/ed9nFZeHj5MXSsKke8sB4IlKvmE.jpg)

Mobile view: 
There are no differences compared to two or three columns banners

---------

## A Discourse banner that can be expanded and collapsed

This is a responsive banner that can be also enabled on mobile devices.

**Automatic installation** : *https://github.com/discourse/discourse-expand-collapse-banner*

**Manual Installation:**


[details="Add the following code in the Common > After Header tab "]
[code]
<!--SECTION BANNER BOX-->

<section class="banner-box">
            
    <div class="container">
	            
	   <div class="row">

                
            <!--EXPAND COLLAPSE BANNER-->
                
            <div class="banner-content_toggle_wrapper">
            <a role="button" tabindex="0" id="banner-content_wrap_toggle">Expand Details</a>
            </div> 
               
                <!--SECTION HEADER-->

                <div class="section-header ">
		
		            <!--TITLE-->
 		            <h2 class="x-title"> This title will be always visible</h2>

		            <div class="colored-line"></div>

		            <div class="description"><p>
		                Sed gravida mauris id neque vestibulum semper. Suspendisse potenti. Nam nec maximus ligula. 
			            Ut eget semper est. Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.
			            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.      
		            </p>
		            </div>
		            <div class="colored-line"></div>
                </div>
	            <!--/END SECTION HEADER-->
	        
	                <!--BANNER CONTENT WRAP-->
                    <div id="banner-content_wrap" style="display: none;">
                    
                    <!--SINGLE BOX-->
		            <div class="col2 single-box">
			
			            <!--IMAGE-->
                        <img src="https://i.imgur.com/oRoO3Ya.png" class="responsive-img">
			
			            <!--HEADING-->
			            <h3>A simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.
			            Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.</p>
			
                	    <!--LIST-->
			            <div>
            		        <ul class="feature-list">
            			        <li><svg class="fa d-icon d-icon-twitter svg-icon svg-node" aria-hidden="true"><use xlink:href="#fab-twitter"></use></svg><a href="your-url"> A tweet</a> to wake up my friends</li>
            			        <li><svg class="fa d-icon d-icon-picture-o svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#far-image"></use></svg> Put the photos in the bag</li>
            			        <li><svg class="fa d-icon d-icon-list svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use xlink:href="#list"></use></svg> Rearrange books in the study</li>
            		        </ul>
                        </div>			

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>
			
		            </div>
		            <!--/END SINGLE BOX-->
		

                    <!--SINGLE BOX-->
		            <div class="col2 single-box">
			
			            <!--IMAGE-->
                        <img src="https://i.imgur.com/ZCXib8B.png" class="responsive-img">

			
			            <!--HEADING-->
			            <h3>Another simple box</h3>
			
			            <!--BOX DESCRIPTION-->
			            <p class="box">Integer velit ante, <a href="www.discourse.org">DISCOURSE</a> amet tristique in, gravida at ligula. 
			            Sed gravida mauris id neque vestibulum semper. Suspendisse potenti. Nam nec maximus ligula. 
			            Ut eget semper est. Sed ornare sit amet justo eu rutrum. Integer sit amet facilisis ipsum.
			            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
			            Sed id congue eros, sit amet suscipit libero. Nunc vitae placerat est.</p>

               		    <!--BUTTON-->
               		    <div class="buttons" id="my-button">
                  	    <a href="enter-a-url" class="btn btn-icon-text ember-view"><svg class="fa d-icon d-icon-user-plus svg-icon svg-node" aria-hidden="true"><use xlink:href="#user-plus"></use></svg> My new button</a>
                        </div>			
			
		            </div>
		            <!--/END SINGLE BOX-->

                </div>
                <!--/END BANNER CONTENT WRAP-->

        </div>
        <!--/END ROW-->

    </div>
    <!--/END CONTAINER-->

</section>
<!--/END BANNER BOX SECTION-->
[/code]
[/details]


[details="Add the following code in the Common > Body tab "]
[code]
<script>
$("body").on("click", "#banner-content_wrap_toggle", function() {
  $("#banner-content_wrap").slideToggle();
  let buttonText =
    $(this).text() === "Expand Details"
      ? "Hide Details"
      : "Expand Details";
  $(this).text(buttonText);
});
</script>
[/code]
[/details]


[details="Add the following code in the Common > CSS tab"]
[code]
/*-------------------------------------------------
   VARIABLES: choose the colors of your banner
-------------------------------------------------*/

$main-color: #5270FE;
$background-color: #BFD7FF;

/*-------------------------------------------------
   EXPAND-COLLAPSE BANNER
-------------------------------------------------*/
#banner-content_wrap_toggle {
    display: block;
    background: $background-color;
    text-align: center;
    color: $main-color;
    font-weight: bold;
    text-decoration:none;
    padding: 6px 12px;
}

#banner-content_wrap_toggle:hover {
    text-decoration:none;
    color: $background-color;
    background: $main-color;
}

.banner-content_toggle_wrapper {
    float: right;
    border: 2px solid $main-color;
}


/*---------------------------------------
   SECTION:  BOXES
-----------------------------------------*/

.section-header {
    padding-bottom: 20px;
    h2 {
        margin-bottom: 20px;
        margin-top: 35px;
    }
}

.banner-box {
    margin-bottom: 20px;
    background-image: url("https://i.imgur.com/4qwhXM3.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-color: $background-color; /* to be sure that even if the image above will not be loaded there will be at least a colored background */
}

#banner-content_wrap {
    backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
}

.x-title {
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 15px;
    text-align: center;
    color: $main-color;
}

.description p {
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 15px;
    text-align: center;
}

.banner-box .single-box {
    padding-bottom: 20px;
    .x-icon {
        font-size: 70px;
    }
}


//COLUMNS MANAGEMENT

.col3 {
    width: 30%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col2 {
    width: 45%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.col4 {
    width: 22.5%;
    float: left;
    position: relative;
    min-height: 1px;
    padding-left: 15px;
    padding-right: 15px;
}

.container::after, .row::after {
    clear: both;
}

.col2, .col3, .col4 {
    text-align: center;
}

.row::after {
    content: " ";
    display: table;
}

//ICON AND BOX HEADING COLOR

.banner-box .single-box .x-icon, .single-box h3 {
    color: $main-color;
}

//BOX HEADING POSITIONING

.banner-box .single-box h3 {
    margin-top: 20px;
    text-align: center;
}

//COLORED LINE

.colored-line {
    margin: auto;
    width: 165px;
    height: 1px;
    background: $main-color;
}

//SINGLE BOX, TEXT ALIGNMENT

.box p {
    text-align: center;
}

//TEXT ALIGNMENT INSIDE BUTTONS

#my-button {
    text-align: center;
    padding-bottom: 5px;
}

//IMAGE SIZE AS ICON SIZE

.responsive-img {
    border-style: none;
    border-width: 1px;
    height: 70px;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}

//LIST ALIGNMENT

.feature-list {
    text-align: center;
    list-style-type: none;
}


//BUTTON BACKGROUND

.col2, .col3, .col4 {
    .btn.btn-icon-text.ember-view {
        background: $main-color;
    }
}

//CLOSE BUTTON ON THE TOP RIGHT

.banner-box .close {
    border: none;
    background: transparent;
    padding-top: 5px;
    float: right;
}

[/code]
[/details]


[details="Add the following code in the Mobile > CSS tab"]
[code]
//MOBILE DEVICES

@media only screen and (min-device-width: 320px) and (max-device-width: 800px) {
    .col2, .col3, .col4 {
        width: 90%;
    }
    .feature-list {
        text-align: center;
    }
    .banner-content_toggle_wrapper {
    float: none;
    padding-left: 0;
    }
    #banner-content_wrap_toggle {
    height: 35px;
    line-height: 35px;
    }
}

[/code]
[/details]

#### What you have to change on this banner:

* `After Header` tab
  * All that is listed in the previous banner and in addition change the `image src` in the two `Single Box`
* `Body` tab
  * If you change the `Expand Detail`s text of the top right button on After Header, remember that you must use the same name in the script in the `Body` tab
* `Common CSS` tab
  * All that is listed in the previous banner

#### And what you can change:

* All that is listed in the previous banner, including the number and size of the columns!

### How it appears:

Desktop view:
![hide-show-desk: 690x284,70%](/images/82368/WpaFKagF7cqNqz9ScRr8l31WJ3.gif)

Mobile view: 
![hide-show-port: 274x499,50%](/images/82368/l7FdXDRaBalaIcaEYKdn1nr96NM.gif) ![hide-show-land: 690x411,50%](/images/82368/eLVr032xlP8O788R13s5U1ppTyj.gif)



> Coming soon other banners