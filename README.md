# Machine-Learning-Naive-Bayes
Iris veri setini kullanarak Naive Bayes sınıflandırma algoritması ile tahminler ve performans ölçümü yapacağız.

## Kütüphaneleri İçe Aktarma ve Verileri Yükleme
İlk olarak, pandas, numpy ve matplotlib.pyplot kütüphaneleri import edilir. Ardından, Iris veri seti pandas'ın read_csv methodu ile import edilir.

## Verilerin Eğitilmesi ve Test Setlerine Ayırma
Veri seti bağımsız değişkenler (X) ve bağımlı değişken (Y) olmak üzere ikiye ayrılır. Bağımsız değişkenlerdeki nitelikler için bir x matrisi, bağımlı değişken için ise bir y vektörü oluşturulur.
Veri seti %67 eğitim ve %33 test için bölünür. Bu bölünme sklearn kütüphanesinin train_test_split methodu ile yapılır.

## Naive Bayes Algoritması Modeli Oluşturma
Naive Bayes sınıflandırma algoritması için GaussianNB import edilir. Ardından, X_train ve Y_train verileri fit edilir ve X_test üzerinde tahminler yapılır.

## Model Performansını Değerlendirme
Tahminler sonrasında performans ölçümü yapmak için confusion_matrix ve accuracy_score metotları kullanılır. Confusion matrix, gerçek sınıf ve tahmin edilen sınıfı içeren bir tablo olup, doğru tahmin edilen ve yanlış tahmin edilen verileri sayısal olarak gösterir. Accuracy score ise tahminlerin doğruluğunu ölçmek için kullanılır.
Sonuç olarak, bu kodlar Naive Bayes sınıflandırma algoritması ile veri seti üzerinde tahminler yapmayı ve performans ölçümü yapmayı göstermektedir.
