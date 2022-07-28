This repo uses git-lfs. To save you some disk space and download time.

If you check out this repo via autoproj and you have included this model-group's package_set, autoproj will take care of it.

If you are checking out this repo via git you probably have to install git-lfs first:

- If you haven't used git-lfs before you probably have to do:
```
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
```

- If you once have added git-lfs to your repos simply do:
```
sudo apt-get install git-lfs
```

Afterwards git-lfs will take care of checking out the lfs files for you.

See also https://packagecloud.io/github/git-lfs/install
