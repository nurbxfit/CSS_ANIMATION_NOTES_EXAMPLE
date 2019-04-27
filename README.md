## NOTES for CSS ANIMATION

# 1. ' transition-property '
    - to create simple animation or movement we basically changing a state of something to another in time.
    - we call this a transition.
    - in CSS we create animation using a transition properties to describe the change and behaviour.
    - thare are 4 major properties for CSS transition:
        1. transition-property : //describe the css properties that we want to change, 
        2. transition-duration
        3. transition-timing-function
        4. transition-delay

    1. transition-property:
        // describe the css properties that we want to change,
        // let say: we want the transisiton effect to be applied to background properties
        // so we set the transition-property value to background 
        // example-code: 
            .animated-box1 {
                background: white;
                width: 300px;
                height: 300px;
                position: relative;
                margin: auto;
                top: 200px;
                transition-property:background ;
                transition-duration: 3s;
            }
            
            .animated-box1:hover{
                background: black;
            }
            
        //then when we change the background properties, 
        // let say from black to white, 
        // the transition effect will be applied and 
        // we can see that the transisiton of background from black to white /// will slowly takes 3second, 

