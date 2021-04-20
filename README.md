# ukiukikouryakusono1
fish1=["アカザ 5~7月 宮前橋 夕方 川虫 底"]
fish2=["アブラハヤ　全シーズン　大鏡の手前、真ん中　昼　川虫　かみつぶし極小、小"]

fishes=fish1+fish2
print(fish1)
print("対象魚")
index = 0
for fish in fishes:
    print(str(index) + '. ' + fish)
    index += 1
print('--------------------')
order = int(input("釣りたい魚を選択してください："))
selected_fish = fishes[order]

print("検索結果："+str(selected_fish))
