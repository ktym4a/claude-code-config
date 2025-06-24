コミット前に必要なチェック（lint、typecheck、テスト）を実行してからコミットを作成してください。

## 実行手順:
1. 現在の変更内容を確認 (git status, git diff)
2. プロジェクトのチェックコマンドを実行
   - lint チェック (npm run lint, ruff, など)
   - 型チェック (npm run typecheck, mypy, など)
   - テスト実行 (npm test, pytest, など)
3. すべてのチェックが通った場合のみコミットを作成
4. 適切なコミットメッセージを作成（英語、Conventional Commits形式）

## 注意事項:
- チェックコマンドが不明な場合は、package.json、Makefile、またはCLAUDE.mdを確認
- エラーがある場合は修正してから再度チェックを実行
- コミットメッセージは変更内容を明確に説明すること