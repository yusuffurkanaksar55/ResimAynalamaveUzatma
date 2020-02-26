import cv2
import numpy as np

resim=cv2.imread("HappyFish.jpg")
cv2.imshow("Balık",resim)

#yuz=resim[0:200,0:100]#ÇIKTISI---> 200 BOYDAN 100 ENDEN KESER FOTOGRAFTA
#cv2.imshow("Kesim",yuz)
#print(resim.shape)#194 yüksekligi, 259 eni,3 farklı renkten(bgr)Çıktısı--> (195,250,3)

#RESMİ UZATMA
uzatılan_resim=cv2.copyMakeBorder(resim,100,100,100,100,cv2.BORDER_REPLICATE)

#RESİM AYNALAMA
ayna_resim=cv2.copyMakeBorder(resim,100,100,100,100,cv2.BORDER_REFLECT)

#RESİM TEKRAR ETME
tekrar_resim=cv2.copyMakeBorder(resim,100,100,100,100,cv2.BORDER_WRAP)

#RESMİ ETRAFINA SARMA
saran_resim=cv2.copyMakeBorder(resim,10,30,50,10,cv2.BORDER_CONSTANT)

cv2.imshow("Uzama",uzatılan_resim)
cv2.imshow("Tekrar",tekrar_resim)
cv2.imshow("Aynalama",ayna_resim)
cv2.imshow("Sarma",saran_resim)




cv2.waitKey(0)
cv2.destroyAllWindows()
