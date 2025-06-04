---
layout: page
title: word-freq
permalink: /word-freq/
nav: true
nav_oder: 4
---

## 텍스트 입력

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<textarea id="textInput" type="text" placeholder="분석할 텍스트를 입력하세요."></textarea>

## 단어빈도시각화
<button onclick="updateChart()">제출</button>
<div style="width: 400px; height: 400px;">
        <canvas id="myChart"></canvas>
</div>
<script src="/assets/js/word-freq.js"></script>