# Angular_note

小知識：Angular 使用 TypeScript ，但瀏覽器不懂 TypeScript，需先透過 CLI 編譯成 JS 才能呈現於瀏覽器。

如果開啟專案並打開 index.html 資料夾可以發現 app-root，這是 CLI 為我們自動生成、將所有 component (src/app中所有檔案)結合在一起的 root component。
```
<body>
  <app-root></app-root>
</body>
```

# 執行 Angular

啟動 Angular 時優先執行 main.ts，其中寫道platformBrowserDynamic().bootstrapModule(AppModule)，而 AppModule 作為參數傳遞 app.module.ts，此時讓 Angular 知道啟動時需要解析src/app底下的其他4個檔案，再將其運行至index.html。
![螢幕擷取畫面 2023-12-05 162506](https://github.com/yuchi0307/Angular_note/assets/67968321/852c363b-5cb6-4ca0-8868-e5f17fd074d3)
