---
title: vtuber-clip プライバシーポリシー
---

# vtuber-clip プライバシーポリシー

最終更新日：2026年11月9日

vtuber-clip（以下「本アプリ」）は、運営者（sinoakix）が個人で使うためのツールです。運営者が管理する YouTube チャンネルに、運営者自身が作った切り抜き動画を非公開で登録するために使います。一般の利用者向けには提供していません。

## 1. 本アプリが利用する Google のデータ

本アプリは、YouTube API サービスを通じて、次の権限を使います。

| 権限 | 使う目的 |
|---|---|
| `https://www.googleapis.com/auth/youtube.upload` | 運営者のチャンネルに、動画を非公開で登録するため |
| `https://www.googleapis.com/auth/youtube.readonly` | 登録の前に、登録先が運営者のチャンネルで合っているか（チャンネルID）を確かめるため |

このほか、API キーを使って、YouTube で公開されている動画の情報（タイトル、公開日時、長さ、再生数などの公開された統計）を取得します。この情報は、新しく公開された動画を運営者に知らせ、運営者が切り抜く動画を選ぶためだけに使います。

## 2. 利用の目的

取得した情報は、上の目的にだけ使います。広告、分析、利用者の追跡、機械学習には使いません。

## 3. 保存と削除

- OAuth の認証情報（トークン）は、運営者のパソコンの中にだけ保存し、外部のサーバーには保存しません
- YouTube API から取得したデータは、30日を超えて保存しません。期限を過ぎたものは自動で削除します
- 運営者以外の人のアカウントに許可をもらって情報を取ることはありません。API キーで取得するのは、ログインしなくても見られる公開情報だけです

## 4. 第三者への提供

取得した情報を、第三者に販売・提供することはありません。

本アプリによる Google API から受け取った情報の利用と移転は、[Google API サービスのユーザーデータに関するポリシー](https://developers.google.com/terms/api-services-user-data-policy)（限定的な使用の要件を含む）に従います。

## 5. YouTube の利用規約と Google のプライバシーポリシー

本アプリは YouTube API サービスを利用しています。本アプリを使うことは、[YouTube 利用規約](https://www.youtube.com/t/terms) に同意することを意味します。Google によるデータの取り扱いについては、[Google プライバシーポリシー](https://policies.google.com/privacy) をご覧ください。

## 6. アクセス権の取り消し

本アプリに与えた権限は、[Google アカウントのセキュリティ設定（サードパーティのアクセス）](https://myaccount.google.com/connections) からいつでも取り消せます。

## 7. 改定

このポリシーを変更する場合は、このページを更新し、最終更新日を改めます。

## 8. お問い合わせ

このポリシーについてのお問い合わせは、[GitHub の Issues](https://github.com/sinoakix/vtuber-clip-privacy/issues) からお願いします。

---

# vtuber-clip Privacy Policy (English)

Last updated: November 9, 2026

vtuber-clip ("the App") is a personal tool used only by its operator (sinoakix) to upload the operator's own clip videos, as private videos, to the YouTube channel managed by the operator. It is not offered to the public.

- **Scopes used**: `youtube.upload` (to upload videos as private to the operator's channel) and `youtube.readonly` (to confirm the destination channel ID before uploading). An API key is also used to read publicly available video information, only to notify the operator of newly published videos and help the operator choose videos to clip.
- **Purpose**: Data is used only for the purposes above, and never for advertising, analytics, tracking, or machine learning.
- **Storage**: OAuth tokens are stored only on the operator's computer. Data obtained from YouTube API Services is not stored for more than 30 days and is deleted automatically after that period. The App never accesses other people's accounts; the API key is used only for information that is publicly visible without signing in.
- **Sharing**: No data is sold or shared with third parties. The App's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
- **YouTube Terms and Google Privacy Policy**: By using the App, you agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms). See the [Google Privacy Policy](https://policies.google.com/privacy).
- **Revoking access**: You can revoke the App's access at any time from [your Google Account's third-party connections page](https://myaccount.google.com/connections).
- **Contact**: [GitHub Issues](https://github.com/sinoakix/vtuber-clip-privacy/issues)
