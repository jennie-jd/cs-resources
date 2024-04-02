## Useful next steps

Suggestions from person 1
> 很多 good-first-issuestag 的 issues 已经被别人领取了  
被领取的 issue 如果有一段时间没有 progress 可以问 maintainer 自己能不能 take， issue 下留 comment 就行。
> 
> 好多这种 issues 管理员好几个月都不上线了也不 reviewPR  
skip maintainer 不活跃的 repo
> 
> 怎样找到活跃的 Python repo 呢？  
https://github.com/search?q=language:python++stars:%3E500+&type=repositories&s=updated&o=desc  
https://github.com/vinta/awesome-python
> 
> 现在最大的问题是怎样找到合适的项目？  
合适的项目取决于你自己的目标。  
对于 beginner 来说，clone 项目，cloc，一般几千到几万行的项目比较好 handle，有清晰的 sub-moudule，comment，readme，contribution guideline，faq，maintainer 在 issue，mr，discussion 以及 im 里活跃的项目比较好。  
简单来说能跑通能读懂的项目就是合适的项目。
> 
> 目标是慢慢提升到可以理解比较复杂的 request 并且同时边实践边学习 system design  
我了解的大多数 popular 的开源项目是 infrastructure / library / tool 类型的。service 类型的也有，但是我了解不多。成熟的 service 类型的 application 可能是你 target 的目标，不过成熟的 service 通常比较复杂，可以试试这个  
https://github.com/search?q=language:python++stars:%3E500++topic:web&type=repositories&s=updated&o=desc
> 
> 希望更快地了解整个 development 过程并且开始阅读 system design 那本书。 是不是应该选择一个 repo 深度钻研呢？  
找一个有完整 setup 流程的 repo follow contribution guideline 来了解流程  
e.g. https://github.com/oppia/oppia/wiki/Contributing-code-to-Oppia  
根据 system design 的 topic keyword 找 wiki 详细的 repo。
> 
> 而不是选好几个 repo 这里做做翻译那里改改 typo?  
typo 和翻译类型的 pr 是了解 当前 repo pr 流程的一个比较好的 starting point，作为 first pr 很合适但也只适合做当前 repo 的 first pr。  
单从学习的角度上将，建议楼主找 documentation 齐全的 repo 熟悉 development 的流程，看 wiki/doc 的长度和详细程度。从 actual code contribution 的角度上讲，找一个 code base 自己能 handle 的更合适。  
目标只是从开源项目中学习 standardize 的流程可以看 wiki 自己跟着 setup，不过我认为如果只是想学 setup / pipeline / standardize development workflow 一类的看讲这个的网课会高效一些。  
通过 github contribution 来了解真正的程序开发可能并不是一个很好走的路。minker 所说的，“‘如何参与开源’是你有能力找到别人提出的bug并且大概知道怎么修复的时候应该提出的问题”以及“没人有义务带新人”是现实，因为大多on boarding doc只是针对project的on boarding。有比较大的 knowledge gap 的话，contribution 会比较困难，大多 maintainer 会假设 contributor 对基本的流程有概念，简单的问题可能会被 ignore，因此需要自己填补 knowledge gap。  

Suggestions from person 2
> 最重要的是找到一个自己感兴趣的repo，就是你平时真的会用的，你真的感兴趣的，愿意花时间去了解，而不是仅仅为了“提升自我”的，这样你才能学得下去。因为刚开始起步阶段真的很枯燥，就是玩命看源代码，也没人给你解释，很多看似简单的问题都需要你对比较大一块的内容有所了解你才知道是咋回事，修复可能需要的知识更多一些。  
不要做翻译，不要改typo。去选一个actively maintained的项目（尽量每天起码每周都有commit的），然后去找相对近期的issue，要是那种带bug的。复现，然后想为什么会出现这个bug，接下来修复，拉PR。不要指望着有个issue，有人已经告诉你需要做什么了，你只需要把代码复制粘贴一下就ok了，这种issue很少，也对你没啥帮助。  
如果你发现，这个项目所有的bug，你都不知道怎么回事，那说明你的水平还不够，回去慢慢修炼。  

Suggestions from person 3
> 最好的办法还是在工作中学习，如果实在想自学的话，可以研究一下大型的API library，例如我前些时调用的google-api-java-client-services。我在payment组，前些时做Google Play的升级  

Useful discussions and channels for git/open source
- My posts on 1point3acres
- My posts on xiao hong shu
- Discord channel Hacktoberfest
- Discord channel CS dojo

Git theoretical knowledge
- [经验总结] 【开心果原创】Git新手入门教程 https://www.1point3acres.com/bbs/thread-1014711-1-1.html
- https://learngitbranching.js.org/

Useful things to learn as a beginner SWE
- Conversation with Steve (Upenn) on linkedin
  - Git
  - System design
  - Something else?

## More resources

### How to get started with open source
- [How to Get Started with Open Source | A Beginner-Friendly Guide](https://www.youtube.com/watch?v=MkaIrwOlP6Y) (done)
  - What projects to look for  
    <img src="https://github.com/jennie-jd/learning-notes/assets/52141333/f75c7b4c-2900-4b57-aeb6-235638c62c22" width="450" height="120" alt="image">
  - A few repos to check out
    - [The first contributions repo](https://github.com/firstcontributions/first-contributions) - good instructions for pull requests from a to z (done)
    - [Active repos for contributing](https://github.com/csdojo-defaang/active-repos-for-contributing) (not started)
    - [YK's open source project](https://github.com/ykdojo/defaang) (not started)

- [Complete Guide to Open Source - How to Contribute](https://www.youtube.com/watch?v=yzeVMecydCE) (done / lots of details / maybe watch again later)

### Introductions to git and github
- [Git Tutorial for Beginners: Learn Git in 1 Hour](https://www.youtube.com/watch?v=8JJ101D3knE) (in progress)
- [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk) (in progress)
