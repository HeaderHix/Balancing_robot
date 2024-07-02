# Balancing_robot





https://github.com/HeaderHix/Balancing_robot/assets/166344986/8234556b-a3af-421c-81b5-d70ef52404cf


PID Calibration






https://github.com/HeaderHix/Balancing_robot/assets/166344986/b0aa7294-eaef-4721-a11b-b2fb8027e547


평지 상태는 안정적





https://github.com/HeaderHix/Balancing_robot/assets/166344986/2d9d2043-2c33-47e2-917e-b2d2aef9d4e2


AA 배터리 3개 넣은 종이컵을 밸런싱 로봇 위에 올려놓았을 때 중심이 무너진 이유는 안정성을 위해 pid 값과 모터의 최대 출력을 모두 낮게 설정하였기 때문인 것 같다. 때문에 무게가 더해졌을 때 중심이 무너지게 되면 밸런스를 복구하지 못하고 그대로 쓰러지게 됐다. 반대로 pid 값과 출력을 높이면 센서에 작은 변화에도 크게 흔들려 안정성을 잃지만 외부 환경 변화에는 더 안정성을 갖는다

또한 대회 평가 기준에, 평지 → 무게 증가 → 경사면의 스테이지로 구성돼 있었기 때문에 경사면에서의 적응을 위해 Setpoint 자체를 약 10도가량 기울여둔 것 또한 2스테이지(무게 증가)에서 패착 요인으로 작용하게 됐다
