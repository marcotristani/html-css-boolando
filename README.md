# STRUTTURA PAGINA

## header navigation bar position fixed     /*display flex con justify-contente: space-beetwen*/
categorie          /*ul lista con 3 categorie ancora*/
  -donna
  -uomo
  -bambini
logo boolean        /*img logo*/
icone               /*ul lista con 3 icone ancora*/
  -profilo
  -cuore
  -shop

## main

immagine1+descrizione block   /*3 immagini che occupano il width main distanziati tra di loro con il gap*/
  {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
   -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
   -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   }
   [immagine:hover .seconda-immagine-prodotto]
  gap
immagine2+descrizione block
   {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
    -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
    -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   }
   [immagine:hover .seconda-immagine-prodotto]
  gap
immagine3+descrizione block
   {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
    -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
    -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   }
   [immagine:hover .seconda-immagine-prodotto]
  wrap
immagine4+descrizione block  /*3 immagini che occupano il widht main distanziati con il gap tra di loro*/
   {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
    -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
    -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   } 
   [immagine:hover .seconda-immagine-prodotto] 
  gap
immagine5+descrizione block
   {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
    -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
    -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   }
   [immagine:hover .seconda-immagine-prodotto]
  gap
immagine6+descrizione block
   {-sconto                    /*posizione assoluta rispetto a immagine prodotto relativa*/
    -sostenibilità             /* posizione assoluta rispetto a icona sconto relativa*/
    -preferito                 /* posizione assoluta rispetto a immagine relativa*/
   }
   [immagine:hover .seconda-immagine-prodotto]
  wrap

# Footer end-bar         /*display flex con 2 blocchi in justify-content:space-between background black*/
{                              /*primo blocco*/
Nome azienda
lista                           /*lista ul*/
  -informazioni legali
  -informativa sulla privacy
  -diritto di recesso
}
{                              /*secondo blocco*/
Trovaci anche su
lista                         /*lista ul*/
   -icona twitter
   -icona facebook
   -icona instagram
   -icona youtube
   -icona social
}