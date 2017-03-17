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
 >**Note:** You don't need any jQuery for mTip to work. It built on pure javascript and supports most of the browsers out there as listed above.
 
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
The last thing to be done is to activate mTip. In order to activate do this add below code in your head tag.
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
backgroundColor      | ny valid html color in hexadecimal/rgb(0,0,0)/nameOfColor | Sets the background color of the mTip tooltip
color                | Any valid html color in hexadecimal/rgb(0,0,0)/nameOfColor| Sets the forecolor/textcolor of the mTip tooltip text
delay                | Any valid integer                                         | Delays the appearence of the tooltip for the number of miliseconds passed as the value of the delay parameter.
opacity              | Any valid integer between 0 - 1                           | Sets the opacity of the tooltip i.e gives transparency to the tooltip with 0 being transparent and 1 being opaque. Also using this can affect the transparency of contents of the tooltip
position             | bottom, left, right, top                                  | This parameter is used to position the mTip tooltip. Based on the value of the option the tooltip position is either bottom, left, right or top.
selector             | Any valid CSS Selector                                    | This parameter is used to initialize tooltip only on those elements which are identified by the selector as passed in the options for example:- use '.className' for selecting elemets having class as 'className'.
trigger              | click, hover                                              | This parameter is used to tell mTip when to show the tooltip i.e based on the value passes the tooltip is shown either on click of the element or mouse hover.

# FAQ's
1.What is mTip?
-  A cross browser javascript custom tooltip plugin. A simple, flexible, extensible and customizable plugin.

2.Need help with implementing mTip?
- Please go through the Getting Started Section. Still if you face any issue feel free to contact.

3.Do we need jQuery for mTip to work?
- No mTip is a pure javascript plugin. You don't need jQuery for mTip to work.

4.Which all browsers do mTip support?
- mTip supports all modern browsers. IE8+, Edge, Chrome, Firefox, Opera.

5.I found a bug/issue with mTip?
- Go ahead and report a issue on issue tracker on [GitHub Issue Tracker](https://github.com/manishjanky/mTip/issues)

6.How can i customize mTip tooltips?
- There is a range of options available that helps to customize mTip tooltips. Please visit Options section to know more about available options the help customize mTip tooltips.

7.How compatible is mTip tooltip with Internet Explorer?
- mTip supports IE 8 and later versions. It works decently with IE8+. But there might be some things which may come up. You can report if you come across one, we will address your query and try to fix if a issue is reported.


> **More Features Coming Soon.**
