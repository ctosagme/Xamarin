## Wack-A Sora 
This Game is a xmal form using / CSharp / Xaml / Visual Studio this is an open-source code focus and no virus code.

## Where to find the code?

- to find the code for the game simple click the main branch and you will see in the drop down menu game_patch_1 you can see on the picture below <br>
![Screensho1](https://github.com/ctosagme/my_picture/blob/main/Screenshot%202023-03-19%20164626.png)

- if you click the game_patch_1 you can all the file picture below

![Screenshot2](https://github.com/ctosagme/my_picture/blob/main/Screenshot%202023-03-19%20164836.png)

## How to run this game to your devices?
- First Download Visual Studio 2022 into your Windows/Macs/Linux [Here](https://visualstudio.microsoft.com/)
- Second when done download the Visual Studio you need to download .NET Multi-platform UI Development
![Screenshot4](https://github.com/ctosagme/my_picture/blob/main/installer.png)

- Third navigate to the top pane of the visual studio installer and click individual components
![Screenshot5](https://github.com/ctosagme/my_picture/blob/main/navigation.png)

- Fourth Search for Xamarin and there's three things will pop Xamarin, Xamarin Remoted Simulator and Android SDK Setup then install.
![Screenshot6](https://github.com/ctosagme/my_picture/blob/main/download_xamarin.png)

## Documentation

First I want to address how the grid is working in just a simple StackLayout with a grid. Stacklayout works is simple, Stacklayout is a organize child view in a one-dimensional stack this is by default this is a oriented vertically.
![Stacklayout](https://learn.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/layouts/stacklayout-images/layouts-large.png#lightbox)

- as you can see here in the game how's the stacklayout working.<br>
<img src="https://scontent.fmnl9-4.fna.fbcdn.net/v/t1.15752-9/336538244_620001529946473_8830619957560444391_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeE-fLOeyiP6L0LzgGhTy7m8mwfluyOBP3-bB-W7I4E_fwGICIrhgJKvvbOidu-tnTSyfGVmA6_QVcol4Hu-d-rs&_nc_ohc=y2-hVKBEEyQAX_2vu9g&_nc_ht=scontent.fmnl9-4.fna&oh=03_AdSILiwYBU1JHEtSjTWYVqTwsh7IlrjzPF4oalLlrnBHjg&oe=643E5AA6" width="300" height="500"/>

- in the game the character that you see is clickable in the code you  will see .xaml file that's where you can find the code. the code work by simple ImageButton this will be a clickable button for the character that you see in the code.
![xaml](https://github.com/ctosagme/my_picture/blob/main/mainpage.png)
- so how the random generate picture works in the game you will know when you click a character the whole grid picture will change overtime the code for this is .xaml.cs
when you open the code in the line of code 14 i put a Public Random r = new Random (); this is where the line of code 68 comes in. you will see i use i did do while syntax with a switch case in this whole code you will see if else statement you will see mole statement T stand for top M stand for Middle and B stand for Bottom when you click the character it will go to the if else statement this is where the random comes in you will see in the line of code 73 i did is r.Next(1,3) "Array 0,1,2" if you click the character when the random print 1 it will go to the if statement then if the character hit 2 or 0 it will go to the else statement <br>
![random](https://github.com/ctosagme/my_picture/blob/main/random.png)

- How's the animation working? the animation is simple coded by the await Task.WhenAny<bool>
this is where  the character rotate, move and faded to rotate i called Rotate to 360 and how many milisecond i put in for example 6000 milisecond this is 6 in second. to move the character i simple TranslateTo 0, 100 to move forward and go back when the milisecond done<br>
![animation](https://github.com/ctosagme/my_picture/blob/main/animation.png)

- How's the Scorring board working? if we go back in the do while loop you will see a counter inside in the do while loop and in while open close parenthesis. to get point in the game go to line of code 223  you will see an if else statement  that says moleHolder == "File: sora.png" this is where when you hit the boy character in the game it will give you plus one point in the else statement if you click the other character you will lose points when the end game is near in the line of code 250 if else statement this is where you gonna see the DisplayAlert  that you win or lose the game the code for displayalert is in the line of code 272 and 276<br>
![scorring](https://github.com/ctosagme/my_picture/blob/main/Scorring.png)
- How's the timer working? in the line of code of 31 
this is on the public MainPage when you start the game in will count down backwards this is because of the counter that you see in the if else statement it will countdown " in the given time " in your screen on the top corner of the game and if the timer run to 0 it will go to the else statement that it will give the displayalert and it will push you to the menu <br>
![timer](https://github.com/ctosagme/my_picture/blob/main/timer.png)
- Menu
This is just a simple menu that pushnavigate in the difficulty of the game. the code are simple check the Page1.xaml and Page1.xaml.cs
![page1](https://github.com/ctosagme/my_picture/blob/main/page1.png)

> note this is an open-source code you can try to yourself if there's an error you can check it on youtube.
