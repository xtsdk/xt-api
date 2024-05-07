---
title: 资产净值更新
position_number: 2
type: put
description: /v4/etf/net-asset
parameters:
    -
        name: symbol
        type: string
        mandatory: false
        default:
        description: 交易对，如果一方是杠杆，必传
        ranges:
    -
        name: netAsset
        type: number
        mandatory: true
        default:
        description: 更新的资产净值
        ranges:
content_markdown:
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
                  "rc": 0,
                  "mc": "string",
                  "ma": [
                    {}
                  ],
                  "result": {
                  }
                }
        title: Response
        language: json
---
