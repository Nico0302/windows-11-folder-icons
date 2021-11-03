# 📁 Windows 11 Folder Icons

[Affinity Designer](https://affinity.serif.com/designer/) template for custom, pixel-perfect Windows 11 folder icons.

![Preview](https://github.com/Nico0302/windows-11-folder-icons/blob/main/art/preview.png?raw=true)

# 🪛 Requirements

- [Affinity Designer](https://affinity.serif.com/designer/)
- [ImageMagick](https://imagemagick.org/script/download.php#windows) (for converting .png files to an .ico)
- [Windows Terminal](https://www.microsoft.com/de-de/p/windows-terminal/9n0dx20hk701) (optional)

# 🖌️ Customization

A Windows folder icon consists of 8 images for different resolutions. This guaranties sharp rendering and readability.

You can customize the color of the folder icon by changing the **foreground gradient**.

It is recommended to chose one of Microsoft's [Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons) ([Download](https://github.com/microsoft/fluentui-system-icons/archive/refs/heads/master.zip)). Some of these icons are also available in different resolutions.

Drag the SVG files of the selected icon into the corresponding icon symbols in the template and delete the example icon. If the icon only supports one or a subset of resolutions drag the same file in all icon symbols.

# 🔼 Export

1. head over to the **Export Persona**
2. select **Export Slices**
3. open the folder containing the exported files in a terminal (if you have Windows Terminal installed you can right-click on it and select **Open in Windows Terminal**)
4. run `magick convert 16.png 20.png 24.png 32.png 40.png 48.png 64.png 256.png icon_name.ico`
