# rime_configs

Personal backup for RIME[http://rime.im/] input configs

- wubi06    新世纪五笔
- double_pinyin_flypy    小鹤双拼
- hepy  小鹤音形
- double_pinyin_bullpy  大牛双拼（只有音）
- daniu_double 大牛 小牛

The files are copied from Internet, thanks for contributors. 


-- Update for 0.10.0
Accoring to https://github.com/rime/squirrel/issues/279

安裝包精簡後只提供輸入法程序及基本開箱體驗所需的最小數據集。

由此獲取 所需輸入方案配方包，佈置在 用戶文件夾。自製方案及補丁文件也繼續放在這裏。

通過命令行安裝預設輸入方案：

curl -fsSL https://git.io/rime-install | bash -s -- :preset

或列舉要額外安裝的配方包名 ℞，如

curl -fsSL https://git.io/rime-install | bash -s -- :preset double-pinyin
