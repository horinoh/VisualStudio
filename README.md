# VisualStudio

## インストール
- ワークロード
    - C++によるデスクトップ開発
    - C++によるゲーム開発
        - Unreal Engineのインストーラ

- 言語パック
    - 日本語のチェックを外して、英語にチェック

## 後から英語版にする場合
- インストーラを起動 - 変更 - 言語パックタブ - 英語にチェック - 変更
- VSを起動 - ツール - オプション - 環境 - 国際対応の設定 - English - OK - VSを再起動

## 検索対象に拡張子(inl)を追加する
- Tool - Options - Text Editor - File Extension - Editor で Microsoft Visual C++ を選択 - Extension に(inlを)記述 - Add

## Visual Assist X

## UE4
- インストール時に Unreal Engine のインストーラを選択しておく
- セットアップ https://docs.unrealengine.com/en-US/Programming/Development/VisualStudioSetup
    - UnrealVS
        - Engine\Extras\UnrealVS\VS2017\UnrealVS.vsix
        - 2019 はまだ無いみたい
    - UE4Visualizer
        - Engine\Extras\VisualStudioDebugging\UE4.natvis