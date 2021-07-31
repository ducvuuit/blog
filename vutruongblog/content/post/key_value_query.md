---
title: "Key/Value/Query trong Attention là gì?"
date: 2021-07-31T14:34:37+07:00
---

Các thông số Key/Value/Query của Attention đến từ paper "Attention Is All You Need".\
Làm thế nào để hiểu chúng?
Key, Value, Query (K, V, Q) là khái niệm đến từ hệ thống truy xuất(retrieval system). Ví dụ, khi bạn nhập một truy vấn (Q) để tìm kiếm một số video trên Youtube, công cụ tìm kiếm sẽ map truy vấn (Q) của bạn với một bộ khóa (K) (tiêu đề video, mô tả, ...) liên kết với các video trong database, sau đó sẽ xuất ra các video phù hợp nhất (V). \
Cơ chế Attention cũng có thể được coi như một quá trình truy vấn. Vì vậy, các khái niệm key, query, value cũng được áp dụng ở đây
