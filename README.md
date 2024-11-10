# Snake-1.0
import pygame

pygame.init()

screen_width = 600
screen_height = 400
screen = pygame.display.set_mode((screen_width, screen_height))
pygame.display.set_caption("Game Ular")

white = (255, 255, 255)
black = (0, 0, 0)
red = (255, 0, 0)

def draw_snake(snake_block, snake_list):
    for x in snake_list:
        pygame.draw.rect(screen, black, [x[0], x[1], snake_block, snake_block])

def your_score(score):
    font = pygame.font.SysFont(None, 25)
    text = font.render("Skor: " + str(score), True, black)
    screen.blit(text, [0, 0])

while not game_over;
    # ... (kode untuk menangani event, menggerakkan ular, mendeteksi tabrakan, dll.)

pygame.quit()
quit()
