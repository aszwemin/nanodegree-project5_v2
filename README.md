Neighbourhood Map Project
==========================

The application consists of the following components:

1. The full page Google map

2. A set of markers in the locations obtained from Google Places API. The set of markers can be filtered based on search results. When the user clicks on the marker, an infowindow is open with the name of the place and some basic details, and the marker bounces to show its position.

3. A search bar. When user starts typing, suggestions are being shown under the search bar (to filter by type or name, icons differentiate between the two). User can then click on the entry and the markers will be filtered accordingly. Removing all text from the search box resets the application to initial state.

4. A list view showing additional data for the currently visible markers (name, icon, address, phone and url, picture and a button to show reviews and opening times). When the user clicks on the result, related marker will bounce and the infowindow for it will be shown.


Project contains a package.json and gulpfile.js that allow for minifying css and js files. In order to make any changes to css or js files, run npm install and then gulp.


Icons for help and settings are taken from:

http://www.iconmay.com/Simple/Architecture_Blueprint/question_mark_questions_about_help_blueprint_architecture_question_mark_icon_772

http://www.iconmay.com/Simple/Architecture_Blueprint/settings_adjustment_arrangement_working_process_blueprint_architecture_settings_icon_744


Styles starting with 'pac' are taken from google maps styles.


Documentation generated with JSDoc can be found in out/index.html.


Libraries and frameworks used:

- Bootstrap

- jQuery

- Knockout

- Knockout Validation


APIs used:

- Google Maps

- Google Places

- Open weather API (http://openweathermap.org/api)
