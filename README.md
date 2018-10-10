# Jupyter Notebooks och dataset till KitsCon

## Jupyters TensorFlow-notebook
Det finns ett gäng docker images med dataanalys-verktyg som Jupyter tillhandahåller, beskrivna [här](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html). Jag har använt senaste versionen av jupyter/tensorflow-notebook. Rekommenderar det pga väldigt smidigt att komma igång!

## Verktyg - samtliga är open source
* [scikit-learn](http://scikit-learn.org/stable/): verktygslåda för data-analys och maskininlärning 
* [TensorFlow](https://www.tensorflow.org): bibliotek för effektiva beräkningar, innehåller verktyg för att underlätta maskininlärning, finns även implementationer i js och lite-variant till android och ios
* [Keras](https://keras.io/): användarvänligt sätt att bygga neruala nätverk i python, måste användas ihop med backend för själva beräkningarna (tex TensorFlow)
* [matplotlib](https://matplotlib.org/): plotting-bibliotek
* [pandas](https://pandas.pydata.org/): diverse datastrukturer och operationer på dessa som är användbara vid data-analys
* [NumPy](http://www.numpy.org/): mest för matriser och matrisoperationer, vilket behövs bla. för att få data i rätt format för modellen

## Dataset
Alla dataset är genererade med scripten i notebook/dataset_generation.

## Lite tips på resurser

### Youtube-klipp med pedagogiska förklaringar om vad maskininlärning är
Detta kanske är lite basic, men det kan vara bra ställen att börja på om man tycker det verkar komplicerat och läskigt!
* [A friendly introduction to machine learning](https://www.youtube.com/watch?v=IpGxLWOIZy4) - Luis Serrano, som verkar ha som mission att förklara komplexa saker på ett väldigt enkelt sätt. Hans kanal är full av klipp i samma anda, fast för olika koncept inom maskininlärning.
* [What is machine learning? (AI Adventures)](https://www.youtube.com/watch?v=HcqpanDadyQ) - Google
* [What is machine learning?](https://www.youtube.com/watch?v=f_uwKZIAeM0) - Oxford Sparks

### Lekplats från TensorFlow
[TensorFlow PLayground](https://playground.tensorflow.org) - lek med ett neuralt nätverk direkt i webbläsaren, peta på parametrar, ändra nätverks-arkitekturen, byt dataset osv och se hur det tränas. Mycket bra "live"-visualisering av träningen.

### Kaggle
Det finns väldigt mycket intressant på [Kaggle](https://www.kaggle.com/). Där finns gratis minikurser inom python, datavisualisering, maskininlärning, Google BiqQuery mm. Kurserna är viss del teori och viss del praktik genom notebooks. Finns också en massa maskininlärningstävlingar och färdiga problem man kan öva på om man inte har svårt att komma på vad man ska träna på eller använda sina kunskaper till. De har även en massa olika dataset. Det finns data med sportboll-saker, pokémon, utbildningsstatistik, avokadopriser, dialoger från Sagan om ringen osv...

### Dataset
Finns även dataset på dessa ställen:
* [UCI Machine learning repository](https://archive.ics.uci.edu/ml/datasets.html) - lätt att söka baserat på properties (hur datan ser ut, antalet features, ev antalet klasser, vilken typ av problem man kan applicera det på osv) 
* https://skymind.ai/wiki/open-datasets
* [KDnuggets](https://www.kdnuggets.com/datasets/index.html) - har lista med massa andra ställen man kan hitta öppna dataset på (Undrar om de ansträngt sig för att göra sidan extra ful...?)

### Kurser, tutorials och artiklar
* [EliteDataScience](https://elitedatascience.com/start-here) - how-to-guider, kodtutorials, artiklar som förklarar koncept, sida med andra verktyg och resurser 
* [Machine Learning Mastery](https://machinelearningmastery.com/) - Jason Brownlee, som har gjort några av kurserna på Kaggle, lär ut maskininlärning riktat till utvecklare (som tycker att matte är för törrt) och har skrivit nån e-bok man kan ladda ned gratis. Men det finns också massa artiklar och tutorials på sidan.
* [Stanfords maskininlärningskurs med Andrew Ng som lärare på Coursera](https://www.coursera.org/learn/machine-learning) - Jag har inte gått den själv, men gissar baserat på kursplanen att det ger en rätt bred kunskap på området, verkar som att han lär ut både matematik, kod, systemdesign och saker som är bra att tänka på. Den har fått väldigt bra betyg i alla fall.
* Ibland kan det ju råka vara så att ens matematik- och statistikkunskaper sviktar lite... , fear not, [Khan Academy](https://www.khanacademy.org/) finns där för oss i de svåraste stunder. :purple_heart:

### Andra verktyg för att bygga modeller
Har inte använt dem själv, men här är några i alla fall:
* [Eclipse Deeplearning4j](https://deeplearning4j.org/) - deep-learning-ramverk för JVM:en, kan importera modeller som definierats med Keras.
* [Caffe2](https://caffe2.ai/) - Facebooks deep-learning-ramverk, Python och C++
* [Microsoft Cognitive Toolkit](https://www.microsoft.com/en-us/cognitive-toolkit/) - deep-learning-ramverk, Python och C++
* [MXNet](https://mxnet.apache.org/) - Används av Amazon, supportar bla. Python, C++, JavaScript, Go och Scala
* [PyTorch](https://pytorch.org/) - Python
