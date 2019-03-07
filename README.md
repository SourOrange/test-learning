# test-learning
print ('happy new year,it just for a test.')
Life is beautiful and beautiful and more...
今天早上7点多起床，这是夏天以后，在秋末的季节里，起的比较早的一次。早上喝了一杯水，穿了一件格子衫，骑了自行车就出来了。
太阳早已经高高挂起，秋末的阳光显然没有夏天那么有青春，反而显得温柔多了。波光嶙峋的江面，微微起伏着，平静地呼吸着，仿佛披着金黄色的鱼鳞，在水中自由自在的戏水。
在隔着江水的沿江路上，侧面被绿树环抱，显然这一带是适合青春老少的人们进行各种活动。有的人来跑步，有的人来骑自行车，虽然路不宽，不过大家都有条不紊的按照自己的节奏进行着。我骑车来到了篮球场，场上早就没人了，因为来打球的都是起早的。把自行车停放在场边后，我就开始带球在场上做热身了。
Good evening,打球回来后，匆匆吃了一碗粥，就投入 javascript 的战斗中了，由于之前学过 HTML 和 CSS 的内容，不过忘记了很多，所以学js的时候总是在想那个结构要怎么实现，于是js也没学习多少啊，！加油啊！明天学些Python!一天学一门！

A new day it is...

Also,I play basketball in the morning.Sunshine the sun still.
OK.let's go python.but just finish you js yesterday first.

啊，这么晚了啊，今天学了一点 django,加油啊小伙子，2B。。不要放弃，要加油，就算写一点点也好，加油啊！！！！
还是一样，早上去打球了。吃完早餐，准备学习js。此刻坐在电脑前，看着一些有关金庸先生逝世的消息，是的，这位给了跨越几代人的充满奇思妙想，侠肝义胆的武侠精神的灵魂人物，金庸先生，永远的离开了我们。想起这位武侠横溢的老先生，在我脑海中浮现的是种种令人神往的电视剧，这些电视剧都是改编自老先生的书籍，其中包括：《神雕侠侣》、《天龙八部》、《笑傲江湖》等著名影视作品。老先生的离开，并不代表其作品的离开，相反，这些'遗产'显得更加格外珍贵。老先生这次是做了一回真正的主角了，只不过永远不会上映，我们也看不到，但是我们知道，在另一个世界中，他身怀绝技、智勇双全、出神入化、登峰造极的绝世武功和仗义豪迈的精神过着淳朴至真的生活。先生，阳光依旧灿烂，天空依旧湛蓝，你带给我们的武侠世界永不落幕，谢谢你。
-----

今天天气让人倍感忧郁，天空没有了白云的点缀，也没有太阳，就像有一个外层罩着的电灯泡，突然没有了外面的一层，只剩下光溜溜的灯泡，显得很冷清的样子。虽然是白天，但是却让人提不起精神来。学习是要继续的，总不能因为天气的缘故，就罢工吧，这样的话，老天可是无故的成为冤大头了啊。走吧，学习去，js吧。

## 哈哈，小子，你还得学习 git .你就等着被折磨吧
好吧，学就就把，晚上好，啊不，已经很晚了，哎，生活真艰难。学习不过来了！才怪
。git 的学习，要不是为了部署django的项目，真是不想装那么多东西进入脑袋，内存不够用啊！！！
<pre>
# 目前在 d 盘下创建了空的 learngit 文件夹，
在 MINGW64中，
cd learngit
git init # 这个命令初始化一个仓库，用来控制这个文件夹中的所有文件的修改啊什么什么的
ls -ah # 显示三个东西，因为你直接去那个文件夹是看不到的，因为被隐藏了啊！！！
</pre>
接着自己去新建一个 txt 文件吧，随便起名，写两行内容就行。然后保存啦，记着在 learngit 这个目录下， 使用 git add . , 这个命令把所有文件都加入到仓库中，或者叫做让 git 关注你了，然后再用  git commit -m "created a new file", 这个命令用来提交记录你的文件囖。 -m 后面的描述是描述啦，描述你这个步骤干的东西。接着 git status, 时刻查看当前的状态。再接着 git log ,可以看你的历史记录。如果没错的话，你会看到它列出了你的 名字和日期，以及你提交的时候记录的名字，就是 -m message 命令中的 message 会显示给你看。当然你可以用 git log --pretty=oneline, 这样你会更简洁的看到提交信息的。<br>
第二次修改 txt 文件的内容，并且保存，然后用 git status, 查看之前的，这里会显示 txt 被修改过了，不过你还没提交，所以你再次输入 git add ., 表示提交所有， 当然了，你可以 git diff txtname, 来查看之间的修改，接着 git commit -m "这次修改的内容描述一下"。很简单吧。
<strong>算上前面的内容，这一节就是第三节吧，反正别压的太紧了</strong><br>
和上面的一样， git add ., git commit -m "...", git log, git diff filename, 你不必一开始就记住这些，随着你深入的学习，你会习惯这些命令的。
现在是，如果我们回退到某个版本咋办？很容易，你可以用 git log, 查看历史状态，会发现 HEAD > ,指向当前的版本，也就是你要回退到某个版本，需要知道某个版本的commitid,比如你要回退到前一个版本就是使用， git reset --hard HEAD^, 或者 git reset --hard id(至少5位6位)， 当然了，如果你关机了。或者关闭了命令窗口，那怎么办，也行，使用 git reflog, 可以查看使用的命令历史，然后可以看到你做的一切修改，和commit 版本号。<br>
<hr>
另外，git 管理修改是，只有你使用 git add 之后，commit 的提交修改才有效，如果不把 git add 放进暂存区，那么commit 的修改只能是提交已经 add 在暂存区的内容，假设你做了两次修改，那么第一次修改之后>>>git add >>> git commit, 这样第一次修改的才确实被提交了，如果第二次修改了，你没有add，那么使用commit就不会提交第二次修改了！！！另外可以使用<<<<em>git diff HEAD -- filename, 查看工作区和版本库里面最新版本的区别。</em>
<br>然后是撤销修改，使用 git checkout ., 或者 git checkout -- filename。
坚持，自律是必修课。我们生活在这里快速发展的时代，科技每逢三天更一新，Keep moving.<br>
想不到从 github 克隆到本地也很容易。 <p style="color:orange;">git clone git@github.com:SourOrange/test-learning.git</p>

因为创建、合并和删除分支非常快，所以Git鼓励你使用分支完成某个任务，合并后再删掉分支，这和直接在master分支上工作效果是一样的，但过程更安全。
<pre>
Git鼓励大量使用分支：
查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>
创建+切换分支：git checkout -b <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>
</pre>
啊，尽然行的通啊，用 git pull <remote>, 可以把远程的内容更新到本地了啊，好啊，不错！
说会 git merge branchname, 这里我们会是fast forword 模式合并，缺点就是分支的信息也没了，而且我们在开发中一定要在分支中合并好，等到发布产品版本的时候再合并到master，并且我们需要留下历史分支的信息，
所以我们先切回master, git checkout master, 再用 git merge --no-ff -m "commit message" branchname，然后你可以使用 git log --graph --pretty=oneline --abbrev-commit,查看到历史分支的信息，
