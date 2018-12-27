# OBF Homepage New

**Installation Guidelines**

  * ***Setup and Plugin Installation***

1. Download/clone repository. Unzip and open *OBF-Homepage-New-master* folder and move all files to the local WordPress directory.
2. Login to wordpress local installation.
3. Go to **Plugins->Add New**
4. Search for '*Advanced Custom Fields*' and install plugin. Activate plugin.
5. Go to **Plugins->Add new** again and search for '*All-in-One WP Migration'* plugin and install. Activate plugin.
6. We're importing from file, and it is above 2 MB, but WP only allows files below that limit. So we will download and install the file extension. Go to [Import WP Migration](https://import.wp-migration.com/) and download the **Basic** version.
7. Go back to the **Plugins menu-> Add New**. Select '*Upload Plugin*' beside the *Add Plugins* heading. Choose the file extension .zip file that was downloaded from [Import WP Migration](https://import.wp-migration.com/) and click on *Install Now*.
8. Once it is installed, click on '*Activate Plugin*' to activate the extension.

  * ***Theme Installation***
1. In the admin dashboard, go to *All-in-One WP Migration menu* and select the *Import* option.
2. In the Import page that shows up, click on Import and import from **'File'**. Navigate to the folder that has the unzipped OBF-Homepage-New theme and then to the '*data*' folder. Select the file with the .WPRESS extension as the file to load. 
3. A dialog box that notifies that the previous theme will be erased might show up. Click on Proceed. 
4. A dialog box that notifies that the data has been imported successfully will show up. Click on the **Permalink Settings** link and login to the WP-admin dashboard through the window that opens up.
5. Go to the bottom of the window and click on *Save Changes*. Do this twice.
6. Go back to the original window and close the dialog box.
7. Go to the **Custom Fields** menu and select the Tools sub-menu.
8. On the right side, click on *Choose file* and navigate to the '*data*' directory again. Choose the .JSON file and click on *Import File*.
9. Visit the site, it should be working now and the posts with custom fields should have the respective custom fields in the edit options. 
 

**Details**

*Update 27/12/2018*
-- Changed the homepage from index page to a static front page to be able to use the News page as a dedicated blog page in accordance with the WordPress model. The News tab is just temporary for now!

-- Fixed some design issues

-- Added use of plugin All-in-One WP Migration.

*Update 20/12/2018*
-- Moved files from wp-content to root directory.

-- Navbar styling issue resolved. Hamburger menu issue still stands. 

-- About page is done.
This is a very basic version, I haven't styled anything or linked to the proper pages. 

-- Separated the header and footer from the main content.

--The sections in the index page are kept as separate posts in the dasboard for easy editing. As of now, the lists of the fellowships and news sections with HTML are in the 'content' part of the post too. 

-- Used this https://github.com/wp-bootstrap/wp-bootstrap-navwalker navwalker class to add items in the navbar dynamically via the dash as required. There's an issue with the styling of the navbar, but it might be some minor fault in the CSS. The menu doesn't seem to be working in the mobile version of this. Need to figure that out as well.

-- As of now, I've added the about, news and fellowships sections as posts editable directly from the wordpress editor. The links don't lead to any valid pages. For the events and projects, it could be better to just use custom posts like Yo recommended?

--Path to the main theme files: OBF-Homepage-New -> obf-new -> wp-content -> themes -> obf-new

 

