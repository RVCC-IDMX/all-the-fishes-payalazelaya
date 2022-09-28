# All the Fishes

### Attributions for Images

[Angel Fish](https://www.freepnglogos.com/pics/fish)

[Blue Fish](https://www.freeiconspng.com/img/3925)

[Tropical FIsh](https://www.freeiconspng.com/img/3928)

[Colorful Fish](https://www.freeiconspng.com/img/41477)

[Fish](https://www.freeiconspng.com/img/3919)

[Fish Tank](https://snipstock.com/image/aquarium-fish-tank-png-images-8-png-84058)

[Bubble](https://www.freeiconspng.com/img/44336)

[Cartoon Fish](https://www.freeiconspng.com/img/26345)

### Code Strategy

#### Fishes
Three of the fishes are facing the other direction because of how multiplying their scale in the x-direction by -1 will make them flip. The six fishes have their own animations that make them float and bob from side to side in the water. Each 2 fishes are moving at different speeds and are located in different positions based on their x and y-axis. The wobbles down below are slight variations from the initial code of how to do wobbles 
``` Wobbles 
let wobble = Math.sin(time / 350) * 40;
let wobble2 = Math.sin(time / 500) * 40;
let wobble3 = Math.sin(time / 200) * 20;
``` 

#### Bubbles 
The bubbles are scaled at random sizes and start to appear at random y and x positions on the canvas. Everytime the bubbles refresh after having been floating across the canvas, their x position is set to 0 and their y position plus scale is randomly generated so it looks like there's a new stream of bubbles coming from the right to the left of the canvas everytime there's active animation going on. 
