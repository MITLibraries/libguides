Hosted Platforms Branding
=========================

This code determines the theming for MIT Libraries' hosted platforms from
Springshare, Lyrasis, and Aeon:

- https://archivesspace.mit.edu
- https://libguides.mit.edu
- https://libcal.mit.edu
- https://libanswers.mit.edu
- https://libguides.mit.edu/staff
- https://mit.aeon.atlas-sys.com/

Each platform's branding materials are contained in a separate directory. For
each platform, there are usually three files:

1. `custom-head.html` - The stylesheets, javascript, and other head elements
   that control presentation and behavior.
2. `custom-header.html` - the HTML markup for the top navigation.
3. `custom-footer.html` - the HTML markup for the footer at the bottm of the
   page.

"Deploying" these files is a manual process. For Springshare platforms, the
files must be copied and pasted into the platform's Look and Feel interface.
For Aeon and ArchivesSpace, the files must be emailed to staff at Atlas and
Lyrasis respectively for placing on their servers.

## Related resources

* The [MIT Libraries Brand Guide](https://libguides.mit.edu/brand) is a great starting point
* [Design system](https://mitlibraries.github.io/mitlib-style/) based on this branding package
* [GitHub repository](https://github.com/mitlibraries/mitlib-style) for that design system
