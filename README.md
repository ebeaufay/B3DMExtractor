# B3DMExtractor

This is a specialized tool for extracting the content of a B3DM file. 
B3DM files are used by OGC 3DTiles to wrap gltf/glb files with a specific metadata structure. The tool will extract the gltf/glb content of the B3DM.

This is a manual tool so you'll have to do the following steps:

1. run "npm install" at the root
2. open the file "src/app.js" and manually change the hardcoded path so that it points to the root of your 3DTiles tileset or a specific B3DM file.
3. run "node src/app.js" from the root

The app will crawl the directory and sub directories looking for B3DM files and save the content next to the original file.

The app does not do any extra work like removing draco compression. Blender supports draco compressed files out of the box.
