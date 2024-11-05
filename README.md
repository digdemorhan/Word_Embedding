# Word_Embedding

# Projenin Ana Teması
Bu projede, ürünler üzerine yazılmış 150.000 yorumdan oluşan bir veri seti kullanılmıştır. Verisetinin eliminasyonu, preprocessing aşamaları ve bu aşamalardan sonra word embedding yöntemleri uygulanmıştır. Proje kapsamında, veri setinden rastgele seçilen 3000 yorum üzerinde ön işleme adımları uygulanarak bir word embedding modeli oluşturulmuştur.

# Kullanılan Kütüphaneler ve Frameworkler
Bu projede kullanılan kütüphaneler ve frameworkler aşağıdaki gibidir:
<ul>
  <li><b>Pandas</b></li>
  <li><b>Numpy</b></li>
  <li><b>NLTK</b></li>
  <li><b>Zeyrek</b></li>
  <li><b>Gensim</b></li>
  <li><b>Scikit-learn</b></li>
</ul>

# Veriseti
Kullanılan veriseti aşağıdaki linkte yer almaktadır ve olumlu, olumsuz ve nötr olarak sınıflandırılmış 150.000 ürün yorumu içermektedir. Verisetindeki üç kategorinin her birinden rastgele 1000 tane veri alınarak toplam 3000 veri ile çalışılmıştır.
Verisetinin linki: https://huggingface.co/datasets/maydogan/TRSAv1

# Preprocessing Adımları
<ul>
  <li><b>Lower Casing</b></li>
  <li><b>Removal of Punctionations</b></li>
  <li><b>Removal of Stopwords</b></li>
  <li><b>Lemmatization</b></li>
  <li><b>Removal of Emojis</b></li>
</ul>

# Word Embedding Modeli
Proje kapsamında geliştirilen word embedding modelinde Gensim kütüphanesi kullanılmıştır. Model, kelimelerin 50 boyutlu vektörler olarak temsil edilmesini sağlamaktadır. Word embedding modelinde seçilen bazı kelimeler için benzer kelimeler bulunmuş, vektör temsilleri alınmış, analoji oyunu yapılarak çeşitli kelimelerle ilişkileri incelenmiştir. CountVectorizer ve TfidfVectorizer kullanılarak metin verileri sayısal formata dönüştürülmüştür.

# Değerlendirme ve Sonuç
Bu projede 150.000 veriden oluşan veriseti elimine edilip 3000 veriye çekilmiş, bazı preprocessing yöntemleri uygulanmış ve word embedding modeli oluşturulmuştur. Bazı kelimeler için benzer kelime ilişkileri saptanmış ve analojilerine bakılmıştır. Bu analizler modelin kelime ilişkilerini öğrenebildiğini ve veriler üzerinde anlamlı kelime ilişkileri çıkarabildiğini göstermektedir.

----
----

# Main Theme of the Project
In this project, a dataset of 150,000 reviews on products was used. Elimination of the dataset, preprocessing steps and word embedding methods were applied after these steps. Within the scope of the project, a word embedding model was created by applying preprocessing steps on 3000 randomly selected comments from the dataset.

# Libraries and Frameworks Used
The libraries and frameworks used in this project are as follows:
<ul>
  <li><b>Pandas</b></li>
  <li><b>Numpy</b></li>
  <li><b>NLTK</b></li>
  <li><b>Zeyrek</b></li>
  <li><b>Gensim</b></li>
  <li><b>Scikit-learn</b></li>
</ul>

# Dataset
The dataset used is available at the link below and contains 150,000 product reviews categorised as positive, negative and neutral. A total of 3000 data were studied by randomly taking 1000 data from each of the three categories in the dataset.
Link to the dataset: https://huggingface.co/datasets/maydogan/TRSAv1

# Preprocessing Steps
<ul>
  <li><b>Lower Casing</b></li>
  <li><b>Removal of Punctionations</b></li>
  <li><b>Removal of Stopwords</b></li>
  <li><b>Lemmatization</b></li>
  <li><b>Removal of Emojis</b></li>
</ul>

# Word Embedding Model
Gensim library was used in the word embedding model developed within the scope of the project. The model allows words to be represented as 50-dimensional vectors. For some words selected in the word embedding model, similar words were found, vector representations were taken, and their relations with various words were analysed by analogy game. Text data were converted into numerical format using CountVectorizer and TfidfVectorizer.

# Evaluation and Result
In this project, a dataset of 150.000 data was eliminated and reduced to 3000 data, some preprocessing methods were applied and a word embedding model was created. For some words, similar word relations were identified and analogies were analyzed. These analyses show that the model can learn word relations and extract meaningful word relations from the data.

