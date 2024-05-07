To initialize your local repository use
---------------------------------------

    git clone https://github.com/YFMARCO/build_manifest.git -b blaze-14 .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
