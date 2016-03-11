# Using DU to get disk usage

Unix systems come with a program called `du` (`disk usage`). The name is very self-explanatory.

__To get a total summary of current directory:__

````bash
du -hs
````

````bash
1G
````

__To get a summary of files and directories:__

````bash
du -hs *
````

````bash
137M  Photos
372K  Bike - GoPro Project.gcs
 15M  7-Minute Workout.mp4
 23M  8 week General Strength Progression - Part 1.mp4
 ````

__To get a summary of a specific file or directory:__

````bash
du -hs Photos
````

````bash
137M  Photos
 ````


