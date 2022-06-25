### [Xasset](https://github.com/KelaKing/Xasset)
原版地址: 感谢大佬贡献~



# XXasset

Export images from xcassets and replace images to xcassets.

## Installing
### [Mint](https://github.com/yonaskolb/mint)
```
$ mint install brickleberry/XXasset
```

## Usage
```
1.安装完mint 工具后需要配置下bash_profile $path路径
2.原版swift 工具只会导出png 改造了一下也可以导出/替换 pdf和svg 文件, 一行工具搞定!👏🏻👏🏻👏🏻
```

```sh
# Export images
xxasset export ~/Foo.xcassets ~/FooImages
# Replace images
xxasset replace ~/FooImages ~/Foo.xcassets
```

## 其他
如果本地编译的包指向还是原来的命令工具, 可以吧源码里编译好的xxasset替换本地类似路径下的可执行文件
<img width="1233" alt="截屏2022-06-25 14 30 27" src="https://user-images.githubusercontent.com/6902330/175761543-8970dd2c-659b-4f57-a56f-a3c95958f0c6.png">
