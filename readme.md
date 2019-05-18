# Codenjoy Almaty [EPAM]

Hackathon organized by EPAM. Task is to implement a game platform for to play with agent.

## Getting Started

To install dependencies
```
pip install requirements.txt
```

To start a game with default bot, enter in the terminal
```
python coins.py
```

## Interactive mode
One can switch one interactive mode by removing the comments on section
```
    '''    
    def on_key_press(self, key, modifiers):
        """ Called whenever the user presses a key. """
        if key == arcade.key.LEFT:
            self.player.x = (self.player.x - 1)%MAX_GRID
            self.player.center_x = (self.player.center_x - CELL_LENGTH)%SCREEN_SIZE
        elif key == arcade.key.RIGHT:
            self.player.x = (self.player.x + 1)%MAX_GRID
            self.player.center_x = (self.player.center_x + CELL_LENGTH)%SCREEN_SIZE
        elif key == arcade.key.UP:
            self.player.y = (self.player.y + 1)%MAX_GRID
            self.player.center_y = (self.player.center_y + CELL_LENGTH)%SCREEN_SIZE
        elif key == arcade.key.DOWN:
            self.player.y = (self.player.y + 1)%MAX_GRID
            self.player.center_y = (self.player.center_y - CELL_LENGTH)%SCREEN_SIZE
    '''
```

One can control the bot in interactive mode by keyboard arrows UP, DOWN, LEFT, RIGHT

## Screenshots
