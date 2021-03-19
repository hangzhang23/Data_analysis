# 数据分析思想

- 用户画像

用户画像是通过分析用户的基础信息、特征偏好、社会属性等各维度的数据，刻画出用户的信息全貌，从中挖掘用户价值，从而提供个性化推荐、精准营销等服务。一般会把用户标签分为如下三种类型
  - **统计类标签**：这类标签是最为基础也最为常见的标签类型，例如：对于某个用户来说，其姓名、性别、年龄、地市、活跃时长等，这类数据可以从用户注册数据、用户消费数据中得出，该类数据构成了用户画像的基础。
  - **规则类标签**：基于用户的行为以及规则，在实际开发画像的过程中，由于运营人员对业务更为熟悉，而数据人员对数据的结构、分布、特征更为熟悉，因此规则类标签的规则由运营人员和数据人员共同协商确定。
  - **学习挖掘类标签**：通过机器学习挖掘产生，根据用户的行为和规则进行预测和判断。比如某个用户检查购买卫生巾，我们可以通过这个行为来推出用户性别为女性。

用户画像的价值在于：

  - **用户引渡**：通过现有用户的画像分析，在相关DMP广告平台做投放，重点推荐其平台上具有相关类似标签的用户，为产品做用户引流，这里用的是相似用户快速扩量的概念。
  - **新用户冷启动**：快速分析新注册用户可能偏向的属性和兴趣偏好，实现服务快速精准推荐，例如用户注册地所在区域，可以通过该区域用户的通用标签推测该新用户的特征。
  - **精准或个性化服务**：这里就是根据丰富的用户画像分析，理解用户并提供精准服务或个性化服务。提供好的服务自然能做到用户的深度沉淀。
  - **多场景识别**：这里就是根据丰富的用户画像分析，理解用户并提供精准服务或个性化服务。提供好的服务自然能做到用户的深度沉淀。
  - **沉默用户唤醒**：基于精细化的标签和多个场景数据，对用户的沉默程度做快速识别，基于画像分析制定运营策略进行激活召回减少用户流失。

对应有一个电商数据用户画像分析，用了一个脱敏的电商用户数据，需要对家电类产品做一些促销活动。所以在这里用了用户画像的思想，通过对促销手中，上线时间，覆盖产品等做分析，得到一些结论可提供给促销计划使用。