# 坐标转换模块

此模块用于百度坐标系(bd-09)、火星坐标系(国测局坐标系、gcj02)、WGS84坐标系的相互转换，仅使用Python标准模块，无其他依赖。

国内常用的坐标形式是(lng, lat), 国外有的网站用的是(lat, lng)(如 osmxn), 使用的时候需要注意 

## 使用说明(coordTrans.py)

### 方法说明

```bash
# 方法说明
gcj02_to_bd09(lng, lat) # 火星坐标系->百度坐标系
bd09_to_gcj02(lng, lat) # 百度坐标系->火星坐标系
wgs84_to_gcj02(lng, lat) # WGS84坐标系->火星坐标系
gcj02_to_wgs84(lng, lat) # 火星坐标系->WGS84坐标系
bd09_to_wgs84(lng, lat) # 百度坐标系->WGS84坐标系
wgs84_to_bd09(lng, lat) # WGS84坐标系->百度坐标系
