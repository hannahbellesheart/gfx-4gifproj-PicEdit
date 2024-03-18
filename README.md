# ![logo] PicEdit
Simple image editor and convertor for the university course work project written in C# on the WPF platform using MVVM pattern.

## Installing
1. Download .NET 7 or higher from [official website].
2. Download the [latest release].
3. Open .exe file and work.

## Image opening and saving

### Image opening
To open the image go to ```File``` -> ```Open```.

### Image saving
To save the image in the same file go to ```File``` -> ```Save``` or clicking on floppy disk icon ![floppy disk icon] in the top left corner. <br/>
To save the image in another file go to ```File``` -> ```Save as```.

## Using
The editor has two tabs:
1. Editing tab
2. Converting tab

### Editing tab
There are four main tools:
1. Scaling
2. Rotation
3. Cropping
4. Painting

You can adjust them on the right panel with sliders and other controls.

❗ To apply adjusted tool just select another tool or save the image. ❗

### Converting tab
There are six main formats:
1. PNG
2. JPG
3. GIF
4. BMP
5. TIFF
6. ICO

To convert image select required format and click on ```Save``` button on the bottom panel.

❗❗❗ Successful converting to **ICO** format guaranteed only for images 128x128 pixels dimensions or lower. 
Other images dimensions converting might be fine but not guaranteed. ❗❗❗ (I don't recommend using it at all)
### Keyboard shortcuts
```Ctrl``` + ```Mouse Wheel``` – zoom in / zoom out. <br/>
```Shift``` + ```Mouse Wheel``` – left / right moving when image zoomed in. <br/>
```Ctrl``` + ```Z``` - undo command. <br/>
```Ctrl``` + ```Shift``` + ```Z``` – redo command. <br/>
```Ctrl``` + ```S``` – save image in the same file. <br/>

## Program Screenshots

![image](https://github.com/mythter/PicEdit/assets/60883514/38425341-8e12-4d6e-a029-e2fe4635928e)

![image](https://github.com/mythter/PicEdit/assets/60883514/e5df1a28-0448-4446-b72c-448104f0d767)

![image](https://github.com/mythter/PicEdit/assets/60883514/90907310-0b41-4edc-b0e1-12a8de124154)

![image](https://github.com/mythter/PicEdit/assets/60883514/1c4d31e7-915b-4a12-a1e4-f6d48a6be7e2)

![image](https://github.com/mythter/PicEdit/assets/60883514/227add54-20ce-4d11-a43d-21a61ae25446)

![image](https://github.com/mythter/PicEdit/assets/60883514/2852c1ba-37be-4214-b52d-4806e6c84bd4)


[official website]: https://dotnet.microsoft.com/en-us/download/dotnet
[latest release]: https://github.com/mythter/PicEdit/releases/latest
[floppy disk icon]: https://github.com/mythter/PicEdit/assets/60883514/29524a65-eb7c-4273-89c8-cb7555cd47bf
[logo]: https://github.com/mythter/PicEdit/assets/60883514/02be7cd1-5d6f-43a9-ba8e-a8a0b2c7475b "Logo"
