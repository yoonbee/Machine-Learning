 Dumbbell culr 운동을 수행할 때 측정된 근전도 신호 데이터를 사용한다. 이 데이터는 시계열 데이터로 (시간  RMS  Angle) 의 형태를 가지고, 이두근과 삼두근의 두가지 label을 가진다. 
 
 이러한 특정 운동은 그 추이를 유지한 많은 data를 확보하는데 어려움을 겪는다. 따라서, train data가 부족한 경우 Data Augmentation을 통해 더 많은 data를 얻을 수 있다. 우리는 Data Augmentation의 방법으로 AAFT( amplitude adjusted Fourier transform) 과 IAAFT ( iterated AAFT ) 의 두가지 방법을 사용하였다. 
 
 이렇게 Augmentation 된 데이터를 세가지 방법으로 ( Line graph, Gramian angular field, CWT Scalogram ) visualization 하여 image dataset 을 구성하였다. 최종적으로 AlexNet을 구현하여 data를 train 하고 실제 이두근과 삼두근의 classification을 진행하고자 한다.  
