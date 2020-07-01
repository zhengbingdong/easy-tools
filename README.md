<h1 align="left"> PHP工具类</h1>

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

	
## License
**MIT**

## 后语
#### 欢迎Star
