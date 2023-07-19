# Magisk Delta

本存储库存储Magisk Delta增量文件

![Delta](https://user-images.githubusercontent.com/84650617/222942594-63336f63-6a26-492e-a1d1-a356b5f777b3.png)

<img src="https://user-images.githubusercontent.com/84650617/224252197-cc54e66d-e4dd-49d4-ab8b-4506a6a3aecd.png" width="25%"/><img src="https://user-images.githubusercontent.com/84650617/223767996-f757e070-1c66-4cea-a783-e65c10640dd9.png" width="25%"/><img src="https://user-images.githubusercontent.com/84650617/224252519-2d676a3e-408d-43db-9f59-17d942d3ed9f.png" width="25%"/><img src="https://user-images.githubusercontent.com/84650617/224252589-98baf8f9-c4a1-4195-bacf-ed63908154f0.png" width="25%"/>

## 介绍

**这不是受支持的 [topjohnwu](https://github.com/topjohnwu) 项目**. 

> 如果你正在寻找官方版Magisk，请 [点击这里下载官方版Magisk](https://github.com/topjohnwu/Magisk)

- [内部文档](./docs/internal-guide.md)
- [FAQ](./docs/faq.md)

**这不是受支持的 [huskydg](https://github.com/huskydg) 项目**. 

> 如果你正在寻找官方版Magisk Delta，请 [点击这里下载官方版Magisk](https://github.com/huskydg/magisk-files)


## 下载

### Canary / Debug

> ⚠ Only accept bugreports from Magisk Delta debug variant. Canary and Debug are built from the same source code. Debug builds have more detailed logs and are suitable for debugging. Canary builds have less logs, are more stable than Debug, and are suitable for most common uses

#### 下载

- [下载 Canary版本](https://petertea5822.github.io/magisk-delta-suu-files/app-release.apk)
- [下载Download Debug版本](https://petertea5822.github.io/magisk-delta-suu-files/app-debug.apk) 


#### 源代码

- Magisk Delta 是 [基于GNU v3的开源项目](#license).  `source-code.zip` 会被上传到这里: <https://github.com/PeterTea5822/magisk-delta-suu-files/releases>
- 编译过程与 [Official Magisk](https://github.com/topjohnwu/magisk#building-and-development)相同 请将`-delta`后缀添加到 `versionName` 在 `config.prop`内


## 贡献者
- Patch vivo_do_mount_check Program author: [wuxianlin](https://github.com/wuxianlin/build_magisk_vivo/) 
- Libsuu author: [4accccc](https://github.com/4accccc/libsuu)
- Magisk delta author: [huskydg](https://github.com/huskydg/magisk-files)

- Magisk author: [topjohnwu](https://github.com/topjohnwu/magisk)
- Magisk contributors: [vvb2060](https://github.com/vvb2060), [yujincheng08](https://github.com/yujincheng08), [RikkaW](https://github.com/RikkaW), [canyie](https://github.com/canyie)
- SuList idea: [MagiskLite](http://t.me/magisklite)
- Maru (zygisk native bridge): [5ec1cff](https://github.com/5ec1cff)
- Other: [osm0sis](https://github.com/osm0sis), [diareuse](https://github.com/diareuse),...
- Monet design: [HardcodedCat](https://github.com/HardcodedCat), [datnerdguy](https://github.com/datnerdguy)

## 许可证

Our license obviously is the same as [Magisk's license](https://github.com/topjohnwu/Magisk#License)

```
Magisk, including all git submodules are free software:
you can redistribute it and/or modify it under the terms of the
GNU General Public License as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
