# Dressify-Challenge
##Brief About Dressify

Dressify is a garment company, which brings the latest fashion trends to the world. They not only rely on their creative juices to differentiate themselves against their competition, but they have started using data science too. Over the last few months, they have captured data points about several dresses which includes their style, price, size, fabric type, pattern and different dress attributes.


##Problem Description:

Dressify wants to identify the most recommended dress for sales based on various attribute of dresses and market. These attributes are responsible for the sales of a dress, hence, the dresses are recommended accordingly. This data set has missing values. Hence, will be required to treat them accordingly. In this data set, you are expected to predict, if a dress should be recommended by Dressify or not.

##Data Set
We have train (359) and test (141) data set, train data set has both input and output variables). We need to predict recommendation for test data set.

**Variable Name	Description**

**ID**	Unique_ID

**Style**	Bohemia,brief,casual,cute,fashion,flare,novelty,OL,party,sexy,vintage,work

**Price**	Low,Average,Medium,High,Very-High

**Rating**	1-5

**Size**	S,M,L,XL,Free

**Season**	Autumn,winter,Spring,Summer

**NeckLine**	O-neck,backless,board-neck,Bowneck,halter,mandarin-collor,open,peterpan-collor,ruffled,scoop,slash etc

**SleeveLength**	full,half,halfsleeves,butterfly,sleveless,short,threequarter,turndown,null

**waiseline**	dropped,empire,natural,princess,null

**Material**	wool,cotton,mix etc

**FabricType**	shafoon,dobby,popline,satin,knitted,jersey,flannel,corduroy etc

**Decoration**	applique,beading,bow,button,cascading,crystal,draped,embroridary,feathers,flowers etc

**Pattern Type**	solid,animal,dot,leapard etc

**Area**	A,B,C,D,E

**Recommended**	Target Variable: Recommended product (0,1)

##Evaluation Metrics

Evaluation metric of this challenge is Confusion_Matrix. A confusion matrix is an N X N matrix, where N is the number of classes being predicted. For the problem in hand, we have N=2, and hence we get a 2 X 2 matrix.
