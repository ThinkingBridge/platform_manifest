[ThinkingBridge] (http://thinkingbridge.org)
====================================


Getting Started
---------------

To get started with ThinkingBridge, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/initializing.html).

To initialize your local repository using the ThinkingBridge trees, use a command like this:

    repo init -u git://github.com/ThinkingBridge/platform_manifest.git -b kitkat

Then to sync up:

    repo sync
    

Building
--------

Now run our build script:

    ./build-tb.sh -device-

example:

    ./build-tb.sh hammerhead
