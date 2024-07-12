- [Golang在函数中给结构体对象赋值的一个坑 ](https://www.cnblogs.com/paulwhw/p/15551745.html)
- [Go总结（三）| 函数传值和传指针的区别](https://chende.ren/2020/11/26122308-003-pass-value-pointer.html)
- golang间接函数调用(无接受值的函数实际上是有接受值的函数)
    - [为什么 Golang 函数赋值会产生内存分配？](https://www.purewhite.io/2020/06/30/golang-indirect-function-allocate/#%E5%87%BD%E6%95%B0%E9%97%B4%E6%8E%A5%E8%B0%83%E7%94%A8%E5%AE%9E%E7%8E%B0)
    - [Go 1.1 Function Calls](https://docs.google.com/document/u/0/d/1bMwCey-gmqZVTpRax-ESeVuZGmjwbocYs1iHplK-cjo/pub?pli=1)


- `var xxx SomeStruct` 会初始化 struct 的各个 field 为默认空值 ( 0,false,"" )
- `var xxx []string` 会初始化成nil
- `xxx := []string{}` 会初始化成0个元素但不为nil的切片
- `var xxx map[string]string` 会初始化成nil
- `xxx := map[string]string{}` 会初始化成0个元素但不为nil的map
