## **Let's promote Korea!**
![영상1](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/%EC%98%81%EC%83%811.gif)

주제는 "대한민국을 알리자!"로 대한민국의 아름다운 전통과 상징들을 알려주는 반응형웹페이지를 만들어보았다😊

Language: `html`, `css`
## 프로젝트설명

### 코드 내용 설명

#### HTML 코드

1. **기본 설정**:
![html 사진(1)](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/html%20%EC%82%AC%EC%A7%84(1).png)
    - `<!DOCTYPE html>`: HTML5 문서 타입을 선언.
   - `<html lang="ko">`: 문서의 언어를 한국어로 설정.
   - `<meta charset="UTF-8">`: 문서의 문자 인코딩을 UTF-8로 설정.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: 뷰포트 설정으로 반응형 웹 디자인 지원.
   - Google Fonts에서 "Nanum Myeongjo" 글꼴을 불러와 사용합니다.

2. **페이지 구조**:

    ![html 사진(2)](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/html%20%EC%82%AC%EC%A7%84(2).png)
   - 상단에 대한민국을 소개하는 이미지 삽입.
   - 네비게이션 바를 통해 다양한 링크 제공.
---
    
![html 사진(3)](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/html%20%EC%82%AC%EC%A7%84(3).png)
   - 텍스트 상자를 통해 대한민국의 국기 정보를 제공.
---
   ![html 사진(4)](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/html%20%EC%82%AC%EC%A7%84(4).png)
   - 원형 이미지를 통해 대한민국을 상징하는 이미지 제공.
---
 ![html 사진(5)](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/html%20%EC%82%AC%EC%A7%84(5).png)
   - 배경 이미지와 정보 상자를 통해 다양한 대한민국 문화 요소 소개.
   - 동일하게 적성 
---
![영상3](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/%EC%98%81%EC%83%813.gif)


**-> 요게 html만 넣은 모습입니다😶‍🌫️**


![영상2](https://github.com/junhee23314/Let-s-promote-Korea/blob/main/Let's%20promote%20Korea_%EC%9E%90%EB%A3%8C/%EC%98%81%EC%83%812.gif)
__[텍스트 상자 & 정보 상자]__
링크를 걸어 클릭 시 해당 사이트로 이동_






#### CSS 코드

1. **글로벌 스타일**:
   - 모든 요소에 기본 폰트와 스타일 설정.
   - 리스트 스타일과 텍스트 장식을 제거하고, 여백과 패딩을 0으로 설정.
```
    *{
  font-family: "Nanum Myeongjo", serif;
  font-weight: 400;
  font-style: normal;
  list-style: none;
  text-decoration: none;
  border-collapse: collapse;
  margin: 0px;
  padding: 0px;
  color:#000;
}
```

2.**이미지 컨테이너**:
-img-container 클래스: 이미지 컨테이너의 너비를 뷰포트 너비의 100%, 높이를 뷰포트 높이의 60%로 설정.
```
.img-container {
  width: 100vw;
  height: 60vh;
  
}

---------------------------------------------------------------------
vw(viewport width), vh(viewport height) 사용
%가 부모 요소의 길이를 기준으로 계산된다면,
vw, vh는 뷰포트의 길이를 기준으로 계산.

각각 뷰포트 가로길이의 몇% 인지와 세로길이의 몇% 인지를 적어주면 됩니다.
뷰포트란 해당 웹페이지를 실행하고 있는 기기(노트북, 스마트폰 등)의 화면크기를 말한다.
```

3. **링크 스타일**:
   - `ap` : 배경색과 텍스트 색상, 폰트 크기 설정.
```
.ap {
  background-color: #FFFFE0;
  color: darkslategray ;
  font-size: 1.3em;
  text-decoration: none;
}

```


4. **배경 이미지**:
   - `bg-image`와 `bg_image2` 클래스: 각각 다른 배경 이미지를 설정.
```
.bg-image{
  background-image:url("image/뒷배경.jpg  ")
  
}

.bg_image2{
  background-image:url("image/뒷배경_.jpg  ")
}
```

5. **헤더와 네비게이션**:
   - `header` 클래스: 페이지 상단의 헤더 스타일 설정.
   - `nav`와 `nav ul li a` 클래스: 네비게이션 바와 링크 스타일 설정.
```
.header{
  width : 100%;
  height : 80px;
  background-color : blue;
  color :#ffffff;
  text-align : center;    
  line-height: 80px;
  
}

.nav{
  width : 100%;
  height : 40px;
  background-color : #D8C8B2;
  color :#ffffff;
  line-height: 40px;

}

nav ul li  a{
    float : left; padding : 0 10px;
  
  }     
```


6. **텍스트 상자**:
   - `text-box` 클래스: 국기 정보를 담는 상자의 스타일 설정.
```
.text-box {
   border: 5px;
   border-radius: 5px;
   padding: 30px;
   float: right;
   margin: 15px;
   margin-right: 300px;
   background-color: #ffffff;
}

```

7. **원형 이미지**:
   - `circle-image`와 `profile` 클래스: 원형 이미지와 프로필 이미지 스타일 설정.
```
.circle-image {
    
    width: 150px;
    height: 150px; 
    border-radius: 70%;
    overflow: hidden;

  }
.profile {
  
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

8. **정보 상자**:
   - `box`, `box2`, `box3`, `box4`, `box5` 클래스: 각각 다른 배경색과 스타일을 가진 정보 상자 설정.
```
.box{
    
  width: 300px;
  background-color: #DDE7E7;
  margin-left: 10px;
  padding: 20px;
  border-radius: 5px;
  margin-left: auto;
  margin-right: auto;
  color: white;
  text-align: center;
   
}

--- `box2`, `box3`, `box4`, `box5`도 background-color만 바뀌고 나머지는 동일. ---
```
### 핵심 내용 요약

1. **HTML 기본 구조**:
   - 문서 타입, 언어, 문자 인코딩, 뷰포트 설정.
   - 외부 리소스 (Google Fonts, CSS 파일) 불러오기.

2. **페이지 레이아웃**:
   - 상단 이미지, 네비게이션 바, 텍스트 상자, 원형 이미지, 정보 상자들로 구성.

3. **CSS 스타일**:
   - 기본 폰트와 스타일, 링크 스타일, 배경 이미지, 헤더와 네비게이션 바 스타일.
   - 텍스트 상자와 원형 이미지 스타일.
   - 정보 상자 스타일 (다양한 배경색 사용).


![ClipWindowsGIF](https://github.com/junhee23314/Let-s-promote-Korea/assets/127848243/8269a124-68b8-44c5-94d6-1b3f103f0c89)



