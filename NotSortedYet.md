

***
Bojan Karlaš (Bojan Karlas), https://scholar.google.com/citations?user=Uv7RWgkAAAAJ&hl=en&oi=ao

A data quality-driven view of mlops, https://arxiv.org/abs/2102.07750

Data Systems for Managing and Debugging Machine Learning Workflows, https://www.research-collection.ethz.ch/handle/20.500.11850/554603

>This thesis aims to tackle the usability problem of modern machine learning systems. This involves taking a broader view which goes beyond the model training part of the ML workflow and developing a system for managing this workflow. This broader workflow includes the data preparation process which comes before model training, as well model management which comes after. We seek to identify various pitfalls and pain points that developers encounter in these ML workflows.  
>이 광범위한 워크플로우는 모델 교육 전에 수행되는 데이터 준비 프로세스와 그 이후에 수행되는 모델 관리를 포함합니다. 우리는 개발자들이 이러한 ML 워크플로우에서 겪는 다양한 함정과 문제점을 식별하고자 한다.  
>
>We then zoom into one particular kind of a usability pain point – labor-efficient data debugging. We pinpoint two categories of data errors (missing data and wrong data), and develop two methods for guiding the attention of the developer by helping them choose the instances of data errors that are the most important. We then empirically evaluate those methods in realistic data repair scenarios and demonstrate that they indeed improve the efficiency of the data debugging process, which in turn translates to greater usability. We finish up with some insights which could be applied to design more usable machine learning systems in the future.  
>그런 다음 작업 효율 데이터 디버깅이라는 특정 유형의 사용적합성 문제를 확대한다. 우리는 두 가지 범주의 데이터 오류(누락된 데이터와 잘못된 데이터)를 찾아내고, 개발자가 가장 중요한 데이터 오류의 인스턴스를 선택할 수 있도록 지원하여 개발자의 주의를 안내하는 두 가지 방법을 개발한다.   

#### 5 Discussion, Conclusion and Future Work

The maturity and richness of the field of applied machine learning revealed many novel problems. As we’ve mentioned in the introduction, the field of “systems for ML” is taking off. However, if we look at the field of regular software development, the development experience and the usability of so many tools that are available for developers, it becomes clear that a lot of work still needs to be done. We are still relatively far off from realizing the dream of having a real IDE for ML with a rich set of Dev/Ops tools, standards and practices.  
응용 기계 학습 분야의 성숙함과 풍부함은 많은 새로운 문제를 드러냈다. 서론에서 언급했듯이, "ML을 위한 시스템" 분야가 도약하고 있습니다. 그러나 정기적인 소프트웨어 개발 분야, 개발자가 사용할 수 있는 수많은 도구의 개발 경험 및 사용성을 살펴보면 여전히 많은 작업이 수행되어야 한다는 것이 분명해진다. 우리는 여전히 풍부한 개발/운영 도구, 표준 및 관행을 갖춘 ML에 대한 실제 IDE를 보유하는 꿈을 실현하기에는 상대적으로 거리가 멀다.


In this thesis we have attempted to make a tiny step in that direction. Based on our direct and indirect experience with applied machine learning, we have identified an array of commonly occuring pain points. We described these pain points in Chapter 2 and provide a toolkit of proposed system components that are meant to overcome them.  
We then zoomed into one particular pain point – labor efficient data debugging guided by some measure of importance. We identified two types of data errors: missing values and wrong values, and propose two measures of importance to tackle them. They were, respectively: information gain (in Chapter 3) and Shapley value (in Chapter 4). We conducted experimental evaluations of those two measures of importance in order to test their effectiveness at their respective data debugging tasks.  
Finally, in this chapter we will briefly go over some lessons learned and proposed recipes for designing usable systems for managing machine learning workflows. If we measure usability as the absence of time wasted on unproductive work, then we argue that our approach for data debugging guided by measures of importance indeed improves usability of the system.


이 논문에서 우리는 그 방향으로 작은 한 걸음을 내딛으려고 시도했다. 응용 기계 학습에 대한 직접 및 간접 경험을 바탕으로, 우리는 일반적으로 발생하는 일련의 문제를 식별했다. 우리는 2장에서 이러한 문제점을 설명하고 이를 극복하기 위한 제안된 시스템 구성 요소의 툴킷을 제공한다.

그런 다음 특정 과제인 노동 효율적인 데이터 디버깅을 중요도에 따라 확대했습니다. 우리는 결측값과 잘못된 값의 두 가지 데이터 오류를 식별하고 이를 해결하기 위한 두 가지 중요도 측정을 제안한다. 그것들은 각각 정보 이득(3장)과 섀플리 가치(4장)였다. 우리는 각각의 데이터 디버깅 작업에서 효과를 테스트하기 위해 이러한 두 가지 중요도에 대한 실험 평가를 수행했다.

마지막으로, 이 챕터에서는 기계 학습 워크플로우를 관리하는 데 사용할 수 있는 시스템을 설계하기 위해 학습된 몇 가지 교훈과 제안된 방법을 간략하게 살펴보겠습니다. 유용성을 비생산적인 작업에 낭비되는 시간의 부재로 측정한다면, 우리는 중요도 척도에 의해 안내된 데이터 디버깅에 대한 우리의 접근 방식이 실제로 시스템의 유용성을 향상시킨다고 주장한다.
***

sss
