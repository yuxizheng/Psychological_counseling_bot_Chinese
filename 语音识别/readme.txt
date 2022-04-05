【数据来源】THCHS-30数据集
【数据介绍】由清华大学语音与语言技术中心（CSLT）出版的开放式中文语音数据库。包含了1万余条语音文件，大约40小时的中文语音数据，内容以文章诗句为主，全部为女声。对学术用户完全免费。
【获取方式】
①矩池云内置：https://www.matpool.com/supports/doc-public-data/，访问路径：/public/data/speech/
②官方下载：http://www.openslr.org/18/

【代码文件介绍】
DFCNN.ipynb为语音转文字的代码，DFCNN-CTC-word-50.h5为50轮汉字权重数据。
DFCNN-拼音.ipynb为语音转汉语拼音的代码，DFCNN-CTC-py.h5为50轮拼音权重数据。
【运行介绍】
DFCNN运行“二、神经网络构建（正式建模）”之后内容即可，DFCNN-拼音运行整个文件即可。
DFCNN-拼音为DFCNN文件的改进。