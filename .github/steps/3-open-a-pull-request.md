<!--
  <<< Author notes: Step 3 >>>
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

## ステップ 3: プルリクエストを開く

_コミットお疲れ様でした！ :sparkles:_

プロジェクトに変更を加え、コミットを作成したので、プルリクエストを通じて提案された変更を共有する時が来ました。

**プルリクエストとは？**: コラボレーションは_[プルリクエスト](https://docs.github.com/ja/get-started/quickstart/github-glossary#pull-request)_で行われます。プルリクエストは、ブランチの変更を他の人に示し、他の人がブランチに対する追加の変更を受け入れたり、拒否したり、提案したりできるようにします。左右の比較では、このプルリクエストは、ブランチで行った変更を保持し、それらを`main`プロジェクトブランチに適用することを提案します。プルリクエストの詳細については、「[プルリクエストについて](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)」を参照してください。

### :keyboard: アクティビティ: プルリクエストを作成する

コミット後、ブランチへの最近のプッシュを示すメッセージと、**Compare & pull request**というボタンが表示されていることに気付いたかもしれません。

![screenshot of message and button](/images/compare-and-pull-request.png)

プルリクエストを自動的に作成するには、**Compare & pull request**をクリックし、以下のステップ6に進みます。ボタンをクリックしない場合は、以下の手順に従ってプルリクエストを手動で設定します。

1. リポジトリのヘッダーメニューにある**Pull requests**タブをクリックします。
2. **New pull request**をクリックします。
3. **base:**ドロップダウンで、**main**が選択されていることを確認します。
4. **compare:**ドロップダウンを選択し、`my-first-branch`をクリックします。

   ![screenshot showing both branch selections](/images/pull-request-branches.png)

5. **Create pull request**をクリックします。
6. プルリクエストのタイトルを入力します。デフォルトでは、タイトルは自動的にブランチの名前になります。この演習では、フィールドを編集して`Add my first file`と表示します。
7. 次のフィールドでは、行った変更の説明を入力できます。ここでは、これまでに達成したことの説明を追加できます。念のため、新しいブランチを作成し、ファイルを作成し、コミットしました。

   ![screenshot showing pull request](/images/Pull-request-description.png)

8. **Create pull request**をクリックします。新しいプルリクエストに自動的に移動します。
9. 約20秒待ってから、このページ（手順に従っているページ）を更新します。[GitHub Actions](https://docs.github.com/ja/actions)が自動的に次のステップに更新されます。

> [!NOTE]
> プルリクエストが開いているタブでGitHub Actionsが実行されている証拠が表示される場合があります。下の画像は、Actionの実行が終了した後、プルリクエストに表示される可能性のある行を示しています。
> 
> ![screenshot of an example of an actions line](/images/Actions-to-step-4.png)
