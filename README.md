# spacemesh快P程序

#### 一. 程序说明

##### 1. fastsmh是spacemesh的快P软件，对于30系的显卡，P图速度最高可以提升50%，40系则提升不明显，只支持N卡，不支持A卡


##### 2. 具体数据(数据为单次测试，没有条件进行多型号测试，所以不一定百分百准确，只做为参考)

| 型号  | 官方数据(MB/s)  | fastsmh速度(MB/s)  | 提升比例  |
|:----------|:----------|:----------|:----------|
| 3070    | 2.51    | 3.81    | 50%    |
| 3060    | 2    | 2.6    | 33.5%    |
| 3080    | 2.9    | 4.9  | 68.9%    |
| 3090    | 4.0    | 6.9    | 72.5%    |
| 50HX    | 2    | 3.4    | 70%    |
| 40HX    | 1.3   | 2.7    | 107%    |
| P102    |     | 1.25    | -    |

##### 3. 运行效果

![image](fastsmh.png)


#### 二. 常见问题


##### 1. 本软件收费吗?

###### 答: 本软件收费，每台机器收费为100元, 永久授权, 新用户可以免费试用三天，请添加客服微信获取试用资格

##### 2. 本软件支持windows吗?

###### 答: 不支持windows, 只支持linux

##### 3. 本软件支持A卡吗?

###### 答: 不支持

##### 4. 可以P到共享目录吗?

###### 答: 可以P到共享目录，但samba共享存在一个问题，如果存储机挂载的硬盘是是在samba共享目录下面的话，会获取不到磁盘的剩余空间，导致P图无法进行, 比如

####### 下面这种情况可以
```
samba 共享目录 为 /mnt/sda
硬盘挂载目录为  /mnt/sda
```

####### 下面这种情况不行
```
samba共享目录为 /mnt
硬盘挂载目录为 /mnt/sda
```



#### 三. 如何购买

###### 可以添加客服微信购买或者申请试用

###### 1. 客服微信: lycaisxw

###### 2. 扫码添加：<img src=webchat.png width=300 height=300/>



