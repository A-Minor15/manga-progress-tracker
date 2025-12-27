# Manga Progress Tracker

漫画作品ごとの読了巻数・進捗を管理するWebアプリケーションです。

## 概要
- フロントエンド: React + TypeScript
- バックエンド: C++ (REST API)
- DB: SQLite
- 環境: Docker / Docker Compose

本アプリケーションは、C++によるWeb API実装と
フロントエンド分離構成の理解を目的として作成しています。

## 機能
- 漫画作品の登録・編集・削除
- 読了巻数・所持巻数の管理
- 読書進捗の可視化

## 技術構成
| Layer | Technology |
|------|------------|
| Frontend | React, TypeScript |
| Backend | C++, cpp-httplib |
| Database | SQLite |
| Infrastructure | Docker, Docker Compose |

## 起動方法
```bash
docker-compose up --build
