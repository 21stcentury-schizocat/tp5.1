""""
Liam.R
2025-01-20
""""

import arcade

SCREEN_WIDTH = 640
SCREEN_HEIGHT = 480


def main():

    arcade.open_window(SCREEN_WIDTH, SCREEN_HEIGHT, "Tutorial arcade")

    arcade.start_render()
    arcade.set_background_color(arcade.color.BLACK)
    arcade.draw_lrbt_rectangle_filled((SCREEN_WIDTH / 2) - 100, (SCREEN_WIDTH / 2) + 100,
                                      (SCREEN_HEIGHT / 2) - 50, (SCREEN_HEIGHT / 2) + 50, arcade.color.ASH_GREY)
    arcade.draw_ellipse_filled(SCREEN_WIDTH / 2 , SCREEN_HEIGHT / 2, 60, 60, arcade.color.AIR_SUPERIORITY_BLUE)
    arcade.draw.draw_circle_outline(50, 200, 60, arcade.color.BUBBLE_GUM, num_segments=8, tilt_angle=35
    arcade.draw.draw_arc_filled(400, 150, 60, 100, arcade.csscolor.ASH_GREY, 0, 180)
    arcade.draw.draw_line(SCREEN_WIDTH / 2, SCREEN_HEIGHT / 2, SCREEN_WIDTH, SCREE_HEIGHT, arcade.color.WHITE, 10)

    arcade.finish_render()
    arcade.run()


main()
