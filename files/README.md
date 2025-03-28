# 2025_PHwal
2025년 프로그래밍언어활용 1학기
##
GitHub에서 사용하는 마크다운(Markdown) 문법을 정리해드릴게요.  

---

## 1. 제목(Header)
`#`을 사용하여 제목을 작성할 수 있습니다.  
`#` 개수에 따라 제목의 크기가 달라집니다.
```md
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
**결과:**
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

---

## 2. 글꼴 스타일  
텍스트를 **굵게**, *기울임*, ~~취소선~~을 적용할 수 있습니다.

```md
**굵은 글씨**
__굵은 글씨__

*기울임 글씨*
_기울임 글씨_

~~취소선~~
```

**결과:**
- **굵은 글씨**  
- *기울임 글씨*  
- ~~취소선~~

---

## 3. 목록 (Lists)  
### ● 순서 없는 목록 (Unordered List)  
`-`, `*`, `+`를 사용하여 순서 없는 목록을 작성할 수 있습니다.
```md
- 항목 1
- 항목 2
  - 하위 항목 2-1
  - 하위 항목 2-2
* 항목 3
+ 항목 4
```
**결과:**  
- 항목 1  
- 항목 2  
  - 하위 항목 2-1  
  - 하위 항목 2-2  
* 항목 3  
+ 항목 4  

### ● 순서 있는 목록 (Ordered List)  
숫자와 점(`. `)을 사용합니다.
```md
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목
   1. 하위 항목 1
   2. 하위 항목 2
```
**결과:**  
1. 첫 번째 항목  
2. 두 번째 항목  
3. 세 번째 항목  
   1. 하위 항목 1  
   2. 하위 항목 2  

---

## 4. 코드 블록 (Code Block)
### ● 인라인 코드 (Inline Code)  
백틱(``)을 사용하여 한 줄짜리 코드를 작성할 수 있습니다.
```md
`print("Hello, World!")`
```
**결과:**  
`print("Hello, World!")`

### ● 여러 줄 코드 블록 (Multi-line Code Block)  
백틱 3개(```` `)와 언어 이름을 사용하여 여러 줄의 코드를 강조할 수 있습니다.
```md
```python
def hello():
    print("Hello, World!")

hello()
```
```
**결과:**
```python
def hello():
    print("Hello, World!")

hello()
```

---

## 5. 링크와 이미지  
### ● 링크 (Link)  
```md
[GitHub](https://github.com)
```
**결과:**  
[GitHub](https://github.com)

### ● 이미지 (Image)  
```md
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
**결과:**  
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

## 6. 인용문 (Blockquotes)  
`>`을 사용하여 인용문을 작성할 수 있습니다.
```md
> 이것은 인용문입니다.
>> 중첩된 인용문입니다.
```
**결과:**  
> 이것은 인용문입니다.  
>> 중첩된 인용문입니다.

---

## 7. 체크리스트 (Task List)  
`- [ ]` 또는 `- [x]`를 사용하여 체크리스트를 만들 수 있습니다.
```md
- [ ] 할 일 1
- [x] 완료된 할 일 2
```
**결과:**  
- [ ] 할 일 1  
- [x] 완료된 할 일 2  

---

## 8. 표 (Table)  
`|`와 `-`를 사용하여 표를 작성할 수 있습니다.
```md
| 제목 1 | 제목 2 | 제목 3 |
|--------|--------|--------|
| 내용 1 | 내용 2 | 내용 3 |
| 내용 4 | 내용 5 | 내용 6 |
```
**결과:**  
| 제목 1 | 제목 2 | 제목 3 |
|--------|--------|--------|
| 내용 1 | 내용 2 | 내용 3 |
| 내용 4 | 내용 5 | 내용 6 |

---

## 9. 수평선 (Horizontal Line)  
`---`, `***`, `___`를 사용하여 수평선을 그릴 수 있습니다.
```md
---
***
___
```
**결과:**  
---
***
___

---

이제 GitHub 마크다운을 자유롭게 활용해보세요! 🚀
