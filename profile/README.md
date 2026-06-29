# johnprk-AI

> **나는 AI를 이렇게 씁니다.** <sub>(2026.06.29 기준 · 생각은 계속 바뀌어서 기입일을 남깁니다)</sub>
>
> - 필요할 때, 필요한 걸 직접 만든다.
> - 귀찮고 반복되는 일은 AI에게 맡긴다.
> - 그렇게 만든 도구는 나의 또 다른 분신이 된다.
> - 내 몫은 세부 구현을 일일이 보는 게 아니라, 결과가 내가 원하고 만족하는 대로 나왔는지 검증하고 강화하거나 고치는 것이다.
> - skills를 공유하더라도, 아직은 나를 위해 쓴다.

<br><br>

## 🖥 앱 (Apps)

### 🐼 토큰 지키미 (Token Guardians)

<table>
  <tr>
    <td rowspan="10" width="44%"><img src="token-guardians-hero.png" width="100%" alt="토큰 지키미" /></td>
    <td width="20%"><b>소개</b></td>
    <td>Claude · Codex의 토큰 잔량을 메뉴바와 데스크탑 캐릭터로 실시간으로 보여주는 앱입니다. 질문을 보내면 5분 프롬프트 캐시 타이머가 돌아, 캐시 골든타임을 놓치지 않게 챙겨줍니다.</td>
  </tr>
  <tr><td rowspan="3"><b>기능</b></td><td>데스크탑 캐릭터(펫) 및 메뉴바로 잔량 시각화</td></tr>
  <tr><td>5분 프롬프트 캐시 타이머</td></tr>
  <tr><td>6종 캐릭터 개발<br>(판다 · 고양이 · 햄스터 · 강아지 · 하마 · 병아리)</td></tr>
  <tr><td><b>지원 OS</b></td><td>macOS 11+ (서명 · 공증 완료) &nbsp;·&nbsp; Windows 11+</td></tr>
  <tr><td><b>개발 기간</b></td><td>2026.04 ~ 진행 중</td></tr>
  <tr><td><b>버전</b></td><td><code>v2.35.0</code></td></tr>
  <tr><td><b>소개 페이지</b></td><td><a href="https://johnprk.github.io/token-guardians/">바로가기 →</a></td></tr>
  <tr><td><b>회고</b></td><td><a href="https://johnprk.github.io/ai/token-guardians/">회고 페이지 →</a> <sub>(작성 중)</sub></td></tr>
  <tr><td><b>제작</b></td><td>개발 : <b>Claude Code</b><br>디자인 : <b>Gemini</b></td></tr>
</table>

<br>

<table>
  <tr>
    <th colspan="2" align="left">📊&nbsp; ai-usage-checkup</th>
  </tr>
  <tr>
    <td width="22%"><b>왜 만들었나</b></td>
    <td>내 Claude Code 사용 습관을 객관적으로 보고, opus한테 코칭받으려고</td>
  </tr>
  <tr>
    <td><b>지원</b></td>
    <td>사용 패턴 분석 · opus 코칭 · 데스크탑 리포트</td>
  </tr>
  <tr>
    <td><b>버전</b></td>
    <td><code>v0.9.5</code></td>
  </tr>
  <tr>
    <td><b>소개</b></td>
    <td><a href="#">소개 페이지 →</a></td>
  </tr>
  <tr>
    <td><b>회고</b></td>
    <td><a href="#">회고 페이지 →</a></td>
  </tr>
</table>

<br>

<table>
  <tr>
    <th colspan="2" align="left">📝&nbsp; todo-widget</th>
  </tr>
  <tr>
    <td width="22%"><b>왜 만들었나</b></td>
    <td>화면 위에 항상 반투명으로 떠 있는 가벼운 할 일 위젯이 필요해서</td>
  </tr>
  <tr>
    <td><b>지원</b></td>
    <td>반투명 오버레이 · 데스크톱 상주 · Electron</td>
  </tr>
  <tr>
    <td><b>버전</b></td>
    <td><code>v0.1.0</code></td>
  </tr>
  <tr>
    <td><b>소개</b></td>
    <td><a href="#">소개 페이지 →</a></td>
  </tr>
  <tr>
    <td><b>회고</b></td>
    <td><a href="#">회고 페이지 →</a></td>
  </tr>
</table>

<br><br>

## 🧩 전용 AI (Skills)

> **반복하는 작업을 대신 맡기려고 만든, 나만의 전용 AI들. 지금까지 3개.**
> 만든 이유 · 효과 · 제작 과정은 각 제작기 글로 이어집니다. <sub>(작성 예정)</sub>

#### 📝 회고 전용 AI

<table>
  <tr><td width="130"><b>하는 일</b></td><td>미션 · 프로젝트 회고 글 작성</td></tr>
  <tr><td><b>사용 방식</b></td><td><b>인터랙티브</b> (인터뷰로 단계마다 맞춤)</td></tr>
  <tr><td><b>기반 skill</b></td><td><a href="https://github.com/johnprk-AI/skills/tree/main/mission-retrospective"><code>mission-retrospective</code></a></td></tr>
  <tr><td><b>상태</b></td><td>사용 중</td></tr>
  <tr><td><b>제작기</b></td><td>예정</td></tr>
</table>

<br>

#### 🧪 기술 블로그 전용 AI

<table>
  <tr><td width="130"><b>하는 일</b></td><td>기술 노트 글 작성</td></tr>
  <tr><td><b>사용 방식</b></td><td><b>위임</b> (자료 주면 한 호흡에)</td></tr>
  <tr><td><b>기반 skill</b></td><td><a href="https://github.com/johnprk-AI/skills/tree/main/tech-learning-note"><code>tech-learning-note</code></a></td></tr>
  <tr><td><b>상태</b></td><td>사용 중</td></tr>
  <tr><td><b>제작기</b></td><td>예정</td></tr>
</table>

<br>

#### 🎓 우테코 답변 전용 AI

<table>
  <tr><td width="130"><b>하는 일</b></td><td>우테코 사전학습 · 토론 산출물 작성</td></tr>
  <tr><td><b>사용 방식</b></td><td><b>워크플로우</b> (정해진 형식대로)</td></tr>
  <tr><td><b>기반 skill</b></td><td><a href="https://github.com/johnprk-AI/skills/tree/main/mission-pre-study"><code>mission-pre-study</code></a></td></tr>
  <tr><td><b>상태</b></td><td>다듬는 중</td></tr>
  <tr><td><b>제작기</b></td><td>예정</td></tr>
</table>

<br>

<sub>전체 스킬 모음 → <a href="https://github.com/johnprk-AI/skills"><b>johnprk-AI/skills</b></a></sub>
