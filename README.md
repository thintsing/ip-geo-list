# IP Geo Location CIDR 地理位置 IP 段列表

> **中文** (默认) | <details><summary>English</summary>

> Automatically generated CIDR block lists grouped by continent, country, and administrative divisions.
> </details>

---

## 数据来源 / Data Sources

- **ip2region** — 中国 IPv4 数据库
- **qqwry.dat** — 纯真 IP 库
- **GeoLite2** (MaxMind) — 全球 IP 定位
- **Huawei Region DB** — 华为区域数据库
- **Meituan IP Location API** — 美团 IP 定位（用于中国争议 IP 仲裁）

<details>
<summary>English</summary>

- **ip2region** — China IPv4 database
- **qqwry.dat** — Chunzhen IP database
- **GeoLite2** (MaxMind) — Global IP geolocation
- **Huawei Region DB** — Huawei regional database
- **Meituan IP Location API** — For disputed Chinese IP arbitration
</details>

---

## 文件结构 / File Structure

### 大洲 / Continents（8 个文件）

```
  africa.txt
  antarctica.txt
  asia.txt
  europe.txt
  north_america.txt
  oceania.txt
  other.txt
  south_america.txt
```

`continents/` 目录按大洲分组。`asia.txt` 包含中国。

<details>
<summary>English: Files in <code>continents/</code> are grouped by continent. <code>asia.txt</code> includes China.</summary>
</details>

### 中国 / China

- `cn_all.txt` — 全中国 CIDR 合并

### 省份 / Provinces（33 个文件）

```
  anhui.txt
  aomen.txt
  beijing.txt
  chongqing.txt
  fujian.txt
  guangdong.txt
  guangxi.txt
  guizhou.txt
  hainan.txt
  hebei.txt
  heilongjiang.txt
  henan.txt
  hubei.txt
  hunan.txt
  jiangsu.txt
  jiangxi.txt
  jilin.txt
  liaoning.txt
  neimenggu.txt
  ningxia.txt
  qinghai.txt
  shandong.txt
  shanghai.txt
  shanxi.txt
  sichuan.txt
  taiwan.txt
  tianjin.txt
  unknown.txt
  xanggang.txt
  xinjiang.txt
  xizang.txt
  yunnan.txt
  zhejiang.txt
```

### 城市 / Cities（261 个文件）

```
  anhui_bengbu.txt
  anhui_bozhou.txt
  anhui_chizhou.txt
  anhui_chuzhou.txt
  anhui_fuyang.txt
  anhui_hefei.txt
  anhui_huaibei.txt
  anhui_maanshan.txt
  anhui_suzhou.txt
  anhui_tongling.txt
  anhui_wuhu.txt
  anhui_xuancheng.txt
  fujian_fuzhou.txt
  fujian_longyan.txt
  fujian_nanping.txt
  fujian_ningde.txt
  fujian_putian.txt
  fujian_quanzhou.txt
  fujian_sanming.txt
  fujian_xiamen.txt
  fujian_zhangzhou.txt
  guangdong_chaozhou.txt
  guangdong_dongguan.txt
  guangdong_foshan.txt
  guangdong_guangzhou.txt
  guangdong_heyuan.txt
  guangdong_jiangmen.txt
  guangdong_maoming.txt
  guangdong_meizhou.txt
  guangdong_qingyuan.txt
  guangdong_shantou.txt
  guangdong_shanwei.txt
  guangdong_shaoguan.txt
  guangdong_shenzhen.txt
  guangdong_yangjiang.txt
  guangdong_yunfu.txt
  guangdong_zhaoqing.txt
  guangdong_zhongshan.txt
  guangdong_zhuhai.txt
  guangxi_baise.txt
  guangxi_beihai.txt
  guangxi_fangchenggang.txt
  guangxi_guigang.txt
  guangxi_guilin.txt
  guangxi_hechi.txt
  guangxi_hezhou.txt
  guangxi_laibin.txt
  guangxi_liuzhou.txt
  guangxi_nanning.txt
  guangxi_qinzhou.txt
  guangxi_wuzhou.txt
  guangxi_yulin.txt
  guizhou_bijie.txt
  guizhou_guiyang.txt
  guizhou_liupanshui.txt
  guizhou_qianxinan.txt
  guizhou_tongren.txt
  guizhou_zunyi.txt
  hainan_haikou.txt
  hainan_sanya.txt
  hebei_baoding.txt
  hebei_cangzhou.txt
  hebei_chengde.txt
  hebei_handan.txt
  hebei_hengshui.txt
  hebei_langfang.txt
  hebei_qinhuangdao.txt
  hebei_shijiazhuang.txt
  hebei_tangshan.txt
  hebei_xingtai.txt
  hebei_zhangjiakou.txt
  heilongjiang_daqing.txt
  heilongjiang_haerbin.txt
  heilongjiang_hegang.txt
  heilongjiang_heihe.txt
  heilongjiang_jiamusi.txt
  heilongjiang_jixi.txt
  heilongjiang_mudanjiang.txt
  heilongjiang_qiqihaer.txt
  heilongjiang_shuangyashan.txt
  heilongjiang_suihua.txt
  heilongjiang_yichun.txt
  henan_anyang.txt
  henan_jiaozuo.txt
  henan_kaifeng.txt
  henan_luoyang.txt
  henan_pingdingshan.txt
  henan_sanmenxia.txt
  henan_xinyang.txt
  henan_xuchang.txt
  henan_zhengzhou.txt
  henan_zhoukou.txt
  henan_zhumadian.txt
  hubei_ezhou.txt
  hubei_huangshi.txt
  hubei_jingmen.txt
  hubei_jingzhou.txt
  hubei_shiyan.txt
  hubei_suizhou.txt
  hubei_wuhan.txt
  hubei_xianning.txt
  hubei_xiaogan.txt
  hunan_changde.txt
  hunan_changsha.txt
  hunan_hengyang.txt
  hunan_loudi.txt
  hunan_shaoyang.txt
  hunan_xiangtan.txt
  hunan_xiangxi.txt
  hunan_yiyang.txt
  hunan_yueyang.txt
  hunan_zhangjiajie.txt
  hunan_zhuzhou.txt
  jiangsu_changzhou.txt
  jiangsu_huaian.txt
  jiangsu_lianyungang.txt
  jiangsu_nanjing.txt
  jiangsu_nantong.txt
  jiangsu_suqian.txt
  jiangsu_suzhou.txt
  jiangsu_taizhou.txt
  jiangsu_wuxi.txt
  jiangsu_xuzhou.txt
  jiangsu_yancheng.txt
  jiangsu_yangzhou.txt
  jiangsu_zhenjiang.txt
  jiangxi_fuzhou.txt
  jiangxi_jian.txt
  jiangxi_jingdezhen.txt
  jiangxi_jiujiang.txt
  jiangxi_nanchang.txt
  jiangxi_pingxiang.txt
  jiangxi_shangrao.txt
  jiangxi_xinyu.txt
  jiangxi_yichun.txt
  jiangxi_yingtan.txt
  jilin_baicheng.txt
  jilin_baishan.txt
  jilin_changchun.txt
  jilin_jilin.txt
  jilin_liaoyuan.txt
  jilin_siping.txt
  jilin_songyuan.txt
  jilin_tonghua.txt
  jilin_yanbian.txt
  liaoning_anshan.txt
  liaoning_benxi.txt
  liaoning_dalian.txt
  liaoning_fushun.txt
  liaoning_fuxin.txt
  liaoning_huludao.txt
  liaoning_liaoyang.txt
  liaoning_panjin.txt
  liaoning_shenyang.txt
  liaoning_tieling.txt
  liaoning_yingkou.txt
  neimenggu_alashan.txt
  neimenggu_baotou.txt
  neimenggu_bayannaoer.txt
  neimenggu_chifeng.txt
  neimenggu_eerduosi.txt
  neimenggu_huhehaote.txt
  neimenggu_hulunbeier.txt
  neimenggu_tongliao.txt
  neimenggu_wuhai.txt
  neimenggu_wulanchabu.txt
  neimenggu_xilinguolei.txt
  neimenggu_xingan.txt
  ningxia_guyuan.txt
  ningxia_shizuishan.txt
  ningxia_wuzhong.txt
  ningxia_yinchuan.txt
  ningxia_zhongwei.txt
  qinghai_haibei.txt
  qinghai_haidong.txt
  qinghai_hainan.txt
  qinghai_xining.txt
  shandong_binzhou.txt
  shandong_dezhou.txt
  shandong_dongying.txt
  shandong_heze.txt
  shandong_jinan.txt
  shandong_jining.txt
  shandong_liaocheng.txt
  shandong_qingdao.txt
  shandong_rizhao.txt
  shandong_weifang.txt
  shandong_weihai.txt
  shandong_yantai.txt
  shandong_zaozhuang.txt
  shandong_zibo.txt
  shanxi_ankang.txt
  shanxi_baoji.txt
  shanxi_datong.txt
  shanxi_hanzhong.txt
  shanxi_jinzhong.txt
  shanxi_lvliang.txt
  shanxi_shangluo.txt
  shanxi_shuozhou.txt
  shanxi_taiyuan.txt
  shanxi_tongchuan.txt
  shanxi_weinan.txt
  shanxi_xian.txt
  shanxi_xianyang.txt
  shanxi_xinzhou.txt
  shanxi_yanan.txt
  shanxi_yangquan.txt
  shanxi_yulin.txt
  shanxi_yuncheng.txt
  sichuan_bazhong.txt
  sichuan_chengdu.txt
  sichuan_dazhou.txt
  sichuan_deyang.txt
  sichuan_guangan.txt
  sichuan_guangyuan.txt
  sichuan_leshan.txt
  sichuan_liangshan.txt
  sichuan_meishan.txt
  sichuan_nanchong.txt
  sichuan_neijiang.txt
  sichuan_panzhihua.txt
  sichuan_suining.txt
  sichuan_yaan.txt
  sichuan_yibin.txt
  sichuan_zigong.txt
  taiwan_tainan.txt
  taiwan_taoyuan.txt
  xinjiang_hami.txt
  xinjiang_kelamayi.txt
  xinjiang_tulufan.txt
  xinjiang_wulumuqi.txt
  xizang_changdou.txt
  xizang_lasa.txt
  xizang_linzhi.txt
  xizang_naqu.txt
  xizang_shannan.txt
  yunnan_baoshan.txt
  yunnan_chuxiong.txt
  yunnan_dali.txt
  yunnan_dehong.txt
  yunnan_honghe.txt
  yunnan_kunming.txt
  yunnan_lijiang.txt
  yunnan_lincang.txt
  yunnan_puer.txt
  yunnan_qujing.txt
  yunnan_wenshan.txt
  yunnan_xishuangbanna.txt
  yunnan_yuxi.txt
  yunnan_zhaotong.txt
  zhejiang_hangzhou.txt
  zhejiang_huzhou.txt
  zhejiang_jiaxing.txt
  zhejiang_jinhua.txt
  zhejiang_lishui.txt
  zhejiang_ningbo.txt
  zhejiang_quzhou.txt
  zhejiang_shaoxing.txt
  zhejiang_taizhou.txt
  zhejiang_wenzhou.txt
  zhejiang_zhoushan.txt
```

---

## 准确性 / Accuracy

中国 IP 使用四源投票机制（ip2region + qqwry.dat + GeoLite2 + Huawei DB），争议段由 Meituan API 裁决。

<details>
<summary>English: Chinese IP geolocation uses a 4-source voting system with Meituan API override for disputed ranges.</summary>
</details>

## 更新频率 / Update Frequency

根据最新地理位置数据库按需生成。

<details>
<summary>English: Generated on-demand from the latest geolocation databases.</summary>
</details>
