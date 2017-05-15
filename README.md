# Swift-Note
NSLog VS Print 
1.最本质的区别NSLog 输出的日志属性在debug下  print 不具备日志属性
2.NSLog是线程安全的而Print 没有
3.print 肯定是比NSLog  具体使用还是要看当前的情况 不考虑线程安全 在debug模式下推荐用print
