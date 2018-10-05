Repositori ini berisi file kodingan untuk tugas mata kuliah **Pemrograman Web** TI & SI semester 3 STTNF.

Tiap direktori berisi file tugas masing-masing mahasiswa.

Baca **dokumentasi** berikut sebelum memulai. :wink:

**Daftar Isi:**
- [Persiapan Pemrograman Web](#)
  - [OS berbasis Linux](#)
    -
  - [wOS berbasis Arch/Manjaro](#)
    - [Installation](#)
  - [OS Windows](#)

====================================================================================================================
# Persiapan 

Yang anda butuhkan adalah
- Text Editor
  - Gedit
  - Geany
  - Sublime Text
  -
- Web Server
  - 


## Debian/Ubuntu GNU+Linux based System

Install the **compiler** (important):

Package Name | Description
------------ | -------------
`g++` | GNU C++ Compiler


Install one of your prefered Text Editor or IDE (optional):

Package Name | Description
------------ | -------------
`gedit` `gedit-plugins` | GNOME text editor + its plugins
`geany` | lightweight and customizable IDE
`codeblocks` | cross-platform Dev-C++ alike IDE
`vim` `vim-gui` | popular Unix keyboard-driven text editor
`emacs` | fully-featured keyboard-driven text editor
`nano` | simple cli text editor (default)

Other Text Editor/IDE outside Debian/Ubuntu official repository:

Name | Description
------------ | -------------
Sublime Text | proprietary freemium text editor
Atom | open-source and hackable text editor powered by GitHub
Komodo Edit | cross-platform and multilingual text editor & IDE
Brackets | text editor powered by Adobe corp.
Visual Studio Code | text editor powered by Microsoft corp.

### Installation
```
sudo apt update
sudo apt install <package_name_1> <package_name_2> <package_name_n>
```

Example: 
`sudo apt install g++ codeblocks`

## Arch GNU+Linux based System
The packages are the same as on [Debian/Ubuntu](https://github.com/TI1NF/Praktikum-SDA#debianubuntu-gnulinux-based-system) official repository.
Additionally, [Atom](https://atom.io) is available in Arch official repository.

Package Name | Description
------------ | -------------
`atom` | open-source and hackable text editor powered by GitHub

Other Text Editor/IDE: 
- Komodo Edit (AUR) 
- Brackets (AUR)
- Visual Studio Code (AUR)

### Installation
```
sudo pacman -Sy
sudo pacman -S <package_name_1> <package_name_2> <package_name_n>
```

Example: 
`sudo pacman -S g++ codeblocks atom`




# Happy Coding! :smiley: :thumbsup:



"Those who have believed and whose hearts are assured by the remembrance of Allah . Unquestionably, by the remembrance of Allah hearts are assured." - 13:28
