# W27：[状态管理](https://github.com/OS-Q/W27)

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属管理节点：[M7](https://github.com/OS-Q/M7)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)


## [平台描述](https://github.com/OS-Q/W27/wiki) 

状态管理平台用于实时长期在线管理系统所有的设备状态，用于引导分配和资源调度

### [共用资源](https://github.com/OS-Q/W27/wiki) 


---

- 边缘设备统一命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

## [包含设备](https://github.com/OS-Q/W27/wiki) 

#### D183：[设备注册查询](https://github.com/OS-Q/D183)

（登记处）用于注册设备到系统中，该设备维护所有注册设备信息

#### D184：[生命周期维护](https://github.com/OS-Q/D184)

（巡检员）用于查询所有设备状态，测试下辖设备是否正常

#### D185：[资源关联调度](https://github.com/OS-Q/D185)

（咨询台）用于优化调度资源，启用相关策略

#### D186：[资源缓冲池](https://github.com/OS-Q/D186)

（投递箱）用于缓冲相关需求，等待资源激活后发布

#### D187：[NULL](https://github.com/OS-Q/D187)



#### D188：[NULL](https://github.com/OS-Q/D188)



#### D189：[NULL](https://github.com/OS-Q/D189)


## [同级平台](https://github.com/OS-Q/M7/wiki/index) 

#### -> W27：[状态管理](https://github.com/OS-Q/W27)

用于监控各个平台的状态信息，维护通信

#### W28：[生成优化](https://github.com/OS-Q/W28)

用于编译源码，配置相应设备系统参数

#### W29：[异常处理](https://github.com/OS-Q/W29)

用于处理各个平台节点设备的异常情况

#### W30：[交互控制](https://github.com/OS-Q/W30)

用于发布系统信息，接收用户控制指令


---

####  qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  © 2018-12-11

---

