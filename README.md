# tachyons-animate
Single purpose classes to help you orchestrate CSS animations

I made this project to help me get more out of my animations. There are NO animation keyframes, only single purpose classes to control:
- animation-play-state : `.pause`
- animation-iteration-count : `.infinite`, `.double`, `.triple`
- animation-direction: `.reverse`, `.alternate`, `.alternate-reverse`
- animation-duration & animation-delay each have a 6 point scale and some absolute values

## Timing Scale:

*Base*:
        a = animation duration
        d = animation delay

*Modifiers*
        1 = 1st step in width scale
        2 = 2nd step in width scale
        3 = 3rd step in width scale
        4 = 4th step in width scale
        5 = 5th step in width scale
        6 = 6th step in width scale

        -1 = literal value 1s
        -2 = literal value 2s
        -3 = literal value 3s
        
*Examples*
        `a1 d-2`
        `a-3 d6
