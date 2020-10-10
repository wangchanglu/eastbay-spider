# eastbay-spider
    1. 通过 scrapy 实现网页信息爬取和采集。
    2. 通过提供的列表页网址（https://www.eastbay.com/category/sale.html?query=sale%3Arelevance%3AstyleDiscountPercent%3ASALE%3Agender%3AMen%27s%3Abrand%3AASICS+Tiger）采集到详情页的信息。
    3. 爬取结果存成一份 JSON文档。
    4. JSON文档要求： 主要信息（标题（title） 价格(price) 颜色(color) 尺码(size) 网站货号(sku) 详情(details) 大图的URL (img_urls)，其它字段随意
    5. 通过设置代理服务器池，增加访问成功率

   注意：网站周五下午可能维护。所以有可能打不开。其他时间段都正常。

