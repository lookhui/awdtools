\#小镇做题家 这个是本人参与金砖前写的一个简易打awd工具，里面可以pwn与web一键获取flag，还有两个模块因时间问题没有写出，如果以后有空可以继续写入

需要说的一点是这个不死马上传只能上传我指定的这个才行

现扫描ip

因为awd模式基本处于一个网段下

扫描80是因为我的内网环境是80

![image-20240420100151085](https://s2.loli.net/2024/04/20/VnPF9m2qzd16kCM.png)

![image-20240420100208973](https://s2.loli.net/2024/04/20/cumBr1vIDZ76ojs.png)

可以发现就我们的130存活

![image-20240420100241071](https://s2.loli.net/2024/04/20/LT8dhsyaUnISeZu.png)

成功的被写入了

工具的作用就是使用小马上传大马

接下来我们使用我们之前上传的小马直接去连接然后上传大马

![image-20240420100545520](https://s2.loli.net/2024/04/20/gX9DsMUdmrQjLfH.png)

执行命令

![image-20240420100628631](https://s2.loli.net/2024/04/20/E4dMzljPxsCAKD6.png)

然后上传我们的马儿

![image-20240420100656831](https://s2.loli.net/2024/04/20/ExAHgPNMtXJIp78.png)

可以发现我们现在这里就只有这一个马

我们可以在里面写一个flag

尝试一下我们这个能不能获取到flag

![image-20240420110138180](https://s2.loli.net/2024/04/20/kw51xyXvnjeq7S4.png)

这样即可访问执行命令

![image-20240420110204542](https://s2.loli.net/2024/04/20/LakWJqhxDHNtwlB.png)

这样就能得到flag

![image-20240420110736805](../AppData/Roaming/Typora/typora-user-images/image-20240420110736805.png)
