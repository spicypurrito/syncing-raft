# Let's try to sync raft save files

1. Figure out where your save files are. It should be in: ```C:\Users\{YOUR USER}\AppData\LocalLow\Redbeet Interactive\Raft```

2. Avoid messing with your files by creating a temporary folder to put your save files in. You can either just create a new file or in cmd prompt make a new directory:

```mkdir "temp_raft_sync"```

3. Copy your save files to the new directory/folder.

xcopy "dir1" "dir2" e.g.

```xcopy "C:\Users\{YOUR USER}\AppData\LocalLow\Redbeet Interactive\Raft" temp_raft_sync```

4. Upload your files to this repo 
