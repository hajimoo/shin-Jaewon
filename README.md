こんにちは、シン・ジェウォンです。  
信頼性の高いバックエンドシステムの構築と、構造的な問題の解決に関心を持つエンジニアです。

単にモデルの精度を追求するのではなく、「実際のシステムとして信頼できるか」という観点で設計・実装することを重視しています。

---

## メインプロジェクト

### 製造業における欠陥検出システム（Recall優先評価）

深刻なクラス不均衡下において、欠陥の見逃し（False Negative）を最小化することを目的としたCNNベースの画像分類システムを開発しました。

製造現場では、欠陥品の見逃しは重大なリスクとなるため、本プロジェクトではAccuracyではなくRecallを優先した評価戦略を採用しました。

---

### システム構成

React Frontend（UI）
↓
FastAPI Backend（推論API）
↓
CNN Model（TensorFlow）
↓
MySQL（ログ保存）

---

### 主な取り組み

- クラス不均衡データの分析
- Recall重視の評価指標設計
- Confusion Matrix / ROCによる検証
- CNNモデルの学習および評価
- FastAPIによる推論APIの実装
- Reactによるフロントエンド開発
- 推論結果のデータベース保存（MySQL）

---

### プロジェクトリポジトリ

- CNN Model:  
  https://github.com/hajimoo/cnn-manufacturing-defect  

- Backend API:  
  https://github.com/hajimoo/defect-detection-api  

- Frontend:  
  https://github.com/hajimoo/defect-detection-frontend  

---

## 現在の取り組み

- バックエンド設計（API設計・責務分離）
- システム信頼性向上のためのロギング設計
- MLモデルの実運用を前提としたAPI化
- フロントエンドとバックエンドの統合

---

## 技術スタック

Python / FastAPI / TensorFlow / NumPy / Pandas  
React / Tailwind CSS  
MySQL / Git
