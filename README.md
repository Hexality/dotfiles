<div align="center">
  <h1>Microsoft "dotfiles"</h1>
<p>Jokes aside, here all the shit I use to customize windows to the brim.</p>

<img align="center" src="https://user-images.githubusercontent.com/17398632/215917149-15d732ed-3c40-4213-b767-c0366f25f978.png">

 <h1></h1>
  
<h2 align="center"> Tools </h2>
<table align="center">
  <tr>
    <th>Name</th>
    <th>Description</th>
    <th>Used/required for</th>
  </tr>
  <tr>
    <th><a href="https://mhoefs.eu/software_uxtheme.php?ref=syssel&lang=en">UltraUX Theme Patcher</a></th>
    <td align="center">Dll patcher</td>
    <td align="center">Unsigned themes.</td>
  </tr>
  <tr>
    <th><a href="https://winaero.com/downloads/winaerotweaker.zip">WinAero Tweaker</a></th>
    <td align="center">Tool made for overall system customization</td>
    <td align="center">Used to remove garbage from Explorer and desktop context menu.</td>
  </tr>
  <tr>
    <th><a href="https://www.startallback.com/">StartAllBack</a></th>
    <td align="center">Taskbar customizations</td>
    <td align="center">Revert to old taskbar design and get extra customization options.</td>
  </tr>
  <tr>
    <th><a href="https://hexed.it/">Hexed</a></th>
    <td align="center">Hex Editor</td>
    <td align="center">Fix some broken colors on the UI that are backed onto DLLs.</td>
  </tr>
  <tr>
    <th><a href="#">Regedit</a></th>
    <td align="center">System Registry Editor</td>
    <td align="center">Modify some context menu entries and colors.</td>
  </tr>
  <tr>
    <th><a href="https://github.com/nptr/msstyleEditor">NTPR's msstyleEditor</a></th>
    <td>Microsoft Styles Editor</td>
    <td>
      <p  align="center">Used to modify some themes to my liking</p>
      <h3 align="center">Edited themes:</h3>
      <p align="center">
        <a href="https://www.deviantart.com/niivu">Niivu's</a> BlissOS and <a href="https://www.deviantart.com/dpcdpc11/gallery">dcpdcp11's</a> Simplify/Maverick11
      </p>
    </td>
  </tr>
  <tr>
    <th><a href="https://www.donationcoder.com/software/mouser/other-windows-apps/desktopcoral">DesktopCoral</a></th>
    <td>Reserves a region on screen that apps can't go over</td>
    <td>Used to lock the topbar in place to keep always visible.</td>
  </tr>
  <tr>
    <th><a href="https://www.rainmeter.net/">Rainmeter</a></th>
    <td align="center">Customized Widgets</td>
    <td align="center">
      Day/Date, Nowplaying, Visualizer
      <h3 align="center">Public widgets (That I used stock or modified):</h3>
      <p align="center">
        <a href="https://visualskins.com/skin/mond">Mond</a>, <a href="https://visualskins.com/skin/lano">Lano</a> and <a href="https://www.deviantart.com/reb70/art/NORD-Music-Player-838393199">Nord</a>
      </p>
      </ul>
    </td>
  </tr>
  <tr>
    <th><a href="">Microsoft PowerToys</a></th>
    <td align="center">Windows Tools for Power Users</td>
    <td align="center">Caffeine, Color picker, FancyZones, Locksmith, SVG explorer addons, Image Resizer, PowerRename, PowerToys Run, Ruler, OCR</td>
  </tr>
  <tr>
    <th><a href="https://store.steampowered.com/app/431960/Wallpaper_Engine/">Wallpaper Engine (Rarely used)</a></th>
    <td align="center">Desktop Interactive Wallpapers</td>
    <td align="center">Used for screenshots/photos only</td>
  </tr>
  <tr>
    <th><a href="https://github.com/PowerShell/Powershell">PowerShell</a> <a href="https://dotnet.microsoft.com/en-us/download/dotnet/7.0">.NET Winforms</a></th>
    <td align="center">Windows Modern Command Prompt</td>
    <td align="center">
      For some widgets like the icons on the side
      <h3 align="center">Basic form example:<h3>
        <pre align="center">
using namespace System.Windows.Forms
using namespace System.Drawing
Add-Type System.Windows.Forms
$mF = [Form]@{}
#$mF.Show() for not interative ones
$mF.ShowDialog() # for the interactive ones </pre>
    </td>
  </tr>
</table>
<h1></h1>
<h2 align="center">StartAllBack Configs</h2>
<table align="center">
  <tr>
    <th/>
    <th>All programs</th>
    <th>General</th>
    <th>Search</th>
    <th>Right side items</th>
  </tr>
  <tr>
    <th>Start menu</td>
    <td>
      ▢ Use large icons
      <br>
      ▢ Display as flyout menu (Windows XP style)
      <br>
      ▣ Display modern apps in a folder
      <br>
      ▢ Override sort order
    </td>
    <td>
      ▢ Hightlight newly installed programs
      <br>▣ Open submenus when I pause on them with the mouse pointer
    </td>
    <td>
      ▣ Search prgrams and settings
      <br>▣ Search public folders
      <br>▢ Use flyout for more results
    </td>
    <td>
      ▢ Use user account picture
      <br>▢ Display glyph icons
      <br>●◌◌ User
      <br>●◌◌ Documents
      <br>●◌◌ Pictures
      <br>●◌◌ Music
      <br>●◌◌ Videos
      <br>●◌◌ Downloads
      <br>●◌◌ OneDrive
      <br>●◌- Favorites
      <br>●◌- Recent Items
      <br>●◌- Network
      <br>●◌- Connect to
      <br>◌◌● This PC
      <br>◌◌● Control Panel
      <br>◌◌● Settings
      <br>●◌◌ Windows Tools
      <br>●◌◌ Devices and Printers
      <br>●◌◌ Default Programs
      <br>●◌◌ Windows Terminal
      <br>●◌◌ Command Prompt
      <br>◌●- Run
    </td>
  </tr>
</table>
<table align="center">
  <tr>
    <th/>
    <th>Taskbar Style</th>
    <th>Behavior</th>
  </tr>
  <tr>
    <th>Taskbar</th>
    <td>
      ▣ Use enhanced classic taskbar
      <br>Visual Styles: Default, Icon size: S, Icon margin: S
      <br>Corner icons opens: Window 11 flyouts
      <br>▣ Use enhanced classic jumplists
    </td>
    <td>
      Taskbar location: Bottom
      <br>Combine: Always, hide labels
      <br>On secondary: same as above
      <br>▣ Centered: Tog. w/ start button
      <br>▣ Segments: Just central segment
      <br>▢ Dynamic transparency (breaks segments)
    </td>
  </tr>
</table>
<table align="center">
  <tr>
    <th/>
    <th>Explorer style</th>
    <th>Extras</th>
  </tr>
  <tr>
    <th>Explorer</th>
    <td>
      Ribbon style: Win7 command bar
      <br>▣ Mica effect on top
      <br>▣ Classic search box
      <br>▣ New icons
      <br>▢ Details pane on bottom
    </td>
    <td>
      ▣ Classic context menus
      <br>▣ Restore control panel applets
      <br>▣ Colorize everything w/ accent
    </td>
</table>
<table align="center">
  <tr>
    <th/>
    <th>Appearance</th>
    <th>Windows settings</th>
  </tr>
  <tr>
    <th>Advanced</th>
    <td>
      ▢ Use custom start menu coloring
      <br>▣ Use custom taskbar coloring: Blur, 50%
    </td>
    <td>
      ▢ Store recently opened programs
      <br>▢ Store recently opened items
      <br>▣ Use new font for classic UI
      <br>Number of jumplist items: 10
    </td>
  </tr>
 </table>
