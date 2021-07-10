# notebooks_classifiers


</h2>

kody źródłowe do pobrania w zależności od rodzajów klasyfikatorów<br>
Modele **czteroklasowe** 
- <b>STD</b> dla etc,bagsvc,gbc,rf,vot
<br> dodano: mlp,nsv,svm,knn<br>
<br> dodano: ovo_mlp, ovo_svm, ovr_mlp<br>

Modele **dwuklasowe** (0,1):
- <b>CNN</b> dla 
<br>CNN_small_w0,CNN_small_w2,CNN_small_w20,CNN_small_raw,
<br>CNN_big_w0,CNN_big_w2,CNN_big_w20,CNN_big_raw,
<br>   CNN_small_w0_2, CNN_big_w0_2
- <b>base</b> dla baseline, baseline_knn, baseline_rf

  ### UWAGA!! Modele :CNN_small_w2_10,CNN_big_w2_10,CNN_big_w2_20,CNN_big_w2_20 wymagają zbyt dużo RAM, należy plik z obrazami podzielić na częsci


<br>
wyniki klasyfikacji zapisywane są do pliku w formacie:
<tt>nazwaKlasyfikatora_nazwaKatalogu.csv</tt>

<br><br>

<b><tt> cnn_multiclass_classifier.zip</tt> </b> : model głęboki uwzględniający niepewność
<br>[artykuł naukowy](https://www.mdpi.com/1424-8220/21/6/1963) 
