# MARKDOWN_20250714
MARKDOWN_20250714

### 10. 체크리스트
`[ ] 또는 [x]를 사용하여 체크 박스 생성`  
- [ ] : 미완료 작업  
- [x] : 완료 작업  
### 9. 표
`|와 -, :(정렬)를 사용하여 테이블을 작성합니다.
|헤더1|헤더2|헤더3|
|:-----------------|:-----------------:|-----------------:|
|데이터1,1789|데이터1,2456|데이터1,3777789|
|데이터1,1|데이터2,1|데이터3,1|
|데이터1,1|데이터2,1|데이터3,1|

### 8. 이미지
`이미지 ![이미지 텍스트](이미지URL)`
![레이아웃](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/layout.png)


### 7. 강조(Emphasis)
- Bold: **텍스트** 또는 __텍스트__
- Italic: *텍스트* 또는 _텍스트_
- Bold + Italic: ***텍스트***

### 6. 링크(Link)
`[링크텍스](URL)형태로 작성합니다.`

[PCWK Daum](https://cafe.daum.net/pcwk)

**같은 페이지 내 하이퍼 링크: commit이후 link 생성(단 prieview에서는 링크 안됨.)**
[여기](#3-인용상자)

### 5. 목록
**순서 있는 목록**
1. 아이템1  
2. 아이템2  
   2.1 1단계 하위 아이템  
   2.2 2단계 하위 아이템
---
***
**순서 없는 목록**  
- 아이템1  
+ 아이템2  
  -단계 하위 아이템  
  -2단계 하위 아이템  
* 아이템3 


### 4. 코드블록
**인라인 코드**  
`System.out.println("Hello, world!);`  

**코드 블록**
```java
public class Hello {

	public static void main(String []args){
		//console : "Hello, world!" 메시지 출력
		System.out.println("Hello, world!");
	}
}
```

### 3. 인용상자
>여기에 인용할 내용을 넣으면 됩니다.  
>빈 줄이 없으면 자동으로 인용 상자에 포함됩니다.
식사 맛나게 하셨나요?

### 2. 제목(heading)
>제목은 # 기호를 사용하여 작성합니다. #의 갯수로 제목의 수준(1~6)을 나타냅니다.
# H1제목
## H2제목
### H3제목
#### H4제목
##### H5제목
###### H6제목

### 1. 문단개행
여름 바다를 걸어 보아요.  
(너무 더워요)
개행 : SPACE 2개

#4-코드


### 4. 프로젝트 수행결과(이미지)  

- 메인페이지  
![메인페이지](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A9%94%EC%9D%B8.png)  

- 로그인 및 아이디 찾기/ 비밀번호 찾기(암호화된 비밀번호 이메일로 전송)  
![로그인](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
![아이디 찾기](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EC%95%84%EC%9D%B4%EB%94%94%EC%B0%BE%EA%B8%B0.png)
![비밀번호 찾기](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%B9%84%EB%B0%80%EB%B2%88%ED%98%B8%EC%B0%BE%EA%B8%B0.png)

- 회원가입(아이디 중복 확인, 비밀번호 규칙 적용, 이메일 토큰 인증)  
![회원가입](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)

- 운동일지(개인별 운동 일지 등록, 수정, 삭제, 총 소모 칼로리 및 운동 시간 조회)
![운동일지](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 운동조회(운동 데이터 및 개인별 소모 칼로리 조회)
![운동조회](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 운동추가(운동 데이터에 없는 운동에 한에서 사용자가 자유롭게 운동 추가)  
![운동추가](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)

- 음식일지(개인별 음식 일지 등록, 수정, 삭제, 총 섭취 영양정보 조회) 
![음식일지](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 음식조회(음식 데이터 및 개인별 섭취 칼로리 조회)
![음식조회](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 음식추가(음식 데이터에 없는 음식에 한해서 사용자가 자유롭게 음식 추가)
![음식추가](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)

- 공지사항(관리자: (공지사항 등록, 조회) 
![공지사항](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 공지사항((공지사항 수정, 삭제), (댓글 등록, 수정, 삭제), 좋아요, 싫어요, 신고)
![공지사항 상세](ttps://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
  
- 커뮤니티(관리자: (공지사항 등록, 조회)   
![자유게시판](https://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
- 커뮤니티((공지사항 수정, 삭제), (댓글 등록, 수정, 삭제), 좋아요, 싫어요, 신고)  
![자유게시판 상세](ttps://github.com/YangSeungHyunn/MARKDOWN_20250714/blob/main/doc/%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%88.png)
