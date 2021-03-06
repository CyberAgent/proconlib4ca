---
layout: algorithm
langs:
  - name: cpp
    code_path: cpp/segment_tree.cpp
    verify_by: muras
    verify_at: AOJ - Range Query - Range Minimum Query (RMQ)
    verify_url: http://judge.u-aizu.ac.jp/onlinejudge/review.jsp?rid=3780147#1
  - name: python
    code_path: python/segment_tree.py
    verify_by: nyama
    verify_at: AOJ - Range Query - Range Minimum Query (RMQ)
    verify_url: http://judge.u-aizu.ac.jp/onlinejudge/review.jsp?rid=3780056#1
---

# 解説

区間（セグメント）を接点とした二分木として構成され、区間に対する演算と値の更新を、共に O(log N) で解決することができる。
RMQ (Range Minimum Query) のような問題を解決するのに適したデータ構造。
実装コードは RMQ を解決する。

# 計算量

要素数を N として

update: log N
query: log N
