# BSM Robotics MyWork
## Remote work tracking without the hassle

### Before you begin
You'll need a github account (github.com). _Use your school email address._

Once you've signed up for github, your teacher will need to invite into the MyWork repository, so talk to them about this.

### The very first time you ever use MyWork
#### If the pi has a `my_work` folder (at `/home/student/my_work`)
Enter the `my_work` folder and run `bash create_my_folder flast00` where flast00 is your BSM email prefix. Github will ask you to log in.

#### If the pi does not have a `my_work` folder
Ask a teacher for help, or if you want to do it yourself:

Enter the home folder for the student user (`/home/student/`) and run `git clone https://github.com/bsmrobotics/my_work.git`. Github will ask you to log in. Then run `bash create_my_folder flast00`

### Working with MyWork
After you've run the `create_my_folder` command, you can just work in the `my_work` directory and save your work as usual. Make directories, create files, save files, run robots, etc.

### Saving your work to the cloud
# You must save your work like this every time or you will 99% certainly lose everything you've done!
Make sure you're in `my_work` and run `bash save_my_work flast00`. Github will ask you to log in.

### Loading your work from the cloud
Make sure you're in `my_work` and run `bash load_my_work flast00`. Github will ask you to log in.

### Updating MyWork
Every now and then your teacher will tell you to update the MyWork scripts. You can do this by running `bash update_my_work_scripts flast00`. This is never a bad idea; you may as well do this every now and then.
