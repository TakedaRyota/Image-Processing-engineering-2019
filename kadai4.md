# 課題４レポート

ORG=imread('Airplane.jpg'); % 原画像の入力
ORG=rgb2gray(ORG); % カラー画像を白黒濃淡画像へ変換
imagesc(ORG); colormap(gray); colorbar;

課題３などと同様に原画像を入力し，白黒濃淡画像に変換して表示した結果を図１に示す。

![原画像](https://github.com/TakedaRyota/Image-Processing-engineering-2019/blob/master/image/kadai4_1.png)

図１　白黒濃淡原画像

imhist(ORG); % ヒストグラムの表示

によってヒストグラムの表示をするために，
Image Processing Toolbox バージョン11.0
をインストールし，実行させた結果を図２に示す。

![原画像](https://github.com/TakedaRyota/Image-Processing-engineering-2019/blob/master/image/kadai4_2.png)

図２　ヒストグラム

ヒストグラムからこの画像は濃度値が４０〜６０と１８０〜２２０あたりが多く含まれていることがわかる。
