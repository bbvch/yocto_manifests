# yocto_manifests
Repositories for various yocto manifests

To use this yocto manifest, please execute the following step:\
1.) repo init -u git://github.com/bbvch/yocto_manifests.git -m px30_evb_manifest.xml\
2.) repo sync\
3.) repo forall -pc 'git checkout --track $REPO_REMOTE/$REPO_RREV'

The last step is important, because the detached revision was not the correct one.
