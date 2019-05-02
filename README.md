# How to Use

## Setup the environment:

    git clone https://github.com/RMPR/facemash.git
    python3 -m venv facemash
    source facemash/bin/activate # for windows search the file activate.bat
    pip3 install -r requirements.txt
    python3 server.py runserver


## fill it with data!

1) add some pictures to the folder `static/face` in format `name1_name2.jpg` and run

2) use the migration tool to add these images to the database:

    python server.py runserver
    python Tools/db_create_helper.py

## run the server

    python server.py runserver


# Screenshots:

because I love Screenshots!

![voting](http://gerneth.info/files/facemash_img/voting.PNG)

![ranking](http://gerneth.info/files/facemash_img/ranking.PNG)

![overview](http://gerneth.info/files/facemash_img/overview.PNG)

