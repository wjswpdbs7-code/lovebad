
- `records.html`
- `home.html`
- `profile_edit.html`

/* 공통 Body 스타일 */
```css
/* 전체 배경*/
body {
    background-color: #f7f9fc; 
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
}

/* 메뉴바 */
.menu {
    margin-top: 50px;
    display: flex;
    justify-content: space-around; 
    align-items: center;
    width: 90%;
    max-width: 400px;
    background-color: white;       
    padding: 15px;                 
    border-radius: 20px;          
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
    margin-bottom: 30px;
}

/* 메뉴 이미지 아이콘 설정 */
.menu img {
    margin: 0 10px;
    cursor: pointer;
}

    <!-- 통일된 하단 메뉴바 (body의 직계 자식으로 배치) -->
    <div class="menu">
        <img class="home" src="img/home.png" alt="홈" width="30" height="30">
        <img class="records" src="img/pen.png" alt="기록" width="30" height="30">
        <img class="game" src="img/game.png" alt="게임" width="30" height="30">
        <img class="setting" src="img/setting.png" alt="설정" width="30" height="30">
    </div>
</body>
```

```css
/* 컨텐츠 박스 공통 속성 예시 */
.container, div.records, .profile-container {
    background-color: white;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
    padding: 30px ~ 40px;
}
```