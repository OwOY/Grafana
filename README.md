<img src="https://fromideatocreation.com/wp-content/uploads/2022/05/headimg-930x300.jpg">

----
# Intro
Grafana 是一個開源的分析與監控解決方案支援很多資料來源。
具備豐富的面板選擇，除了基本文字、圖表、表格等，管理者亦可使用如甘特圖、流程圖等面板來顯示所監控的資料及訊息，並可由管理者自行調整顯示資料的色彩。
Grafana 的另一個便利特點是可將監控的頁面儲存成樣板，若輸入的資料來源相同，有新的主機上需安裝 Grafana 平台時，只需匯入樣版即可。
<br><br>
# 使用方法
### 安裝
- docker
```
docker run -d --name grafana -p 3000:3000 grafana/grafana
```
### 完成
1. 完成上述設定後可從 localhost:3000 看到此登入頁面
![image.png](/grafana/1.png)
2. 登入(預設帳號:admin, 密碼:admin)
3. 進入設定頁面
![image.png](/grafana/2.png)
4. 選擇套版(可至[Grafana官網](https://grafana.com/grafana/dashboards/)選擇喜歡的版面)，按下Load
![image.png](/grafana/3.png)
5. 完成
![image.png](/grafana/4.png)

----
# 參考文件
- https://ithelp.ithome.com.tw/articles/10222742
- https://sectools.tw/docker-monitor/
- [Grafana官網](https://grafana.com/grafana/dashboards/)
