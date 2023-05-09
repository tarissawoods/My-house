# My-house
# A nice house on a sunny, partly cloudy, day.
# Its purpose is to entertain and just show a picture of a house.
import simplegui

def draw_handler(canvas):
    canvas.draw_polygon([(0,500), (600,500), (600,600), (0, 600)], 2, "black", "green")
    canvas.draw_polygon([(150,200), (450, 200), (450,550), (150,550)], 2, "black", "tan")
    canvas.draw_polygon([(100,200), (300, 10), (500,200)], 2, "black", "darkred")
    canvas.draw_polygon([(250,350), (350, 350), (350, 550), (250,550)], 2, "black", "black")
    canvas.draw_circle([340,450], 2, 6, "gold", "gold")
    canvas.draw_polygon([(200, 250), (250,250), (250, 325), (200,325)], 2, "black", "yellow")
    canvas.draw_polygon([(350, 250), (400,250), (400, 325), (350,325)], 2, "black", "yellow")
    canvas.draw_line([225, 250], [225, 325], 4, "black")
    canvas.draw_line([375, 250], [375, 325], 4, "black")
    canvas.draw_line([200, 290], [250, 290], 4, "black")
    canvas.draw_line([350, 290], [400, 290], 4, "black")
    canvas.draw_circle((520, 60),50, 6, "yellow", "yellow")
    canvas.draw_circle((520,90), 12, 8, "white", "white")
    canvas.draw_circle((465,40), 10, 8, "white", "white")
    canvas.draw_circle((455,30), 10, 8, "white", "white")
    canvas.draw_circle((480,45), 8, 8, "white", "white")
    canvas.draw_circle((450,40), 10, 8, "white", "white")
    canvas.draw_circle((435,45), 8, 8, "white", "white")
    canvas.draw_circle((510,100), 14, 8, "white", "white")
    canvas.draw_circle((530,100), 14, 8, "white", "white")
    canvas.draw_circle((550,105),10, 8, "white", "white")
    canvas.draw_circle((490,105), 10, 8, "white", "white")
    canvas.draw_circle((90,60), 20, 8, "white", "white")
    canvas.draw_circle((100,70), 20, 8, "white", "white")
    canvas.draw_circle((110,70), 20, 8, "white", "white")
    canvas.draw_circle((70,70), 20, 8, "white", "white")


frame = simplegui.create_frame(' My house :) ', 600, 600)
frame.set_canvas_background("lightblue")
frame.set_draw_handler(draw_handler)
frame.start()
