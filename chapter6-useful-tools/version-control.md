# version control

The text editor solves the problem of codewords very well, so another problem comes in that you need to work with a lot of people in the development of a project, and the code will produce multiple versions over time. The more intuitive idea is to manage the file name rename, such as `file0.c, file1.c...`, a little better will use `file-2014-10-05.c...` The version management method is a bit too naive for a slightly larger project. Besides, if you change it, it will hurt the lactic acid. Smart programmers have already thought of a solution for you - Version Control! Professional things should be handed over to professional tools. So another problem has come again - ** version control tools so much, which one is strong? Lan Xiang does not seem to have version control tools...** You can find the following in a random search:

1. [Git](http://en.wikipedia.org/wiki/Git)
2. [Subversion] (http://en.wikipedia.org/wiki/Subversion)
3. [Mercurial] (http://en.wikipedia.org/wiki/Mercurial)

Overall, version control can be divided into two types, distributed and non-distributed. ←\_← Non-distributed can be understood as centralized, which means that there must be a centralized server when using. Just like military training, the team must report to the platoon leader. This platoon leader is equivalent to the server in the centralized version control tool. You think, what you need to do is to report to the platoon leader, naturally it is quite uncomfortable, right or wrong π\_π, the representative of which is Subversion.

If this version of the server is away from you, and it happens that a certain bear child has nothing to unplug your network cable, the switch of the router is down - in short, you can't make it difficult to connect to a foreign server. That's it, then teamwork naturally can't go on happily at this time. Since it is not a friend with centralized version control, let us be friends with the local distributed version control tool! Discard Subversion, keep safe~

Even the development of Subversion itself has turned to git in April Fool's Day in 2014. Hahahaha, the vote finally passed... [[svn1]](#ref-quit-sub) [[svn2]](#git -svn-diff) [[svn3]](#svn-april-fool)

## Distributed Version Control Tool - git

The benefit of distributed is that it can be relied on a central server unlike centralized version control tools, and development can be done locally, without relying on the network. The representative is [Git] (http://en.wikipedia.org/wiki/Git). Git is another great artifact that Linus Torvalds brings to all mankind after Linux. Put a git in the branch and merge aspect of the big killer feature to wake up everyone, powerful cut?

![Git-branch](../images/git-branch-1.png)


### Practical Tutorial

1. [git - concise guide] (http://rogerdudler.github.io/git-guide/index.zh.html), the simplest git guide I have seen so far, the original English version has been translated into various other Language, comics, super friends, love
2. [Git Brief Tutorial] (https://gist.github.com/bigeagle/3953973), b brother's tutorial, simple and practical.
3. [Git Branch Management Strategy] (http://www.ruanyifeng.com/blog/2012/07/git.html), a strategy for Git branch management provided by Qi Yifeng.
4. [Git Tutorial - Liao Xuefeng] (http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) - Easy to understand git Chinese tutorial
5. [Git Magic] (http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/), very suitable for getting started tutorial, text super friend love ≖‿≖✧
6. [Pro Git] (http://git-scm.com/book), the official tutorial, very comprehensive, easy to get started, then look at the first few chapters is enough.


## Notes

1. <a name="ref-quit-sub">[svn1]</a> [Why are we giving up Subversion] (http://www.infoq.com/cn/articles/thoughtworks-practice-partiv)
2. <a name="git-svn-diff">[svn2]</a> [Five basic differences between GIT and SVN | External Journal IT Review] (http://www.vaikan.com/5 -fundamental-differences-between-git-svn/)
3. <a name="svn-april-fool">[svn3]</a> [[INFRA-7524] April Fools: migrate Apache Subversion project over to the git repo - ASF JIRA](https://issues. Apache.org/jira/browse/INFRA-7524)