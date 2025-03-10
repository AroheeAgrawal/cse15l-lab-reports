# Lab Report 4
## Step 4: Log into ieng6
Keys Pressed:`ssh <space> a1agrawal@ieng6.ucsd.edu <enter>` This allowed me to log into my `ieng6` account
![Image](IMG_8202.jpg)
## Step 5: Clone your fork of the repository from your Github account (using the SSH URL)
Keys Pressed: `git <space> clone <space> <Command+V> <enter>` I typed this to clone the repositiory. I pasted the ssh url that I had copied from github for the forked repository.
![Image](IMG_8203.jpg)
## Step 6: Run the tests, demonstrating that they fail
Keys Pressed: `cd <space> lab7` This changed the repository to lab7 which is where the test file is located.`bash <space> test.sh <enter> ` I ran the tests by running the `test.sh` file
![Image](IMG_8204.jpg)
## Step 7: Edit the code file to fix the failing test
Keys Pressed: `vim <space> ListExamples.java <enter>` I opened the ListExamples file in `Vim` so that I could edit it. `<up><up<up><up><up><up>`Then I used the up arrow to navigate to the begining of the merge method where the error was. Then I clicked `v` so that I could enter visual mode on `Vim`. `<down><down><down><down>`And clicked the down arrow 
until I reached the line that contained the comment saying change index1 to index2. This highlighted the block of code that contained the incorrect index incrementation. After this I typed `:s/index1/index2/g<enter>`
this replaced all of the occurences of index 1 to index 2 within the highlighted block of text. Then I pressed `<esc>` to exit visual mode and typed `:wq <enter>` to save the changes and exit `Vim`.
![Image](IMG_8210.jpg)
![Image](IMG_8205.jpg)
## Step 8: Run the tests, demonstrating that they now succeed
Keys Pressed: `<up><up><enter>` The command to run the `test.sh` file was 2 up in the command history so I used the up arrow to access it. 
![Image](IMG_8209.jpg)
## Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)
Keys Pressed: `git <space> add <space>  .<enter>` I added the changes locally and then `git <space> commit <space> -m <space> "changed <space>  index1 <space> to <space> index2"<enter>` this let me commit the changes locally. After that I entered `git <space> push <space> origin <space> main<enter>` so that I could push them to the repository.
![Image](IMG_8206.jpg)
