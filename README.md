# 目錄
<ul>
  <li>運作流程</li>
</ul>


# Angular 運作流程<br/>
<h3> index.html > main.js > app.module.ts > app.component.ts </h3><br/>

Angular 是模組(NgModule)為基礎的高度元件框架，模組內還可以有其他模組，執行時只會有一個始組模組(巨人)，始組巨人通常是但並非總是 AppModule。

![angulr01](https://github.com/yuchi0307/Angular_note/assets/67968321/f45141e3-0a50-460b-82d8-f4c6cbc14f67)

在 main.ts 中有 AppModule ，打開 app.module.ts 可見 bootstrap 屬性指定 AppComponent 為起始元件。

Anguler 透過元件呈現介面，元件又依附組件，一班來說會在起始模組中指定起始元件。

![螢幕擷取畫面 2023-12-06 101901](https://github.com/yuchi0307/Angular_note/assets/67968321/9f10f970-ab5a-4680-89ce-37ab0d0016bc)

@Component 裝飾器將 AppComponent 化為一個 Angular Component 並設定 html, css屬性，將網頁包含有 app-root 的標籤都替換成 ./app.component.html。

![螢幕擷取畫面 2023-12-06 101939](https://github.com/yuchi0307/Angular_note/assets/67968321/b4d094f2-1c6d-4c96-8e29-0e7cfd55da9f)
