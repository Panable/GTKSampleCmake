#Required Packages
sudo pacman -S sigc++-3.0 gtk4 glibmm pangomm cairomm pkg-config glib2 pango cairo gtkmm-4.0 graphene cmake make

Will work with Clion, just need to refresh CMakeLists.txt each time, or you can just remove the glob recursive from CMakeLists and have CLion add them in manually for you.
