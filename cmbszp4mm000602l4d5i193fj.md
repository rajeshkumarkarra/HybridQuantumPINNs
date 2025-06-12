---
title: "Swift lang made easy"
seoTitle: "Swift language made easy"
datePublished: Thu Jun 12 2025 06:20:27 GMT+0000 (Coordinated Universal Time)
cuid: cmbszp4mm000602l4d5i193fj
slug: swift-lang-made-easy
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1749709051318/a2564fb9-caaf-4dc2-b9b3-bf16616cd43d.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1749709196372/2e18401b-e725-478f-894c-68a9458dec73.png
tags: swift

---

```swift
import Foundation
import Complex
import Numerics

var interstingNumbers = [
  "primes": [2, 3, 5, 7, 11, 13, 17, 19, 23, 29],
  "triangular": [1, 3, 6, 10, 15, 21, 28, 36, 45, 55],
  "hexagonal": [1, 6, 15, 28, 45, 66, 91, 120, 153, 190],
]

for key in interstingNumbers.keys {
  interstingNumbers[key]?.sort(by: >)
}

print(interstingNumbers["primes"]!)
```