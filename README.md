# DirectIO-in-LevelDB

DirectIO is not implemented in LevelDB. Someone may need to enable DirectIO in order to test the performance of the filter policy.
This file can be replaced by the original LevelDB file to enable DirectIO.

In addition, you'd better set linux kernal vm.drop_caches = 3 every time you test the DirectIO.
