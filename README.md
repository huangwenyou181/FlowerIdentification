# FlowerIdentification
这是一个可以用来帮助我们识别花卉的项目，我们小组在导师的指导下，经过小组成员的不懈努力最终完成了项目，取得了不错的成果。

## 项目背景：认识花
自然界中有各种各样漂亮的花朵，有着很高的物质价值和精神价值。但是我们对花的认知非常少，有时候我们看到一朵漂亮的花却不知道它的名字。因此，我们小组决定在花卉识别方面做一个系统来解决这一问题。该系统可以帮助我们随时随地给花拍照来了解一朵花，帮助我们认识一朵花。

## 项目整体目标
我们的目标是做一个网页，该网页可以对用户拍照的照片或者上传的照片进行花卉识别和检测。为了达到这一目标，我们的项目分下面两部分进行：
（1）模型训练。训练出一个可供用于识别花朵的模型。
（2）搭建网页。网页部分又分为前端和后端。
             前端：主要是供用户交互的界面。
             后端：调用训练好的模型，对用户上传来的图片进行处理，返回识别后的图片。从数据库中返回识别到的花朵的信息。
             
## 预期效果
1.用户在手机或者电脑上输入网页URL进入系统。
2.用户选择上传图片或者拍照。
3.系统识别图片中的花朵，并返回识别后的图片。
4.系统返回数据库中该花朵的信息供用户了解。

## 我负责的部分
模型的训练，得到一个可以识别出图片中花朵的模型；
网页后端功能的实现。

## 用到的技术以及编程语言语言
平台：我训练模型用到的平台是百度提供的Aistudio。在对数据集进行处理时，我用到的平台是华为云提供的ModelArts平台。项目开发用到的工具是Visual studio code。
模型：现在初步确定的模型是yolov3 或则ssd等等，主要是看哪种模型得到的结果的精确度更加高。
后端：基于flask框架搭建系统的后端，实现网页的功能以及用户的交互。
编程语言：python，html，css，JavaScript




