# -
测试本地远程分支commit记录

情况一 本地新建分支 push branchName:branch1

情况二 在branch1的基础上新建本地分支2 push上去  分支名称 branch2

结论：直接在分之一的基础上新建的本地分支 本地代码不会变 会继承自branch1

情况三 ：切换到master分支上再新建本地分支 branch3
结论 ：之前提交的分支记录在这个分支中提交并不存在  本地代码内容和master分支相同 之前的别的分支的commit会被stash暂存起来 

