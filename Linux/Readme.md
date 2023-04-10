# #######
# Time: 1hr                                                                                                                        # No.of.Questions 9
# #########


1.   Create a  user  called `alex` and 
     `alex` must configure a cron job that runs `daily at 14:23. and executes "/bin/echo "alex"` and 
      create a user called `peter` and deny the user `peter` for creating cronjob.

2. Create the user `"david"` with uid `9805`

3. locate the files of owner `"david"` and copy to the directory `/opt/found` directory.
    note : if the folder `found` not found please create 

4. List all lines which have string `"semisocial"` from `"/usr/share/dict/words"` file and copy the lines in
`/root/word.found`
note: Download file from `https://gist.githubusercontent.com/saikrishnama/67e3412d7596dccf7de1cd05c713480f/raw/a5d23610047d8eec865770327d0d57941ede1e42/words.txt`
place the file under `"/usr/share/dict/words"` 


5. Configure a user account.
    Create a user `mark` uid is `3400`. 
    set the Password: `Redhat@312`
    The user's login ```shell``` should be `non-interactive`.

6.  Add 3 users: `harry, maxwell, john`.
    The requirements: The Additional group of the two users: `harry, maxwell` is the `admin` group. The user: `john's` login shell should be `non-interactive`. 
    note: if the `admin` group not present please create the admin group
      
7. Create a directory under `/opt` named `piller`. Its respective group is requested to be the `piller` group. The group users could `read and write, while other users are not allowed to access it`. The files created by users from the same group should also be the `piller group`.

8. Create a backup -
    Create a backup file named `/root/backup.tar.bz2`, contains the content of `/usr/local`, tar must use `zip`to compress.

9.  Install the appropriate `Kernel` from the url `https://pkgs.org/download/kernel` . Your machine should
    boot with `updated kernel`.
    find the right kernel for your `os`
    
