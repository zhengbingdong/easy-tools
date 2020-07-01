<h1 align="left"> PHP工具类 <code align="right">持续更新中</code></h1>

##### 111

## 官网
<a href="http://www.qianduanwang.vip" target="_blank">共享屋素材</a>

## 更多分享信息内容请关注我的公众号：程序猿的栖息地
![程序猿的栖息地](http://www.qianduanwang.vip/uploads/layedit/20200701/3bc47221b2cc967887b9e7f661d21e2c.jpg)

## 安装

```shell
$ composer require zhengbingdong/easy-tools
```

## 时间工具类
    use Zhengbingdong\EasyTools\Dates;

    得到某天凌晨零点的时间戳 ：Dates::get_friend_date()

    友好时间显示 ：Dates::getFriendDate()

    友好时间显示 ：Dates::getFriendDate()

    获取当前时间的前7天 ：Dates::getLast7Days()

    获取星期几的信息 ：Dates::getWeekDay()

    获取月份 ：Dates::getMonth()

## Zip压缩解压工具类
    use Zhengbingdong\EasyTools\ZipTools;

    对相应目录文件进行压缩 ：ZipTools::addFileToZip()

    #事例
    使用示例
    $zip = new ZipArchive();
    $path = $_SERVER['DOCUMENT_ROOT'];
    $zipName = $_SERVER['DOCUMENT_ROOT']."/20180826.zip";
    if($zip->open($zipName, ZipArchive::CREATE) === TRUE){
    	addFileToZip($path, $zip); // 调用方法，对要打包的根目录进行操作，并将ZipArchive的对象传递给方法
    	$zip->close(); // 关闭处理的zip文件
    }
    从zip压缩文件中提取文件 ：ZipTools::unZip()

    # 事例
    使用示例：
    $filename = $_SERVER['DOCUMENT_ROOT'].'/unzip.zip';
    $path = $_SERVER['DOCUMENT_ROOT'].'/unzip';
    unZip($filename,$path );

## 数组工具类
    use Zhengbingdong\EasyTools\ArrayTools;
    更新中...

## 英文字母工具类
    use Zhengbingdong\EasyTools\CharacterTools;
    更新中...

## url相关的工具类
    use Zhengbingdong\EasyTools\CurlsTools;
    更新中...

## 文件工具类
    use Zhengbingdong\EasyTools\FileTools;
    更新中...

## http协议相关的工具类
    use Zhengbingdong\EasyTools\HttpTools;
    更新中...

## 图片工具类
    use Zhengbingdong\EasyTools\ImageTools;
    更新中...

## 日志工具类
    use Zhengbingdong\EasyTools\LogTools;
    更新中...

## 地图工具类
    use Zhengbingdong\EasyTools\MapTools;
    更新中...

## 数字工具类
    use Zhengbingdong\EasyTools\NumberTools;
    更新中...	

## 服务器相关的工具类
    use Zhengbingdong\EasyTools\ServerTools;
    更新中...

## 敏感字符串工具类
    use Zhengbingdong\EasyTools\StrFilterTools;
    更新中...

## 字符串相关操作的工具类
    use Zhengbingdong\EasyTools\StringTools;
    更新中...

## 上传文件工具类
    use Zhengbingdong\EasyTools\UploadTools;
    更新中...

## 校验工具类，如验证ip、手机、邮箱等
    use Zhengbingdong\EasyTools\VerifyTools;
    更新中...

## app版本校验工具类
    use Zhengbingdong\EasyTools\VersionTools;
    更新中...

## 操作xml相关的工具类
    use Zhengbingdong\EasyTools\XmlTools;
    更新中...


## License
**MIT**

## 后语
#### 欢迎Star
