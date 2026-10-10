文件说明：
1、图表代码.txt
  - 这个记事本中的内容，可以直接复制到ECharts官方编辑器中运行查看效果
  - 拷贝到ECharts for PowerBI中后，替换第1部分的示例数据即可
  - 官方编辑器地址：https://echarts.apache.org/examples/zh/editor.html?c=line-simple

2、图表代码 v1.0 与 v1.1 的区别
  - 在v1.1版本中，增加了事件卡片控制参数，可以控制是否显示，以及显示哪些数据
  - 对应代码如下：
// ===== 商业事件注释配置：数组可添加任意多个条目 =====
// 这里的对象数组仅用于注释配置，不属于 Power BI 原始数据。
// enabled=false 隐藏单条注释；总开关 false 隐藏所有注释。
const showAnnotations = true;
const annotations = [
  {
    enabled: true,
    year: '2020',
    title: '疫情冲击',
    reason: '新冠疫情影响影院营业和影片上映，\n全年票房同比大幅下降。'
  },
  {
    enabled: true,
    year: '2023',
    title: '市场恢复',
    reason: '影院经营及影片供给逐步恢复，\n全年票房较上年显著回升。'
  }
];
