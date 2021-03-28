# ⚙️首次安装

## 视频教程

{% embed url="https://youtu.be/GKGnlF4zZVg" caption="" %}

## 步骤 1

为了防止服务器会出一些不可预料的BUG.你可以整一个测试服务端然后进行测试,然后再把插件放到服务器去食用

{% hint style="danger" %}
如果你已经有了旧版本的 ItemsAdder(v1.0) 那么请先将目录 **plugins/ItemsAdder** 移动到 **ItemsAdder\_backup**
{% endhint %}

* 安装 [**ProtocolLib**](https://www.spigotmc.org/resources/protocollib.1997/)
* 安装 [**IALib**](https://www.spigotmc.org/resources/ialib.75974/)
* 安装 [**LightAPI**](https://www.spigotmc.org/resources/lightapi-fork.48247/)
* 将 **ItemsAdder.jar** 放到服务端的插件目录
* 打开你的服务器
* 让Itemadder插件进行**初始化**,中国的腐竹需要用科学上网来下载材质包[当然得在放服务端机子里用科学上网,不是玩家用科学上网哦]
* 关闭服务器或者进服务器进行初步测试

## 步骤 2

* 插件加载完成后进入服务器然后输入命令 `/iazip`
* 打开Itemadder的配置文件 **[plugins\ItemsAdder\config.yml]**
* 按照下面的按钮来进行下一步的配置

{% page-ref page="plugin-usage/resourcepack-hosting/resourcepack-self-hosting.md" %}

{% hint style="warning" %}
当你想让插件更新资源包 `pack.zip`，请输入指令 `/iazip`
{% endhint %}

### 可选步骤

{% hint style="info" %}
如果你想开始制作一些自定义物品,你可以先查看下面按钮的内容

{% page-ref page="faq/removing-default-stuff.md" %}
{% endhint %}

