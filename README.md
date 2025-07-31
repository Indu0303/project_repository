import random
width=10
height=10

def print_board(snake, food):
    for y in range(height):
        for x in range(width):
            if[x,y]==food:
                print('f',end=' ')
            elif[x,y] in snake:
                print('s',end=' ')
            else:
                print('.', end=' ')
        print()
    print()
