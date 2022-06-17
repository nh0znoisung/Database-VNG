# MySQL

## Document

<https://en.wikipedia.org/wiki/MySQL>

<https://www.tutorialspoint.com/mysql/index.htm>

<http://www.mysqltutorial.org/basic-mysql-tutorial.aspx>

## 0. Storage Engine

Nắm được ưu/nhược điểm của các storage engine cơ bản của MySQL: InnoDB, MyISAM,...

<https://dev.mysql.com/doc/refman/8.0/en/storage-engines.html>

<https://viblo.asia/p/gioi-thieu-cac-storage-engine-trong-mysql-Eb85oEb8Z2G>

## 1. Installation

Tìm hiểu và sử dụng thành thạo:

- Cài đặt MySQL server sử dụng docker
- Tạo database và table
- Thao tác với MySQL: select, insert, update, delete, alter...

<http://www.ntu.edu.sg/home/ehchua/programming/sql/mysql_howto.html>

## 2. Data Types

Nắm được các kiểu dữ liệu cơ bản của MySQL.

Sử dụng đúng kiểu dữ liệu để đạt hiệu quả tốt nhất.

<https://dev.mysql.com/doc/refman/5.7/en/data-types.html>

Tìm hiểu các dữ liệu đặc biệt và cách xử lý:

- utf8mb4
  - <https://dev.mysql.com/doc/refman/5.5/en/charset-unicode-utf8mb4.html>
  - <https://mathiasbynens.be/notes/mysql-utf8mb4>

## 3. Transaction

Tìm hiểu transaction của MySQL:

- Tại sao phải sử dụng transaction
- Cách sử dụng transaction
- Xử lý khi gặp lỗi trong transaction

<https://dev.mysql.com/doc/refman/8.0/en/sql-syntax-transactions.html>

Nắm được khái niệm giao dịch trong hệ thống phân tán:

<https://en.wikipedia.org/wiki/Distributed_transaction>

## 4. Isolation

Nắm được isolation level cơ bản

<https://en.wikipedia.org/wiki/Isolation_(database_systems>)

Xác định isolation level của MySQL để xử lý đồng thời (concurrency)

<https://dev.mysql.com/doc/refman/8.0/en/innodb-transaction-isolation-levels.html>

## 5. Indexes

Nắm được indexes cơ bản

- Cách dùng index
- Các loại index
- Cấu trúc và cơ chế hoạt động của index

<https://dev.mysql.com/doc/refman/8.0/en/mysql-indexes.html>

<https://github.com/pingcap/tidb-academy-labs/blob/master/3-query-optimization.md>

### 6. Connector

Nắm được một số cách kết nối với MySQL: jdbc, golang driver

<https://www.mysql.com/products/connector/>

### 7. Assignment

Sử dụng drivers (tuỳ ngôn ngữ) và database `mysqlsampledatabase`, để thực hành và ghi chép kiến thức, kinh nghiệm, vấn đề, . . . thành tài liệu theo các yêu cầu sau:

Transaction

- Đưa ra ít nhất 3 trường hợp cần transaction và implement.

Isolation

- Đưa ra các trường hợp ví dụ nếu có cho mỗi isolation khác nhau.

Indexes

- Đưa ra ít nhất 3 câu query và thiết kế index.
