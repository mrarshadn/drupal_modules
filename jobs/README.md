# Installation
* Clone this module in Drupal 7 Installed Directory under subdirectory sites/all/modules
* After module enable
  * Copy view code from jobs.install function jobs_views_default_views() and exclude first and last two lines of code
  * Paste above code in Views > New View > Import code
  * Press Save
* Admin > Structure > Content Types > Job Listing > Manage Display
  * In Job Category Select Format "Label" then in New screen select "Show entity labels regardless of user access"
## Testing
* After Installation open Web Browser and hit URL YOUR_DRUPAL_URL/jobs
* To check view YOUR_DRUPAL_URL/jobs-view
