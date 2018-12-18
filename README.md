# Render Animatic

"Render Animatic" is a Blender addon to render only keyframes or only frames pointed to by markers.

This program was initially based on another addon with the same name which was posted in [stackexchange](https://blender.stackexchange.com/questions/1718/is-it-possible-to-render-only-keyframes-from-dope-sheet) by Christian Brinkmann ([p2or](https://github.com/p2or)), and later has been rewritten entirely.

---

## Usage

Select menu (Topbar > Render > Render Animatic)

![topbar_menu](https://raw.githubusercontent.com/iRi-E/blender_render_animatic/images/screenshot_topbar_menu.png)

In the popup dialog, set options and click OK button to start rendering

![popup_dialog](https://raw.githubusercontent.com/iRi-E/blender_render_animatic/images/screenshot_popup_dialog.png)

## Render Options

### Filter Type

How to pick frames to render:

* Step: Use constant frame steps same as the regular animation render
* Keyframes: Render only keyframes visible in the current timeline
* Markers: Render only frames pointed to by markers

### Viewport Render

Use the viewport render instead of the actual rendering engine.

### In and Out Points

Write the start and end frames of the rendering range as well.

### Frame Duplication

Copy rendered frames to fill gaps in the image sequence.

### View Context

Take snapshots of the active viewport instead of the current scene.
