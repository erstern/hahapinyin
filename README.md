## 汉语拼音定制输入方案，献给CHemperor！

基于[地球拼音](https://github.com/lotem/brise/blob/master/preset/terra_pinyin.schema.yaml)、[明月拼音](https://github.com/rime/brise/blob/master/preset/luna_pinyin.schema.yaml)、[明月拼音·筆畫輔助碼](https://github.com/rime-aca/schemata/blob/master/luna_pinyin_stroke/luna_pinyin_stroke.schema.yaml)及[中州韻之貓顏文字](https://github.com/hitigon/meow-emoji-rime/blob/master/meow_emoji.schema.yaml)制作，并为CH私人定制！

#### 定制方案的安装启用（仅适用于rime-gits-20151010-alpha -- 即新版RIME for Window$，Win7及更高版本有效。）
  1. [点我下载](http://pan.baidu.com/s/1i3GW9LV) 新版RIME安装包，解压到某一硬盘分区的根目录（其他路径也可以，只是文件夹名最好不要有空格），进入rime-gits-20151010-alpha文件夹，以管理员权限运行「install」，接下来的提示均允许，之后「Ctrl + Shift」启动一次RIME。
  2. [点我下载](http://git.oschina.net/erstern/haha_pinyin/repository/archive/master)，[或者是我](https://github.com/erstern/haha_pinyin/archive/master.zip) 下载哈哈拼音配置文件，解压。（两个下载地址分别为github与git.oschina，同步推送。）
  3. 进入「C:\Users\Administrator\AppData\Roaming\Google\Google Input Tools\Rime」,把刚才解压的配置文件全部复制进来。注意「Users」可能为中文「用户」，「AppData」可能为隐藏文件夹。
  4. 点击「Ctrl + Alt + Delete」启动任务管理器，kill掉两个「GoogleInputTools」开头的进程（kill之后会自动活过来，点击一次「结束进程」即可），再次「Ctrl + Shift」启动RIME等待数秒，新配置生效；或重启计算机生效。
  5. 按「Ctrl+`」，选择「哈哈拼音・何喝专享」即可开始使用。

下次只要（在中文模式下）直接輸入「vhaha」就能看到本方案最新版本地址，同樣方法下載並使配置生效即可。

#### 聲調
可以輸入符號 `- / < \` 作爲漢語拼音方案四種聲調，如輸入`a`，則字母分別轉寫爲``ā á â à``，其餘類推。

#### Tips
  - 輸入「ü」時，在聲母「j q x」後，可用「u」替代，顯示時可自動轉寫爲「ü」；「l n」後仍以「v」表示。
  - 聲母爲「j q x」時，可以省略介母「i」，如「加」可簡化爲「ja」，「千」可簡化爲「qan」，「向」可簡化爲「xang」。
  - 點擊字母「v」進入標點和其他符號輸入模式，符號列表可[點我](http://git.oschina.net/erstern/myRIMEschemas/blob/master/haha_pinyin/symbols_CH.yaml查看。
  - 在區分聲調的同時，也可使用默認不帶聲調的[朙月拼音](https://github.com/lotem/brise/blob/master/preset/luna_pinyin.dict.yaml)方案。
  - 取消默認的方案切換鍵[F4]，不影響 RIME 在 Excel 等軟件中快捷鍵的使用。
  - 同時支持[朙月拼音·筆畫輔助碼](https://github.com/rime-aca/schemata/blob/master/luna_pinyin_stroke/luna_pinyin_stroke.schema.yaml)方案。輸入全拼後可以繼續鍵入五筆畫作爲輔助碼，如「木（mu）」，可輸入「muhspn」（mu+橫豎撇捺）確定字型。同時支持速成模式，即「全拼+五筆畫首筆+五筆畫末筆」，「木」爲「muhn」（mu+橫捺）。
  - 中文狀態下，可同時輸入英文，無需轉換。
  - 按「Ctrl+`」，選擇「Easy English」可進入英文輸入模式，可以提示完整英文拼寫。
  - 新加入顏文字！

#### Eggs
鍵入「v」後，輸入特定字符，有驚喜！

#### 歡迎提出寶貴建議
