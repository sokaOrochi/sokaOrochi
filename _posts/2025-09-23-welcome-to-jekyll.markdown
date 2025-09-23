---
layout: article
title: "日誌模板"
date: 2025-09-23 18:20:00 +0800
modify_date: 2025-09-23 19:15:00 +0800
category: log
lightbox: true
---

# 我的第一篇日誌
歡迎來到 Jekyll！這是你的第一篇日誌文章。編輯或刪除它，然後開始寫作吧！

## 這是第二級標題

愛因斯坦的質能等價公式非常著名，它的形式是 
    $E=mc^2$
這個公式揭示了質量和能量之間的深刻聯繫。

二次方程式的求根公式如下：

$$
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
$$

這個公式可以解決所有形如 $ax^2 + bx + c = 0$ 的方程式。

```mermaid
graph TD
A[前端] -->|HTTP API| B[后端]
B --> C[数据库]
B --> D[任务队列]
D --> E[Worker]
E --> F[存储服务]

    subgraph 前端
    A1[波形编辑器] --> A2[标注面板]
    end
    
    subgraph 后端
    B1[Django/Flask] --> B2[音频处理接口]
    end
    
    subgraph 存储
    F1[PostgreSQL] --> F2[MinIO/S3]
    end
```

[//]: # (本地查看)
[![一張可點擊放大的圖片](/assets/img/demo.png)](/assets/img/demo.png)

[//]: # (公網查看)
{% capture image_path %}{{ '/assets/img/demo.png' | relative_url }}{% endcapture %}
[![一張可點擊放大的圖片]({{ image_path }})]({{ image_path }})
