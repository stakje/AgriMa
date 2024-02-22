<div align="center">
<h1>后稷•首个中文开源农业大模型</h1>
</div>

### 模型简介
后稷•首个中文开源农业大模型是由山西大学与山西农业大学联合研发，以[Baichuan](https://huggingface.co/baichuan-inc)为底座，基于海量有监督农业领域相关数据微调，具备广泛的农业知识和智能分析能力，该模型旨在为农业领域提供全面而高效的信息处理和决策支持。
### 说明
1. 本项目仍在不断迭代更新，考虑到农业领域覆盖广泛，且存在领域数据集资源严重匮乏的问题，我们目前仅发布了在作物学相关问答数据集上的微调模型，其他领域模型我们会在后续陆续公布；
2. 本项目所提供的数据与模型仅供科研使用，严禁用于商业用途；
### 新闻
- [**2024.02.22**] 👋 👋 👋 后稷-v1.0版本模型发布，目前模型已支持作物学领域；
### 更新计划
- [ ] 覆盖更多农业相关领域, 目前仅支持作物学领域，后续将会更新园艺学、农业资源利用、植物保护、畜牧学、兽医学、草业科学、林学以及水产等学科；
- [ ] 基于农业知识图谱、农业教材以及期刊文章预训练模型；
- [ ] 开源预训练数据以及指令微调数据;
- [ ] 构建农业领域评测Benchmark;
- [ ] 发布AgriMa技术评测报告;
### 部分测试
问题 | Baichuan | AgriMa
:--: | :--: | :--:
小麦浇灌越冬水有什么作用？应注意哪些事项？| 浇灌越冬水，又称冬灌，一般在11月中下旬，结合冬前中耕，对小麦进行灌溉。冬灌可以提高小麦的抗寒能力，增强小麦的抗病性，对小麦的生长发育具有积极作用。小麦浇灌越冬水，有什么作用？应注意哪些事项？ 1、小麦浇灌越冬水，有什么作用？ 浇灌越冬水，可以提高小麦的抗寒能力，增强小麦的抗病性，对小麦的生长发育具有积极作用。小麦浇灌越冬水，可以使小麦根系在土壤中生长时间更长，吸收土壤中的水分，使小麦的根系发育更旺盛，从而提高小麦的抗旱能力。 2、浇灌越冬水，应注意哪些事项？ 浇灌越冬水，应注意浇水量，不宜过多，以免降低小麦的抗寒能力。浇灌越冬水，应注意浇灌时间，浇灌时间不宜过早，以免小麦根系遭受冻害。浇灌越冬水，应注意浇灌深度，浇灌深度应根据土壤的实际情况确定，不宜过深，以免影响小麦的生长。 3、小麦浇灌越冬水，应注意哪些事项？ 浇灌越冬水，应注意浇灌方式，浇灌方式应根据小麦的生长情况确定，一般采用沟灌或膜下滴灌。浇灌越冬水，应注意浇灌方式，避免造成小麦根系的损伤，影响小麦的生长。浇灌越冬水，应注意浇灌时间，避免在冬季气温过低时浇灌，以免造成小麦根系冻害。 4、小麦浇灌越冬水，应注意哪些事项？ 浇灌越冬水，应注意浇灌深度，避免造成小麦根系损伤，影响小麦的生长。浇灌越冬水，应注意浇灌次数，避免造成小麦根系的损伤，影响小麦的生长。浇灌越冬水，应注意浇灌次数，避免造成小麦根系的损伤，影响小麦的生长。浇灌越冬水，应注意浇灌次数，避免造成小麦根系的损伤，影响小麦的生长。浇灌越冬水，应注意浇灌次数，避免造成小麦根系的损伤，影响小麦的生长。| 越冬水是小麦生长过程中不可缺少的环节，其作用主要有以下几点：1.可以提高土壤的保水能力，使土壤更加稳定，有利于小麦安全越冬。2.可以补充土壤中的水分，保证小麦的正常生长，提高小麦的抗旱能力。3.可以改善土壤结构，提高土壤的肥力，促进小麦生长。4.可以调节土壤的酸碱度，保持土壤的平衡状态。小麦浇灌越冬水需要注意以下几点：1.选择合适的灌溉时间。一般来说，越冬水应在小麦生长过程中进行，以保证小麦生长需要的水分。2.灌溉量要适当。过量灌溉会导致土壤过湿，不利于小麦的生长。3.灌溉方式要合理。可以选择滴灌、喷灌等方式，提高灌溉效率。4.灌溉过程中要注意安全，避免出现事故。
大豆茎叶生长茂盛，但是不结荚、空荚、瘪粒，是什么原因？| 1、大豆营养生长旺盛，生殖生长受到抑制，所以造成空荚、秕粒。2、大豆植株长势过旺，养分大量向茎叶输送，不向籽粒输送，导致空荚。3、大豆营养生长与生殖生长失调，造成空荚、秕粒。4、土壤水分过多，大豆根系吸收能力减弱，养分输送不畅，造成空荚。5、土壤缺硼、缺锌，大豆花芽分化时，花粉管不能正常发育，导致花粉败育，不能受精结荚。6、土壤中氮肥过多，导致大豆徒长，植株瘦弱，抗逆性差，空荚、秕粒多。7、土壤中磷肥过多，导致大豆荚多籽粒少，空荚、秕粒多。8、土壤中缺钙，影响大豆根系吸收，造成空荚、秕粒多。9、土壤中缺硼，影响大豆花芽分化，花粉管不能正常发育，导致花粉败育，不能受精结荚。10、土壤中缺锌，影响大豆花芽分化，花粉管不能正常发育，导致花粉败育，不能受精结荚。11、土壤中缺钾，影响大豆光合作用，导致大豆植株徒长，瘦弱，空荚、秕粒多。12、土壤中缺钼，影响大豆根瘤菌发育，导致大豆生长缓慢，植株矮小，空荚、秕粒多。13、土壤中缺铁，影响大豆叶绿素合成，导致叶片黄化，空荚、秕粒多。14、土壤中缺锰，影响大豆光合作用，导致植株生长缓慢，叶片黄化，空荚、秕粒多。15、土壤中缺钙，影响大豆光合作用，导致植株生长缓慢，叶片黄化，空荚、秕粒多。16、土壤中缺硫，影响大豆叶绿素合成，导致叶片黄化，空荚、秕粒多。17、土壤中缺锌，影响大豆花芽分化，花粉管不能正常发育，导致花粉败育，不能受精结荚。 | 营养供应不足。大豆生长需要充足的养分，如果养分供应不足，就会导致茎叶生长茂盛，但是不结荚、空荚、瘪粒。这种情况可以通过加强施肥、合理施肥等措施来解决。光照不足。大豆生长需要充足的光照，如果光照不足，就会导致茎叶生长茂盛，但是不结荚、空荚、瘪粒。这种情况可以通过加强通风、合理遮阴等措施来解决。病虫害影响。大豆茎叶生长茂盛，但是不结荚、空荚、瘪粒，也可能是受到了病虫害的影响。这种情况可以通过加强病虫害防治等措施来解决。
大白菜在生长发育过程中如何防止烧心病的发生？| 1、选用抗病品种。2、大白菜施肥：在基肥施足的基础上，追肥宜少施勤施，避免过量施用氮肥，增施钾肥。3、加强大白菜的栽培管理：1大白菜要与其他作物轮作，避免连作。2大白菜播种后及时覆盖地膜，并浇水，促进大白菜的快速生长。3及时中耕除草，提高地温，促进根系发育。4大白菜在生长过程中，发现有病株及时拔除，并带出田外烧毁。5大白菜生长期间，要根据大白菜的长势及时追肥，以保证大白菜的正常生长。6大白菜收获后，及时清理田间残株病叶，集中烧毁，以减少病源。7大白菜收获后，及时浇水，以利于大白菜的越冬。8大白菜在生长期间，遇到干旱天气，要及时浇水，保持土壤湿润，促进大白菜的正常生长。9大白菜收获后，及时清除田间残株病叶，集中烧毁，以减少病源。10大白菜收获后，及时浇水，以利于大白菜的越冬。11大白菜在生长过程中，发现有病株及时拔除，并带出田外烧毁。12大白菜生长期间，要根据大白菜的长势及时追肥，以保证大白菜的正常生长。13大白菜收获后，及时清理田间残株病叶，集中烧毁，以减少病源。14大白菜收获后，及时浇水，以利于大白菜的越冬。15大白菜在生长期间，遇到干旱天气，要及时浇水，保持土壤湿润，促进大白菜的正常生长。16大白菜收获后，及时清除田间残株病叶，集中烧毁，以减少病源。17大白菜收获后，及时浇水，以利于大白菜的越冬。18大白菜在生长期间，发现有病株及时拔除，并带出田外烧毁。19大白菜生长期间，要根据大白菜的长势及时追肥，以保证大白菜的正常生长。| 烧心病是一种由大白菜心腐病菌引起的病害，其病原菌可以在土壤中存活，因此，在大白菜的生长发育过程中，应注意以下几点：1.选择健康的种子。选择健康的种子，可以减少病原菌的数量，从而降低烧心病的发生率。2.科学施肥。科学施肥可以提高大白菜的抗病能力，降低烧心病的发生率。3.合理浇水。合理浇水可以保持土壤的湿度，避免土壤过干或过湿，从而减少病原菌的存活机会。4.及时清除病株。及时清除病株可以减少病原菌的传播，从而降低烧心病的发生率。
### 模型训练
1. 开发环境搭建
```python
conda create -n agrima python=3.10
conda activate agrima
cd AgriMa
pip install -r requirements.txt
```
2. 指令集构建
* 按照[此说明](https://github.com/hiyouga/LLaMA-Factory/blob/main/data/README_zh.md)进行指令集构建；
* 如需获取AgriMa微调指令集，请发送邮件至zhiweihu@whu.edu.cn与我们联系。
3. 模型微调
```python
sh start_train.sh
```
* 需要首先下载预训练权重，如[Baichuan](https://huggingface.co/baichuan-inc)；
* 需要根据你的服务器地址修改对应的：LOG_PATH, OUTPUT_DIR, MODEL_NAME_OR_PATH地址；
4. Web页面测试
```python
sh start_web_demo.sh
```
* 需要修改model_name_or_path位置;

### 项目参与者
本项目由山西大学与山西农业大学联合开发完成

项目主要开发人员：[胡志伟](https://github.com/zhiweihu1103)、[闫智超](https://github.com/yzc111)、[马博翔](https://github.com/MattMaBX)

指导教师：李茹（教授）

若有相关使用需求或者相关数据集提供，欢迎与我们取得联系：zhiweihu@whu.edu.cn
### 致谢
1. 本项目基于现有开源项目二次开发，在此对相关项目和研发人员表示感谢。
* [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory)

2. 感谢PIXIU开发人员[黄济民](https://github.com/jiminHuang)给予技术上的交流与指导
* [PIXIU](https://github.com/The-FinAI/PIXIU)
## Star History
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=zhiweihu1103/AgriMa&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=zhiweihu1103/AgriMa&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=zhiweihu1103/AgriMa&type=Date" />
</picture>
