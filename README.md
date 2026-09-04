### 안녕하세요 👋

** 주요 수행 업무 ** 

- 불확실성 정량화 (Predictive Entropy, Semantic Entropy, SAR)
- 오류 탐지와 선택적 재생성
- QA · 수학 추론에서의 검증 가능한 생성

---

### Researches

**Improving Uncertainty Quantification and Knowledge-Intensive Routing via Query Understanding in Large Language Models**
`PAKDD 2026` `특허 출원` · 제1저자 · 제1발명자 · [paper](https://link.springer.com/chapter/10.1007/978-981-92-1468-6_16) · [code](https://github.com/kangmc1/Improving-Uncertainty-Quantification-via-Query-Understanding)
- 불확실성 지표로 오답 가능성이 높은 질문 선별 → 해당 질문만 RAG · Recitation 프롬프트로 재생성
- Llama-3.1 / Qwen2.5 / Ministral / OLMo-2 4종 × NQ · TriviaQA · WebQuestions 3종
- vLLM 배치 추론, dev set 임계값 결정까지 스크립트 하나로 재현

**Can We Entrust Justice to AI?: How Persona Traps Contaminate Reasoning in Criminal Investigation**
`ACL 2026` `Findings` · 공동 1저자 · 교신저자 · [paper](https://aclanthology.org/2026.findings-acl.843/)
- 중립화한 살인 미스터리 시나리오에 페르소나(성별 · 인종 · 관계) 주입
- 동일한 증거 조건에서 결론이 흔들리는 정도를 측정
- 인구통계 속성보다 적대적 관계 정보의 오염이 훨씬 큼

**Make LLMs See Like Investigators, Not Just Think More: The Role of Structured Analysis in Investigative Reasoning**
`ACL 2026` `Main Conference (Long)` · 제2저자 · [paper](https://aclanthology.org/2026.acl-long.1056/)
- 수사관의 구조적 가설 분석 기법을 LLM 추론에 이식 (PRISM 프레임워크)
- MuSR 벤치마크 · LLM 10종에서 범용 프롬프팅 전략 전부 상회
- Ablation 결과, 개선폭의 89% 가 가설 구조화 단계에서 발생

**DLM Semantic Remasking**
`특허 출원` · 제1발명자 · [code](https://github.com/kangmc1/DLM-remasking-math-reasoning)
- Diffusion LM 이 생성한 수학 풀이에서 오류 시작 지점 탐지 → 그 뒤만 재생성
- 채점기 · sympy 검산 · 보조 LLM 세 신호로 오류 탐지

> 페르소나 · 수사 추론 두 편은 공동 연구로 코드 비공개.
