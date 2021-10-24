# Pulsating-social-media-buttons
Pulsating Social media button using HTML and CSS
# HTML 
The HTML part is quite simple in this case all that matters is the CSS part. The HTML icons are created by linking "<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">"  to the HTML file. 

The links for the buttons are specified through the "anchor" tag and social icons are created by setting class for the anchor tag. Example class "fa fa-facebook" creates facebook icon and similarly all other icons are created.

# CSS
The CSS part here plays the major role in creating a pulsating effect for the buttons. Pulsating effect is similar to movement of heart beat. 

This movement is created by "animation" property in CSS. Firstly for the icons padding, width and font size is set to 25px and text is made to align to the center. The background color is set according to the requirement.

The icons are made to appear round by setting the "border-radius" to 50%. The transition for background color is set to 0.2 seconds so that the background color takes 0.2 seconds to change it's color.

The box-shadow is set to "0 0 10px black" so that the buttons will have shadow and appear to be floating . The following properties are specified when the buttons are hovered. The background color is made to change to white within a span of 0.2 seconds as mentioned below. 

The pulsating effect is created by the "animation" property. The "animation-name" is set to "heart" and the "animation-duration" to 0.5 seconds so that the animation will last till 0.5 seconds. The animation-iteration-count is set to "infinite" so that the animation would repeat infinite number of times.

The animation effect is specified by "@keyframes" followed by the animation name. Inside this the change of properties are specified. The properties are made to change with a difference of  5px in all the properties. The box-shadow is made to change fro 100px to 10px so that it would look like the button is pulsating.
