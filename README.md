# Books-Light-up-Life
Developed for reading habit formalization and recommendation for next generation.


## A Brief History of Humankind

July 17, 2022 
- Finished reading of page from 1 to 43
- This book presents readers the history of Homo Sapiens in the stage of cognitive revolution, agricultural revolution and scientific revolution. At the very beginning, it define the concept of Homo Sapiens and explain it through the revolution from Big Bang, atom, modules, organisms, culture and history. Then, Uniqueness of Homo Sapiens was introduced compared to other spices such as other human/sister/brother, Lions, etc. The idea is the deep cooperating based on mythical stories when the group is large enough. Though stable interlinks sharing the same faith, sapiens become dominant as the top of pyramid. Usage of tools inspired by big brains recharged via having cooked food to kill other animals enact human stand out. Next, description for the progress for how the sapiens behave is taken into consideration as a context of history instead only the arena of biology. If we want have a better understanding about our self, we research on nature of archaic forager. This relys on the archelogical finds on bias of their daily life. However, the short duration of such forager existence and unavailability of artifact in findings makes the investigation problmatic. Anothe solution would be to know the social stucture of modern survived forager, then speculate the way their ancetor lives. This path also posses problems, like the effect on social structure of foragers due to the industrial development, the limited representation of less population of modern foragers for inhospitable area, and cultural distinction even in the same region. 

## PhD Dissection of Deep Nueral Networks - David Bau

July 25, 2022
- 21/192 for table of contents, abstact, acknowledgement, 1.1 dissecting a classifier 
- This work is about interpretable deep neural network. Attempts are conducted as follows,
	- What do a neuron work for? Human-understandable concept is capatured by the neuron. Is it casually or 
		systematically? That means if other neurons can detect concepts. Are those 
		neurons take effect individually or in group? To answer those questions, the author quantify
		the concept selective properties among all neurons in each layer by a classifier using CNN on
		images with labeled concepts. He then detects the concept preference for each neuron. We may express
		this by two ways, 1) visualizing all firing neurons with respect to a certain concept for all layer each time,
		2) calculating the frequency of firing neurons for all concepts in statistics. The result is that 1) neurons tend to 
		find concepts in later layers, while the front layers account for basic textures, 2) presence of neuron to detect
		the object class is not explict in trainning process. Distributed coding claims that concepts are captured
		by a population of neurons and a neuron can detect concept because of its membership of that group. The author
		disputes this by testing the concept selective capacity with random feature combination. Learning a concept is the 
		task of each neuron. Then neural causality is invesitgated. Two puzzles then emerge: 1) Removal of the conceptual 
		neuron will cause the failure of the 
		detection of that concept? 2) Why this? Does the supervised label will make the concept detector into reality?
		He refers that some articles about the demage of conceptual neuron on the classification, while removing other 
		neuron does not matter too much. He also points the casual links between the conceptual neuron and final object
		class detection accuracy. However, it is also need to be investigated further as we can not directly to ask the 
		classifier when a neuron is remove instead we just see the out-box/result/accuracy decrease. To solve the latter 
		problem, we may move forword to the unsupervised setting.