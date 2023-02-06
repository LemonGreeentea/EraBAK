eratohoK1. 18.1용_SELECT_CHARA_LIST 「정」소트 대응

·SELECT_CHARA_LIST나 SELECT_CHARA_LIST_MULTI로 「정」을 누르고 나서[전의 캐릭터] [다음의 캐릭터]를 누른 결과가 소트에 대응하고 있지 않다
·SELECT_CHARA_LIST나 SELECT_CHARA_LIST_MULTI로 「정」을 누르고 나서[돌아오는]을 누르면 소트되어 있지 않다（그 상태로 적당한 버튼을 누르면 정상적으로 소트 된다）
를 수정합니다.

파일은
ERB\SYSTEM\SELECT_CHARA_LIST.ERB
뿐입니다.

이것으로 문제 없게 동작하고 있네요? 괜찮네요?



개변 부분의 재개변·유용에 대해
 - era로 이용한다면 자유
 - era 이외로 이용한다면 불가
로 합니다（eratohoK 본체의 readme.md에 써 있는 「명기하고 있지 않는 경우」와 같습니다）
덧붙여 개변 부분은 ERB\SYSTEM\SELECT_CHARA_LIST.ERB의 극히 일부분인 것으로, 그 이외의 부분은 내가 이렇다 저렇다 말하는 대상이 아닙니다.
