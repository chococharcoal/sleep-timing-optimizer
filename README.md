# sleep-timing-optimizer



## English Description

Sleep Timing Optimizer is an HTML-based application that recommends an optimal bedtime using the dual process sleep-wake model. 
By entering today’s wake-up time and tomorrow’s planned wake-up time, the program suggests the best time to go to sleep today. 
The result is visualized with Chart.js.

NOTE: This was written for a high school math project, so it simplifies equations from this link (https://pubmed.ncbi.nlm.nih.gov/25084361/) and may not exactly reproduce the original study. Some aspects of the paper were simplified or approximated. 


Features
- Calculates optimal sleep start time based on today’s and tomorrow’s wake times.
- Visualizes sleep pressure (H(t)) and circadian thresholds using Chart.js.
- Interactive and easy-to-use interface.
- Reset button to clear inputs and chart.



How it works
- Implements the dual-process model:
  - Process S: homeostatic sleep pressure
  - Process C: circadian rhythm modulation
- Simulates sleep-wake states over a 24-hour cycle.
- Recommends the first feasible sleep onset명

Sleep Timing Optimizer는 HTML 기반 프로그램으로, 수면-각성 이중 조절 모델을 기반으로 대략적인 최적 취침 시간을 추정해주는 프로그램입니다.
오늘 내가 일어난 시간과 내일 일어나야 할 시간을 입력하면 오늘 몇시에 자는것이 좋은지 계산합니다.
계산된 결과는 Chart.js를 사용해 그래프로 시각화됩니다.

참고: 이 프로그램은 고등학교 수학 수행평가용으로 제작되었으며, 프로그램에서 구현된 수식이 원래의 수식과 차이가 있을 수 있습니다. 수식은 링크된(https://pubmed.ncbi.nlm.nih.gov/25084361/) 연구를 참고했지만, 이 논문의 결과를 정확히 구현하지 않으며 일부 수치는 근사하거나 단순화된 다른 수치로 대체되었을 수 있습니다.


주요 기능
- 오늘과 내일의 기상 시간을 기반으로 최적의 취침 시작 시간을 계산
- Chart.js를 이용해 수면 압력(H(t))과 생체 리듬 임계값 시각화
- 직관적이고 상호작용 가능한 사용자 인터페이스 제공
- 입력과 차트를 초기화하는 리셋 버튼 제공



작동하는 방법
- 이중 조절 모델 구현:
  - Process S: 항상성 수면 압력
  - Process C: 생체 리듬 변동
- 24시간 주기 동안 수면-각성 상태 시뮬레이션
- 기상 12시간 이후 가능한 첫 수면 시작 시간 추천


사용 방법
1. 브라우저에서 파일 열기
2. 오늘과 내일의 기상 시간 입력
3. "수면 시간 계산" 버튼 클릭하여 추천 취침 시간 확인
4. 그래프 표시:
   - 검은색 선: 수면 압력 H(t)
   - 빨간 점선: 상위 임계값
   - 파란 점선: 하위 임계값
5. "리셋" 버튼 클릭하여 입력과 차트 초기화



사용한 기술
- HTML / CSS / JavaScript
- [Chart.js](https://www.chartjs.org/) 그래프 시각화



참고 문헌 / 자료
Sleep Need, Previous Sleep, and Wake Times Influence Cognitive Performance 
— PMID: 25084361, https://pubmed.ncbi.nlm.nih.gov/25084361/
