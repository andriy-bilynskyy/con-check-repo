# con-check-repo
Connection checker repo manifest
Main git is located at:
https://github.com/andriy-bilynskyy/con-check.git

#### Install repo

	sudo curl https://storage.googleapis.com/git-repo-downloads/repo > /usr/local/bin/repo
	sudo chmod a+x /usr/local/bin/repo


#### Get project

	repo init -u https://github.com/andriy-bilynskyy/con-check-repo.git
	repo sync -c
	
#### Build project

from project root folder

	mkdir build
	cd build
	cmake ..
	make
	sudo make install
