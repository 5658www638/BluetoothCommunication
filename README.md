# BluetoothCommunication
蓝牙通讯安卓服务器和客户端
安卓蓝牙通讯服务器和客户端，亲测能用

主要参考以下代码
* 服务器代码参考：https://blog.csdn.net/nishigesb123/article/details/90401981
* 客户端代码参考：https://blog.csdn.net/weixin_44902943/article/details/113107078
* 服务器的那篇博客有客户端和服务器的代码，但是客户端不知道为什么老是不能用，只有服务器的代码可以用
* 客户端的那篇博客只有客户端的代码，原本是用来做遥控车上位机的。那篇博客的代码中搜索蓝牙地址的那部分，个人觉得没太大必要，就改为了在列表中显示曾经配对成功的设备。
* 客户端是主动去连接服务器的，服务器等待客户端去连接。
* 这两个代码里，客户端需要提前与服务器的手机配对成功，然后才能在列表中进行显示，客户端才可以根据这个列表的地址主动连接服务器，也就是说服务器是不需要知道地址的，只需要客户端知道服务器地址并且二者曾经连接成功过就行
* 本人对该代码进行了修改，因为非科班出身，仅为兴趣驱使，所以代码仅供参考。
