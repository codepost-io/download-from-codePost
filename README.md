# download-from-codePost

Use this script to download submissions from a codePost assignment to your local file system. 

Usage:
* Replace line 7 with your codePost API key. Read more about codePost API keys [here](https://docs.codepost.io/reference#authentication).
* `python download-from-codePost.py <course name> <course period> <assignment name>`

After executing, a folder with the following structure will be created in the directory from which the script was run.
```
assignmentName/
   student1@codepost.io/
      file1.py
      file2.txt...
   student2@codepost.io/
      file1.py
      file2.txt...    
```
