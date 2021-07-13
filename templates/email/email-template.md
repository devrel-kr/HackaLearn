# email-template

이메일에 사용되는 템플릿 뼈대는 모두 동일하며, 절차마다 수정되어야하는 부분은 아래와 같다

- [x] `<img id ="banner" src="">`의 이미지 배너 링크 (적용 완료)
- [ ] `<tbody id="contents-body">`의 메일 내용 부분
    ``` html
    <div id="dear">
    ... 
    </div>

    <div id="list">
    ...
    </div>

    <div id="detail">
    ...
    </div>

    <div id="ending">
    ...
    </div>

    <div id="from">
    ...
    </div>
    
    <div id="button">
    ...
    </div>
    ```
    
---

1. 등록 확인

[email-template-1.html](email-template-1.html)

<img width="450" alt="banner-1" src="../banners/confirm-registration.png">

2. 제출 독려

[email-template-2.html](email-template-2.html)

<img width="450" alt="banner-2" src="../banners/keep-it-up.png">

3. 제출 진행 상황

[email-template-3.html](email-template-3.html)

<img width="450" alt="banner-3" src="../banners/work-in-progress.png">

4. 최종 제출

[email-template-4.html](email-template-4.html)

<img width="450" alt="banner-4" src="../banners/confirm-submission.png">

5. 수상 축하

[email-template-5.html](email-template-5.html)

<img width="450" alt="banner-5" src="../banners/congrats.png">
