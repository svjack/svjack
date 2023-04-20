### Hi there 👋 
### This is <b>Zhipeng Yang (svjack)</b> !

[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/FernandoRoldan93)
![python](https://img.shields.io/badge/python-v3.9-blue)
🤗
<!--
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/froldanzafra/)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:Fernando.Roldan.Zafra@gmail.com)
-->

<!--
<img align="left" 
alt="img" src="https://aeiljuispo.cloudimg.io/v7/https://s3.amazonaws.com/moonup/production/uploads/1670144568552-634dffc49b777beec3bc6448.jpeg?w=200&h=200&f=face" 
width="20%" height="auto" />
-->

![svjack's GitHub stats](https://github-readme-stats.vercel.app/api?username=svjack&count_private=true&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=svjack&layout=compact)](https://github.com/svjack/github-readme-stats)

Welcome to my Github page!  I am Zhipeng Yang (svjack), An artificial intelligence engineer in Hangzhou China.

## Recent update repos (group by Domain)

### StableDiffusion
<table>
<tr>

<td>

[![Stable-Diffusion-Chinese-Extend](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Stable-Diffusion-Chinese-Extend)](https://github.com/svjack/Stable-Diffusion-Chinese-Extend)

</td>

<td>

[![Stable-Diffusion-Pokemon](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Stable-Diffusion-Pokemon)](https://github.com/svjack/Stable-Diffusion-Pokemon)

</td>

</tr>

<tr>
<td>

[![ControlLoRA-Chinese](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=ControlLoRA-Chinese)](https://github.com/svjack/ControlLoRA-Chinese)

</td>


</tr>
</table>

### NLP

<!--
Context2Dialogue
Daliy-Dialogue
GLM-Open-Dialogue
docvqa-gen
Sbert-ChineseExample
tableQA-Chinese
DeepPavlov-Chinese-KBQA
NLP-demos-with-translate

PhotoWCT
Detector-in-Detector

PyArrowExpressionCastToolkit

https://github.com/svjack/COMET-ATOMIC-En-Zh
-->

<table>
<tr>

<td>

[![Sbert-ChineseExample](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Sbert-ChineseExample)](https://github.com/svjack/Sbert-ChineseExample)

</td>

<td>
	
[![COMET-ATOMIC-En-Zh](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=COMET-ATOMIC-En-Zh)](https://github.com/svjack/COMET-ATOMIC-En-Zh)
	
</td>

<tr/>
	
<tr>
	
<td>

[![Context2Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Context2Dialogue)](https://github.com/svjack/Context2Dialogue)

</td>


	
<td>

[![Daliy-Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Daliy-Dialogue)](https://github.com/svjack/Daliy-Dialogue)

</td>
	
</tr>

<tr>

<td>

[![GLM-Open-Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=GLM-Open-Dialogue)](https://github.com/svjack/GLM-Open-Dialogue)

</td>


<td>

[![docvqa-gen](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=docvqa-gen)](https://github.com/svjack/docvqa-gen)

</td>

</tr>
	
<tr>

<td>

[![tableQA-Chinese](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=tableQA-Chinese)](https://github.com/svjack/tableQA-Chinese)

</td>

<td>

[![DeepPavlov-Chinese-KBQA](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=DeepPavlov-Chinese-KBQA)](https://github.com/svjack/DeepPavlov-Chinese-KBQA)

</td>
	
</tr>

<tr>

<td>

[![NLP-demos-with-translate](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=NLP-demos-with-translate)](https://github.com/svjack/NLP-demos-with-translate)

</td>
</tr>

</table>

### CV

<table>
<tr>

<td>

[![PhotoWCT](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=PhotoWCT)](https://github.com/svjack/PhotoWCT)

</td>

<td>

[![Detector-in-Detector](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Detector-in-Detector)](https://github.com/svjack/Detector-in-Detector)

</td>

</tr>
</table>

### DATA

<!--
https://github.com/svjack/img2dataset-pq2hf-transform-toolkit
-->

<table>
<tr>
	
<td>

[![mg2dataset-pq2hf-transform-toolkit](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=img2dataset-pq2hf-transform-toolkit)](https://github.com/svjack/img2dataset-pq2hf-transform-toolkit)

</td>

<td>

[![PyArrowExpressionCastToolkit](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=PyArrowExpressionCastToolkit)](https://github.com/svjack/PyArrowExpressionCastToolkit)

</td>

</tr>
</table>

<!--
from huggingface_hub import HfApi
import requests
import pandas as pd

hf_api = HfApi()

resp = requests.get("https://huggingface.co/api/spaces?search=svjack")
df = pd.DataFrame(resp.json())

df = df[
    df["id"].map(
        lambda x: x.strip().startswith("svjack")
    )
]

df["info"] = df["id"].map(
    lambda x: hf_api.space_info(x)
)

info_df = pd.DataFrame(
df.sort_values(by = "likes", ascending = False).apply(
    lambda x: 
    (
        "https://huggingface.co/spaces/{}".format(x["id"]),
        x["info"].cardData["title"],
        x["info"].cardData["emoji"],
        x["likes"]
    ),
    axis = 1
).values.tolist())
info_df.columns = ["url", "title", "emoji", "likes"]
info_df = info_df.sort_values(by = ["likes", "title"], ascending = False)
del info_df["likes"]

print("\n".join(info_df["title"].values.tolist()))

#### deepl
target_str = '''
Stable Diffusion 姿势 ControlNet Lora 中文模型
问题生成器
中文实体属性提取器
Stable Diffusion 面部 ControlNet 中文模型
Bloom日常对话英文模型 
中英文翻译
翻译
SPIGA 面部识别对齐
中文疑问词提取器
英文文档图片问题生成器
中文文档图片问题生成器
Stable Diffusion中文提示句扩展GPT模型
哈利波特中文知识库问答
中文GPT对话模型
中文GPT日常对话模型
中文GLM开放对话模型
多语言GLM开放对话模型
从中文中提取相似的英文语段模型
根据上下文生成对话英文模型
日常事件图谱推断英文模型
Stable Diffusion 边缘 ControlNet Lora 中文模型
Stable Diffusion 边缘 ControlNet 中文模型
根据上下文生成对话中文模型数据搜索
根据上下文生成对话中文模型
日常事件图谱推断 Lora T5-large 中文模型
日常事件图谱推断中文模型
Bloom GPT 中文对话样本搜索
Bloom对话中文模型 
Bloom GPT 英文对话样本搜索
Bloom日常对话中文模型
'''
import numpy as np

target_l = pd.Series(target_str.split("\n")).map(lambda x: x.strip()).map(lambda x: x if x else np.nan).dropna().values.tolist()

info_df["中文标题"] = target_l

info_df = info_df[["url", "title", "中文标题", "emoji"]]
info_df = info_df.reset_index().iloc[:, 1:]
info_df.index = pd.Series(info_df.index).map(lambda x: x + 1).values.tolist()

print(info_df.to_markdown())
-->

## Interested in Artificial Intelligence ? Have a try my recent online demo in HuggingFace Space 🤗
## Recent update Huggingface Space reps 

|    | url                                                                                       | title                                                | 中文标题                                       | emoji   |
|---:|:------------------------------------------------------------------------------------------|:-----------------------------------------------------|:-----------------------------------------------|:--------|
|  1 | https://huggingface.co/spaces/svjack/ControlNet-Pose-Chinese                              | ControlNet Pose Lora Chinese                         | Stable Diffusion 姿势 ControlNet Lora 中文模型 | ⚡      |
|  2 | https://huggingface.co/spaces/svjack/Question-Generator                                   | Question Generator                                   | 问题生成器                                     | 😻      |
|  3 | https://huggingface.co/spaces/svjack/Entity-Property-Extractor-zh                         | Entity Property Extractor Zh                         | 中文实体属性提取器                             | 🦀      |
|  4 | https://huggingface.co/spaces/svjack/ControlNet-Face-Chinese                              | ControlNet Face Chinese                              | Stable Diffusion 面部 ControlNet 中文模型      | 💻      |
|  5 | https://huggingface.co/spaces/svjack/bloom-daliy-dialogue-english                         | Bloom Daliy Dialogue English                         | Bloom日常对话英文模型                          | 📚      |
|  6 | https://huggingface.co/spaces/svjack/Translate-Chinese-to-English                         | Translate Chinese To English                         | 中英文翻译                                     | 📚      |
|  7 | https://huggingface.co/spaces/svjack/Translate                                            | Translate                                            | 翻译                                           | 🌍      |
|  8 | https://huggingface.co/spaces/svjack/SPIGA-face-alignment                                 | SPIGA Face Alignment                                 | SPIGA 面部识别对齐                             | 📉      |
|  9 | https://huggingface.co/spaces/svjack/Question-Words-Extractor-zh                          | Question Words Extractor Zh                          | 中文疑问词提取器                               | 📈      |
| 10 | https://huggingface.co/spaces/svjack/Question-Generator-on-English-Doc                    | Question Generator On English Doc                    | 英文文档图片问题生成器                         | 📚      |
| 11 | https://huggingface.co/spaces/svjack/Question-Generator-on-Chinese-Doc                    | Question Generator On Chinese Doc                    | 中文文档图片问题生成器                         | 🚀      |
| 12 | https://huggingface.co/spaces/svjack/prompt-extend-gpt-chinese                            | Prompt Extend Gpt Chinese                            | Stable Diffusion中文提示句扩展GPT模型          | 🌍      |
| 13 | https://huggingface.co/spaces/svjack/Harry-Potter-Knowledge-Question-Answer-in-Chinese    | Harry Potter Knowledge Question Answer In Chinese    | 哈利波特中文知识库问答                         | 🧙      |
| 14 | https://huggingface.co/spaces/svjack/gpt-dialogue-chinese                                 | Gpt Dialogue Chinese                                 | 中文GPT对话模型                                | 📊      |
| 15 | https://huggingface.co/spaces/svjack/gpt-daliy-dialogue-chinese                           | Gpt Daliy Dialogue Chinese                           | 中文GPT日常对话模型                            | 📚      |
| 16 | https://huggingface.co/spaces/svjack/GLM-Open-Dialogue-Chinese                            | GLM Open Dialogue Chinese                            | 中文GLM开放对话模型                            | 🦀      |
| 17 | https://huggingface.co/spaces/svjack/GLM-Open-Dialogue                                    | GLM Open Dialogue                                    | 多语言GLM开放对话模型                          | ⚡      |
| 18 | https://huggingface.co/spaces/svjack/Extract-Similar-Chinese-Span-by-English-From-Chinese | Extract Similar Chinese Span By English From Chinese | 从中文中提取相似的英文语段模型                 | 🔥      |
| 19 | https://huggingface.co/spaces/svjack/English-Context-Dialogue-Generator                   | English Context Dialogue Generator                   | 根据上下文生成对话英文模型                     | 👁       |
| 20 | https://huggingface.co/spaces/svjack/English-Comet-Atomic                                 | English Comet Atomic                                 | 日常事件图谱推断英文模型                       | 🐢      |
| 21 | https://huggingface.co/spaces/svjack/ControlNet-Canny-Chinese                             | ControlNet Canny Lora Chinese                        | Stable Diffusion 边缘 ControlNet Lora 中文模型 | 💩      |
| 22 | https://huggingface.co/spaces/svjack/ControlNet-Canny-Chinese-df                          | ControlNet Canny Chinese                             | Stable Diffusion 边缘 ControlNet 中文模型      | 🦐      |
| 23 | https://huggingface.co/spaces/svjack/context-dialogue-chinese-sample-search               | Context Dialogue Chinese Sample Search               | 根据上下文生成对话中文模型数据搜索             | 💻      |
| 24 | https://huggingface.co/spaces/svjack/Chinese-Context-Dialogue-Generator                   | Chinese Context Dialogue Generator                   | 根据上下文生成对话中文模型                     | 🐰      |
| 25 | https://huggingface.co/spaces/svjack/Chinese-Comet-Atomic-T5-Large-Lora                   | Chinese Comet Atomic T5 Large Lora                   | 日常事件图谱推断 Lora T5-large 中文模型        | 🏃      |
| 26 | https://huggingface.co/spaces/svjack/Chinese-Comet-Atomic                                 | Chinese Comet Atomic                                 | 日常事件图谱推断中文模型                       | 🚀      |
| 27 | https://huggingface.co/spaces/svjack/bloom-gpt-dialogue-chinese-sample-search             | Bloom Gpt Dialogue Chinese Sample Search             | Bloom GPT 中文对话样本搜索                     | 🐢      |
| 28 | https://huggingface.co/spaces/svjack/bloom-dialogue-chinese                               | Bloom Dialogue Chinese                               | Bloom对话中文模型                              | 🌖      |
| 29 | https://huggingface.co/spaces/svjack/bloom-dialogue-english-sample-search                 | Bloom Daliy Dialogue English Sample Search           | Bloom GPT 英文对话样本搜索                     | ⚡      |
| 30 | https://huggingface.co/spaces/svjack/bloom-daliy-dialogue-chinese                         | Bloom Daliy Dialogue Chinese                         | Bloom日常对话中文模型                          | 🌍      |

<!--
#### 🌱 Things I am currently working on: 
- Finish my Computer Engineering Master Degree  
- Taking online courses about Data Science and Machine Learning 
- Business practices on [bi4 Group Spain](https://github.com/bi4group) 🚀 *coming soon*

#### :muscle: Things I am challenging myself with:
- Waking up earlier to make good use of the day
- Coding at least 4 hours a day
- Exercising 3 days a week
- Improving my CV with some education apart from university

-->

<br/>

#### :computer: Programming languages and tools: 
<p>
  <!--
	<img width="50%" align="right" src="https://github-readme-stats.vercel.app/api?username=FernandoRoldan93&show_icons=true&hide_border=true" />
  -->
  
<code><img width="10%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/pytorch/pytorch-ar21.svg"></code>
<code><img width="10%" src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-ar21.svg"></code>



<!--
</p>

<sub>Credits to: <br/>[IreneHerrerart](https://www.artstation.com/ireneherrera) for the wonderfull [picture](https://github.com/FernandoRoldan93/FernandoRoldan93/blob/master/cover_image.jpg)</sub>

-->
