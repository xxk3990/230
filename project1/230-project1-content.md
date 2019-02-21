# Jump Block

The game I'm thinking of doing is a game where the player has to get from one side of the map to the other by jumping on blocks. Once the user lands on a block, they only have a small amount of time to jump onto the next one before the one they are standing on disappears. To add an extra challenge, what I could do is make some of the blocks move up and down or left and right, so the user has to time their jump correctly. For the blocks that go up and down, I could make the next jump above it so the user can ride it up and then time their jump onto the next one. For the one that moves left and right, I could make the next one some distance away so the user can ride it. If possible, I'd have the map follow the user, so as the user progresses the map changes. This would also make the game a bit longer and more challenging too. Either that or I could add more levels without having the map change as the user moves. Or both, not entirely sure yet!

### Controls
- A & D to move, option to choose left & right arrow keys to move instead
- Space to jump
- For longer jumps, they can hold either jump button down or arrow key down followed by space to speed up for a longer jump

### Game Features
- Stationary blocks that disappear after a few seconds
- Blocks that move up and down (also disappear after a few seconds, but allow the user to take it up before disappearing)
- Blocks that move left and right (also disappear but allow the user to ride it to the other side before disappearing)
- Timer telling the user how long they can stand on the block for, resets when they jump onto a new one
- Players' number of lives left. If they miss a jump and fall off the bottom of the screen, have them restart and lower numLives by 1

### HTML for Index.html
- Image of game home page
- Brief description of the game (not all info in above description), in a main tag with p tags
- at the top of the page, a nav-bar (ul) with links to the other pages

### HTML for proposal.html
- nav-bar repeated
- fuller overview of game (full description), also in main tag with p tags
- Lists of different aspects of the game:
-   A ul of genres this game could fall under
-   A ul of possible platforms this game could be used for 
-   A ul of game features
-   A ul of game controls
- Images of drawings of gameplay (probably something I will do in a painting or other drawing software)

### HTML for documentation.html
- nav bar repeated
- Formatted like a word doc
- Incldues all sources (if any)
- Incldues where I met project requirements

### HTML for project.html
- nav bar repeated
- Indication that it is a place holder

### CSS formatting for all pages
- Grid for all text and image layouts
- For index.html, image left-center with text next to it (or image centered above text)
- Nav-bar spread out with flexbox
- Nav-bar items will have different colors, text-size, etc for different "anchor states"
- for proposal.html, images in center with text below
- for documentation.html, text in center
- Mobile media query (@media screen and (max-width: 480px)), with 1 column grid layout for mobile
- Lists will have a list-style-type of none

### CSS design for all pages
- wrapper background color of forestgreen
- maybe two columns on either side with different colors (maybe a gold-ish color?)
- text color of black
- a font family of Didot or Times New Roman
- section titles bolded or underlined



