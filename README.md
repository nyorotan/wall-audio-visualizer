🌐 **English**|[日本語](./README.ja.md)

# 🎨 Wallpaper Audio Visualizer

![ ](./doc/d.jpg)  
**"Illuminate your desktop wallpaper with the music playing on your PC."**

Wallpaper Audio Visualizer is an application that brings dynamic, beautiful animations to life on your desktop wallpaper, synchronized in real-time with the music playing on your PC.

## ✨ Features

- **Enjoy Music Visually**  
  Waveforms and geometric patterns respond in real-time to the tempo and volume of your music.
- **"Behind Desktop" Design (Doesn't Interfere with Daily Operations)**  
  Animations run right behind your desktop icons. **You can double-click desktop icons or drag & drop files just as you normally would without the app interfering.**
- **Space-Saving "Taskbar Mode"**  
  In addition to full desktop display, you can embed a compact visualizer (500px width) directly into your taskbar.
- **10 Diverse Visual Styles**  
  Choose from classic frequency bars, rainbow-glowing geometric patterns, tachometer/speedometer styles, and more depending on your mood.
- **Multi-Monitor Support**  
  Select any specific monitor to display the visualizer when using multiple displays.

## 🚀 Getting Started

1. **Launch**: Double-click `wall-audio-visualizer.exe` in the application folder to run it.
2. **Setup**: The app will automatically move to the desktop wallpaper layer (your desktop might flash briefly for a few seconds right after launching, which is normal behavior—please wait a moment).
3. **Play Music**: Play music via YouTube, Spotify, iTunes, etc., and the visualizer will instantly react to the audio.

## 🛠 Usage

When launched, an icon will appear in the system tray at the bottom right of your screen.

![ ](./doc/b.jpg)

- **Change Style**: **Right-click** the system tray icon to open the menu. Choose your favorite style such as "Classic", "Rainbow", or "Spirograph".
- **Toggle Taskbar Mode**: Select "Switch to Taskbar Mode" in the menu to embed a compact visualizer into your taskbar.
- **Switch Display Monitor**: Select a monitor from the "Display" submenu to choose where to render the visualizer (Desktop Mode only).
- **Exit Application**: Click "Exit" in the menu to completely close the app.

### ⌨️ Useful Hotkeys

Operate the visualizer quickly using your keyboard without using a mouse or interfering with other applications.  
Press and hold the **Home** key while pressing the target key:

- **[Home] + [S]**: Toggle between Desktop Mode and Taskbar Mode.
  - In Taskbar Mode, it automatically switches to the classic style and embeds compactly (500px width).
  - Pressing it again automatically restores your previous monitor and style.
- **[Home] + [0] ~ [9]**: Instantly switch visual styles (some styles are disabled in Taskbar Mode).
- **[Home] + [ESC]**: Instantly exit the app.

*Note: While the app is running, it hooks the Home key to prevent conflicts with other apps. As a result, the standard Home key behavior (such as moving the cursor to the beginning of a line) will be disabled.*

## 🎨 Visual Styles (10 Styles)

Choose from a variety of styles to match your mood.

![ ](./doc/a.jpg)

1. **Classic**: A timeless style where bars extend upward from the bottom like piano keys to the beat of the music.
2. **Symmetrical**: A balanced, beautiful style expanding mirrored upward and downward from the screen center.
3. **Top-Down**: A unique style where bars stretch downward from the top, like light showering from the ceiling.
4. **Radial**: A futuristic style expanding in a circular blossom from the screen center.
5. **Rainbow**: The classic bar graph enhanced with vibrant rainbow gradient colors.
6. **Symmetrical Rainbow**: A flamboyant style combining central expansion with rainbow color shifts.
7. **Top-Down Rainbow**: A mystical style featuring light cascading downward in seven colors.
8. **Radial Rainbow**: One of the most dynamic styles, featuring circular expanding light that shifts color over time.
9. **Tachometer**: A mechanical style where a speedometer-like needle swings rhythmically to the bass beat.
10. **Spirograph**: A mesmerizing style where complex geometric lines overlap and mutate endlessly, like a kaleidoscope or spirograph ruler artwork.

## 🎉 New Feature: Taskbar Mode

Embeds a compact visualizer directly inside your taskbar.

![ ](./doc/c.jpg)

- *Note: Taskbar Mode is not supported when the taskbar is positioned vertically (left or right side of the screen).*
- ***Behavior Differences by Windows Version***:
  - **Windows 10**: The taskbar region (ReBarWindow32) is automatically adjusted so the visualizer fits cleanly without overlapping app icons.
  - **Windows 11**: Due to Windows 11 taskbar specifications, **the visualizer display may overlap with app icons on the taskbar** depending on your layout. Please keep this in mind.

> *Note: In Taskbar Mode, only landscape-oriented styles (1–3, 5–7) are supported to maintain clear visibility within the limited height. Radial, Tachometer, and Spirograph styles (4, 8, 9, 10) are disabled.*

## 💡 Frequently Asked Questions

- **Q. Will this prevent me from clicking my desktop icons?**  
  A. **Rest assured, there is zero impact.** The app is designed to sit behind desktop icons as part of the wallpaper layer, so mouse inputs are never captured by the visualizer. You can interact with desktop icons and organize files as usual.
- **Q. Will it slow down my PC?**  
  A. It is designed to be lightweight. If you experience slowdowns, try closing unnecessary background applications.
- **Q. Does it respond to microphone input?**  
  A. No, this app is specifically designed to respond only to system audio played internally on your PC.
- **Q. What should I do if the visualizer does not show up?**  
  A. Try exiting the app completely and launching it again. Also, note that certain active wallpaper configurations might cover the visualizer.

## 🗑 How to Uninstall

This app does not modify any system configurations or registry entries. To uninstall, **simply delete the application folder by moving it to the Recycle Bin**.

## ⚠️ Notes & Precautions

- Exclusively for Windows OS.
- Exiting the app will stop the wallpaper effects.
- The desktop may flicker briefly upon startup; this is expected behavior while inserting the layer behind the wallpaper icons.
- **Taskbar Mode (Windows 11)**: On Windows 11, the visualizer may overlap with pinned/running app icons due to OS taskbar limitations.
- Since this app manipulates the desktop render layer, avoid using it simultaneously with other live wallpaper software.
  > *Note: Compatibility with the author's separate project `Decorate the screen (-decoscreen-)` is supported.*

---

## License

This project is released under the `MIT License`. Feel free to use it for both commercial and non-commercial purposes.

- **Copyright**: © 2026 nyorotan

## Version Info

- **Version**: v1.1.2
- **Author**: nyorotan

_Enjoy your music, Enjoy your desktop!_
