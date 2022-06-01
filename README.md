<div align="center">
  
# TF - IDF
  
</div>

## Project

프로젝트 설명

- python으로 TF-IDF를 구현
- list에 담겨진 단수, 복수 문자열 또는 문자열을 입력하면 TF-IDF 결과를 리턴한다
<details>
  
<summary>TF-IDF(Term Frequency-Inverse Document Frequency) 란 무엇인가?</summary>
<br>
  
TF- IDF는 모든 문서에서 자주 등장하는 단어는 중요도가 낮다고 판단하며 (the, a 등 불용어) 특정 문서에서만 자주 등장하는 단어는 중요도가 높다고 판단한다. 

TF-IDF 값의 높 낮음이 중요도를 나타낸다

여기서 `TF`는 특정 문서에서 특정 단어의 등장 횟수, `DF`는 특정 단어가 등장한 문서의 수 이며, `IDF`는 DF에 반비례 하는 수 이다


![image](https://user-images.githubusercontent.com/86823305/171410168-603e0a3d-f988-4df1-80a2-9baee57c35eb.png)


위는 IDF를 구하는 공식인데 log가 들어가게된다 log를 취해주지않고 그냥 역수를 사용하면 n값이 늘어남에 따라 IDF값이 기하급수적으로 커져 log를 취하게된다

</details>




