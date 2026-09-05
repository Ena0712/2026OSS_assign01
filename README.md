프로젝트명 : 자기소개용 페이지 제작
=======================================================

프로젝트에 대한 간단한 설명

위 프로젝트는 자기소개용 페이지를 AI를 이용하여 구성 1차 제작후, 2차로 직접 수정을 가해 제작하는 프로젝트이다.

------------------------------------------------

완성 페이지:

[Vercel Deploy URL](https://oss1-vercel.vercel.app)


index.html URL:

https://github.com/Ena0712/2026OSS_assign01/blob/main/index.html


index2.html URL:

https://github.com/Ena0712/2026OSS_assign01/blob/main/index2.html


------------------------------------------------------------
Key Learning: visual studio code 사용방법, terminal 이용방법, html을 이용한 페이지 제작 방법


Development Flow: VS Code → Git → GitHub → Vercel 흐름


Code Modification: 페이지 중단, 하단 내 내용변경


Problem & Solution: AI를 통한 페이지 구상 및 디자인 작업 내 크기 오차 및 색 지정 실패 등


Reflection: 수업 중 작성한 노트 첨부

----------------------------------------------------------------------
Index.html
html치면 html:5나오는거 선택
Body 사이에 작성

Sauce control에서 뭐 바꿩는지 작성하고 commit하기

 terminal에서 새로 열어가지고
git log --oneline <-뭐 커밋했는지 로그 확인
git remote -v <-연결된 깃헙그거 확인 
{
origin  https://github.com/2026-2-OSS/assign01-c02-22500738.git (fetch)
origin  https://github.com/2026-2-OSS/assign01-c02-22500738.git (push)
별칭		주소
}

git branch -a <-브랜치확인
git push origin main [푸쉬]
		별칭	 브랜치
<올리는 매커니즘>
git add .
git commit -m “내용”

git commit -am “내용” <-이건 뭔지 모르겠음….

git push origin main [푸쉬]
		별칭	 브랜치

배포
내 레퍼토리에 이름같은 거 만들고 그거 주소 떠와서
git remote add [내가 정한이름] [내가 떠온 주소]
git remote -v로 확인하고
[내가정한이름]에도 푸쉬해야함!!

vercel에서 newproject누르고 왼쪽에 git 레포지토리에 아까 새로한 레포지토리넣고 depoly하기

============================================================================
