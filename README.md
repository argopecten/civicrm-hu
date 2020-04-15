# hu_HU localization files for CiviCRM

Core files from:
- https://github.com/civicrm/l10n/tree/master/po/hu_HU
- https://www.transifex.com/civicrm/civicrm/language/hu/

Extensions: TBD
- https://github.com/civicrm/civicrm-l10n-extensions
- https://www.transifex.com/civicrm/civicrm_extensions/language/hu/

# Update process
## General translation process
Translate for the whole CiviCRM community.
	1. Lookup and update string in transifex
		a. [Core](https://www.transifex.com/civicrm/civicrm/language/hu/)
		b. [Extensions](https://www.transifex.com/civicrm/civicrm_extensions/language/hu/)
	2. Wait for the daily process to upload .mo files to CiviCRM download area, and download it:
		a. [Core](http://download.civicrm.org/civicrm-l10n-core/mo/hu_HU/civicrm.mo)
    b. [Extensions]()

## Specific (manual) translation process
How to edit your own site's CiviCRM translation files, to make small local changes, for a single site.
See: https://civicrm.org/blog/spidersilk/how-to-edit-your-own-sites-civicrm-translation-files
	1. Clone this repo .po repo
	2. Edit po files with PoEdit
	3. Concat all .po files into one .po
	4. Compile .po into .mo
  5. Upload the .mo file to site sites/all/modules/civicrm/l10n/hu_HU
