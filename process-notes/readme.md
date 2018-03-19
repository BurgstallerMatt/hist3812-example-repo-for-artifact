# readme

So starting to use the scann3D has been an interesting experience not sure why but the picture kept on adding extra eyes to the scan tried taking out some of the blurry pictures, but that didn't work out very well at all still not sure what is wrong with it

Started work on 3d project today Tuesday 16th
took pictures of Terry Fox statue in front of parliament hill
had to get on Matt's shoulders to take some of the higher pictures, hopefully they turn out well
weather was a bit crappy out, little bits of blowing snow, and a bit cloudy, could end up affecting the overal image
Regard3D

Terry Fox File
TRied adding photo set
opens other window was hidden behind
selected all and added
picture set name Terry Fox
Unknown focal length for far too pictures, try using pictures with better focal lengths
Picture set, recognizes camera make and model, but not sensors, had to add in the sensors by googling the sensors for phone sensors were 4.69 X 3.52 mm or 0.23 inches (5.8 mm) Tried changing the focal point and sensory width to make it work

nothing changed
Starting over file place /Users/johnw/Documents/test4/test4.r3d

retried adding the picture set again, still did not work, came up with the same warning
changed Motorola to motorola, see if uppercase lower cchanges
changes still did not work
changing metadata, using exiftool, google search it phil harvey

if having problems on mac, click control, then click open

electricarchaeology.ca Shawns personal website

Shawn does computer type commmands to try and change the senors, it doesnt work

tried changing things through multiple different ways, still not showing up as changes through regard3D

trying to use submlime text, it is a text editor, shows you precisely what is on a file, Excel is by microsoft and it is the devil, they were adding some form of little info which we could not see we copied the model number and info directly, and it finally showed the sensory width Computing the picture matches

takes a long time

finally worked after 27 minutes compute matches

wait more

TRiangulate, we decided to try Global triangulation because it fit our setting needs (used the came camera and same amount of zoom)

we realized at this point that it was not showing us an image that we wanted, went back tmo computing the pictures, and changed the keypoint sensitivity and keypoint matching ratio to ultra

may need to edit pictures

ended up having to leave because it was taking too long, was at 30 minutes and looked like only 50% loaded

went home and used Paint to get rid of the background images of the file

saved files should work better on regard3D next time hopefully

Jan 22

Users/marcbitar/Documents/Terry/Terry.r3d going through the command terminal
ls for list
cd for change directory
make: new
Camera model: XT1650
Focal l;ength 3.7 mm
sensors 5.8 mm had to change the settings, the commands used are on shawns website https://electricarchaeology.ca/2018/01/20/3d-models-from-archival-film-video-footage/ step 2 Compute matches
ultra settings for all Triangulate
used incremental structure from Motion Densification
Used CMVS/PMVS and preset settings, then tried chagning settings level 0 Cells size 1 Threshold 0.79 wsize 8 min num image 3 Create Surface
Tried one with texture and one with colour (thing) the one with colour seemed to look better
exported it
then went back to try and play with some of the pictures
took too long, so had to stop and export the primary image
Opened up Meshlab

Opened up the new 3D rendering that had been produced
getting rid of the extra bits around the image
Used the select vertexes tool, dragged around what i didn't want
then used the tool "delete the current set of selected vertices" button
repeated until had gotten rid of everything didnt want
with the new image that was produced the file was saved as a .ply file
tried uploading to sketchfab
file uploaded but there were parts of the image that were missing
not sure eactly what occured
tried using the file in a different format and exported as an .obj file
same problem occured
i hate sketchfab currently
tried again and the file now has a colourful background
where did the colour come from
still hate sketchfab
able to upload an image that is just a blank model of the image with no colour, still shows texture though
need more time to try and figure out how to upload it without losing parts of the model
Trying Meshlab again

used the first version of the model from Regard3D
repeated same steps to remove excess dots around image
exported mesh as .obj file
moved the previous .obj and .mtl files out of the folder, and put in seperate folder
zipped the folder with the new .obj file in it
upload to meshlab
no more weird missing colour patches
i hate meshlab less now
new model

there are parts of the model missing, from when cleaning up the random dots
will need to figure out how to attach everything together for next module when looking more into 3D printing

Module 2: History is a Remix

meshmixer

start off filling some of the wholes in Terry image

step 1: edit- make solid

step 2: change "solid type" to sharp edge preserve

seems to have filled in all the holes from the original model, no more gaps between legs and in head, no more colour though, just the shading

find model to remix with

download "Arabian Horse" from sketchfab

try to figure out how to put the two models together

open "arabien horse" in meshmixer

import terry file

select upper body of terry object

turn object to solid seperate part

delete full terry image

go to "mesh mix" and select "my part"

select the torso of Terry and drag onto screen

adjust it accordingly to give image of a centaur. where horses head is

select the part of the horse that is behind terry's torso

once selected, use the delete key to get rid of it

select both of the objects in the object window and then "combine" them using the edit toolbar

Modual 3:

game about terry and the horse becoming the centaur in the end
using sugarcube
game starts
player given either horse or terry character using either function (https://twinery.org/wiki/function)
Gives story for the two options after given, using historical facts and other such things to progress the story
following the terry story, trying to go chronologically with his life
using basic commands"[[insert name of next/previous slide]]" to get the story to move forward or backwards in the sequence.
created link to begining passage when you die, using code script found here https://blogs.stockton.edu/textscape/files/2015/04/A-Twine-Cheat-Sheet.pdf under the "Creating a link that differ..." section
attempted to try and use a key in the game to make it so that your positive decisions would end up giving you a better outcome
the coding kept on giving me errors saying it was not identified and such, even when i copied the info directly from the guide http://www.adamhammond.com/twineguide/ -decide to scrap using the key all together
making a strange story for the horse
come to an option where you must choose head or tailhttps://twinery.org/wiki/function using the either function
set it up so it randomly chooses one when you make your choice
depending on what you chose your answer will be right or wrong, and thus you get sent to the correspongding spot
Continue story to end it off with either losing or getting to the final objective
export the file and upload using philome.la
