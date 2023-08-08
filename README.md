# tarzan-code-snippets README

为tarzan项目提供代码片段能力

## 版本信息

### 0.0.2

提供了两种可直接使用的模板

单表格列表页：t_single_table_list_page + t_single_table_list_page_ds + t_services

头行表列表页：t_head_row_table_list_page + t_head_row_table_list_page_ds + t_services

我们建议你的目录结构为：

``` 
  XxxPage
    XxxPageList
      index.tsx (使用t_xxx_list_page)
    XxxPageDetail
      index.tsx (新版正在开发中，可使用detail_page_normal_ts)
    services
      index.ts (使用t_services)
    stores
      listPageDS.ts (使用t_xxx_list_pag_ds)
      detailPageDS.ts (新版正在开发中，可使用detail_page_DS_normal_ts)
``` 

---

### 0.0.1

初始测试版本

提供代码片段：

list_page_normal_ts

list_page_DS_normal_ts

detail_page_normal_ts

detail_page_DS_normal_ts

edit_table_in_row

edit_table_in_modal

---
