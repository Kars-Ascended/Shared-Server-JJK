# Before running anything;

this tutorial assumes you are cd'd into the jjk server folder that contains stuff like level.dat, /data, /advancments, etc...
it also assumes you have git installed. go download it if not

you can turn these commands into batch files to run if you dont like running commands every time,
put the commands into a txt
save the txt as a .bat
make sure the top line of the txt cd's into your mc world, for example for me it would be: 
    cd "C:\Users\white\AppData\Roaming\gdlauncher_carbon\data\instances\JJK\instance\saves\Shared-Server-JJK"

# Commit (save to github)

add files

    git add .

commit

    git commit -m "update"

push to github

    git push

# Pulling (update from github)

pull / update local with repo

    git pull

# Clone (pull for new machine)

download repo for new machine

    # cd into where your worlds are stored then run:
    git clone https://github.com/Kars-Ascended/Shared-Server-JJK.git

# Marks

M = modified
A = added, waiting for push
D = deleted
U = updated but unadded / new
