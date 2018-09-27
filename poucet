while not front_is_clear():#tant que ce n'est pas libre devant lui
    turn_left()#on tourne
while front_is_clear():#tant que c'est libre
    if next_to_a_beeper():#si il detecte un beeper
        pick_beeper()#on le prend
    if left_is_clear():
        if front_is_clear():
            move()
        if right_is_clear():
            repeat(turn_left,3)
            move()
        else:
            turn_left()
            move()
    if right_is_clear():
        repeat(turn_left,3)
        if front_is_clear():
            move()
    if front_is_clear():
        move()
    while not front_is_clear():
        if left_is_clear():
            if front_is_clear():
                move()
            if right_is_clear():
                repeat(turn_left,3)
                move()
            else:
                turn_left()
        if right_is_clear():
            repeat(turn_left,3)
            if front_is_clear():
                move()#tant que ce n'est pas libre devant lui
        turn_left()#on tourne à gauche
