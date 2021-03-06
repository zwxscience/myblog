---
layout: titled
nocomment: true
title: 来人，给红包
subtitle: 给 weixiang 打赏点书资吧，让他写出更棒的文章！
---

{% include follow.html %}

Hi,我是 weixiang ，英文名<strong>Xavier</strong>，目前从事通信行业。
至于为什么学计算机的转战通信，那就是另外一个千里随妻的故事了。
可能我读书时的快乐比别人更强吧，似乎从小就喜欢看书。
自从识字后，似乎每个寒暑假里，都是抱着从别人那里借来的书看，因为那时资源有限，看的也是五花八门。
读到好书欣然起舞，甚至要逐字逐句的读出来，不知翻了多少遍；
读到文笔差些的书，有时嫌弃的看不下去了，因为没别的书看，也是只能忍着恶心看完。
在高中，因为课业压力，很少有时间看些闲书。俗话说，压抑久了，人也就变态了。
到了大学，看到图书馆那么多书，就像鱼进了大海，恨不得每天都要抱着睡。
及至后来，有了手机之后，发现手机也可以看唉，整个人就不行了，吃饭也抱着手机，睡觉也抱着手机。
回想起来，这也可能是我考研失利的一个原因。后来离开了校园，进了知网，那也是有很多书看的，似乎我的一生总是伴着它呀！


正如首页所说明的，好读书，不求甚解。
因为许多书都是粗粗一读，因此我每年的读书量还是挺大的。
以前还不觉得，近期买了Kindle之后，我所有的读书记录都能在亚马逊上能查到，稍微统计了一下如下表所示。

<div id="reading-chart" style="height: 400px"></div>

在平时我就喜欢在各个论坛和贴吧上搜书，都存在我的百度网盘上面，大约有<strong class="text-xlarge">200G</strong>的数据量，大都是支持kindle格式的书籍。
网盘好像对大数据量的分享链接都是很短暂，有需要的话私信或者发邮件给我，我免费share给你们。

每本书不管好坏，都凝聚了作者的日夜的心血。但是这么多书，我肯定不能全买正版的啊:cry:。
所以看书时一面抱有很强的负罪感，另一方面暗地安慰自己说就权当借书看了，书非借不能读也。
我当然是想支持他们，所以我每年还是会买一批书来看，买的书技术类的还是占多数的，没办法，为了能将来拿更多的money～

所以，如果你愿意贡献一份书资的话，weixiang 在这里先行谢过啦！

自2016年2月份开始我娃就来到杭州啦，因此身上多担负了一份奶爸的责任。
看书的时间也大大减少了，但这并不影响我看书的热情，我会抽空忙先继续的！最后送上一张近期萌娃照吧。

<img src="{{ site.loadingImg }}" data-src="http://blog.zhangweixiang.com/img/mybaby.jpg" />

### 附小诗一首

> 我是什么时候爱上读书的呢？
> 

> 应该是春天，
> 
> 萌芽将将从斜坡上探出头来，
> 
> 小羊咩咩在跟前吃草，
> 
> 刚下过雨的泥土传来一阵阵清香，
> 
> 我坐在石头上拿着书，
> 
> 那种感觉真好。
> 

> 应该是夏天，
> 
> 外面乌云闪电，
> 
> 雨水从窗沿上成串滴下，
> 
> 落在院子里的桶上叮咚叮咚，
> 
> 我躺在床上看着书，
> 
> 那种感觉真好。
> 

> 应该是秋天，
> 
> 黄昏时候太阳一点也不刺眼，
> 
> 照在秸垛发出金色的光，
> 
> 风吹来都是暖融融的，
> 
> 远处传来一阵阵嬉闹，
> 
> 我斜倚在上面端着书，
> 
> 那种感觉真好。
> 

> 应该是冬天，
> 
> 外面呜呜寒啸，
> 
> 屋里烟囱烧得通红烟火正旺，
> 
> 小猫咪趴在我腿上，
> 
> 蜷作一团发出一阵呼噜，
> 
> 我坐在沙发上捧着书，
> 
> 那种感觉真好。
>


# 打赏方式

## 方法一：微信识别二维码发红包

<img src="{{ site.loadingImg }}" data-src="http://blog.zhangweixiang.com/img/mm_facetoface_collect_qrcode_1455414545364.png" />

## 方法二：支付宝扫一扫

<img src="{{ site.loadingImg }}" data-src="http://blog.zhangweixiang.com/img/zhifubao.jpg" style="max-width: 500px;"/>

## 方法三：转账到我的支付宝账号

`zwxscience@163.com`




<script type="text/javascript">
 var loadJs = [['{{ site.url }}/js/echarts-all.js', function() {
        // init echarts
        var chart = echarts.init($('#reading-chart')[0]);
        chart.setOption({
            tooltip: {
                trigger: 'value'
            },
            legend: {
                data:['2015', '2016', '2017']
            },
            grid: {
                x: 40,
                x2: 40,
                y: 40
            },
            calculable: true,
            xAxis: [{
                type: 'category',
                data: ['1月', '2月', '3月', '4月', '5月', '6月',
                        '7月', '8月', '9月', '10月', '11月', '12月'],
                axisLine: {
                    show: false
                }
            }],
            yAxis: [{
                type: 'value',
                axisLine: {
                    show: false
                }
            }],
            series: [{
                name: '2015',
                type: 'bar',
                data: [0, 0, 0, 0, 0, 0, 0, 14, 9, 13, 12, 10],
                itemStyle: {
                    normal: {
                        color: '#D0648A'
                    }
                },
                markPoint: {
                    data: [{
                        type: 'max', 
                        name: '最大值'
                    }, {
                        type: 'min',
                        name: '最小值'
                    }]
                },
                markLine: {
                    data: [{
                        type: 'average',
                        name: '平均值'
                    }]
                }
            }, {
                name: '2016',
                type: 'bar',
                data: [5, 3, 5, 4, 3, 4,5, 3, 4,2,3,3],
                itemStyle: {
                    normal: {
                        color: '#3c78d8'
                    }
                },
                markPoint: {
                    data: [{
                        type: 'max', 
                        name: '最大值'
                    }, {
                        type: 'min',
                        name: '最小值'
                    }]
                },
                markLine: {
                    data: [{
                        type: 'average',
                        name: '平均值'
                    }]
                }
            }, {
                name: '2017',
                type: 'bar',
                data: [3, 3, 2, 4, 3, 5,4,3, 3,2,4,3],
                itemStyle: {
                    normal: {
                        color: '#FFEC8B'
                    }
                },
                markPoint: {
                    data: [{
                        type: 'max', 
                        name: '最大值'
                    }, {
                        type: 'min',
                        name: '最小值'
                    }]
                },
                markLine: {
                    data: [{
                        type: 'average',
                        name: '平均值'
                    }]
                }
            }//end of last year
            ]
        });

        $(window).resize(chart.resize);
    }]];
</script>
