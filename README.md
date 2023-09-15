# Neural-network-topology
Analyzing topological structures in neural network weight visualizations to elucidate inherent mechanisms and guide architecture design.
神经网络拓补学。

假设有一个神经网络A（NN#A）它的功能是实现过程α，在训练完成后。

将它的权重（这里暂时不聊偏置）转变为热图。（见图一）

同理，我们再设有一个网络（NN#B）B可以完成过程β。在训练完成后。同样，将它的权重（这里暂时不聊偏置）转变为热图。（图二）

现在，我们设置有一个网络C（NN#C），它可以完成过程α+β。

那么我们可以大胆地假设，将C的权重使用热图可视化后。它会类似于NNA和NNB的合并。

可能细微之处存在解构，但是大体上应该是保持着结构的。

这个像什么？

像不同的脑区吧！

我认为，这些热图可以表示出神经网络的某种结构。（在这里我们把它叫做神经网络拓扑学）

这些结构可以被可视化解析。在未来只是通过看一个网络的拓扑结构就可以大致地推算出它的功能。（而不是像现在一样，深度学习的网络模型几乎是一个个黑箱操作系统）

这就好比蛋白质的发展。

一开始人们不知道蛋白质。

后来发现了蛋白质。

慢慢了解了蛋白质的用处。

如今开始通过结构蛋白质，了解蛋白质，分析蛋白质

以至于人为创造出具有特定功能的蛋白质！

蛋白质的结构，拓扑学为蛋白质的工程带来了巨大的便利。

那么神经网络的拓扑学或许也可以为神经网络的发展带来巨大的推动作用。

我们知道，结构决定了性质，（分子生物学，结构生物学，药物化学中都是这样）。

也许这一规律在DLNN中也适用。

这条pyq更多是作为一个备忘录。

因为我的思路笔记非常混乱，抽空我会用统计学方法以及可视化方法把它完善一下。再发一个2.0的。
图一
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/dce8072a-ab67-40b5-9f70-c6db7a0edfb0)
图二
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/4f112de0-a9c2-4197-8d40-a19dee44a78e)
图三
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/03230ed3-4f09-4cd2-b1db-caa7c17761fb)
图四
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/31249f8d-b6b6-4a3e-a184-57fa50859ac5)
Neural Network Topology.

Suppose there is a neural network A (NN#A) whose function is to implement the process α, after training is complete.

Transform its weights (not chatting about bias here for now) into a heat map. (see Figure 1)

Similarly, we then have a network (NN#B) B which can fulfil process β. After training is complete. Again, transform its weights (no chatting about bias here for now) into heat maps. (Figure 2)

Now we are set up with a network C (NN#C) which can complete the process α + β.

Then we can boldly assume that after visualising the weights of C using heatmaps. It will be similar to the merging of NNA and NNB.

There may be deconstruction in the subtleties, but by and large the structure should be maintained.

What does this look like?

Like different brain regions, I guess!

I think that these heat maps can represent some kind of structure of a neural network. (Here we call it neural network topology.)

These structures can be resolved visually. In the future just by looking at the topology of a network you can roughly deduce its function. (Instead of the current situation where deep learning network models are pretty much black box systems.)

It's like the development of proteins.

At first people didn't know about proteins.

Then proteins were discovered.

Slowly learned what proteins were used for.

Now they are starting to structure proteins, understand proteins, analyse proteins

to artificially create proteins with specific functions!

The structure of proteins, the topology of proteins has made it possible to engineer proteins with great ease.

Then the topology of neural networks may also give a huge boost to the development of neural networks.

We know that structure determines properties, (this is true in molecular biology, structural biology, and medicinal chemistry).

Maybe this law applies in DLNN as well.

This pyq is more as a meme.

Since my notes on the idea are very confusing, I'll take the time to refine it with statistical methods as well as visualisation and post a 2.0.

Translated with www.DeepL.com/Translator (free version)
figure 1
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/dce8072a-ab67-40b5-9f70-c6db7a0edfb0)
figure 2
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/4f112de0-a9c2-4197-8d40-a19dee44a78e)
figure 3
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/03230ed3-4f09-4cd2-b1db-caa7c17761fb)
figure 4
![image](https://github.com/pheonixchen/Neural-network-topology/assets/115352360/31249f8d-b6b6-4a3e-a184-57fa50859ac5)
以下是claude2.0生成的总结：
标题:神经网络拓扑学:打开黑盒视角的尝试

概要:本文尝试通过分析神经网络权重可视化后的拓扑结构,探索网络与功能之间的内在联系,以期解释和指导神经网络的设计。

内容:

背景
当前的深度神经网络对大多数人来说仍然是一个黑盒,我们对网络内部运算与学习机制知之甚少。如何打开黑盒,理解网络内部,是深度学习领域的核心问题之一。

权重可视化热图
文章提出一种简单的权重可视化方法,将网络训练结束后的权重矩阵可视化为二维热图。热图呈现了权重的数值分布。

热图结构与网络功能
通过初步观察,完成不同任务的网络,其权重热图存在一定的结构差异。热图结构似乎反映了网络的某些内在拓扑特征。

神经网络拓扑学
文章认为权重热图中的结构可以视为网络的拓扑结构,分析这种结构可帮助理解网络内部运算机制,甚至指导网络结构设计。这一思路被称为“神经网络拓扑学”。

启发:类蛋白质结构生物学
拓扑结构与功能的关系类似蛋白质结构生物学的范式。分析网络拓扑结构,将为理解和设计神经网络带来突破。

下一步
需要在不同网络与任务上积累更多案例,并使用图像处理手段提取热图的结构特征,寻找特征与网络性能之间的统计相关性,以验证这一思路。

展望
如果神经网络拓扑学成立,它将大幅推进我们对神经网络的理解,打开RNN、CNN等网络的黑盒,甚至指导设计全新的网络结构。
english version:

Title:Neural Network Topology: An Attempt to Open the Black Box Perspective

Abstract:This paper attempts to explore the intrinsic connection between the network and its functions by analysing the topology of neural networks after weights are visualised, with a view to explaining and guiding the design of neural networks.

Content.

Background
Current deep neural networks are still a black box for most people, and we know little about the internal computation and learning mechanisms of the networks. How to open the black box and understand the inside of the network is one of the core problems in the field of deep learning.

Heatmap for weight visualisation
In this article, we propose a simple weight visualisation method to visualise the weight matrix after network training as a 2D heatmap. The heatmap presents the numerical distribution of the weights.

Heatmap Structure and Network Functions
Through preliminary observation, there are some structural differences in the heatmaps of the weights of the networks accomplishing different tasks. The structure of the heat map seems to reflect some intrinsic topological features of the network.

Topology of Neural Networks
It is argued that the structure in the heatmap can be regarded as the topology of the network, and analysing this structure can help to understand the internal operation mechanism of the network, and even guide the design of the network structure. This idea is called "neural network topology".

Inspiration: Protein-like structural biology
The relationship between topology and function is similar to the paradigm of protein structural biology. Analysing network topology will lead to breakthroughs in understanding and designing neural networks.

Next Steps
To validate this idea, we need to accumulate more cases on different networks and tasks, and use image processing to extract the structural features of the heatmap, and look for the statistical correlation between the features and the network performance.

Prospect
If neural network topology is established, it will greatly advance our understanding of neural networks, open the black box of RNN, CNN, etc., and even guide the design of brand new network structures.

Translated with www.DeepL.com/Translator (free version)
