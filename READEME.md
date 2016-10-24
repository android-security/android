## Getting Started ##
---------------

To get started with this ROM, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository use a command like this:

    repo init -u git://github.com/android-security/android.git -b aosp-5.1

To only sync the patched AOSP forks:

    repo init -u git://github.com/android-security/android.git -b aosp-5.1 -m minimal.xml

Then to sync up:

    repo sync

