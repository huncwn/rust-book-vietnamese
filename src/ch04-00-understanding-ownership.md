# Hiểu về Ownership

_Ownership_ là tính năng độc đáo nhất của Rust và có ý nghĩa sâu sắc đối với phần còn lại của ngôn ngữ.
Nó cho phép Rust thực hiện các đảm bảo an toàn bộ nhớ mà không cần trình thu gom rác, vì vậy điều quan trọng là phải hiểu cách thức hoạt động của _ownership_.
Trong chương này, chúng ta sẽ nói về _ownership_ cũng như một số tính năng liên quan: borrowing, slices và cách Rust sắp xếp dữ liệu trong bộ nhớ.
