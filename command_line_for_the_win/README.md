# Command Line For The Win

## After I have completed the challenges up to the 27th, and took screenshots. I used the sftp to upload my screenshots to remote sandbox, to push it to the github after.

 

## Steps

1. **Connect to the Remote Machine:**
   - I initiated the SFTP connection using the following command:
     ```bash
     sftp 0fab3a2a44b3@0fab3a2a44b3.8358262e.alx-cod.online
     ```

2. **Navigate to the Remote Directory:**
   - Once connected, I moved to the directory on the remote machine where I wanted to upload the files. In my case, it was:
     ```bash
     cd /alx-system_engineering-devops/command_line_for_the_win
     ```

3. **Upload the Files:**
   - I used the `put` command to upload the entire "command_line_for_the_win" directory, including its contents:
     ```bash
     put -r "C:\Users\hi\ALX_SE\alx-system_engineering-devops\GIT_TO_PUSH\alx-system_engineering-devops\command_line_for_the_win"
     ```

4. **Verify and Exit:**
   - I checked to make sure everything was in the right place by listing the contents of the remote directory:
     ```bash
     ls
     ```
   - Once satisfied, I gracefully exited the SFTP session:
     ```bash
     exit
     ```
