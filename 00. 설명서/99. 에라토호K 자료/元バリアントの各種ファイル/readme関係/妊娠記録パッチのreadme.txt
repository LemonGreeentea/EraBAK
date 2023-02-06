20150518_era 연희[戀姬]_임신 기록의 readme

·적용 방법
그대로 덧쓰기해 적용할 수 있습니다.
능력표시에"2[임신 기록]"버튼이 추가됩니다.
동고의 세이브 데이터는 확인용입니다. 토우카씨로 확인해 주세요.
다른 캐릭터의 기록이 일부 이상합니다만 작업중의 데이터가 섞이고 있는 탓입니다.

·편집원
era 연희[戀姬] 20150506

·편집점
CSV/VariableSize.csv : CSTR, 100을 130으로 했다
ERB/TRAIN/PREGNANT.ERB : 228행째에 기록을 위한 함수 호출을 추가했다
ERB/TRAIN/PREGNANT_RECORD.ERB : 신규 작성. 기록 처리의 메인 부분
ERB/TRAIN/PREGNANT_RECORD.ERH : 신규 작성. ↑그리고 사용하는 변수를 기술
ERB/SHOP/SHOP_LIFE.ERB : @SELECTED_SHOWDATA의 첫머리에 표시 변환 버튼을 추가
ERB/SYSTEM/SHOW_INFO.ERB : @SHOW_INFO(ARG:0)의 첫머리에 표시의 호출을 추가

·하고 있는 것
어느 캐릭터가 누구의 아이를 몇회 임신했는지의 기록을 취합니다.
기록하는 타이밍은 임신 발각시입니다.
부친의 이름을 CSTR에 기록해, CFLAG에 회수를 기록하고 있습니다.

CSTR와 CFLAG의 사용 범위는 ERH로 지정하고 있습니다.
잠정으로 CSTR:100-129, CFLAG:250-279를 사용하도록(듯이)하고 있습니다.

·파일의 개변등은 자유롭게 아무쪼록.

