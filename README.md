
# RuhsatPro – IFC Model Kontrol ve Onay Platformu

## Açıklama


## İçindekiler
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)
- [İletişim](#iletişim)

## Kurulum
#sample.ifc dosyası
Bu dosyada

TR_Category Mapping File.txt

Bu dosya 

TR_CustomParameterMappingSets.txt

Bu dosya içinde aşağıdaki adrese değiştirmelisiniz


Dosya temel olarak aşağıdaki parametreleri güncellemektir.
PropertySet:	Qto_Area	I	IfcSpace
	Area	Area	Area

PropertySet:	Pset_BagimsizBolum	I	IfcSpace
	BagimsizBolumNo	Text	ECB_BagimsizBolumNo	
	BlokNo	Text	ECB_BlokNo
	ArsaPayi	Text	ECB_ArsaPayi
	Cinsi	Text	ECB_Cinsi
	
PropertySet:	Pset_EmsalAlanTipi	I	IfcSpace
	EmsalAlanTipi	Text	ECB_EmsalAlanTipi	
				
PropertySet:	Pset_NetAlanTipi	I	IfcSpace
	Eklenti/Degil	Boolean	ECB_Eklenti/Degil

PropertySet:	Pset_ArsaBilgileri	T	IfcSite
	ArsaAlani	Text	ECB_ArsaAlani
	KAKS	Text	ECB_KAKS	
	TAKS	Text	ECB_TAKS