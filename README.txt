Froese, Noel - Assignment 1, Part 2: 2D Platformer Scene
Unity version: 6.6 (Universal 2D).

Requirements
1. 2D scene with area and reachable static platforms: Completed
2. Two vertical platforms (higher/lower than the start): Completed
3. Two horizontal platforms reachable by jumping: Completed
4. Tilemap, grid and tile palette tools: Completed
   - One Grid with four Tilemaps: Ground, Platforms, Background and Decor
   - Tile Palettes created by dragging each sliced sprite sheet into the Tile Palette window; the level was painted with the Paint and Box Fill brushes, with the Active Tilemap set per layer
5. At least 3 external tilesheets: Completed
   - (ground and platforms)
   - (decor)
   - (background)
6. All tilesheets and static sprites in a single Sprite Atlas: Completed
   - GameAtlas (Sprite Atlas V1, Always Enabled) contains all three sheets; filter mode Point, compression None
7. Background and foreground on different layers: Completed
   - Sorting layers "Background" and "Foreground". The Background tilemap and the large background sprites are on Background; Ground, Platforms and Decor are on Foreground
8. Camera clear colour changed: Completed
   - Main Camera background set to [colour] to match the sky
9. Quality (layout, scale, import settings): Completed
   - Every sheet uses Sprite Mode Multiple, Filter Mode Point, Compression None, and Pixels Per Unit equal to the tile size, sliced with Grid By Cell Size, so there are no gaps between tiles
   - Jumps are at most 2 to 3 tiles up and 4 tiles across
   - The large background images use their own Pixels Per Unit since they are not on the tile grid
10. Submission zip with Unity .gitignore: Completed
    - Froese-Noel-a1-p2.zip made from a fresh clone of the private repo