# self_vnpy

基于量化开源框架vnpy，添加的一些个人开发。

### 改动
+ 添加jqdata源，涉及文件：
    + trader/mddata
    + app/cta_backtester/engine.py
    + app/cta_strategy/engine.py 
    + app/script_trader/engine.py
    + trader/setting.py 

+ 修改默认数据库地址（因为vn station选择了地址，为了保持全局使用的数据库一致），涉及文件：
    + trader/setting.py 

+ 注释加载数据进度条，涉及文件：
    + app/cta_strategy/backtesting.py

+ 添加策略工具文件
    + app/cta_strategy/tools.py
    + app/cta_strategy/\_\_init\_\_.py