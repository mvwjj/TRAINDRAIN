# Submission package #
This is an example submission archive for the VAR course. You HAVE TO follow its structure when submitting your final-VAR project.

In your submission, this file (`README.md`) should contain some brief description of your project, mainly names of the authors. Format of this file is not mandatory (this file will not be machine-parsed).

## Rules of the submission: ##

1) The content of this archive HAS TO have this structure:

```
root/            
 |- bin_vr/      - [MANDATORY] all .exe and .dll files required to run your VR project (in Unity3D use the "Build" button in "Build Settings" dialog)
 |- bin_ar/      - [MANDATORY] individual AR builds
 |- doc/         - [MANDATORY] userman.pdf (user manual) (EXACT NAMES ARE MANDATORY)
 |- media/       - screen-shots [MANDATORY - at least 3] and walkthrough video [MANDATORY], ordered alphabetically by "quality"
 |- web/         - [OPTIONAL] please, try build web player (https://www.youtube.com/watch?v=ck4MDy1pUoQ)
 \- package.json - [MANDATORY] project meta information for machine processing (see the NOTES + the example package.json as you are required to strictly follow its internal format, this HAS TO be a valid json file)
 ```

2) Your submission will be rejected if this instructions are not followed.
 
## NOTES: ##
- Screens and videos should be ordered by their importance (or "how much they characterize your project") - the alphabetically first screen-shot is the best to describe your game. At least 3 screen-shots have to be included. Artwork and posters are acceptable (but the alphabetically first screen HAS TO be a screen-shot).
- The `bin_vr/` directory has to contain everything needed to run your game (nothing more and nothing less). Unity will create this for you. If you ship binaries for more than one platform, include them too (use subdirectories, for example: bin/win32, bin/linux32, bin/android).
- The content of the `source/` directory will be available only to your teachers and will not appear on the public website of the course (unless you allow it in the `package.json` file).
- This archive contains dummy files of a though project organized as requested, please inspect it carefully.

## STRUCTURE OF `package.json`: ##

This json file contains information for our automatic archive processor and website generator. Use our example package.json as a template for yours. Please, **validate your json file before submitting** (common mistakes are forgotten commas in the authors field or, conversely, the remaining comma after the last item in the list).

### Description of the variables: ###
-  `"title"` - string containing the title of your project/game
-  `"team"` - team number used in the course (it must be a valid integer - 02 is not a valid integer)
-  `"source"` - root folder of your unity project ( originaly var_vr_project)
-  `"has_web_build"` - set `true` if web build was succesfull
-  `"authors"` - array of all authors working on this project (each author has the "fullname" and "email" fields, use your university email here)
-  `"term"` - (Y % 100) * 10 + S, where Y is the opening calendar year of this academic year and S equals 1 for the winter semester or 2 for the summer semester,  for example: 121 means the winter semester of the academic year 2012/2013
-  `"summary"` - max 2 sentences characterizing your game
-  `"opensource"` - boolean value, if you want your sources (src/ directory) to be available for download to public, set it to true; setting to false means your sources will only by available to your teachers/lecturers
-  `"genres"` - TAGS/Genres/subGenres specify your game for web-filters - [sample list](https://pixune.com/blog/video-game-genres/) - `VR` is mandatory for VAR projects.
-  `"links"` - [NOT MANDATORY] string - if you have created any external website (outside of the CTU domain), you can link it here
Use UTF-8 as the encoding for the package.js file.

DO NOT PACK ANY VISUAL STUDIO INTERMEDIATE FILES (for example .o files).
USE THE RELEASE BUILD TARGET (NOT DEBUG).
DO NOT INCLUDE .svn DIRECTORIES  (or .git, or whatever your VCS creates) - SVN CREATES .svn IN ALL SUB-DIRECTORIES OF YOUR PROJECT.
