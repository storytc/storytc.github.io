---
permalink: /resources
title: "Resources"
author_profile: true
redirect_from: 
  - /resources/
  - /resources.html
---

<style>
.project-section {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
}

.section-main-title {
    text-align: center;
    margin-bottom: 30px;
    font-size: 1.8rem;
    color: #2c3e50;
}

/* 卡片容器 */
.project-card {
    display: flex;
    flex-wrap: wrap; /* 手机端自动换行 */
    background: #fff;
    border-radius: 16px;
    overflow: hidden; /* 确保图片圆角 */
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    border: 1px solid #f0f0f0;
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-8px);
}

/* 图片区域 */
.project-image {
    flex: 1 1 400px; /* 电脑端占据一定宽度，手机端自动变宽 */
    background: #f8f9fa;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* 保证图片填满容器不拉伸 */
    transition: transform 0.5s ease;
}

.project-card:hover .project-image img {
    transform: scale(1.05); /* 悬停图片微放大 */
}

/* 内容区域 */
.project-content {
    flex: 1 1 350px;
    padding: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.project-badge {
    background: #007bff;
    color: white;
    padding: 4px 12px;
    border-radius: 20px;
    font-size: 12px;
    width: fit-content;
    margin-bottom: 15px;
}

.project-title {
    margin: 0 0 15px 0;
    font-size: 1.6rem;
    color: #333;
}

.project-description {
    color: #666;
    line-height: 1.7;
    margin-bottom: 20px;
}

/* 技术栈标签 */
.tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 25px;
}

.tech-stack span {
    background: #f1f3f5;
    color: #495057;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 13px;
    font-family: monospace;
}

/* 访问按钮 */
.visit-btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: #333;
    color: #fff !important;
    padding: 12px 24px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    width: fit-content;
    transition: background 0.3s;
}

.visit-btn:hover {
    background: #007bff;
}

/* 响应式调整 */
@media screen and (max-width: 768px) {
    .project-image {
        height: 250px; /* 手机端固定图片高度 */
    }
    .project-content {
        padding: 20px;
    }
}
</style>


<section class="project-section">
    <h2 class="section-main-title">🌟 Representative Work</h2>
    
    <div class="project-card">
        <div class="project-image">
            <img src="/assets/images/project-screenshot.png" alt="Project Screenshot">
        </div>

        <div class="project-content">
            <div class="project-badge">Featured Tool</div>
            <h3 class="project-title">Single-cell Multi-omics Portal</h3>
            <p class="project-description">
                这是一个交互式的多组学可视化平台。我们整合了超过 10 万个造血干细胞样本数据，支持用户在线进行差异表达分析、细胞轨迹推断以及基因调控网络的可视化。
            </p>
            
            <div class="tech-stack">
                <span>R Shiny</span>
                <span>Python</span>
                <span>D3.js</span>
                <span>Docker</span>
            </div>

            <a href="https://your-project-link.com" target="_blank" class="visit-btn">
                Visit Website 
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
            </a>
        </div>
    </div>
</section>
