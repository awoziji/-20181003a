
语言资源构建
信息抽取与知识图谱
舆情监测与社会计算
邮箱:huanyong@iscas.ac.cn

 github项目列表
 会议总结与报告资料
项目名称	中文名称	项目技术点
KnowledgeGraphSlides	知识图谱CCKS会议报告合集(2013-2018)	知识图谱, 学习资源
CCKS2018Summary	CCKS2018会议总结	知识图谱,个人心得
CCL2018Summary	CCL2018参会总结	自然语言处理,心得
 语言资源构建
项目名称	中文名称	项目技术点
MiningZhiDaoQACorpus	知道类问答社区数据集	语言资源库，语料库，580万问题，983万问答对
CausalCollocation	频繁因果词对库	语言资源库，因果对
ChineseNLPCorpus	中文自然语言处理处理用语言资源	语言资源库，语义库，常用词典, 语言资源观, 语料库
SentimentWordExpansion	情感词扩展	SOPMI
BaikeInfoExtraction	百科信息抽取	Urllib,xpath
SougouWordCollector	搜狗词库自动构建	Urllib,Scrapy
BaikeKnowledgeSchema	百科知识体系构建	Urllib,xpath,递归，知识库本体概念
 自然语言处理基本组件
项目名称	中文名称	项目技术点
WordSegment	分词	HMM, MAXCUT,Ngram
HuanNLP	自然语言处理组件	HMM, maxent, CRF
Pinyin2Chinese	拼音转文字	Trie树，HMM, bigram
QueryCorrection	查询纠错	edit-distance
ChineseCixing	中文词形查询	字形，音形
ChineseAntiword	中文反义词查询	反义词
 信息抽取
项目名称	中文名称	项目技术点
WordMultiSenseDisambiguation	中文多义词词义消歧	百科知识库,词义语义表示,词义语义相似度计算
TextFeatureExtraction	文本特征提取	IG，CHI ，DF，MI
WordCollocation	搭配抽取	MI
KeyInfoExtraction	关键信息提取	TFIDF，TextRank
EventTriplesExtraction	事件三元组提取	dependency parser
知识图谱与事理图谱
项目名称	中文名称	项目技术点
AbstractKnowledgeGrap	抽象知识图谱	抽象知识图谱，抽象实体，抽象状态，抽象动作
GoodsKG	电商商品概念与销售知识图谱	商品概念，商品类知识
ZhidaoChatbot	基于问答社区的逻辑知识问答	问答社区，逻辑问答
EventPredictBasedOnEG	基于事理图谱的未来事件预测	事理图谱，事件预测
QAonMilitaryKG	军事知识图谱与问答项目	知识图谱,军事,基于模板问答方式
TravelKnowledgeGraph	出行知识图谱	路径规划,推荐,知识模型
PersonRelationKnowledgeGraph	中文人物关系图谱	bootstrapping, 远程监督, 训练数据回标, 关系抽取
CrimeKgAssitant	法律罪行智能助手	知识图谱, 智能预判, 自动问答
QASystemOnKG	医疗知识图谱与自动问答	知识图谱构建及自动问答
ComplexEventExtraction	复合事件图谱	复合事件，条件事件、反转事件抽取
CausalityEventExtraction	因果事件图谱	因果图谱，因果事件抽取
SequentialEventExtration	顺承事件图谱	动宾短语提取，事件图谱
LanguageKnowledgeGraph	语言政策知识图谱	Neo4j,Echarts,D3js
HyponymyExtraction	上下位关系图谱	模式匹配，上下位概念表示
MusicLyricChatbot	歌词对对碰	es搜索,歌词知识库
 文本挖掘与社会计算
项目名称	中文名称	项目技术点
IdealWordCloudKit	自定义形状词云项目	wordcloud, tfidf, 可视化
WeiboIndexSpyder	微博指数采集	selenium,xpath
BaiduIndexSpyder	百度指数采集	xpath,selenium
AliIndexSpyder	阿里指数采集	selenium,xpath
DocSentimentAnalysis	基于句法依存的情感分析	Template, Dependencyparser
LearningBasedSentiment	基于深度学习的情感分析	CNN,RNN,ML
TextGrapher	文本结构化图谱表示	EventExtraction，知识表示
ImportantEventExtractor	文本重要性计算	textrank
ZhuguanDetection	文本主观性计算	subjective knowledge base
SentenceSimilarity	句子相似度计算	distance, hash, haiming ,eidtdistance
TopicCluster	文本话题聚类	LDA，Kmeans
EventMonitor	特定事件追踪	新闻采集，事件监测架构，scrapy
PoemMining	中国古代诗词挖掘	语料库构建，文本挖掘
LawCrimeMining	司法文本挖掘	语料库构建，文本挖掘
ChineseHumorSentiment	中文幽默情绪计算	语料库构建，幽默分类与情绪计算
LanguagePlatform	集成自然语言处理技术的语言平台	Neo4j,Echarts,Django
 深度学习与语义表示
项目名称	中文名称	项目技术点
ChineseTextualInference	中文文本蕴含/推理	Textual entailment, keras, 文本分类
SiameseSentenceSimilarity	siamese相似问句匹配	siamese lstm network, keras, 文本分类
MedicalNamedEntityRecognition	中文电子病例命名实体识别	keras, bi-lstm-crf
ChineseEmbedding	中文向量大全(字符向量、词向量、拼音向量、依存向量、词性向量)	SKIP-GRAM，Co-Matrix
Word2Vector	词向量表示	CBOW, SKIP-GRAM，Co-Matrix
Sentence2Vector	句子向量表示	CBOW
Seq2SeqTranslation	端到端的翻译模型	keras, lstm
