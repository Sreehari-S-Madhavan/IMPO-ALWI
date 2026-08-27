# IMAGE SETUP INSTRUCTIONS

To use your uploaded images as game themes and backgrounds:

## Step 1: Save Your Images

Save your uploaded images to this `images` folder with the following filenames:

1. **gandhi-banana-trees.jpg** - The image of Gandhi with the young man at a table with banana trees in the background

2. **banana-superhero-standing.jpg** - The image of the person in the banana-themed superhero costume standing in the jungle

3. **expressions-triptych.jpg** - The image showing three facial expressions (smiling, crying, angry)

4. **comic-battle-scene.jpg** - The comic book-style battle scene with the banana superhero fighting

## Step 2: File Formats

If your images are in a different format (PNG, GIF, etc.), update the file extensions in the `MEDIA` configuration in `index.html` (around line 1002-1058).

## Step 3: Alternative Paths

If you prefer to store images elsewhere, update the paths in the `MEDIA` object in `index.html` to match your file locations.

## Step 4: Test the Game

Once images are saved, open `index.html` in a browser. The game will randomly select from the provided images for backgrounds and result screens.

## Note

The game will work perfectly even without images - it will fall back to the CSS-generated Doomsday/Avengers-inspired cinematic theme if images are missing or fail to load.
