# pygame_samples (sionmad)

 ### - demo_01.py: pygameの超簡単なデモ。
 ### - demo_02.py: 7セグのシミュレーション、各セグメントを2ブロックで構成。Seven_segクラス使用。
 ### - demo_LCD_font_01.py: 5x7のLCDフォント制作用。LCD_fontクラス使用。
 ### - demo_LCD_font.py: 5x7のLCDフォント、完成版。

 ### - demo_freetype.py: pygame.freetypeでテキスト表示。（新しい方式）
 ### - demo_freetype.py: pygame.fontでテキスト表示。（古い方式）
 ### - demo_openmoji.py: オープンソースの絵文字、openmojiのデモ。キー操作のデモ。
 ### - seven_seg_pg.py: Seven_segクラス
 ### - lcd_font_pg.py: LCD_fontクラス
 

https://github.com/user-attachments/assets/e8f8d758-f412-490b-9c19-6f0d6c4b1850


 :trollface:





## demo01_.py 

#### ウインドウタイトル

pygame.display.set_caption("pygame demo - window title here")

( )の中を変えることによって、ウィンドウタイトルを変更することができる。

例
変更前
![alt text](<スクリーンショット 2025-05-03 113151.png>)
変更後
![alt text](<スクリーンショット 2025-05-03 113359.png>)

#### 色
screen.fill((238, 238, 170))  # back ground color

こちらも( )の中身を変えると背景色が変わる。
なお、中の数字はRGBカラーコードになっている。

変更前
![alt text](<スクリーンショット 2025-05-03 113359.png>)　

変更後（色がダサいがそこは気にしない）
![alt text](<スクリーンショット 2025-05-03 114156.png>)

pygame.draw.circle(screen, (176, 176, 222), (320, 240), 120)
    pygame.draw.circle(screen, (222, 176, 222), (120, 120), 20)
    pygame.draw.circle(screen, (222, 176, 222), (120, 120), 20)
    pygame.draw.rect(screen, (120, 120, 120), Rect(120, 120, 200, 120))

    これらもscreen,の隣にある( )の中身を変えると色が変化する。
    