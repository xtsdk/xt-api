---
title: Update net asset 
position_number: 2
type: put
description: /v4/etf/net-asset
parameters:
    -
        name: symbol
        type: string
        mandatory: false
        default:
        description: Trading pair, if one party is margin, required
        ranges:
    -
        name: netAsset
        type: number
        mandatory: true
        default:
        description: net asset
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
