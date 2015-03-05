# Gsnake
Gluttonous Snake Game wrote in JavaScript on Canvas  
Play on http://zhiyishou.github.io/Gsnake/  
<br>
<br>
Without js library about Canvas , just basic use of Canvas api in single html file , For Study and Fun.
##Shoot
!["runing shoot"](http://zhiyishou.github.io/Gsnake/images/shoot_2.png)  
<br>
<br>
##The function tree structure
<pre>
|----script   
    |----Definations
        |----Global Snake variables
        |----Global Canvas variables
        |----Global Panel variables
        |----Global Stage variables
        |----Global Game status variables
    |----Init Functions
        |----initPanel
        |----initButtons
        |----initStage
        |----initCanvas
        |----initMaps
        |----SnakeNode
        |----initSnake
        |----produceSingle
        |----init
    |----Draw Funcitons
        |----drawScore
        |----drawButton
        |----drawButtons
        |----drawSnake
        |----drawSingle
        |----drawStage
        |----draw
    |----Action Functions
        |----moveSnake
        |----main
    |----Event Functions
        |----KeyDown
        |----getOffsetPosition
        |----determineButton
        |----MouseMove
        |----ClickButton
        |----debounce
        |----bind
        |----Pause
        |----Start
        |----ReStart
        |----Died
    |----ROCK and ROLL
        |----init()
        |----main()
</pre>
