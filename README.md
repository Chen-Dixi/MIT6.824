# MIT6.824

课程地址：[**https://pdos.csail.mit.edu/6.824/schedule.html**](https://pdos.csail.mit.edu/6.824/schedule.html)

## 如何才能更好的学习 MIT 6.824 ？

[https://zhuanlan.zhihu.com/p/110168818](https://zhuanlan.zhihu.com/p/110168818
)
不建议直接照着别人完成的作业实现！这样就没有上这门课的必要了
不要去 github 上搜代码！

## MIT 6.824 分布式系统 | 材料准备和环境搭建

[https://zhuanlan.zhihu.com/p/260470258](https://zhuanlan.zhihu.com/p/260470258)

## Github 资料浏览
[其它的一些资料](https://github.com/Anarion-zuo/AnBlogs)

## Lab1
### Run  

在`src/main`路径 运行:
```
go build -race -buildmode=plugin ../mrapps/wc.go
```
```
go run -race mrcoordinator.go pg-*.txt
```

之后多个worker可以并发执行，启动多个终端运行下面程序：
```
go run -race mrworker.go wc.so
```

`src/mr/`路径下为自己实现的代码

## Lab2
- [**Lab2A**](https://github.com/Chen-Dixi/MIT6.824/blob/2A/src/raft/raft.go)

```bash
go test -run 2A -race
```

- [**Lab2B**](https://github.com/Chen-Dixi/MIT6.824/blob/2B/src/raft/raft.go)

```bash
go test -run 2B -race
```

- **Lab2C**
- **Lab2D**