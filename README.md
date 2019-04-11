# speedoops.github.io

---
title: test_markdown_tablesdd
date: 2019-04-11 22:36:07
tags:
---

dkddk #layout > div:nth-child(1) > div > div > div.post-content > table > thead > tr > th:nth-child(1)


<style>
table th:first-of-type {
	width: 15%;
}
table th:nth-of-type(2) {
	width: 35%;
}
table th:nth-of-type(3) {
	width: 35%;
}
table th:nth-of-type(4) {
	width: 15%;
}
</style>

| 对比项 | Hexo                     | Jekyll                   | 小结 |
| ---- | ------------------------ | ----------------------- | ------------------------------ |
| 语言 | nodejs                   | ruby                     | Hexo优 |
| 速度 | 生产静态站点的速度非常快 | 随着网站内容增加越来越慢         | Hexo优 |
| 效率 | 本地环境生成html后再上传 | markdown上传github后可以直接生成html，可以使用github的在线编辑器在线编辑修改文章 |Jekyll优|

<hr/>
嵌入HTML时要写在一整行，否则会导致一堆`<p>`或`<br>`换行
<div id="content_views" class="markdown_views">
<table>
    <tr>
        <th>第一列</th>
        <th>第二列</th>
        <th>第三列</th>
        <th>第四列</th>
    </tr>
    <tr>
        <td rowspan="3" bgcolor="Hotpink"><font color="DodgerBlue">我占了三行</font></td>
        <td>第一列</td>
        <td>第二列</td>
        <td>第三列</td>
    </tr>
    <tr>
        <td>第一列</td>
        <td>第二列</td>
        <td>第三列</td>
    </tr>
    <tr>
        <td>第一列</td>
        <td>第二列</td>
        <td>第三列</td>
    </tr>
    <tr>
        <td>第一列</td>
        <td>第二列</td>
        <td>第三列</td>
        <td>第四列</td>
    </tr>
</table>
</div>

<style>
# 摘自csdn
.markdown_views > br {
	display: none;
}

.markdown_views table {
    border-collapse: collapse;
    display: table;
    width: 100%;
    text-align: center;
    margin-bottom: 24px
}
.markdown_views tbody {
    border: 0
}
.markdown_views table tr {
    border: 0;
    border-top: 1px solid #ddd;
    background-color: #fff
}
.markdown_views table tr:nth-child(2n) {
    background-color: #f7f7f7
}
.markdown_views table tr td, .markdown_views table tr th {
    font-size: 14px;
    color: #4f4f4f;
    line-height: 22px;
    border: 1px solid #ddd;
    padding: 8px;
    word-break: normal!important;
    vertical-align: middle
}
.markdown_views table tr td code, .markdown_views table tr th code {
    white-space: normal;
    word-break: normal!important
}
.markdown_views table tr th {
    font-weight: 700;
    background-color: #eff3f5
}
</style>
