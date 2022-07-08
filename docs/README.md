# About LeoCAD

LeoCAD is a CAD program for creating virtual LEGO(R) models. It's available
for free under the GNU Public License v2 and works on the Windows, Linux
and macOS Operating Systems.


# Installation

You can download the latest version of LeoCAD and its Parts Library from
the main website at https://www.leocad.org

It's recommended that you install the latest drivers for your video card
since LeoCAD uses OpenGL to take advantage of hardware acceleration for
rendering.

## LeoCAD for Windows

  Download the latest LeoCAD-Windows.exe to your computer, double click on
  the icon to launch the installer and follow the instructions.

## LeoCAD for Linux

There are multiple ways to install LeoCAD on Linux.

* Snap Store
  
  You can find LeoCAD in your distribution's Snap Store. Alternatively, you
  can enter `sudo snap install leocad` to install it using the command line.

* AppImage

  Download the latest LeoCAD-Linux.AppImage, make the file executable
  (`chmod +x`) and run it.

* Flatpak

  You can also install LeoCAD releases as a Flatpak from Flathub:
    https://flathub.org/apps/details/org.leocad.LeoCAD

  Note: there might be a delay for new releases to appear there. If
  you have it already installed, it will be updated.

* From source

  If you prefer to compile LeoCAD yourself, go to the GitHub releases page
  at https://github.com/leozide/leocad/releases/latest and download the
  source archive from there. If you do not already have a Parts Library
  installed, you will need to download one and follow the installation
  instructions. More information on how to compile your own executable is
  available in the Documentation section of https://www.leocad.org

## LeoCAD for macOS

  Download the latest LeoCAD-macOS.dmg to your computer, double click on
  the icon to open the archive, copy LeoCAD.app to your Applications folder
  and then launch it from there.

New users should read the online tutorial located at
https://www.leocad.org/docs/tutorial1.html to learn how to use LeoCAD.


# Online Resources

- Website:
  https://www.leocad.org

- GitHub page:
  https://github.com/leozide/leocad

- Unstable builds:
  https://github.com/leozide/leocad/releases/tag/continuous

# Use Case: AutoPrint
This use case is for continuous 3D printing of LeoCAD output as obj format. This is the first step of continuous 3D printing and one can use the current version in Craftnetics repository to export the overall Lego design piece by piece. Please see the video below:

<p align="center">
  <a href="https://www.youtube.com/embed/DyD8s7upo6U">
  <img src="./LeoCAD_AutoPrint.gif"
     alt="LeoCAD AutoPrint Export"
     style="float: center; margin-right: 10px;" />
  </a>
</p> 

## Requirements
- Importing LDraw Database for LDR models: If you would like to open the provided LDR example (small truck) without appropriate database all you will see the image below:
 {Add Image}
 
Instead, you need to install the provided [database](https://www.ldraw.org/parts/latest-parts.html) in the repository and import it to your LeoCAD installation. Once you import the database you should see the bricks on the right hand side of the user interface under parts window (Please see the animated gif or YouTube video below).
<p align="center">
  <a href="https://youtu.be/el6temkfzkc">
  <img src="./AutoPrint/AddingLibraryLeoCAD.gif"
     alt="LeoCAD AutoPrint Export"
     style="float: center; margin-right: 10px;" />
  </a>
</p>


# Legal Disclaimer

LEGO(R) is a trademark of the LEGO Group of companies which does not sponsor,
authorize or endorse this software.
