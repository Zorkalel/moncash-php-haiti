# moncash-php-haiti
Nan repo sa mwen eksplike andetay koman ou ka entegre API MONCASH la pouw reyalize peyman an liy ki trè fasil e mwen ka rasirew
ke lew fin li README sa wap ka entegrel, san pale anpil ann komanse

1. Enstale COMPOSER e Telechaje MONCASH-PHP, siw te deja fèl alo ann kontinye malgre sa
----------------------------------------------------------------

Google COMPOSER pou plis enfo sou sal ye ak lot bagay men nan pou nou lap pèmet nou byen jere entegrasyon API aaa ke se swa nan 
rele AUTOloader a oubyen Load repo Moncash-git la, pa enkyetew siw debitan oupa konprann tout men byento wap abitye e wap konprann
yo si Google se bon zanmiw.

Nan lyen sa [TELECHAJEM](https://getcomposer.org/download/) wap jwenn posibilite pouw telechaje e enstale COMPOSER kit se Windows/Linux e li trè
fasil a enstale tankou pou **WINDOWS** wap jis enstale yon pwogram epi `NEXT NEXT INSTALL` aprèsa tout bagay fini e pou **LINUX** menm se jis 
`COPY PASTE MV` epi li fini alor mwen konseyew ale gade pouw ka wè, Ann kontinye ....


2. Kreye yon Pwojè ( folder ou directory )
----------------------------------------------------------------

Yon pwojè se langaj Git men ou ka konprann li tankou se yon **folder/directory** kote ki gen sitWEB wap devlope aaa, alor sawap fè se kreye yonnn siw pat genyen men siw te genyen alor kontinye swiv nou pouw ka swiv kijan ou pral rele pwojè moncash poul vini nan pwojè ou a.

Men konya sak rete se poun telechaje trokèt tout api-moncash laaa ki se template la e nap ka telechajel si nou ale direk sou lyen sa [TELECHAJEM](https://github.com/ecelestin/ecelestin-Moncashsdk-php.git) oubyen tou nou ouvri yon TERMINAL/LigneDeCommande epi nou ekri sa a `git clone https://github.com/ecelestin/ecelestin-Moncashsdk-php.git` epi se konsa wap jis rete chay la ki se **vendor** la pouw telechaje


3. Kreye yon fichye `composer.json`
------------------------------------------------------------------
Nan fichye sa a se li ki pral edew pouw clone vèsyon korèk api-moncash la, donk wap jis bezwen kreye yon fichye ki rele
`composer.json` ladanl ke wap pral bezwen mete kod sa a ki pi ba

```
{
	"repositories": [{
		"type": "vcs",
		"url": "https://github.com/ecelestin/ecelestin-Moncash-sdk-php.git"
	}],
	"require": {
		"DGCGroup/MonCash-PHP-SDK": "dev-master"
	}
}
```
Ebyen mezanmi pran san nou pou nou byen kopye/kole kod sa a paske li vrèman esansyèl pou ou ka lanse telechajeman api-moncash la
e map ba nou lyen sa a [PARSE ERROR LINE 1 STRING](https://jsonlint.com/), ebyen lyen sa a se si tout fwa ta gen erè sentaks alors nap jis pran kod sa a epi kopye/kole nan platfom sa a epi lap ranje bon sentaks la pou nou oswa ale nan folder COMPOSER sou kont git mwen an epi nap jwenn fichye mwen itilize aa nap ka telechajel pou evite erè.

4. Ann Fini ak yon **UPDATE**-----------------------------------------
-----------------------------------
Bon nan denye etap sa nou pral jis bezwen fè yon kopi/kole nan yon TERMINAL/ligneDeCommande liy sa `composer update` epi lap pran kelke minit poul rele api-moncash la e aprè yon 2-5 minit li ta dwe fini si entenet nou miyo li dwe bon.

epi konyea poum rasirew ke telechajeman ou korek jis gade nan pwojè ou epi gade siw jwenn folder/directory sa yo :

..* 






