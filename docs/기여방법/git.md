# git 세팅

## fork
우선 디지텍 위키 원본 리포지토리 https://github.com/digitech-wiki/digitech-wiki 로 이동한다

![!\[\]()](fork.png)
이후 성공적으로 fork가 된다면 자신의 리포지토리에 원본 리포지토리가 fork가 됐을 것이다

![Alt text](forked.png)

## Clone

**fork된 자신의 리포지토리를 clone한다.**

![Alt text](clone.png)
Code 버튼을 누르면 나오는 주소를 복사한 뒤 ``git clone https://github.com/maldron0309/digitech-wiki.git`` 
> 위 주소는 예시이므로 자신의 리포지토리를 clone해야한다

## Commit and Push

커밋 메세지는 자신이 무엇을 했는지 쓰면 된다
> [add] 기여방법 문서 추가

> [add]는 신규 추가 내용, [wip]는 진행중, [mod]는 수정 사항 - 필수는 아니지만 보기 편하다 

이후 변경사항 commit 후 push하게 된다면 다시 자신의 리포지토리 돌아온 뒤

![Alt text](push.png)

**commit ahead**를 클릭 한다.

## Pull Request

![Alt text](PR.png)

push하는 리포지토리가 원본 리포지토리가 맞는지 확인 후 **Create pull request**를 클릭한다.

![Alt text](PR2.png)

**자신이 작업한 내용을 요약하여 적고, 자신의 학번을 적은 후** Create pull request를 클릭한다.

![Alt text](PR3.png)

이제 PR은 완료 되었다. 원본 리포지토리 주인이 승인 하게 된다면, **Merge**가 되어 우리가 변경한 내용이 원본 리포지토리에 적용되게 된다.

## Sync

![Alt text](Sync.png)

Sync fork를 통해 자신의 리포지토리도 원본 리포지토리의 변경사항 만큼 최신 상태로 만들면 된다.