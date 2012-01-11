PullToRefresh

A simple iPhone class for adding pull-to-refresh functionality to any scrollable view.

![](http://s3.amazonaws.com/leah.baconfile.com/blog/refresh-small-1.png)
![](http://s3.amazonaws.com/leah.baconfile.com/blog/refresh-small-2.png)
![](http://s3.amazonaws.com/leah.baconfile.com/blog/refresh-small-3.png)
![](http://s3.amazonaws.com/leah.baconfile.com/blog/refresh-small-4.png)

Inspired by [Tweetie 2](http://www.atebits.com/tweetie-iphone/), [Oliver Drobnik's blog post](http://www.drobnik.com/touch/2009/12/how-to-make-a-pull-to-reload-tableview-just-like-tweetie-2/)
and [EGOTableViewPullRefresh](http://github.com/enormego/EGOTableViewPullRefresh).


How to install

1. Copy the files, [PullToRefresh.h](https://raw.github.com/tpuronen/PullToRefresh/master/Classes/PullToRefresh.h),
[PullToRefresh.m](https://raw.github.com/tpuronen/PullToRefresh/master/Classes/PullToRefresh.m),
and [arrow.png](http://github.com/tpuronen/PullToRefresh/raw/master/arrow.png) into your project.

2. Link against the QuartzCore framework (used for rotating the arrow image).

3. Create PullToRefreshController and give it a UIScrollView (or subclass) and a block to be executed when view is pulled down.

Enjoy!
