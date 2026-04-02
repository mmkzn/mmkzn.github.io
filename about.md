---
layout: default
title: 关于我
---

<main class="main-content">
    <div class="container">
        <div class="about-card">
            <div class="about-header">
                <div class="about-avatar">
                    <img src="{{ site.avatar }}" alt="{{ site.author }}">
                </div>
                <h1 class="about-name">{{ site.author }}</h1>
                <p class="about-bio">欢迎来到我的小天地 🌸</p>
            </div>

            <div class="about-content">
                <section class="about-section">
                    <h2>🎯 关于这个博客</h2>
                    <p>这是一个用 Jekyll 搭建的二次元风格个人博客。主要分享一些技术笔记、生活感悟和兴趣爱好。</p>
                </section>

                <section class="about-section">
                    <h2>💻 技术栈</h2>
                    <div class="skill-tags">
                        <span class="skill-tag">编程</span>
                        <span class="skill-tag">Web开发</span>
                        <span class="skill-tag">二次元</span>
                    </div>
                </section>

                <section class="about-section">
                    <h2>🎮 兴趣爱好</h2>
                    <ul class="hobby-list">
                        <li>✈️ 旅行探索</li>
                        <li>🎵 听音乐</li>
                        <li>📚 阅读</li>
                        <li>🎮 游戏</li>
                    </ul>
                </section>

                <section class="about-section">
                    <h2>📬 联系方式</h2>
                    <p>欢迎通过以下方式联系我：</p>
                    <div class="contact-links">
                        <a href="https://github.com/{{ site.github_username }}" target="_blank" class="contact-link">
                            GitHub
                        </a>
                    </div>
                </section>
            </div>
        </div>
    </div>
</main>
