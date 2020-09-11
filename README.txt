Update Destination from Source EXTREMELY fast.


WHAT DOES IT DO?
Mode 1: (Default) Copy Missing - Only copies file names not found in destination directory.
Mode one is useful if you dont edit the files. (like a music library, picture directory etc...)

Mode 2: Update - Is Mode One plus compares file timestamps so if source timestamp is newer than destination timestamp destination file will be updated.
Mode two is useful if you edit files. (documents, or you edit your music and pictures too you can still use it...) or download updates for files.



WHAT DOES IT NOT DO?
This not designed to delete files and folders from your chosen backup destination.



WHY?
1. Many files/directories are updated automatically like programs, for example Steam games.
2. Alot of the time I am editing many files in many places and find myself going in and out of directories everywhere copying things over to backup drives.
3. I wrote this because I have a lot of documents and games and when i back up i'd like it to be faster and so instead of procrastinating i saved my future self time and kept leanrning.
4. I would like to update my backup drives, not overwrite everything. This is better for long term drive health by writing conservatively and saves enormous amounts of time.



NOTES:
1. Running in admin account is preferable.
2. Initial backup will of course take time (as much time as operating system takes to write) but after that it can be insanely fast once only new/new+updated files are being written to the destination.
3. Try it with a huge Steam library and you will see.



Recent Experiment In Write Mode 1: Codename 'Shift Steam Game Planetary Annihilation Titans':
Steam Game before downloading Planetary Annihilation Titans update: 3,638,532,352 bytes.
Steam Game after downloading Planetary Annihilation Titans update:  3,639,084,249 bytes.
Time to backup whole game (3,638,532,352 bytes): approx. 3 minutes.
Time to 'shift' the game: approx. 2 seconds.
Result: The games play.

Example Source: D:\Documents
Example Destination: X:\Documents

Example Source: D:\Steam
Example Destination: X:\Steam