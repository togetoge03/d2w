# Bug Reporter for BK — プライバシーポリシー / Privacy Policy

---

## 日本語

最終更新日：2026年5月20日

### 1. はじめに

Bug Reporter for BK（以下「本拡張機能」）は、BacklogへのバグレポートをChromeブラウザのサイドパネルから行うためのChrome拡張機能です。本ポリシーでは、本拡張機能が収集・利用する情報について説明します。

### 2. 収集する情報

#### ローカルに保存する情報（お使いのブラウザ内のみ）

- BacklogスペースURL
- Backlog APIキー
- 選択中のプロジェクト設定
- ピン留めしたプロジェクト情報
- ピン留めした課題情報

#### 一時的に処理する情報（送信・保存は行いません）

- 閲覧中のページのスクリーンショット画像
- ページURL・ブラウザ情報（OS、ブラウザ名・バージョン等）
- Backlogの課題詳細ページのコメント欄に含まれるユーザーID（`@メンション` 挿入機能での抽出に使用。ページ内のDOMのみを参照し、外部への送信は行いません）

#### ユーザー操作によりローカルに保存される情報

- ダウンロードボタンを押した場合、スクリーンショット画像がお使いのデバイスに保存されます。この操作はユーザーの明示的な操作によってのみ行われます。

### 3. 情報の利用目的

- Backlog APIへのバグ起票・コメント追加（入力内容・スクリーンショットをBacklogサーバーへ送信）
- 設定情報の保存と復元

### 4. 第三者への情報提供

本拡張機能は、ユーザーが明示的に送信操作を行った場合のみ、入力内容およびスクリーンショットを**ユーザー自身が設定したBacklogスペース**へ送信します。それ以外の第三者（広告事業者・分析サービス等）への情報提供は一切行いません。

### 5. 外部サーバーとの通信

本拡張機能が通信する外部サーバーは、ユーザー自身が設定したBacklogスペース（例：`yourspace.backlog.com`、`yourspace.backlog.jp`）のみです。開発者のサーバーへのデータ送信は行いません。

### 6. データの保管

設定情報はChromeの`storage.local`に保存されており、お使いのデバイス上にのみ存在します。拡張機能をアンインストールすることで、すべてのデータが削除されます。

### 7. お問い合わせ

開発者：togetoge
連絡先：<mensisinfinitum@gmail.com>

---

## English

Last updated: May 20, 2026

### 1. Overview

Bug Reporter for BK (the "Extension") is a Chrome extension that allows users to file bug reports to Backlog directly from the browser side panel. This policy explains what information the Extension handles and how it is used.

### 2. Information Collected

#### Stored locally (on your device only)

- Backlog space URL
- Backlog API key
- Selected project settings
- Pinned project data
- Pinned issue data

#### Processed temporarily (never transmitted or stored externally)

- Screenshots of the active browser tab
- Page URL and browser environment details (OS, browser name and version, etc.)
- User IDs found in comment threads on Backlog issue pages (used locally to generate @mention text; only the page DOM is read, nothing is transmitted externally)

#### Saved locally by user action

- When the user clicks the download button, a screenshot image is saved to their local device. This only occurs as a result of an explicit user action.

### 3. How Information Is Used

- Submitting bug reports and comments to the Backlog API (user-entered content and screenshots are sent to the configured Backlog space)
- Saving and restoring user settings

### 4. Sharing with Third Parties

The Extension only transmits data to the **Backlog space configured by the user**, and only when the user explicitly clicks the submit button. No data is shared with any third party, including advertisers or analytics services.

### 5. External Communication

The only external server the Extension communicates with is the Backlog space specified by the user (e.g., `yourspace.backlog.com`, `yourspace.backlog.jp`). No data is sent to the developer's servers.

### 6. Data Storage

Settings are stored in Chrome's `storage.local` and exist only on your local device. Uninstalling the Extension removes all stored data.

### 7. Contact

Developer: togetoge
Email: <mensisinfinitum@gmail.com>
