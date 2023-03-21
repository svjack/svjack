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

## Recent update repos (group by Knowledge Domain)

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
-->

<table>
<tr>

<td>

[![Sbert-ChineseExample](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Sbert-ChineseExample)](https://github.com/svjack/Sbert-ChineseExample)

</td>

<td>

[![Context2Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Context2Dialogue)](https://github.com/svjack/Context2Dialogue)

</td>

</tr>

<tr>
	
<td>

[![Daliy-Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=Daliy-Dialogue)](https://github.com/svjack/Daliy-Dialogue)

</td>

<td>

[![GLM-Open-Dialogue](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=GLM-Open-Dialogue)](https://github.com/svjack/GLM-Open-Dialogue)

</td>

</tr>
	
<tr>
<td>

[![docvqa-gen](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=docvqa-gen)](https://github.com/svjack/docvqa-gen)

</td>



<td>

[![tableQA-Chinese](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=tableQA-Chinese)](https://github.com/svjack/tableQA-Chinese)

</td>
</tr>

<tr>
<td>

[![DeepPavlov-Chinese-KBQA](https://github-readme-stats.vercel.app/api/pin/?username=svjack&repo=DeepPavlov-Chinese-KBQA)](https://github.com/svjack/DeepPavlov-Chinese-KBQA)

</td>

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

<table>
<tr>

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

print(info_df.to_markdown())
-->

## Interested in Artificial Intelligence ? Have a try my recent online demo in HuggingFace Space 🤗
## Recent update Huggingface Space reps 

|    | url                                                                                       | title                                                | emoji   |
|---:|:------------------------------------------------------------------------------------------|:-----------------------------------------------------|:--------|
|  0 | https://huggingface.co/spaces/svjack/Question-Generator                                   | Question Generator                                   | 😻      |
|  1 | https://huggingface.co/spaces/svjack/ControlNet-Pose-Chinese                              | ControlNet Pose Chinese                              | ⚡      |
|  3 | https://huggingface.co/spaces/svjack/Entity-Property-Extractor-zh                         | Entity Property Extractor Zh                         | 🦀      |
|  2 | https://huggingface.co/spaces/svjack/bloom-daliy-dialogue-english                         | Bloom Daliy Dialogue English                         | 📚      |
| 22 | https://huggingface.co/spaces/svjack/Translate-Chinese-to-English                         | Translate Chinese To English                         | 📚      |
| 20 | https://huggingface.co/spaces/svjack/Translate                                            | Translate                                            | 🌍      |
|  4 | https://huggingface.co/spaces/svjack/Question-Words-Extractor-zh                          | Question Words Extractor Zh                          | 📈      |
| 10 | https://huggingface.co/spaces/svjack/prompt-extend-gpt-chinese                            | Prompt Extend Gpt Chinese                            | 🌍      |
| 21 | https://huggingface.co/spaces/svjack/Harry-Potter-Knowledge-Question-Answer-in-Chinese    | Harry Potter Knowledge Question Answer In Chinese    | 🧙      |
|  5 | https://huggingface.co/spaces/svjack/gpt-dialogue-chinese                                 | Gpt Dialogue Chinese                                 | 📊      |
| 16 | https://huggingface.co/spaces/svjack/gpt-daliy-dialogue-chinese                           | Gpt Daliy Dialogue Chinese                           | 📚      |
| 19 | https://huggingface.co/spaces/svjack/GLM-Open-Dialogue-Chinese                            | GLM Open Dialogue Chinese                            | 🦀      |
| 18 | https://huggingface.co/spaces/svjack/GLM-Open-Dialogue                                    | GLM Open Dialogue                                    | ⚡      |
| 15 | https://huggingface.co/spaces/svjack/Extract-Similar-Chinese-Span-by-English-From-Chinese | Extract Similar Chinese Span By English From Chinese | 🔥      |
| 11 | https://huggingface.co/spaces/svjack/English-Context-Dialogue-Generator                   | English Context Dialogue Generator                   | 👁       |
|  7 | https://huggingface.co/spaces/svjack/English-Comet-Atomic                                 | English Comet Atomic                                 | 🐢      |
|  6 | https://huggingface.co/spaces/svjack/ControlNet-Canny-Chinese                             | ControlNet Canny Chinese                             | 💩      |
|  9 | https://huggingface.co/spaces/svjack/context-dialogue-chinese-sample-search               | Context Dialogue Chinese Sample Search               | 💻      |
| 12 | https://huggingface.co/spaces/svjack/Chinese-Context-Dialogue-Generator                   | Chinese Context Dialogue Generator                   | 🐰      |
|  8 | https://huggingface.co/spaces/svjack/Chinese-Comet-Atomic                                 | Chinese Comet Atomic                                 | 🚀      |
| 14 | https://huggingface.co/spaces/svjack/bloom-gpt-dialogue-chinese-sample-search             | Bloom Gpt Dialogue Chinese Sample Search             | 🐢      |
| 13 | https://huggingface.co/spaces/svjack/bloom-dialogue-chinese                               | Bloom Dialogue Chinese                               | 🌖      |
| 23 | https://huggingface.co/spaces/svjack/bloom-dialogue-english-sample-search                 | Bloom Daliy Dialogue English Sample Search           | ⚡      |
| 17 | https://huggingface.co/spaces/svjack/bloom-daliy-dialogue-chinese                         | Bloom Daliy Dialogue Chinese                         | 🌍      |

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
