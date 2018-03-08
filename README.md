#1
x=int(input('finansmanGelir:'))
y=int(input('pazarGelir:'))
z=int(input('kiraGelir:'))
toplamGelir=x+y+z
print('geliriniz:',toplamGelir)
e=int(input('ucret:'))
f=int(input('finansmanGider:'))
g=int(input('pazarGider:'))
h=int(input('kiraGider:'))
j=int(input('muhasebeGider:'))
toplamGider=e+f+g+h+j
print('gideriniz:',toplamGider)
kar=toplamGelir-toplamGider
if kar>=1000:
    print('işletmeniz kar elde etmekte',kar)
elif kar<1000:
    print ('işletmeniz zarar etmekte',kar)
else:
    print('işletmeniz başabaş noktasında')
#2
x=int(input('Standart Çevrim Zamanı:'))
y=int(input('Standart Üretim Sayısı:'))
z=int(input('Planlanmış Üretim Sayisi:'))
e=int(input('Plansız Duruş:'))
performans=((x*y)/(z-e))
print('Performansınız:',performans)
a=int(input('Planlanmış Üretim Süresi:'))
kullanabilirlik=((a-e)/a)
print('Kullanabilirlik oranınız:',kullanabilirlik)
b=int(input('Sağlam Ürün Miktarı:'))
c=int(input('Toplam Üretim Miktarı:'))
kalite=(b/c)
print('Kalite oranınız:',kalite)
oee=(kullanabilirlik*kalite*performans*100)
if oee>=100:
    print('Ekipman Etkinlik Oranınız yüksek',oee)
else:
    print('Ekipman Etkinlik Oranınız düşük',oee)
#3
x=int(input('Satış Miktarı:'))
y=int(input('Birim Satış Fiyatı:'))
ciro=x*y
adambasi_ciro=ciro/25
print('Adambaşı Cironuz:',adambasi_ciro)
