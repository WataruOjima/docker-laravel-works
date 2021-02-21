# docker-laravel-works

# テーブル設計

## users テーブル

| Column           | Type      | Options        |
| ---------------- | -------   | -----------    |
| id               | integer   | auto_increment |
| name             | VARCHAR   |                |
| email            | VARCHAR   |                |
| password         | VARCHAR   |                |
| created_at       | TIMESTAMP |                |
| updated_at       | TIMESTAMP |                |

## posts テーブル
| Column           | Type      | Options        |
| ---------------- | -------   | -----------    |
| id               | integer   | auto_increment |
| user_id          | integer   |                |
| text             | VARCHAR   |                |
| created_at       | TIMESTAMP |                |
| updated_at       | TIMESTAMP |                |