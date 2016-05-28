Install the Sins of Solar Empire Eclipse Plugin



# Introduction

Welcome to the Sins of a Solar Empire Eclipse Plugin. This guide will help you configure install and setup the Sins of a Solar Empire Plugin.

InstallPlugin

# Details

## Install Sins of Solar Empire Eclipse Plugin.

Unzipping the latest soseplugin\_v.x.x.zip and copy the jar file contained into the eclipse dropins directory. (**_Make sure to delete any previous plugin jar_**) Restart Eclipse.

![http://dl.dropbox.com/u/5790092/SinsTools/dropin_sose_plugin.jpg](http://dl.dropbox.com/u/5790092/SinsTools/dropin_sose_plugin.jpg)

## Activate Entity Validation (This step only needs to be performed once).
![http://dl.dropbox.com/u/5790092/SinsTools/activate_entiti_validator.jpg](http://dl.dropbox.com/u/5790092/SinsTools/activate_entiti_validator.jpg)

## At this point the tool is running but it doesn't know where the reference files are.

Here is how it looks before associating the reference files. First screen is for abiltiies&nbsp;the tool&nbsp;can't find (Errors). Second screen is for String references&nbsp;the tool&nbsp;can't find (Warnings).

![http://dl.dropbox.com/u/5790092/SinsTools/before_associating_reference_files.jpg](http://dl.dropbox.com/u/5790092/SinsTools/before_associating_reference_files.jpg)

![http://dl.dropbox.com/u/5790092/SinsTools/missing_string.jpg](http://dl.dropbox.com/u/5790092/SinsTools/missing_string.jpg)

## Now to tie in the reference files. First select Window/Preferences

![http://dl.dropbox.com/u/5790092/SinsTools/edit_preferences.jpg](http://dl.dropbox.com/u/5790092/SinsTools/edit_preferences.jpg)

## Then set the three reference directories previously loaded. (TRINITY)

![http://dl.dropbox.com/u/5790092/SinsTools/Sose_preferences.jpg](http://dl.dropbox.com/u/5790092/SinsTools/Sose_preferences.jpg)

## Then set the reference directories (REBELLION)
This plugin will support the previous versions of sins and rebellion, BUT not in the same workspace. You will need to create another workspace for Rebellion and setup the SOASE preferences for that workspace similar to below.

![https://dl.dropbox.com/u/5790092/SinsTools/rebellion_preferences.jpg](https://dl.dropbox.com/u/5790092/SinsTools/rebellion_preferences.jpg)

## Force the project to re-validate now.
(occasionally required to validate the entire project currently). However, saving in an individual file will force a re-validation for that entity without performing this step.

![http://dl.dropbox.com/u/5790092/SinsTools/clean_project.jpg](http://dl.dropbox.com/u/5790092/SinsTools/clean_project.jpg)

## Any remaining errors will be highlighted as shown.

![http://dl.dropbox.com/u/5790092/SinsTools/remaining_syntax_error.jpg](http://dl.dropbox.com/u/5790092/SinsTools/remaining_syntax_error.jpg)