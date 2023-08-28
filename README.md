# WebGL_Fullscreen_Template
 A full screen template for Unity WebGL builds

 ## Overview

 The default UnityWebGL template is not the cleanest when it comes to appearance.
 This templates removes a lot of the noises and makes that the built game will stretch across the whole page like full screen game!

  ## Usage

  Download the `FullScreen` folder and place it under `Assets/WebGLTemplates` (Create the folder if it doesn't exist).

  Under `Edit -> Project Setting -> Player -> Resolution and Presentation`, you can find the newly imported templated to be selected.

  ![](https://github.com/ZhengYiHu/WebGL_Fullscreen_Template/blob/main/~ReadMeMedia/SelectTemplate.png)

  Make sure that [Decompression Fallback](https://docs.unity3d.com/Manual/webgl-deploying.html) is enabled in `Edit -> Project Setting -> Player -> Publishing Settings -> Decompression Fallback` while using the default compression settings.
  
  ![](https://github.com/ZhengYiHu/WebGL_Fullscreen_Template/blob/main/~ReadMeMedia/PublishingSettings.png)

  And Build the Game `File -> Build Settings -> WebGL5 -> Build`
  
  ![](https://github.com/ZhengYiHu/WebGL_Fullscreen_Template/blob/main/~ReadMeMedia/BuildSettings.png).

  ## Customization

  You can customize the favicon by replacing `FullScreen -> TemplateData -> favicon.ico` and the initial loading background under `Edit -> Project Setting -> Player -> Splash Image`.
  Further customization is also possible by modifying `index.html` and `TemplateData -> style.css` manually.