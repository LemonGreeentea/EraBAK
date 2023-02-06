eratohoK1. 11.3_특수 세력 군주 란 댐 이름 불안정 수정


http://jbbs.shitaraba.net/bbs/read.cgi/otaku/16783/1503407321/113#113
그리고 불안정이 보고되고 있지만
https://github.com/wamekukyouzin/eratohoK/commit/e834a39c104cab7fbae39b3e463050d67adc98b6
그럼 수정 되어 있지 않은 것 같은 것으로, 그것을 수정합니다.

또,
여자 당신을 주인공으로 해 개시한 후, 특수 세력 군주의 이름이 란 댐에서 생성되었을 경우에 군주가 여성명이 된다
를 수정합니다.
성별을 결정하는 처리를 머리 쪽으로 이동한 것과 CALL SET_RANDOM_NAME_K 및 SET_RANDOM_NAME_J의 인수를 변경하고 있습니다.


자주(잘) 보면, 원래 ERB\R_CHARA\NAME_LIST.ERB 에 있는 @SET_RANDOM_NAME_K 나 @SET_RANDOM_NAME_J 의 내용이 미묘할지도 모르지만, 거기는 노 터치입니다.


ERB\SYSTEM\SP_COUNTRY\SP_COUNTRY_FUNCTIONS.ERB
1 파일만을 덧쓰기하는 형태가 됩니다.


본체 거두어들여졌을 경우는, 패치 작가에 의한 신규 작성 개소 및 변경 개소의 권리를 방폐[放棄] 합니다.
NTRY\SP_COUNTRY_FUNCTIONS.ERB
1�t�@�C��������㏑������`�ɂȂ�܂��B


�{�̂Ɏ�荞�܂ꂽ�ꍇ�́A�p�b�`��҂ɂ��V�K�쐬�ӏ�����ѕύX�ӏ��̌�����������܂��B
