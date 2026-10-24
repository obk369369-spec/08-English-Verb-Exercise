# 영어 말하기 훈련 기록 복구본 (2026-10-25)

## 범위 및 보존 상태
이 문서는 2026-10-25 대화에 제공된 SRT 녹취와 확인 가능한 과거 학습 관련 기록 요약을 보존한 것이다. **전체 과거 대화의 완전한 원문 아카이브가 아님**. 기존 코드와 파일은 수정하지 않는다.

## 2026-10-25 제공 SRT: 사용자 확정 요구
- AI는 영어로만, 초등학생 수준(A1)의 짧고 듣기 쉬운 질문을 한다. 사용자가 한국어 설명을 명시적으로 요구할 때만 한국어를 사용한다.
- 동사 또는 동사구 한 가지를 여러 차례 반복한다. 매번 현재/과거/미래, 긍정/부정/의문, 동사구 변형을 바꾸어 사용자가 직접 말하도록 한다.
- 사용자가 답할 때마다 문법 오류와 부자연스러운 표현을 **명시적으로 교정**하고 자연스러운 영어 문장을 제시한다. 교정을 생략하거나 틀린 문장을 맞다고 칭찬하지 않는다.
- 몇 차례 반복한 뒤 다음 동사구를 제시하고 같은 과정을 반복한다. 설명보다 사용자 발화 비중을 높이고, 교정 후 바로 다음 질문으로 진행한다.
- 사용자가 영어가 떠오르지 않아 한국어로 답할 경우 의미를 살려 쉬운 영어 문장으로 바꾸어 연습을 이어간다.
- 사용자 연습 사례: work hard, learn, listen to / listen up, help / help out / help with / help someone, helping me out.
- 'listen to'는 일반적으로 '듣다', 'listen up'은 주의를 환기할 때 쓰는 명령형 표현이다. 'listen up to someone'을 일반적인 'listen to someone'의 대체로 교정하지 않는다.
- 'I used to'는 과거의 습관, 'these days I usually'는 현재의 습관에 적합하다.

## 녹취에서 확인된 사용자 발화 및 교정 예
1. 'I will learn how to make coding.' → 'I will learn how to code.'
2. 'Yes, I work hard.' (last week 질문에 대한 답) → 'Yes, I worked hard last week.'
3. 'I helped help someone in church.' → 'I helped someone at church.'
4. 'Maybe these days, I don't make any relationship with other people, so I used to listen to ChatGPT when working...' → 'These days, I don't meet many people, so I often talk to ChatGPT about work and personal problems.'
5. 'I have to someone in church because I gave 11조 for church.' → 의미 확인 필요. '십일조'를 뜻했다면 'I gave a tithe at church.'; 이를 특정인을 도왔다는 사실로 단정하지 않는다.
6. 'Please tell me who helped someone.'은 문법적으로 가능하지만 '누가 누군가를 도왔는지 말해 주세요'라는 뜻이다. 'Who did I help?' 또는 'Who helped me?'와는 뜻이 다르다.

## 확인 가능한 이전 프로젝트 기록 (완전 원문 미확보)
- 2025-11: 프로젝트명 English Verb Exercise; 경로 /tools/English_Verb_Exercise/index.html.
- 초기 명칭 Verb Pressure Speech Corrector; 동사 중심 반복, 빠른 반사 발화, 음성 교정 목표.
- 과거 문서: '8번 동사 활용 도구.doc', '동사 활용 영어 도구 4단계 + .doc', '동사 활용 연습.doc'.
- v1.1.0 관련 기록: 동사 패턴 자동 생성, 압박/일상/비즈니스 모드, 난이도 조절, 구조화 리스트 저장.
- 2025-11-30 관련 기록: SRT/TXT 업로드와 브라우저 동사 추출, 영상 /api/extract-verbs UI가 언급되었으나 서버 엔드포인트 미구현으로 기록됨. 실제 배포 및 실행은 별도 검증 필요.
- 과거 드라마 대사 기반 meet/go 시제 변형 연습 기록 존재. 원문 전체는 미확보.

## 다음 검증 과제
- 기존 GitHub 파일과 과거 대화/문서 원본을 대조해 중복 없이 보존할 것.
- 아직 접근·확인하지 못한 과거 대화는 '누락 없음'으로 판정하지 말 것.
- 학습 규칙/기록과 실행 코드 변경을 분리하고, 실제 실행과 read-back 증거로만 완료 판정할 것.
