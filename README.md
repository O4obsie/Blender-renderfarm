

# Blender-renderfarm
the code to render any blender project with google colab


## **list of contents**

- [**list of contents**](#list-of-contents)
- [**How to use it**](#how-to-use-it)
  - [One Frame Rendering](#one-frame-rendering)
  - [Animation Rendering](#animation-rendering)
- [**Update**](#update)
- [**Help**](#help)


## **How to use it**

- you need to download the [`rstuteam.render.ipynb`](https://github.com/rstusoftdev/Blender-renderfarm/releases/download/1.9.060122/rstuteam.render.ipynb) file or [`Automatic Update Version`](https://colab.research.google.com/drive/1V6hH37_DvhrZMeW4uZYKi_d_80Z5YlJX?usp=sharing) for automatic update

- Uploud the `rstuteam.render.ipynb` file to your Google Drive (if you use the downloadable file link)

- Before you start, you must uploud your project to Google Drive (i highly recommend you to make a new folder for your project)

- Start the `rstuteam.render.ipynb` file with [Google Colab](https://colab.research.google.com/)

- If you use the Automatic Update Version, you must make a copy to Google Drive by pressing the `Copy to Drive` button

- Before run, go to `Edit > Notebooks Settings` and change the setting from `None` to `GPU` for more faster rendering

- Run the **`Startup`** and the **`Check`** Code Cell

- on **`Select Blender Version`** Code Cell, Choose the blender version for rendering your project, and then run it

- on **`Data`**, you need a permission for Google Drive Access, just Accept it


There are 2 options of rendering
<br><br>


### **One Frame Rendering**
in this option, there are **4** types of setting that you must to know about it
<br><br>

- **`file_location`** <br>

Put your .blend file location
> for the example `"/content/drive/My Drive/Blender-rstufarm/alex.blend"` 

<br>

- **`output`** <br>

Set your output project result location
> for the example `"/content/drive/My Drive/Blender-rstufarm/alex"` 

<br>

- **`frame`** <br>

Set frame that you want to render it
> for the example `1` 

<br>

- **`format`** <br>

this option is for output format result, such as .png, .bmp, .tga, etc. <br>
you can change this option by clicking the option and choose the format you want
> for the example `PNG` 

<br><br>

> note: for the `GPU_set` Code Cell, always choose the `-P setgpu.py` option, by clicking the `none` option and change it to `-P setgpu.py` option

<br>
if you done with the settings, you can run it and wait for the result

---

<br>


### **Animation Rendering**
this option is usually use to render multiple frame, such as animation, image sequence , etc. <br> there are **6** types of setting that you must to know about it
<br><br>

- **`file_location`** <br>

Put your .blend file location
> for the example `"/content/drive/My Drive/Blender-rstufarm/alex.blend"` 

<br>

- **`output`** <br>

Set your output project result location
> for the example `"/content/drive/My Drive/Blender-rstufarm/alex"` 

<br>

- **`frame_start`** <br>

Set the start frame for animation rendering
> for the example `1` 

<br>

- **`frame_end`** <br>

Set the end frame for animation rendering
> for the example `250` 

<br>

- **`frame_step`** <br>

Set number of frames to step forward after each rendered frame.
> for the example `1` 

<br>

- **`format`** <br>

this option is for output format result, such as .png, .avi, .jpeg, etc. <br>
you can change this option by clicking the option and choose the format you want
> for the example `AVIJPEG` 

<br><br>

> note: for the `GPU_set` Code Cell, always choose the `-P setgpu.py` option, by clicking the `none` option and change it to `-P setgpu.py` option



<br>
if you done with the settings, you can run it and wait for the result

---


## Update

Update every 5 months


## Help

type your help or issue on issue section in this repository
