dmenu-scripts - My implementation of dmenu to simulate Rofi functions (run, drun, window, filebrowser and theme-selector)
=========================================================================================================================

### Dependencies:
  
  * **Arch Linux:**
    
    ```shell
    $ sudo pacman -S gcc make coreutils sed expat freetype2 libxinerama git wmctrl \
      dex brotli fontconfig libbsd libmd libpng libx11 libxau libxdmcp libxft \
      libxrender xdg-utils --noconfirm
    ````

  * **Debian/Ubuntu:**

    ```shell
    $ sudo apt install gcc make coreutils sed libexpat1-dev libfreetype-dev xdg-utils \
      libxinerama-dev git wmctrl x11-utils dex libxft-dev libfreetype6-dev libpng-dev \
      libfontconfig1-dev libbrotli-dev libxrender-dev libmd-dev libxau-dev libbsd-dev \
      libxdmcp-dev -y
    ````

### Build and install:

* Open terminal and run the following commands:

  ```shell
  $ git clone https://github.com/q3aql/dmenu-scripts
  $ cd dmenu-scripts
  $ sudo make install clean
  ````

### dmenu scripts that simulate Rofi:

  ```shell
  dmenu_run
  ```

<img src="examples/dmenu_run.png" /> 


  ```shell
  dmenu_drun
  ```

<img src="examples/dmenu_drun.png" /> 


  ```shell
  dmenu_wrun
  ```

<img src="examples/dmenu_wrun.png" /> 


  ```shell
  dmenu_fbrun
  ```

<img src="examples/dmenu_fbrun.png" /> 


  ```shell
  dmenu_themes
  ```

<img src="examples/dmenu_themes.png" /> 


  ```shell
  dmenu_cmd
  ```

<img src="examples/dmenu_cmd.png" /> 


  ```shell
  dmenu_close
  ```

<img src="examples/dmenu_close.png" /> 
 
### External links:

  * [dmenu homepage](https://tools.suckless.org/dmenu/)
  * [Rofi homepage](https://github.com/davatorium/rofi)

