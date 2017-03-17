# [mTip](https://manishjanky.github.io/#/mtip)
A flexible, simple and extensible Javascript plugin for custom tooltips by Manish Kumar under MIT license.
### Compatible with 
#### Mozilla Firefox
#### Google Chrome, 
#### IE8+ 
#### Opera

No Jquery required.
Fully Customizable with available options

# Getting Strated

### Download & Include mTip.js
After you Download mTip include mTip.js files in your html.

```javascript
      <head>
             <script type="text/javascript" src="mTip/mTip.js"></script>
      </head>
 ```
 ### Set up Your Markup
 To have the elements to show mTip tooltips set the data-mtip=* attribute to whatever text you want to be shown in the tooltip.
 ```javascript
      //Apply tooltip to a span element
      <span data-mtip="This is a span">This is a span</span>

      //Apply tooltip to a div
      <div data-mtip="This is a div">This is a div</div>

      /Apply tooltip to a image
      <img src="img.jpg" data-mtip="This is a Image">This is a Image</div>
```
### Activate mTip Tooltip
To last thing to be done is to activate mTip. In order to activate do this add below code in your head tag.
```javascript
                //If you are using jQuery
                <script>
                    $(document).ready(function(){
                        mTip();
                    });
                </script>

                //If you are not using jQuery
                <script>
                        window.onload=function(){
                            mTip();
                        }
                </script>

                //If you want to use mTip in angular projects keep the below code in your controller
                <script>
                     $scope.$on('$viewContentLoaded', function () {
                        //Here your view content is fully loaded !!
                        mTip();
                     });
                </script>
```
And there you go nothing else needed. You are successfuly done away with using the default html tooltips and in place of that you will now see tooltips of your choice which you can even configure according to your choice. Read more in Options on how to customize the mTip tooltips.

# Options
mTip gives you a range of options which you can use to customize your tooltips to your satisfaction. Here is how you can use these options.

```javascript
                <script>
                    $(document).ready(function(){
                        mTip({
                            color:"white",
                            backgroundColor:"rgb(158, 226, 235)",
                            position:"bottom"
                        });
                    });
                </script>
```
Below is the list of currently available options. More to come soon.
Option               | Accepted Values                                           | Description
-------------------- | ----------------------------------- |--------------------------------------
backgroundColor      |Any valid html color in hexadecimal/rgb(0,0,0)/nameOfColor |Sets the background color of the mTip tooltip
#### More Features Coming Soon.
