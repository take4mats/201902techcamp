---?image=assets/img/yamaki2.jpg
@title[toppage]

# 開発合宿
はじまるよ！

2019/02/25-27 @ 山喜旅館

[george](https://github.com/take4mats/201902techcamp)

---

## 今回のゴール設定

---

### テーマ
Serverless x CI/CD

---

### これを

![current](assets/img/sls_arch_current.jpg)

+++

### いろいろ工夫して (1/2)
- CI/CD パイプラインを gitlab で組む
  1. unit test ?
  2. deployment by serverless framework
  3. scenario test by Robot Framework w/ RESTinstance
  4. stress test by Gatling ?

+++

### いろいろ工夫して (2/2)
- remove Azure
- refactor AWS
  - resolve "hell of callback"
  - other tweak

---

### こうしたい

![goal](assets/img/sls_arch_goal.jpg)

---

