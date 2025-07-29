<!--
  <<< Author notes: Step 3 >>>
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

## ステップ 3: プルリクエストを開く

コミットの作成、お疲れさまでした！ :sparkles:

プロジェクトに変更を加えてコミットを作成したので、今度はプルリクエストを通じて提案した変更を共有しましょう！

**プルリクエストとは？** : コラボレーションは_[プルリクエスト](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_で行われます。プルリクエストは、あなたのブランチでの変更を他の人に表示し、人々があなたのブランチを受け入れ、拒否、または追加の変更を提案できるようにします。並行比較では、このプルリクエストはあなたがブランチで行った変更を保持し、それらを`main`プロジェクトブランチに適用することを提案します。プルリクエストの詳細については、「[プルリクエストについて](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)」を参照してください。

### :keyboard: アクティビティ: プルリクエストを作成する

コミット後に、ブランチへの最近のプッシュを示すメッセージが表示され、**Compare & pull request**と書かれたボタンが提供されることに気づいたかもしれません。

![screenshot of message and button](/images/compare-and-pull-request.png)

プルリクエストを自動的に作成するには、 **Compare & pull request** をクリックして、下記のステップ6にスキップしてください。ボタンをクリックしない場合は、以下の手順でプルリクエストを手動で設定してください。

1. リポジトリのヘッダーメニューの **Pull requests** タブをクリックします。
2. **New pull request** をクリックします。
3. **base:** ドロップダウンで、 **main** が選択されていることを確認します。
4. **compare:** ドロップダウンを選択し、`my-first-branch`をクリックします。

   ![screenshot showing both branch selections](/images/pull-request-branches.png)

5. **Create pull request** をクリックします。
6. プルリクエストのタイトルを入力します。デフォルトでは、タイトルは自動的にブランチの名前になります。この演習では、フィールドを編集して`Add my first file`と入力しましょう。
7. 次のフィールドは、行った変更の説明を提供するのに役立ちます。ここでは、これまでに達成したことの説明を追加できます。思い出してください、あなたは：新しいブランチを作成し、ファイルを作成し、コミットを行いました。

   ![screenshot showing pull request](/images/Pull-request-description.png)

8. **Create pull request** をクリックします。新しいプルリクエストに自動的に移動します。
9. 約20秒待ってから、このページ（手順を読んでいるページ）を更新してください。[GitHub Actions](https://docs.github.com/en/actions)が自動的に次のステップに更新されます。

> [!NOTE]
> プルリクエストが開かれたタブでGitHub Actionsが実行されている証拠が見えるかもしれません！下の画像は、アクションの実行が完了した後にプルリクエストで見られる可能性のある行を示しています。
> 
> ![screenshot of an example of an actions line](/images/Actions-to-step-4.png)
