# Click-and-Color

Interactive Region Colorizer (Mask Filling Tool)
This simple, single-file web application is designed to quickly and interactively color independent regions within geographical or geometrical mask maps. By clicking on the regions separated by black lines in the PNG mask images you upload, you can instantly fill them with a unique color.

🎨 Features
Single-File Architecture: All HTML, CSS (Tailwind), and JavaScript are contained within a single index.html file. No additional setup or server is required.

Fast Flood Fill: An optimized Breadth-First Search (BFS) based Flood Fill algorithm that quickly identifies and fills the clicked region.

Unique Color Guarantee: Every clicked independent region is filled with a random, bright RGB color that has not been previously used on the same image.

Flexible Mask Support: The application colors all neighboring pixels that share the initial clicked pixel's color, stopping only when it reaches the black borders.

Output Saving: The ability to save the final colored image as a PNG file.

🚀 Setup and Running (Offline Use)
Running this application is incredibly easy, requiring no command-line knowledge or extra software.

Download: Download the project as a ZIP from the Code / Local section in the top right.

Extract: Extract the downloaded ZIP file into a folder on your computer.

Run: Double-click the index.html file inside the folder and select the browser you want to use to open it.

The application is now ready to use!

🖱️ How to Use?
Once the application is open in your browser, click the 'Upload Mask PNG' button to select your mask map with black borders.

When the map appears on the screen, click with your mouse or tap with your finger on the empty area (not the border) you wish to color.

The clicked region will instantly fill with a random and unique color.

Continue coloring different regions.

When you are finished, click the 'Save Colored Image' button to download the colored PNG file.

🤝 Contribution
If you would like to contribute to the project, provide feedback, or report bugs, please feel free to open an 'Issue' or send a 'Pull Request'!
