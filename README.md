# Smart_Flowerpot
2022 경북대학교IDCE 창의회로설계첼린지 출품작입니다.

서보모터와 조도센서를 이용해 자동으로 햇빛을 추적하며  화분이 회전하여 최적의 일조량을 제공하는 SMART 화분을 제작했습니다.

BCD 카운터가 값의 증가를 반복하며 조도센서값을 ADC IC로 확인합니다. D flip-flop과 op amp comparator을 이용해 조도량에 변화가 생기면 모터가 지정된 값만큼 회전합니다.

DAY-HOUR down count 알람을 이용하여 급수 주기를 설정할 수 있습니다.
