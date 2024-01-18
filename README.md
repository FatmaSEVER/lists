# lists

liste = ['bmw', 'mercedes', 'opel', 'mazda']

print(len(liste))

print(liste[0])
print(liste[3])

#mazda'yı toyota ile değiştir.

liste = [liste[0], liste[1] , liste[2] , 'toyota']

#ya da

liste[-1] = 'toyota'

#listenin içinde 'mercedes' var mı?

result = 'mercedes' in liste
print(result)

print(liste[-2])

print(liste[0:3])

liste[-2:]=['toyota','renault']
print(liste)

liste = liste + ['audi','nissan']
print(liste)

del liste[-1]
print(liste)

liste = liste[::-1]


liste= [12,16,12,20,18]
liste.pop(-1)      # son elemanı sil.
liste.remove(12) # 12 elemanını sil. 
print(liste.count(12)) #liste içerisinde kaç adet 12 var?
