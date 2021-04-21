# trimlinkto
### Trims 'Link to ' off of .desktop file links

Links created in the Caja file manager (i.e. by drag & drop from a web browser)
are preappended with the text 'Link to '.

When run as a Caja Action with %f as the parameter, this script trims 'Link to ' off of the names of all displayed filenames in the working directory specified by %f. Real filenames are not effected. The script also includes an option to automatically change the icon of each modified link to a specified icon.

See the `trimlinkto` file or run the command `./trimlinkto -h` for configuration details.
