# programlama
programlama ödevleri
soru1
def gelir(x,y,z):
    gelir=(x+y+z)
    return gelir
x=int(input("Finansman gelirini giriniz:"))
y=int(input("Pazar gelirini giriniz:"))
z=int(input("Kira gelirini giriniz:"))
k=gelir(x,y,z)
print("geliriniz:",k)
def gider(a,s,d,f,g):
    gider=(a+s+d+f+g)
    return gider
a=int(input("Ücreti giriniz:"))
s=int(input("Finansman giderini giriniz:"))
d=int(input("Pazar giderini giriniz:"))
f=int(input("Kira giderini giriniz:"))
g=int(input("Muhasebe giderini giriniz:"))
r=gider(a,s,d,f,g)
print("gideriniz:",r)
def kar(k,r):
    kar=(k-r)
    return kar
q=kar(k,r)
print("karınız:",q)
if (k-r)==1000:
    print("kar veya zarar yok")
elif (k-r)>1000:
    print("kardasınız")
else: 
    print("zarardasınız")


soru2
def kullanilabilirlik(x,y):
    kullanilabilirlik=(x-y)%x
    return kullanilabilirlik
x=int(input("planlanmış üretim süresini giriniz"))
y=int(input("Plansız duruşu giriniz"))
k=kullanilabilirlik(x,y)
print("Kullanılabilirliğiniz:",k)
def performans(z,a,x,y):
    performans=(z*a)%(x-y)
    return performans
z=int(input("standar çevrim zamanını giriniz"))
a=int(input("üretim miktarını giriniz"))
f=performans(z,a,x,y)
print("performansınız:",f)
def kalite(q,w):
    kalite=(q%w)
    return kalite
q=int(input("Sağlam ürün miktarını giriniz"))
w=int(input("Toplam üretim miktarını giriniz"))
r=kalite(q,w)
print("kaliteniz:",r)
def oee(k,f,r):
    oee=(k*f*r)
    return oee
oee=(k,f,r)
print("oee niz:",oee)

soru3
def ciro(x,y):
    ciro=(x*y)
    return ciro
x=int(input("Satış miktarını giriniz:"))
y=int(input("Birim satış miktarını giriniz:"))
c=ciro(x,y)
print("cironuz:",c)
def adambasiCiro(c,z):
    adambasiCiro=(c%z)
    return adambasiCiro
z=int(input("Çalışan sayınızı giriniz:"))
a=adambasiCiro(c,z)
print("Adam başı cironuz:",a)
