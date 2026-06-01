# setup-app-practice

##概要
Coachtech 教材 Tutorial 9-2「Bladeテンプレートハンズオン」で作成した成果物です。
Laravel SailとDockerを使って商品一覧ページを作成しました。

##使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Sail(Docker Compose)
- MySQL, phpMyAdmin

##学んだこと
コントローラから適切なデータを渡し、ビューで表示する方法を学習した

##動作確認
1.作成したプロジェクトのダウンロード
git clone git@github.com:2n4p/9-2-5_hands-on.git


2.ディレクトリの移動
cd 9-2-5_hands-on


3.Docker Desktopの起動


4.Sailの起動
./vendor/bin/sail up -d


5.エイリアス設定（任意）
・Zshの場合
echo "alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'" >> ~/.zshrc

・Bashの場合
echo "alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'" >> ~/.bashrc

・シェルの再起動
exec $SHELL