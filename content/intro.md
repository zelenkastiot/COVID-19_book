# Вовед
<p align="left">
 [![Binder](https://raw.githubusercontent.com/zelenkastiot/binder_badges/b6c245586b19a37fabf2612ef06922f4d73672bf/badges/covid19book-badge.svg)](https://mybinder.org/v2/gh/zelenkastiot/COVID-19_book/master?urlpath=lab/tree/content/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CiiyvS2x_6rDYZqDF9ioTrFKxT7b5QRz?usp=sharing%2Fgithub%2Fzelenkastiot%2FCOVID-19_book%2Fblob%2Fmaster%2Fcontent%2F02_codingSIR%2F2_scenario.ipynb)

</p>
<br> **Летен семестар, 2020** <br> <br>
- **Ментор:** Акад. Љупчо Коцарев <br> 
- **Студенти:** Филип Карафилоски, Кирил Зеленковски <br>
<br>

### Тема на проектот
Репродусибилна [Jupyter книга](https://jupyterbook.org/intro.html) за кратко истражување повразно со параметрите на *SIR* модел, нивното меѓусебно влијанието претставено со интерактивни графици, *Curve Fitting* за COVID-19 податоци за *Италија*.

Во последните неколку месеци, голем дел data scientists, ентузијасти и луѓе со слободно време почнаа 
да читаат за моделирање на заразни болести. Повеќето од статиите и обидите што кружат на Интернет се 
обидуваат директно, слепо да ги соодвестуваат моделите со бројот на случаеви на COVID19, без спознавање 
на теоријата и логиката позади самите модели. 

Како тема за проектот се одлучивме да се обидеме да го истражиме феноменот и позадината зад моделирањето 
на заразни болести. *SIR* моделот со своите равенки и параметри ги објаснуваме слично на начинот на кој ние
самите ги истражувавме со прости примери и *Python* Jupyter тетратки. Опфаќаме и елаборираме различни варијанти од 
класичниот модел, со додавање на нови компоненти и состојби како и едноставен обид за Curve Fitting за real-world податоци.

Проектот нуди: <br>

**Репродусибилност:** Тетратките во книгата се комплетно <u>репродусибилни</u> во две инстанци: 
- [Binder](https://gist.github.com/zelenkastiot/ca6f8dc92d1a9722a6e73dfb9ecd3265) (Linux container, [повеќе за Binder](https://blog.jupyter.org/mybinder-org-serves-two-million-launches-7543ae498a2a#:~:text=What%20is%20mybinder.org%3F,a%20collection%20of%20interactive%20notebooks.&text=All%20they%20have%20to%20do,without%20having%20to%20install%20anything.)) 
- [Google Colab](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d#:~:text=What%20is%20Google%20Colab%3F,TensorFlow%2C%20PyTorch%2C%20and%20OpenCV.) тетратка

За *Google Colab* потребно е само gmail профил за *Binder* нема потреба од никакво поврзување. 


**Транспаретност:** Ќелиите за код можат да се прошируваат при кликнување на "+", каде може да се следи кодот за секоја фигура, графикон. 


**Интерактивност:** Книгата содржи голем број на интерактивни графици кои ја користат *Python* библиотеката [Plotly](https://plotly.com/), каде може да се манипулираат исходите на кривите со променување на иницијалните вредности со помош на лизгачи, 
мени со опции и временски зависни лизгачи. 

<br> <br>
Пример за интересна <a href="https://plotly.com/chart-studio-help/create-animations/">анимација</a> на фигура изработена во *Python*: 


![life expectancy](GIF1.gif)



<hr>
<p align="center">
<img src="https://raw.githubusercontent.com/zelenkastiot/images/master/image_thumb-15.png" style="width:20px;"></img> <br>
</p>