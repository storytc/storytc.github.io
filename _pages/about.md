---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 容器：限制宽度并居中 */
.custom-card-container {
    max-width: 800px;
    margin: 20px auto;
    padding: 0 15px; /* 移动端防止贴边 */
}

/* 卡片主体 */
.my-card {
    background: #ffffff;
    border-radius: 12px;           /* 圆角 */
    padding: 25px;
    margin-bottom: 25px;           /* 卡片间距 */
    border: 1px solid #f0f0f0;     /* 浅色边框 */
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05); /* 微弱阴影 */
    transition: all 0.3s ease;     /* 动画过渡 */
    display: block;                /* 强制独占一行 */
    width: 100%;
    box-sizing: border-box;
}

/* 鼠标悬停效果：向上浮起，阴影加深 */
.my-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
    border-color: #007bff;         /* 悬停时边框变蓝 */
}

/* 内部装饰 */
.card-tag {
    display: inline-block;
    padding: 4px 10px;
    background: #e7f3ff;
    color: #007bff;
    font-size: 12px;
    border-radius: 5px;
    margin-bottom: 15px;
}

.card-title {
    margin: 0 0 10px 0;
    font-size: 1.4rem;
    color: #333;
}

.card-desc {
    color: black;
    line-height: 0.4;
    font-size: 1rem;
    margin-bottom: 15px;
}

.card-footer {
    font-size: 0.9rem;
    color: #999;
    border-top: 1px solid #fafafa;
    padding-top: 10px;
}

/* 1. 大容器设置 */
.side-by-side-container {
    display: flex;          /* 开启弹性布局 */
    flex-wrap: wrap;        /* 关键：空间不足时自动换行 */
    gap: 20px;              /* 两个盒子之间的间距 */
    width: 100%;
    margin: 20px 0;
}

/* 2. 两个小盒子的基础样式 */
.info-box {
    flex: 1;                /* 默认在有空间时平分宽度 */
    min-width: 300px;       /* 关键：当屏幕宽度小于这个值时，强制换行 */
    background: #ffffff;
    padding: 20px;
    border-radius: 12px;
    border: 1px solid #eee;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

/* 3. 内部文字排版 */
.info-title {
    margin-top: 0;
    color: #007bff;
    border-bottom: 2px solid #e7f3ff;
    padding-bottom: 8px;
    font-size: 1.25rem;
}

.info-list {
    list-style: none;       /* 去掉默认圆点 */
    padding-left: 0;
    margin-bottom: 0;
}

.info-list li {
    margin-bottom: 10px;
    line-height: 1.5;
    color: #444;
    position: relative;
    padding-left: 15px;
}

/* 自定义小圆点 */
.info-list li::before {
    content: "•";
    color: #007bff;
    font-weight: bold;
    position: absolute;
    left: 0;
}
</style>

<p style='font-size:1rem;text-align:justify;line-height:1.5'>Greetings! I'm currently a final-year Ph.D. student at Peking Union Medical College, specializing in stem cell biology and computational biology. My research focuses on unraveling hematopoietic stem cell heterogeneity and its cell fate choices governed by epigenetic modifications, including DNA methylation and chromatin accessibility. My long-term goal is to understand complex biological systems utilizing computational methods.</p>



<div class="side-by-side-container">
    
    <div class="info-box">
        <h3 class="info-title">🎓 Education</h3>
        <ul class="info-list">
            <li><strong>2023-2026:</strong> Ph.D. in Stem Cell and Regenerative Medicine, PUMC</li>
            <li><strong>2020-2023:</strong> M.S. in Stem Cell and Regenerative Medicine, PUMC</li>
            <li><strong>2016-2020:</strong> B.S. in Clinical Pathology, Hebei Meidican University</li>
        </ul>
    </div>

    <div class="info-box">
        <h3 class="info-title">🔬 Research Interests</h3>
        <ul class="info-list">
            <li>Single-cell epigenetics/genomics</li>
            <li>Lineage tracing and cell dynamics</li>
            <li>Deep learning in genomics</li>
	    <Li>Generative models</li>
        </ul>
    </div>

</div>


## Publications

<div class="custom-card-container">
     <div class="my-card">
        <div class="card-tag">Education</div>
        <ul><li><p class="card-desc">2023-2026, Ph.D. Stem Cell and Regenerative Medicine, PUMC.</p></li></ul><br>
	<ul><li><p class="card-desc">2020-2023, M.S. Stem Cell and Regenerative Medicine, PUMC.</p></li></ul><br>
	<ul><li><p class="card-desc">2016-2020, B.S. Clinical Pathology, Hebei Medical University.</p></li></ul>
    </div>

    <div class="my-card">
        <div class="card-tag">Research Interests</div>
        <ul><li><p class="card-desc">Single-cell epigenetics/genomics</p></li></ul><br>
        <ul><li><p class="card-desc">Single-cell epigenetics/genomics</p></li></ul><br>
        <ul><li><p class="card-desc">Single-cell epigenetics/genomics</p></li></ul>
    </div>

</div>



