```py
class Kiki:
    def __init__(self):
        self.details = {
            "age": 22,
            "boy": true,
            "locale": "Indonesia",
            "languages": ["Javascript", "Java", "PHP", "Python"],
            "tools": ["NetBeans", "Visual Studio Code", "Intellij Idea", "Android Studio", "Processing 4"],
            "system": "Windows"
        }
```
 <p align="center">
  <a href"https://discord.com/users/867236993683816458"><img src="https://lanyard.cnrad.dev/api/867236993683816458"/></a>
</p>

import matplotlib.pyplot as plt
import numpy as np

def draw_pacman():
    fig, ax = plt.subplots()
    ax.set_aspect('equal')
    
    # Create a circle with an arc removed
    circle = plt.Circle((0, 0), 1, color='yellow', zorder=1)
    wedge = plt.patches.Wedge((0, 0), 1, 45, 315, color='black', zorder=2)
    
    ax.add_patch(circle)
    ax.add_patch(wedge)
    
    # Set the limits and hide the axes
    ax.set_xlim(-1.2, 1.2)
    ax.set_ylim(-1.2, 1.2)
    ax.axis('off')
    
    plt.savefig('pacman.png', dpi=300, bbox_inches='tight')
    plt.show()

draw_pacman()
![Pac-Man](https://github.com/username/username/raw/main/pacman.png)
