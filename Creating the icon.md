The first step comes when you want to create the native builds templates for a game is to create the icon files.

## 1. Create `.png`s of the icon:
You'll have to create `.png` images of the icon with different resolutions, transparency is allowed.

### Required resolutions:
- 16x16
- 32x32
- 48x48
- 64x64
- 128x128
- 256x256
- 512x512

Give the images proper filenames, like `icon_16x16.png`.

## 2. Create a `.ico` for the Windows builds:
You could use GIMP for this process:

1. Create an image with the resolution of 256x256
2. Create 6 layers with the following resolutions:
  - 16x16
  - 32x32
  - 48x48
  - 64x64
  - 128x128
  - 256x256
 3. Copy the icon from the `.png`s created earlier, each one with the corresponding layer
 4. Export as a `.ico` with the default settings.
