---
title: "不拖沓"
author: vampirefan
date: 2012-09-18 18:37
comments: true
categories: 学习
tags: 
- wordpress
- php
- ruby
---

专利号拿到了，可是晚了一周，否则可以作为奖学金评选条目。可见做事情要快，不能拖，要做的事情就应该尽全力最快的解决掉。以前一直认为自己效率挺高的。上大学以后却不像从前那么提前迅速的处理事情了。凡事喜欢拖到最后的deadline。这是个极其不好的习惯。一定要改！今天开始，把能做的事情都做完，要做的事情安排好；不拖沓每一件事情！要有效率的过好每一天！

<!-- more -->

发现一个学`ruby`的好东西：[http://rubykoans.com/](http://rubykoans.com/),在排错中学习，一个一个文件的排错，一点一点的到达终点。想法特别好，做的也特别有创意有系统。觉得像`C/C++`、`prel`、`php`是不是都可以做成像这样的学习方式。很赞很赞~


啊对了，`wordpress`上面设置访问权限终于有人告诉我答案了，亲测可行。这里感谢百度上回答我问题的[朋友](http://zhidao.baidu.com/question/473338969.html&__bd_tkn__=6ea61e3576378a035253a361a6b329b0800286af8078338d51fed8133ea5c69d362ad36bb4bcda3b39bb3949f6bbe47087ac3af56e60b1f4e7eb60157c5bfe319e6fa0fe570f03de0125270dd244cb0d3f7e9371785dbffed53e447e065e462fb9177f3b49b0aadeef7efdaccbdc8d0cc23326f04fab)~原理是在进入网站的时候执行`login.php`登陆页面。    

* 在当前主题的`function.php`中添加：

        function liveme_if_login()
        {
        	if(!is_user_logged_in())
        	{
        		auth_redirect();
        	}
        }

* 再在`header.php`中添加：

        <?php liveme_if_login();?>

可是我已经把博客搬到这里来了，暂时也没时间折腾`wordpress`,就先放下，感觉博客的搭建方法会一直有新技术出现的。暂时先不折腾这个了。`python`
框架也出来很多了。。。 ：）

最近“购岛”闹得沸沸扬扬，其实我对政治一直不是很感兴趣。虽然，在看很多爱国电影，电视剧，小说后会热血沸腾，爱国心澎湃。但平时是不怎么关心的。其实呢，很多事情上，国家对外的表现是它们的表现，有很多因素制约的。很多人说，呀，要打仗了。。。我其实并不希望。打仗终究不是好的解决办法。但是现在的中国，应该表现出自己的强势！我一向是对我国充满信心，充满自豪的。