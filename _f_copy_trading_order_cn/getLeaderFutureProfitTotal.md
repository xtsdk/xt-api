---
title: 获取预计待分润汇总
position_number: 8
type: get
description: /v1/copy-trade/my-profit-future-total
parameters:

content_markdown: >-
    #### **限流规则**

    10/s/apikey
left_code_blocks:
    -
        code_block:
        title: Java
        language: java
    -
        code_block:
        title: Python
        language: python
right_code_blocks:
    -
        code_block: |-
                        {
                        "returnCode": 0,
                        "msgInfo": "success",
                        "error": null,
                        "result": 0 // 待分润总量
                        }
        title: Response
        language: json
---