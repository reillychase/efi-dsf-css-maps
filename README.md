#EFI DSF CSS MAPS
Mappings of common CSS tweaks for EFI's Digital Storefront layouts

Currently something as simple as changing the color scheme of a DSF layout requires days of reverse engineering by highlighting each colored element with an inspector tool, finding its CSS class, changing the color, then saving to the master CSS file.

The goal of this project is to provide easy to use mapping template of the common CSS classes where, for example, a color change would need to take place in order to change the DSF layout to match your own branding or your client's.


>**Always apply your CSS customizations by adding them to the end of the storefront CSS file!**


The customizations at the bottom will automatically override the classes above them. Never edit the original CSS classes directly. Always save your CSS customizations to a file outside of DSF. This way when DSF updates the master CSS file, simply allow it (no need to mess with their terrible CSS code merging tool), then add your styles back to the bottom of the master CSS again and everything will be fine.
