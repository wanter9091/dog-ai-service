# DOG-AI-SERVICE
반려견과 보호자를 위한 AI 비서

---

## 번외
>윈11 한글 마지막 2번 써지는거 해결법
>>https://m.blog.naver.com/sbs5709/223075779033

---

## 각 branch 용도
> ### main(*중요)
>> 메인 branch  
>> main에 대한 모든 업데이트는 <span style='background-color: #fff5b1'>**test에서 먼저 시도**</span>하여 이상이 없을 시에 <span style='background-color: #fff5b1'>**팀원 모두의 동의**</span>를 구하고한다.
>
> ### test
>> 각자의 개인 branch에서의 업데이트를 먼저 테스트 해보는 곳.
>
> ### backup
>> 만일의 사태를 대비한 백업용 branch  
>> main이나 test에서 이상이 없다면 주기적으로 백업해두자
>
> ### []
>> 성한빈 개인 branch
> ### []
>> 심규샹 개인 branch
> ### wanter9091
>> 오병재 개인 branch


---

## 초기설정.
>터미널/cmd/git bash에서 프로젝트를 저장할 위치로 이동 후 아래 코드 입력
>>git clone https://github.com/wanter9091/dog-ai-service.git

---

## 디렉토리 구조
>

---

## GIT 명령어 모음
> branch 새로 생성 후 해당 branch로 즉시 전환
>> git switch -c [branch명]
>
> branch 목록 조회(*로 강조된 곳이 현재 branch)
>> git branch
>
> branch 전환 코드 2가지(최근에는 switch를 더 자주 사용한다고함. checkout은 참고용)
>> git switch [branch명]
>> git checkout [branch명]
>
> branch 병합하기(현재 branch를 대상으로 명령어의 branch를 덮어씌우는 느낌)
>> git merge [branch명]
>

---

## .gitignore 예시 사용법(원하는 파일의 커밋제한)
>// 1. '파일명'으로 제외하는 방법 (* 해당 방법은 경로 상관없이 지정한 파일명으로 모두 제외할 수 있다)  
>ignoreFileName.js
>
>// 2. 특정 '파일'만 제외하는 방법 (* 현재 기준을 .ignore파일이 있는 경로라고 생각하면 된다)  
>src/ignoreFileName.js
>
>// 3. 특정 '디렉토리' 기준 이하 파일들 제외 방법  
>node_module/
>
>// 4. 특정 디렉토리 하위의 특정 '확장자' 제외하는 방법  
>src/*.txt
>
>// 5. 특정 디렉토리 하위의 그 하위의 특정 '확장자' 제외하는 방법  
>src/**/*.txt
>
>// 6. 특정 '확장자' 제외하기  
>.txt
>
>// 7. 4번 특정 '확장자'에서 일부 제외 할 파일  
>!manual.txt

---

