# Magic Mirror
The project I chose to do is the magic mirror, which is essentailly a rapsberry pi with node.js that shows a screen that has the time, weather, and other usefull things. I chose to do this project so I can use the product as an alternative for my phone. 

```

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aidan S. | Oak Park and River Forest High School | Mechanical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my second milestone, I added a feature to the magic mirror that allowed the mirror to turn off after a 2 minute timer ended. My biggest challenge in the process of working on this project came when I was trying to figure out how to use motion sensors to turn on and off my mirror. Unfortunately, they did not end up working. Hopefully I can come back to this project and figure them out. The other challenges came when trying to upload the Javascript on day one and I was easily able to fix them because they were simply outdated lines and I just replaced them with newer versions that supported my pi's version. At BSE I learned a lot about how to use a raspberry pi to create a project, which was really fun. I hope now to use raspberry pi's to create other projects in the future.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/1oT3m4xKQ28?si=u0axokpFt0taX8kL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My project is a magic mirror that provides the date, time, weather, news, and more. I uploaded and ran a program on a raspberry pi computer to display the mirror on a monitor. Later on I will integrate motion detectors to automatically turn on the display when there is motion, and turn off the display after no detected motion for a short period of time to conserve energy. I also plan to add a frame to make it look more pretty.

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry pi 4 kit | computer runs the program to show the mirror | $147.79 | <a href="https://www.amazon.com/RasTech-Raspberry-Starter-Heatsink-Screwdriver/dp/B0C8LV6VNZ?th=1"> Link </a> |
| Wireless keyboard and mouse | Used to control the raspberry pi and run the program | $19.99 | <a href="https://www.amazon.com/Wireless-Keyboard-MARVO-Ergonomic-Compatible/dp/B09P33RWFJ/ref=sr_1_8?crid=25NZHWHJCCIRD&dib=eyJ2IjoiMSJ9.CM5cH1es5BlyFktB1Vxilllr0GbyvUQicyIGHEoVMN48koGBB4W65cZI_1H2q92yKd5_fpnd930q_3UerO24pIF6pdZip6_SQ6Il27zBX9MA1x2A9-n7CNykZa4EPSitgeYhmTzpXSBa3o2k3_S_E97l79BQEp1qunXNSVk1_PicqHudGgKgkrllQS7vokvqnkGDoPLnbvqzgPIXekwHd2ubXzOCZYISrfTiobaE11uCsMxLJmBGacsZcCD9jPno4j5jr3YAD6LH27YuPKInv4YJ5HRbEPGFg1Po9YNknbs.LuRKWFF1zq8wm3HIkvonUc5Jeupk3PiCaeMXJvTHcBY&dib_tag=se&keywords=wireless%2Bmouse%2Band%2Bkeyboard&qid=1779915988&sprefix=wireless%2Bmouse%2Band%2Bke%2Caps%2C606&sr=8-8&th=1"> Link </a> |
| 7 inch lcd display | used for display of the magic mirror | $45.99 | <a href="https://www.amazon.com/Hosyond-Display-1024%C3%97600-Capacitive-Raspberry/dp/B09XKC53NH?th=1"> Link </a> |
| 3 motion detectors | used to turn off display after no detected movment for a certain amount of time | $8.45 | <a href="https://a.co/d/0cDGkhb4"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
