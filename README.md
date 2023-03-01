# DirectIO-in-LevelDB

DirectIO is not implemented in LevelDB. Someone may need to enable DirectIO in order to test the performance of the filter policy.
This file can be replaced by the original LevelDB file to enable DirectIO.

In addition, you'd better set linux kernal vm.drop_caches = 3 every time you test the DirectIO.



# 据大佬们反馈说是有内存泄漏问题，工作太忙实在没有时间细看，若有大佬有修复方案可以直接提issue反馈哈，省的我无人子弟了
