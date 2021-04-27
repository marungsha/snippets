Compress Folder

tar -zcvf <filename.tar.gz> <folder>
-z = Compress the desired file/directory using gzip
-c = Stand for create file (output tar.gz file)
-v = To display the progress while creating the file
-f = Finally the path of the desire file/directory to compress


Extract 

tar -xvzf <your-tar-file.tar.gz>
-z: Compress the desired file/directory using gzip
-x: Stand for extract file (input tar.gz file). If any files are named on the command line, only those files will be extracted from the archive.
-v: To display the progress while creating the file