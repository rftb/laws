#Ride Development Standards - This Repo is no longer applicable.



###[Javascript](#JS) 		
###[CSS](#CSS) 		
###[Wordpress](#Wordpress) 		
###[Optimization](#Optimization)   
<br>		
___

The Ride Standards are always changing, don't be afraid to suggest additions if you find a great way to do something that is not here, or to improve upon something tha tis already here. Just bring it up with the other developers so that we can discuss.   

##[<br>](id:JS)JS

#### Standards

###### + Minify and combine Plugins

     // easing 1.83
	jQuery.easing.jswing=jQuery.easing.sw…    
	
	// RoyalSlider  v8.1
	(function(a){function b(b,c){this.slid… 
               		               		
###### + Initilization script should go in **js/scripts.js**

##<br>[<br>](id:CSS)CSS


####Standards

###### + Use **ems** for test sizing
###### + always use **box-siging: border-box;** for div
###### + use our CSS reset [Download](https://github.com/rftb)
###### + better sans font stack.  
	font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
###### + Use sprites for hover states and small UI elements



####Formatting 

    .Selector {  
	  margin: 0 0 0 0;  
	  box-sizing: border-box;  
	}


##<br>[<br>](id:Wordpress)Wordpress

#### Starting a new theme

###### + Use our Framework [Download](https://github.com/rftb/ride)
The Framework has a few features that should be taken advantage of. For Custom Content blocks we are using the plugin [Meta-Box]() *Which is already embedded in the theme*. The config file is **inc/config-meta-boxes.php** 
###### + Use enque_styles( ) && enque_script( ) in functions.php for adding CSS & JS
###### + Home Template -> home.php
###### + Custom Post Types -> inc/post-types.php



##<br>[<br>](id:Optimization)Optimization

####Images 

We need to focuis on speed, without sacrificeing clarity, make your best judgement on compression, ***always keep a copy of the  original***



###### + Optimization Apps
* ImageOptim - PNG (Free)
* Compress - JPG ($9)









#<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>