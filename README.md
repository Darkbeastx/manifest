ASTRO-OS

To get started with ASTRO-OS Building, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Syncing Source

To initialize your local repository, use this command:

    repo init -u https://github.com/Project-AstroOS/manifest -b pie

Then to sync up:

    repo sync -c -j8 --force-sync --no-clone-bundle --no-tags

To Build:

    . build/envsetup.sh 
     lunch astro_<device>-userdebug 
     brunch <device>-userdebug
