# beautifulprogram
test
01 aprel

def draw_column():
    screen = turtle.Screen()
    screen.bgcolor("white")
    
    col = turtle.Turtle()
    col.shape("turtle")
    col.color("black")
    
    # Рисуем основание колонны
    col.penup()
    col.goto(-50, -150)
    col.pendown()
    col.begin_fill()
    col.forward(100)
    col.left(90)
    col.forward(10)
    col.left(90)
    col.forward(100)
    col.left(90)
    col.forward(10)
    col.left(90)
    col.end_fill()

    # Рисуем ствол колонны
    col.penup()
    col.goto(-30, -140)
    col.pendown()
    col.begin_fill()
    col.forward(60)
    col.left(90)
    col.forward(120)
    col.left(90)
    col.forward(60)
    col.left(90)
    col.forward(120)
    col.left(90)
    col.end_fill()

    # Рисуем капитель
    col.penup()
    col.goto(-50, -20)
    col.pendown()
    col.begin_fill()
    col.forward(100)
    col.left(90)
    col.forward(20)
    col.left(90)
    col.forward(100)
    col.left(90)
    col.forward(20)
    col.left(90)
    col.end_fill()

    col.hideturtle()
    turtle.done()

# Запуск программы
draw_column()
