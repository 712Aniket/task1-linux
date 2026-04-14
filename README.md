1. Creating and Renaming Files/Directories
Create a directory named test_dir using mkdir.
Inside test_dir, create an empty file called example.txt.
Rename example.txt to renamed_example.txt using mv

Answer:

mkdir test_dir (This will create a directory)

cd test_dir (change directory to test_dir)

touch example.txt (this will create an empty file inside test_dir)

mv example.txt renamed_example.txt (This will rename the file from example.txt to renamed_example.txt)



2. Viewing File Contents
Use cat to display the contents of /etc/passwd.
Display only the first 5 lines of /etc/passwd using head.
Display only the last 5 lines of /etc/passwd using tail.


Answer:

cat /etc/passwd (to view the contents from the file passwd)

head -5 /etc/passwd

tail -h /etc/passwd

3.Searching for Patterns
Use grep to find all lines containing the word "root" in /etc/passwd.

Answer:
cat /etc/passwd | grep root(to find the line which contains the word "root")


4. Zipping and Unzipping
Compress the test_dir directory into a file named test_dir.zip using zip.
Unzip test_dir.zip into a new directory named unzipped_dir.

Answer:

zip test_dir .. (to zip file in current directory)

unzip test_dir.zip -d unzipped_dir (Unzip the directory)



5. Downloading Files
Use wget to download a file from a URL (e.g., https://example.com/sample.txt).

Answer:

wget https://getsamplefiles.com/ (to download the file)


6. Changing Permissions
Create a file named secure.txt and change its permissions to read-only for everyone using chmod.

Answer: 

ls -la secure.txt ( first checked file permissions )

chmod 444 secure.txt (change file permission to read only for everyone i.e. owner, group and others)



7. Working with Environment Variables
Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!".

Answer:

export MY_VAR="Hello, Linux!" (export the variable,This variable will be set for the current terminal only) 

echo $MY_VAR (to check the variable has been set or not)