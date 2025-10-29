# me
# 自己紹介ディクショナリー

```phython
myinfo={
    '名前':'岸波壮智',
    '学籍番号':'1254810223',
    '趣味':'一人で東京を迷走すること🗼',
    '出身地':'茨城の何もないとこから来た',
    '好きなアーティスト':'Mrs. GREEN APPLE🍏',
    '一言':'私へ、大学四年間頑張ってほしいです'}
print(myinfo)
```

from PIL import Image
import matplotlib.pyplot as plt

# 画像を読み込む（Pillow使用）
```phython

from PIL import Image

img = Image.open(r'c:\Users\asami\OneDrive\画像\カメラ ロール\image.webp')
img.show()
```
# matplotlibで表示
plt.imshow(img)
plt.axis('off')  # 座標軸を非表示
plt.show()

