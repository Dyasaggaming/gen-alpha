meme_dict = {
            "MEWING = teknik meniruskan pipi",
            "KAREN = seseorang yg dianggap suka mengeluh terutama di tempat umum",
            "SIGMA = pemimpin yg dominan,penyendiri,keren dan populer" 
            "SKIBIDI = sesuatu yg negatif,buruk atau jelek"
            }  

word = input("ketika kata yg kamu mengerti(gunakan huruf kapital semua!): ")

if word in meme_dict.keys():
    # Apa yang harus kita lakukan jika kata itu ditemukan?
    print(meme_dict[word])
else:
    # Apa yang harus kita lakukan jika kata itu tidak ditemukan?
    print('Kata yang kamu cari tidak ada')
