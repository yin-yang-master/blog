+++
title = "Bài 0: Giới thiệu tổng quan về DSA"
date = 2025-07-26T19:32:16+07:00
draft = false
tags = ["Cơ bản", "Đại cương"]
categories = ["Cấu trúc dữ liệu và giải thuật"]
+++

Cùng tìm hiểu về cấu trúc dữ liệu và giải thuật (DSA)

<!--more-->


Cấu trúc dữ liệu và giải thuật (Data Structures and Algorithms - DSA) là hai khái niệm cốt lõi trong lĩnh vực Khoa học Máy tính.

Chúng đóng vai trò nền tảng trong việc thiết kế, xây dựng và tối ưu các chương trình phần mềm hiệu quả, ổn định và có khả năng xử lý dữ liệu lớn.

## Cấu trúc dữ liệu là gì?

{{< admonition open=true >}}
Cấu trúc dữ liệu là cách tổ chức, lưu trữ và quản lý dữ liệu trong bộ nhớ máy tính để có thể truy cập và xử lý hiệu quả.
{{< /admonition >}}

Trước tiên, hãy xem xét một ví dụ không liên quan đến máy tính, chỉ để hiểu khái niệm.

Giờ hãy nhìn vào thời khóa biểu của bạn:
| Thứ      | Tiết 1 | Tiết 2 | Tiết 3 | Tiết 4 |
|----------|--------|--------|--------|--------|
| Thứ 2    | Toán   | Văn    | Lý     | Hóa    |
| Thứ 3    | Anh    | Sinh   | Toán   | Sử     |
| Thứ 4    | Văn    | Địa    | Hóa    | Thể dục|
| Thứ 5    | Toán   | Lý     | Anh    | Tin    |
| Thứ 6    | Sinh   | Văn    | Sử     | CN     |

Đây chính là một cấu trúc dạng bảng hai chiều (có thể gọi là ma trận hoặc mảng 2 chiều trong lập trình).

Mỗi dòng là một ngày trong tuần, mỗi cột là một tiết học. Dựa vào “tọa độ” hàng và cột, ta dễ dàng xác định được `tiết thứ 3 của thứ Ba là môn gì?`.

Tại sao lại cần một bảng như vậy? Giả sử bạn có danh sách tất cả các tiết học trong tuần ghi ngẫu nhiên như thế này:

```text
Thứ Hai - Tiết 1: Toán
Thứ Ba - Tiết 4: Sử
Thứ Tư - Tiết 2: Địa
...
```

Bạn sẽ rất mất thời gian để tra cứu và khó nhìn tổng quan. Nhưng khi đưa nó vào một bảng rõ ràng, bạn có thể:
 - Dễ dàng xem hôm nay học gì.
 - Biết ngay ngày nào có môn mình yêu thích.
 - Nhìn tổng thể và sắp xếp lịch học thêm, ôn tập.

→ Chính nhờ cách tổ chức hợp lý, thời khóa biểu giúp ta quản lý thông tin hiệu quả hơn rất nhiều.



Một số cấu trúc dữ liệu phổ biến bao gồm:
 - Mảng (Array)
 - Danh sách liên kết (Linked List)
 - Ngăn xếp (Stack)
- Hàng đợi (Queue)
- Cây (Tree)
- Đồ thị (Graph)
- Bảng băm (Hash Table)

Việc lựa chọn cấu trúc dữ liệu phù hợp tùy thuộc vào tính chất và yêu cầu cụ thể của từng bài toán.

## Giải thuật là gì?

Giải thuật (thuật toán) là tập hợp các bước xử lý logic để giải quyết một vấn đề cụ thể. Giải thuật tốt không chỉ đúng mà còn cần hiệu quả về thời gian và bộ nhớ.

Một số loại giải thuật thường gặp:

 - Tìm kiếm (Search): tuyến tính, nhị phân,...
 - Sắp xếp (Sort): nổi bọt, chọn, chèn, nhanh, trộn,...
 - Đệ quy (Recursion)
 - Quy hoạch động (Dynamic Programming)
 - Tham lam (Greedy)
 - Chia để trị (Divide and Conquer)
 - Duyệt đồ thị (BFS, DFS)

## Vai trò của cấu trúc dữ liệu và giải thuật trong lập trình


