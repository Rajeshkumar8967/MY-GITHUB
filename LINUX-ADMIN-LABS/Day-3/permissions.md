whoami                      - it prints the user name
id                          - it shows the id's of user in groups and other folders
sudo adduser devopsuser     - it adds new user 
passwd devopsuser           - it add password for user
groups                      - it shows gropus where user in different groups
chmod 755 file.txt          - it changes the file permissions 
chmod 644 file.txt          - same as before command but some permissions changes
chown user:user file.txt    - it changes owners and groups permissions for the files



the values of permissions 
1-x (execute permission)
2-w (write permission)
4-r (read permission)

for individual permissions numbers are used 
for full permissions like 
example execute permission for all owner,groups,others use ("+" permission symbol r,w,x)
ex:-
chmod +x notes.txt - it gives execute permission to all
chmod 644 notes.txt - it gives individual permissions to all
  
