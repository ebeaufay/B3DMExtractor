# B3DMExtractor

Extract the gltf/glb from a single B3DM file or an entire 3DTiles tileset

This is a manual tool so you'll have to do the following steps:

1. run "npm install" at the root
2. open the file "src/app.js" and manually change the hardcoded path so that it points to the root of your 3DTiles tileset or a specific B3DM file.
3. run "node src/app.js" from the root

The app will crawl the directory and sub directories looking for B3DM files and save the content next to the original file.

The app does not do any extra work like removing draco compression. Blender supports draco compressed files out of the box.
