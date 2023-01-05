3. 추가한 내용 커밋 후 편집 
    1. 코드 가장 상단에 대제목 및 설명 부분을 설정하기 위한 코드 추가하여 알맞게 수정
        
        ```html
        ---
        description: ~~~ 메뉴얼이에요.
        ---
        
        # 대제목
        ```
        
        ![4.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3c8b16ec-8781-4d1e-95de-9f77b56dce2c/4.png)
        
    2. 이미지 교체 
        
        → MD 파일로 복사된 기존 이미지 코드는 그대로 업로드하면 보이지 않으므로
        
        → 3에서 업로드한 이미지의 경로 + 이름으로 코드를 아래와 같이 수정
        
        ```html
        <figure><img src=".Assets/Manual_Gitbook_20230105(1).png" alt=""><figcaption></figcaption></figure>
        ```
        
        <figure> … <figcaption></figcaption></figure>
        
        이게 있으면 이미지 전체 채우기 / 없으면 원본 크기로 업로드됨
        
    3. 커밋 후 gitbook에서 확인

### 결과

- GitHub에서 이미지 이름으로 연결 후 GitBook에서 확인하면 잘 올라가 있음 !
- 노션 Enter로 생긴 빈칸?은 복사가 되지 않는 것 같아서 정렬은 손으로..
- Summary 는 **GitBook** 에서 한번 Edit 후 Merge 해야 GitHub에 생김
    
    → 갱신은?
    

### 그래서 수동으로 확인 필요한 점

1. 이미지는 대부분 채우기 형태로 업로드 하는데, 간혹 원본으로 업로드 되어야하는 이미지가 있는지 수동으로 확인 필요
2. 1, 2, 3 처럼 순서가 있는 리스트의 경우 하위에 있는 이미지 들여쓰기가 되어있는지 확인 필요
    
    ![5.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f7389daf-ab7f-4d3d-8cd8-a28de42644da/5.png)
    
3. 노션에서 복사 시, Enter로 생긴 빈칸?은 복사가 되지 않는 것 같아서 정렬은 손으로.. 

### GitBook 에서 따로 수정 필요한 부분들

1. 표 개행? 이 안예쁠 때는 깃북으로 수정
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6623a7a-bdaf-4df5-ad4f-119a35507974/Untitled.png)