# EmergeFi — RWA Tokenization Platform

> **Strategic Analysis 2026 · Confidential**

---

## 01. Summary

인도네시아/사우디아라비아에서 MSME 매출 채권, Gig-worker EWA 자산 담보 대출 상품을 공급하는 플랫폼 'EmergeFi'
→ **특정 Asset Class × Jurisdiction에 집중한 모델**

### Key Questions & Answers

| | 질문 | 답변 |
|---|---|---|
| **Q1** | 플랫폼은 궁극적으로 특정 Asset Class × Jurisdiction에 집중해야 하는가? | Securitize, Centrifuge 등 글로벌 선두 플랫폼들은 Private Credit 외 기관 펀드/ETF, deRWA 등 멀티 자산을 공급 중 → **Asset Class × Jurisdiction의 확장 필요** |
| **Q2** | 우리의 플랫폼 모델은 RWA에 투자하는 투자자들을 위해 어떤 모습이어야 하는가? | 기관투자자와 HNWIs는 보안이 검증된 단일 플랫폼에서 '유동성을 누리길 원함' → 파트너 금융기관이 투자자에게 **1) 기술 안정성, 2) 유동성이 보장된 3) 단일 인프라를 제공**할 수 있도록 뒷단 기술을 공급하는 것이 핵심 |

### 단계별 플랫폼 확장 전략

| Phase | 전략 | 상태 |
|---|---|---|
| **Phase 1** — 기존 전략에 집중 | **플랫폼 기능:** Whitelabeling / **Asset Class:** 리테일용 Private Credit / **Jurisdiction:** Undersupply credit gap이 확실한 동남아(인도네시아/사우디) 집중 | `NOW` |
| **Phase 2** — Asset Class × Jurisdiction 확장 | **플랫폼 기능:** Whitelabeling + SaaS 고도화 / **Asset Class:** 리테일용 → 기관용 Private Credit + STO / **Jurisdiction:** Phase 1 track-record 기반 글로벌 (한국 포함)으로 확장 | `NEXT` |
| **Phase 3** — Liquid Model (deRWA) 도입 | **플랫폼 기능:** Whitelabeling + Trading Pool 모듈 / **Asset Class:** Phase 2와 동일 / **Jurisdiction:** Phase 2와 동일 | `FUTURE` *(논의 필요)* |

---

### 01-1. 플랫폼 기능: Whitelabeling (B2B Infra)

- RWA 시장에서 유동성 공급은 핵심이나, 초기 사업체가 유동성과 라이선스를 동시에 갖추기는 어려움
- Whitelabeling 모델: 1) 토큰화 엔진, 2) 컴플라이언스 모듈 등 **핵심 인프라를 모듈화**하여 금융기관에 제공 → 파트너가 자체 브랜드로 RWA 상품 발행·유통
- 파트너의 1) **investor/lender pool**, 2) **현지 라이선스** 활용 → 자체 유동성 확보 없이 빠른 시장 진입 및 거래량 생성

#### Direct Matching vs Whitelabeling 비교

| 구분 | Direct Matching | ✓ Whitelabeling |
|---|---|---|
| **포지셔닝** | 투자자-발행사 직접 연결 'Hub' — 플랫폼이 곧 브랜드 | 금융기관에 인프라 공급하는 'Enabler' — 파트너 브랜드 뒤의 기술 엔진 |
| **핵심 역량** | · 자체 유동성 공급 능력 · 브랜드 신뢰도 · 강력한 심사(Underwriting) 역량 | · **on/off ramp** (실물자산 토큰화) · **모듈화된 기술 스택** (토큰화, 컴플라이언스 API) · 파트너별 커스터마이징 대응력 |
| **수익 모델** | 중개 수수료 + AUM 기반 운용 보수 → 초기 유동성 확보가 선행 조건 | **Setup + SaaS + Tx Fee** → 파트너 수 × 거래량 비례 복합 수익 |
| **규제 부담** | Jurisdiction별 VASP·중개업 라이선스 필수 — 진입 비용 높음 | **기술 제공자** 포지션 → 규제 부담을 파트너에게 이전, 빠른 시장 진입 |
| **확장성** | Jurisdiction별 별도 라이선스·법인 필요 → 선형적 확장 | 동일 스택을 다수 파트너에 복제 → **지수적 확장**, 파트너가 현지 규제 해결 |
| **리스크** | 자산 디폴트·밸런스시트 리스크를 플랫폼이 직접 부담 | **Capital-light 모델** — 자산 리스크는 파트너 부담, 기술 리스크에 집중 |

#### 모듈화된 기술 스택 상세

| 모듈 | 설명 |
|---|---|
| **토큰화 엔진** (Tokenization Engine) | 실물 대출채권을 온체인 토큰으로 변환하는 핵심 모듈. 자산 발행·상환·이자 분배를 자동화하며, Originator가 자체 브랜드로 발행할 수 있는 화이트라벨 인터페이스 제공 |
| **컴플라이언스 API** (Compliance Module) | 국가별 KYC/AML/KYB 규제 요건을 파트너 시스템에 Embedded로 제공. OJK(인도네시아)·SAMA(사우디) 등 현지 규제 프레임워크에 맞춤 대응 |
| **커스터디 연동** (Custody Integration) | BitGo·Copper 등 기관급 수탁사 API를 사전 통합하여 파트너가 별도 수탁 인프라 구축 없이 즉시 토큰 자산의 안전한 보관·이전이 가능하도록 Plug-in 환경 제공 |

---

### 01-2. Asset Class 확장 범위: 광의의 Private Credit 중심

- *'Undersupply credit gap'* 해결에 집중. **Phase 1** 리테일 PC 모듈 → **Phase 2** 기관용 PC + STO로 점진적 확장
- ETF/국채 등 외부 기관 평가 자산은 Whitelabeling 핵심 가치와 거리가 있어 후순위

| 구분 | Private Credit (리테일) | Private Credit (기관용) | STO (부동산 등) | ETF (국채/주식/MMF) |
|---|---|---|---|---|
| **기초 자산** | MSME 매출채권, Gig-worker EWA | 대형 사모펀드(PEF) 산하 기업 대출, 대규모 인프라 대출 | 빌딩 지분, 부동산 수익권 | 미국 국채(T-Bills), 대형 우량주 묶음 |
| **Value Prop.** | **8~12%** 고수익 → 소액 자금이 실물 경제의 모세혈관에 흐르게 함 | **7~9%** 중고수익 → 검증된 우량 기업 대상의 안정적 현금흐름 | 자산 가치 상승(Cap. Gain) 기대; 상징성 있는 실물 소유권 | **4~5%** 저수익 → 절대적 안전성과 무위험 수익률(Risk-free) |
| **Requirements** | 대량의 데이터 처리, 차주별 세밀한 스코어링, 자동화된 정산 시스템 | 고도의 기업 실사(DD), 복잡한 계약 구조 설계 능력 | 감정 평가, 신탁 구조 설계, 규제 당국의 개별 승인 | 대형 자산운용사 제휴, 실시간 기준가(NAV) 산출 |
| **Economics** | **높은 스프레드(Spread)** → 관리 비용은 들지만 마진율이 가장 높음 | 안정적 운용 보수 → 건당 규모가 커서 AUM 성장에 유리 | 거래 수수료 중심 → 유동성이 낮아 회전율 확보가 관건 | 박리다매 → 압도적 규모 경제가 필요하며 마진이 낮음 |
| **브랜드 연결** | *핵심: undersupply credit needs 해결* | 유동성 확대를 통한 플랫폼 가치 제고 | 사업 영역 확장 | 완전한 통합 RWA 플랫폼화 |

---

### 01-3. Jurisdiction 확장 범위

#### PHASE 1 → PHASE 2

| | PHASE 1: 동남아 (인도네시아, 사우디) | PHASE 2: 글로벌 (한국 포함) |
|---|---|---|
| **핵심 역할** | 현지 Originator에게 토큰화 모듈을 제공하여 MSME/EWA 채권의 온체인 발행·관리를 가능하게 함 | 글로벌 증권사·금융기관에 STO 발행 인프라를 공급하여 기관용/STO 자산의 토큰화 시장 진입 |
| **파트너 역할** | · **현지 라이선스·규제 대응**은 파트너(Originator)가 담당 — 우리는 기술 제공에 집중 | · **한국** — 장외거래중개업 라이선스 보유 증권사/플랫폼이 투자자 유통 담당 *(논의 필요)* |
| | · 파트너가 보유한 **investor/lender pool · 현지 라이선스**를 통해 투자자 유입 | · **글로벌** — Phase 1 파트너 네트워크를 통해 동남아 리테일 자산의 글로벌 투자자 접근성 확보 |

---

### 01-4. 경쟁 포지셔닝: 기존 Whitelabeling 플랫폼 vs Shard Lab

글로벌 Whitelabeling 플레이어들은 **선진국 기관 자산**에 집중 → 이머징마켓 Private Credit 영역에 공백. Shard Lab은 **동남아/중동 현지 Originator에 임베디드**되는 토큰화 인프라로 이 공백을 메움.

| 구분 | Centrifuge (Whitelabeling) | Securitize (Whitelabeling) | ✓ Shard Lab (Whitelabeling) |
|---|---|---|---|
| **포지셔닝** | **DeFi 네이티브 RWA 인프라** | **End-to-end 증권 토큰화** | **Undersupply market 위주 RWA 인프라** |
| **타겟 고객** | 글로벌 자산운용사, DeFi 프로토콜, 에너지 인프라 기업 | BlackRock·Apollo·Hamilton Lane 등 글로벌 Top-tier 기관 | **OJK/SAMA 인가 P2P·BNPL·SME 렌딩 플랫폼** (Amartha, Modalku, Lendo 등) |
| **핵심 자산군 확장 Path** | 사모대출(MSME/개인) → 사모대출(기관용) → deRWA | 국채 및 공공채권 → 사모 펀드 및 대체투자 → 주식 및 ETF | 사모대출(MSME/개인) → 사모대출(기관용) → deRWA |
| **지리적 집중** | 미국·유럽 중심, 멀티체인 글로벌 배포 | 미국 + EU(스페인 CNMV) — SEC/ESMA 이중 라이선스 | **인도네시아·사우디 집중** → Phase 2 글로벌 (한국 포함) 확장 |
| **보유 라이선스** | SEC Transfer Agent — 2021년 Centrifuge V3 론칭 이후 취득 (플랫폼 성장 후 추후 확보) | SEC Broker-Dealer · Transfer Agent · ATS / EU DLT Pilot (스페인 CNMV) — 2019년 인수, 2024년 추가 (플랫폼 성장 후 추후 확보) | 기술 제공자 (라이선스 불요) — 파트너의 기존 OJK · SAMA 라이선스 활용 → 자체 라이선스 취득 없이 빠른 시장 진입 |
| **Value Proposition** | **리테일 대상 RWA 투자 상품 제공 플랫폼** — $1.3B 누적 배포, DeFi 유동성 연결(Aave·MakerDAO), V3 아키텍처 | **KKR, Apollo 등 Top tier 기관 사모대출 중심의 신뢰 가능한 플랫폼** — $4B+ AUM, BlackRock BUIDL 독점 발행, $1.25B 밸류에이션 | **Undersupply market의 강력한 현지 네트워크 기반, 다양한 RWA 투자 상품 제공 플랫폼** — Originator가 이미 보유한 대출 포트폴리오를 즉시 토큰화 — 전 기능이 이머징마켓에 최적화 |

> **핵심:** 기존 플레이어는 '기관급 자산 온체인화'에 집중. 동남아/중동 P2P·SME 렌딩은 토큰화 인프라 구축 기술력 부재 → Shard Lab이 이 **'기술 공백'**을 메우는 포지션

---

## 02. Market Landscape

> Tokenized RWA × Jurisdiction Matrix

- 현재 RWA 토큰화 시장은 특정 자산군 및 국가에 집중하는 것이 아닌 **멀티 자산 플랫폼으로 진화 중**
- 일부 사모대출에 집중하는 플랫폼이 존재하나, **TVL 기준으로 확장성에 제한적**
- 이는 RWA 시장 역시 투자자가 Asset Class × Jurisdiction를 구별해서 보는 것이 아니라 **플랫폼 자체의 1) 유동성, 2) 리스크, 3) 기술 안정성**을 기준으로 하나로 인식하기 때문

### RWA 토큰화 Jurisdiction × Asset Class 매트릭스

| Jurisdiction | 국채 및 공공채권 | 사모 대출 (기관용) | 사모 대출 (MSME/개인) | 사모 펀드 및 대체투자 | 부동산 | 주식 및 ETF | 원자재 및 금 | IP 및 문화 자산 | 에너지 및 탄소배출권 | deRWA |
|---|---|---|---|---|---|---|---|---|---|---|
| **US** (SEC) | Centrifuge, Hashnote, TrueFi, Ondo (~$9.2B+) | Centrifuge, Maple, Securitize, Figure, Goldfinch (~$18.9B) | Goldfinch, Credix, Creditcoin (~$180M) | Securitize, ADDX (~$1B+) | RealT, Figure, Securitize (~$170M) | Ondo, Securitize, Centrifuge (~$1.2B) | Paxos, Tether Gold (~$3.9B) | Royal, JKBX | Toucan, KlimaDAO, Flowcarbon | Centrifuge, Maple, Pendle (~$5B+) |
| **크립토 친화국** (UAE) | Realize, Ondo | Centrifuge, Fasset (~$900M) | Fasset | ADDX | MANTRA, Prypco (~$1.5B+) | Ondo | Paxos, Tether Gold | — | MANTRA, AirCarbon | — |
| **KR** (FSC) | — | — | — | — | Kasa, Lucentblock, Funble (~₩30B) | — | — | MusicCow, 서울거래소, TogetherArt | — | — |
| **신흥국 (EM)** (ID·SA) | — | — | D3 Labs, Helix (ID $88B 잠재) | — | droppRWA, Tokenize ID | — | — | — | droppRWA | — |
| **Global** (퍼미션리스) | Ondo, Securitize | Centrifuge, Maple, Goldfinch | Goldfinch, Credix, Creditcoin | Securitize, ADDX | RealT, Prypco | Ondo, Securitize | Paxos, Tether Gold | Royal, Story Protocol | Toucan, KlimaDAO | Centrifuge, Maple, Pendle (~$5B+) |

### Credit Structure Guide

#### A. "그릇(Wrapper)" ≠ "내용물(Asset)"

Securitize PE 탭에는 6개 상품이 있지만, 절반은 실질적으로 Credit(부채) 상품. PE 탭에 있는 이유는 법적 구조(사모펀드 LP)가 동일하기 때문.

> ⚠️ **판별법:** 이자를 주면 Credit, 시세차익을 노리면 Equity. 플랫폼 분류(Category)가 아니라 수익 모델로 판단할 것.

| 상품명 | Securitize 라벨 | 실제 기초자산 | 수익 모델 | 본질 |
|---|---|---|---|---|
| Apollo ACRED | Diversified Credit | 직접대출 + 자산담보 + 하이일드 혼합 | 이자 (쿠폰) | → Private Credit |
| AAA CLO Fund | Fixed Income | 선순위 대출 묶음 AAA 트랜치 | 이자 (쿠폰) | → Private Credit |
| Hamilton SCOPE | Senior Credit | 기업 선순위 담보대출 + 워런트 | 이자 + 잠재 지분 | → PC + PE 하이브리드 |
| Hamilton EOV | Direct Equity | 비상장 기업 공동투자 | 시세차익 | → 순수 PE |
| Hamilton Sec. VI | Secondary | 기존 PE 지분 할인 매입 | 시세차익 | → 순수 PE |
| KKR Healthcare | Growth Equity | 비상장 헬스케어 지분투자 | 시세차익 | → 순수 PE |

#### B. Credit 위계 구조 — 리스크 vs 수익률

| 등급 | 수익률 | 설명 |
|---|---|---|
| **Gov Securities** | ~4.5% | 국채/T-Bills. 정부 보증. "은행 금고" |
| **AAA CLO** | ~6.5–7.5% | 수백 개 대출 묶음, 최상위 트랜치. "계급제" — 하위가 먼저 손실 |
| **Diversified Credit** | ~7–9% | 직접대출+자산담보+하이일드 혼합. "혼합 부대" |
| **Senior Credit** | ~9–11% | 기업 1:1 직접대출. 담보 1순위. "전부 공격수" + 워런트 시 PE 겸비 |

> Senior Credit vs AAA CLO: Senior는 전원 동일 리스크 (직접 타격, 수익 높음). AAA CLO는 하위 트랜치가 방패 (안전, 수익 낮음).

---

## 03. Investor Behavior

> 인터뷰 기반 투자자 행동 분석

### 인터뷰 대상

| | 이름 | 프로필 |
|---|---|---|
| **Interview 1** | Aniket (Biconomy) | Crypto HNWIs · 포트폴리오 50%+ 디지털 자산 · BTC 30% / Blue-chip 70% |
| **Interview 2** | Met & Aran (AMS Fund w/ Gulf Binance) | 태국 기반 기관·HNWIs 펀드매니저 · 규제 준수 중심 투자 전략 |

### A. 플랫폼 결정 요소 — "Yield보다 Security"

**Selection Criteria**

- **Interview 1:** Technology 기반 **안정성/보안이 가장 중요**. 매칭 엔진 성능, 스프레드, 즉각적 입출금, 고객 지원이 핵심. Yield는 변동성이 높아 크게 연연하지 않고, 보안과 시스템 안정성을 먼저 확인
- **Interview 2:** **법 테두리 내 기술적 보완과 규제 준수(compliance)**가 보장된 환경이 가장 중요. 정권 교체마다 규제 방향이 달라지므로 기민한 대응이 관건. 태국 'SIX Networks'가 정부 협력으로 신뢰 구축 → local regulatory safety가 1순위

**Alpha Sourcing**

- **Interview 1:** **X(트위터) 커뮤니티**에서 발견 → 직접 리서치 검증: 1) 투자자 누구인지, 2) 플랫폼 얼마나 오래됐는지, 3) 거래량
- **Interview 2:** **'Inner Circle'이 가장 중요**. 창업자-빌더-투자자 간 프라이빗 Alpha group chat, 데모데이, 저녁식사로 정보 공유. 기관투자자는 블록체인 컨퍼런스에서 팀 문화·개발자 역량을 in-person 확인

### B. RWA의 해결 과제 — "유동성 극대화"

**Lock-up Period**

- **Interview 2:** Private credit은 lock-up이 길어 투자자가 두려워함. 적절한 기간은 **7-14일**. 'Liquid staking'처럼 유동성 확보하면서 수익 내는 방식에 익숙. MakerDAO — 실물자산 담보로 DAI 발행, 현금처럼 사용

**자산 유동성 모델**

- **Interview 2:** **"7~14일 내 돈을 뺄 수 있는가?"**가 자산 종류보다 더 중요. MakerDAO처럼 '리퀴드 모델' 공통 적용하면 Multiple 자산 전략이 훨씬 유리. 투자자는 Jurisdiction 신경 쓰지 않음. 돈의 안전한 보호와 접근(회수)만 중요

### C. 브랜드 전략 — "All-in-One Global Shop"

**Brand Architecture**

- **Interview 1:** **안정성이 보장되는 하나의 플랫폼에 모든 것을 다 넣는 것이 유리**. Private credit으로 쌓은 신뢰가 STO 진출 시에도 큰 도움. 믿을 만한 플랫폼 하나를 찾아서 메이저로 이용 (예: "Hyperliquid"만 사용)
- **Interview 2:** **그릇(플랫폼)은 하나, 알맹이(자산)는 유동성 위주 다각화**. 자산 종류보다 '도박 사이트'처럼 안 보이게 **신뢰감 있는 브랜딩**이 중요. 좋은 예시: Pendle — "Liberating Yield". 초기엔 단일 asset class 집중 추천

**UI/UX 선호**

- **Interview 1:** UI/UX는 가능한 한 **단순하고 쉬워야(Simple and Easy)** 유리함
- **Interview 2:** 돈이 **어디로 가고, 어떻게 상환되는지 end-to-end로 모두 파악할 수 있는 UI/UX**가 가장 중요. UX 잘 설계해야 함. 안 그러면 도박 사이트로 인식되기도 함

---

## 04. Brand & Strategy

> 단계별 플랫폼 확장 전략 · 브랜드 포지셔닝

### 4-A. 단계별 플랫폼 확장 전략

#### Phase 1 — 현재 역량 활용 · 플랫폼 기반 구축 `NOW`

- **사업 영역:** GrabJoob 파트너십 기반 인도네시아·사우디 EM 시장 내 MSME 매출채권 및 Gig-worker EWA 자산 담보 대출 상품으로 시장 진출
- **주요 기술:** 토큰화 엔진, KYC/AML 컴플라이언스 API, On/Off Ramp, 기관 커스터디 연동

#### Phase 2 — Asset Class × Jurisdiction 확장 `NEXT`

- **사업 영역:** Phase 1 트랙레코드 기반으로 기관용 PC(CLO), 부동산 STO로 자산군 확장. UAE·싱가포르 등 크립토 친화 관할권으로 다변화
- **주요 기술:** Multi-asset 발행 프레임워크, 크로스보더 결제·환전, 기관급 대시보드 고도화

#### Phase 3 — Liquid Model (deRWA) 도입 `FUTURE`

- **사업 영역:** deRWA 발행 — 대출 채권 소액 유동화, $1 단위 투자 및 즉시 회수. Yield Stripping + DeFi 연동으로 'One Stop RWA Platform' 완성
- **주요 기술:** Yield Stripping 엔진 (PT/YT 분리), DeFi 유동성 풀 연동 (Aave·MakerDAO 등)

### 4-B. 플랫폼 브랜딩 — 네이밍 후보

| 이름 | 의미 |
|---|---|
| **AnchorFi** | 변동성 큰 시장에서 실물 자산이라는 '닻(Anchor)'을 내려 수익을 고정한다는 의미 |
| **PrivaFi** | Private Credit와 DeFi의 앞/뒷글자를 딴 세련된 약칭 |
| **RootFi** | 모든 금융 수익의 뿌리(Root)는 결국 실물 경제의 대출과 자산에서 온다는 철학 강조 |
| **Velos** | Velocity(속도)의 어근. 자금 회전 속도가 빠른 스마트한 사모 대출 인프라임을 강조 |
| **Synchro** | 현실의 자금 흐름과 온체인 데이터를 실시간으로 동기화(Sync)한다는 기술적 신뢰 강조 |
| **A-set** | Asset(자산)의 줄임말 + "A-Set(한 세트)" = 완벽한 자산 구성(A-set)이라는 의미와 "자산을 세팅하다"라는 중의적 표현 |
| **KASU** | 일본어로 '카수(貸す)'는 "빌려주다(Lend)"라는 뜻. Private Credit 플랫폼으로서의 뿌리를 강조 |
| **BADA** | 한국어로 시원하게 트인 "바다"이자, 수익을 "받아!"라는 명령형과 동음. 일본어로 바다(場多)는 "기회가 많은 곳"으로도 해석 가능 |

---

## 05. Benchmarking — 실패 사례 분석

### Goldfinch Protocol
- **유형:** EM Private Credit · Ethereum · 2021~
- **TVL:** 50M+ → ~$100M 정체
- **실패 요인:**
  - **디폴트:** Stratos Markets 3건($7M) 포함 7건+ 상환 지연/디폴트 — DeFi 최대 사모대출 손실 사례
  - **이해충돌:** 차주(Stratos)가 Goldfinch 투자자이자 어드바이저 — 자금을 미공개 크립토에 전용
  - **유동성 고착:** 대출 만기 1~4년으로 LP 출금 불가 장기화, Senior Pool 이용률 98%

### Credix Finance
- **유형:** EM 사모 대출(브라질) · Solana · 2022~
- **결과:** 사실상 중단 — DeFi → B2B SaaS 피벗
- **실패 요인:**
  - **단일 시장 리스크:** 브라질 EM 사모 대출에 과도하게 집중 → 지역 분산 실패
  - **Solana 생태계 의존:** FTX 붕괴 이후 Solana DeFi TVL 급감과 함께 자금 유입 감소
  - **비즈니스 피벗:** 온체인 DeFi 대출에서 전통 B2B 신용 SaaS로 전환 — 온체인 모델 포기
  - **규모의 경제 실패:** $11.25M 조달에도 TVL $50M 미만, 수수료 모델 구축 실패

### Creditcoin (CTC)
- **유형:** L1 크레딧 프로토콜 · 2019~
- **결과:** ATH 대비 -97% ($8.71 → ~$0.25)
- **실패 요인:**
  - **TVL 부재:** 자체 L1에 대출 기록만 존재, 실질적 자금이 잠긴 TVL이 사실상 0
  - **토크노믹스 논란:** Bithumb '주의 자산' 지정(2025.4) → 66% 급락, 거래소 신뢰 상실
  - **유틸리티 부족:** 토큰이 거버넌스용이나 실질적 수요 창출 메커니즘 부재
  - **경쟁력 상실:** Centrifuge·Maple 대비 차별화 없이 '마이크로론 기록' 수준에 정체

---

## ★ For Team Discussion (Internal Only)

### 6-Month Plan

| 월 | 🤝 Business Development | ⚙️ Product |
|---|---|---|
| **M1-2** | 🎯 **Anchor Originator 소싱 및 MOU 체결** `최우선` — 인니/사우디 현지 P2P·SME 대출 플랫폼 1순위 후보 접촉 → Pilot 제안 → MOU 체결 및 기술 연동 요건 합의 | **프론트엔드 / 백엔드 / Admin 개발** `최우선` — 플랫폼 코어 프론트엔드·백엔드 아키텍처 구축 및 파트너 운영용 Admin 대시보드 개발 |
| | **Whitelabeling 상업 모델 설계 및 Pricing 확정** `선순위` — Setup Fee + SaaS + Tx Fee 3-tier 과금 모델 설계 → 파트너별 커스텀 패키지 확정 (초기 파트너 Setup Fee 면제 인센티브) | |
| **M3-4** | **Anchor Pilot 런칭 및 트랙레코드 생성** `최우선` — 첫 번째 대출채권 토큰화 실행 — 실제 운영 데이터 기반 트랙레코드 확보 | **주요 모듈 설계 및 개발** `최우선` — 토큰화 엔진 · KYC/AML · On/Off Ramp · Distribution · Custody 등 핵심 모듈 설계 및 개발 |
| | **2순위 Originator 파이프라인 구축** `선순위` — 다양한 자산 유형(인보이스·운전자금·BNPL) Originator 2~3개사 추가 접촉 및 소싱 | **화이트라벨 아키텍처 설계** `선순위` — 파트너가 자체 브랜드로 독립 운영 가능한 멀티테넌트 화이트라벨 구조 설계 |
| **M5-6** | **Originator 파이프라인 확장 (3~5개사)** `선순위` — Anchor Pilot 트랙레코드 기반으로 추가 Originator 소싱 → Pilot 계약 및 기술 연동 | **주요 모듈 API 통합** `최우선` — 토큰화 엔진 · Custody · KYC/AML 등 핵심 모듈 간 API 연동 및 엔드투엔드 통합 테스트 |
| | **글로벌 GP 네트워크 사전 태핑** — Phase 2 기관용 확장 대비 대형 운용사 RWA 담당자 초기 미팅 및 Whitelabeling 인프라 컨셉 제안 | **멀티 Originator 동시 운영 체계 구축** `선순위` — 복수 파트너가 독립적으로 운영 가능한 테넌시(Tenancy) 구조 완성 및 운영 안정성 검증 |

---

### Originator 파트너사 리스트

> Whitelabeling 모델의 핵심은 **이미 대출 채권을 보유하고 있는 현지 Originator**를 확보하는 것 — 아래 리스트는 OJK/SAMA 라이선스를 보유하고 실제 대출을 집행 중인 플랫폼으로, 토큰화 인프라 도입 시 **즉시 자산 공급**이 가능한 후보군

#### 🇮🇩 인도네시아 Originator (OJK Licensed · P2P/SME Lending)

**Tier 1 — 대규모 Originator (Anchor Client 후보)**

| Originator | 개요 | 자산 유형 |
|---|---|---|
| [Akulaku](https://www.akulaku.com) | 동남아 4개국 통합 금융 생태계(인니·필리핀·베트남·말레이) — BNPL + P2P + 전자상거래. Ant Group 투자, **유니콘 ($2B)** | BNPL·소비자 대출 |
| [Kredivo](https://www.kredivo.com) | 인도네시아 최대 디지털 신용 플랫폼 — AI 기반 즉시 신용 승인, 3,000만 건+ 대출 집행. Multi-finance 라이선스 보유. Mizuho·Victory Park Capital 투자 | 소비자 신용·BNPL |
| [Modalku](https://modalku.co.id) | Funding Societies 인도네시아 법인 — 동남아 최대 P2P SME 대출 플랫폼, 누적 IDR 65조 집행(동남아 5개국). Softbank·Sequoia 투자 | SME 단기 운전자금 |
| [Amartha](https://amartha.com) | 마이크로파이낸스 테크 플랫폼 — 농촌 여성 소상공인 대상 그룹 대출 모델, 누적 IDR 35조(~$2.1B) 집행, 330만+ MSME 서비스. Accion·Mastercard 파트너 | 마이크로 운전자금 |

**Tier 2 — 특화형 Originator (자산 다변화 후보)**

| Originator | 개요 | 자산 유형 |
|---|---|---|
| [KoinWorks](https://koinworks.com) | 종합 핀테크 플랫폼 — SME 대출·교육 대출·사업자금 제공, 네오뱅크 기능 확장. MDI Ventures·Quona Capital 투자, 누적 IDR 1.6조 Series C | SME·교육 대출 |
| [Danamas](https://danamas.co.id) | Sinar Mas Group 계열 P2P — OJK 최초 라이선스 취득 플랫폼, 소상공인 마이크로 대출 특화. 대기업 계열 안정성 | 마이크로 대출 |
| [Alami](https://alamisharia.co.id) | 인도네시아 대표 샤리아 P2P 렌딩 — OJK 인가 이슬람 금융 전문 플랫폼, SME 대상 무라바하(Murabahah) 기반 파이낸싱 | 샤리아 SME 대출 |

#### 🇸🇦 사우디 Originator (SAMA Licensed · Debt Crowdfunding)

**Tier 1 — SAMA 인가 SME 대출 플랫폼**

| Originator | 개요 | 자산 유형 |
|---|---|---|
| [Funding Souq](https://fundingsouq.com) | 사우디·UAE 이중 라이선스 보유 P2P — SAMA + UAE DFSA 인가, 글로벌 투자자 접근 가능. SME 채무 크라우드펀딩 전문 | SME 채무 크라우드펀딩 |
| [Lendo](https://lfrtech.com) | 사우디 대표 P2P 인보이스 파이낸싱 플랫폼 — SAMA 인가, 샤리아 적합. SME 미수금 선지급 전문. Derayah·Shorooq·500 Startups 투자 ($7.2M Series A) | 인보이스 파이낸싱 |
| [Raqamyah](https://raqamyah.com) | SAMA 인가 샤리아 크라우드렌딩 — SME 대상 직접 대출 연결, POS 연동 자동 상환 시스템 도입. Impact46 투자 | SME 직접 대출 |
| [Forus](https://forus.sa) | SAMA Sandbox 출신 크라우드펀딩 — SME 성장 자금 전문, 차별화된 차주 프로필링 기술. 개인·기관 투자자 모두 수용 | SME 성장 자금 |

**Tier 2 — BNPL / 소비자 금융 (대규모 자산 풀)**

| Originator | 개요 | 자산 유형 |
|---|---|---|
| [Tabby](https://tabby.ai) | GCC 최대 BNPL 유니콘(**$3.3B**) — 사우디/UAE/쿠웨이트 운영, 디지털 지갑·카드 등 종합 금융. 단기 할부 채권 대규모 보유 | BNPL 할부 채권 |
| [Tamara](https://tamara.co) | GCC BNPL 유니콘(**$1B**) — 2,000만 고객, 87,000 가맹점. Goldman Sachs·Citi $2.4B 파이낸싱 확보. 대규모 소비자 채권 풀 보유 | BNPL 소비자 채권 |
| [Roya Financing](https://royafinancing.com) | SAMA 인가 금융사 — 개인·SME 대상 샤리아 적합 대출, 차량·사업자금 등 맞춤형 파이낸싱 특화 | 개인·SME 대출 |

#### 🌐 Phase 2 확장 후보 (Institutional · Korea)

| 파트너사 | 개요 | 유형 |
|---|---|---|
| [Shoreline Capital](https://www.shorelinecap.com) | 아시아 사모대출 전문 펀드 — 특수 상황(Special Situations) 크레딧 투자에 특화 | 기관용 PC |
| [SeaTown Holdings](https://www.seatownholdings.com) | Temasek 자회사, 싱가포르 본사 — 사모대출·크레딧 전략 운용 | 기관용 PC |
| [IMM 인베스트먼트](https://www.immgroup.com) | 한국 최대 규모 대체투자 운용사 — 메자닌 대출, 사모대출 블라인드 펀드 | 한국 기관 PC |
| [VIG 파트너스](https://www.vigpartners.com) | 한국 미드캡 사모펀드 — VIG Alternative Credit 별도 법인 운영 | 한국 기관 PC |

#### 🔐 인프라 파트너사 (KYC · Custody · Infra)

| 파트너사 | 개요 |
|---|---|
| [Sumsub](https://sumsub.com) | 글로벌 KYC/AML 인증 플랫폼 — 220개국 14,000+ 문서 검증, AI 기반 신원확인·AML 스크리닝·트랜잭션 모니터링. Revolut·Mercuryo 등 2,000+ 기업 사용 |
| [KDAC](https://www.kdac.co.kr) (한국디지털자산수탁) | 신한은행 전략 투자 한국 디지털자산 수탁 전문사 — 에어갭 환경·멀티시그 기반 보관, ISMS 인증 |

---

### Regulation Monitoring `URGENT`

STO 법안은 이미 통과(2026.1.15)되었으나, **디지털자산기본법(스테이블코인)**은 은행 51%룰·거래소 지분제한 등 핵심 쟁점이 남아 있어 **3월 초 절충안 확정 후 3월 중순 발의**가 예상됨 — 은행 중심 구조 고착화 시 후발 진입 문턱이 높아지므로, **TF 최종안 확정 시점에 맞춰 한국 시장 진입 전략 수립** 필요.

#### 📡 한국 디지털자산기본법 · 스테이블코인 TF (Last updated: 2026.02.26)

| 날짜 | 출처 | 제목 | 요약 |
|---|---|---|---|
| 2026.02.25 | 헤럴드경제 🔥 | 디지털자산기본법 은행 중심 컨소·거래소 지분제한 절충안 착수 | 민주당 디지털자산 TF가 은행 중심 컨소시엄(50%+1주)·대주주 지분제한 절충안 마련 작업에 착수. 이르면 **3월 중순 발의** 예상 |
| 2026.02.24 | 이투데이 🔥 | 與, 스테이블코인·대주주 지분 '절충안' 이르면 다음주 마련 | 자문위원 17명이 참석한 TF 회의 진행. 법안의 **95% 합의 완료**, 나머지 5% 쟁점 조율 중. 3월 초 통합안 윤곽 전망 |
| 2026.02.24 | 파이낸셜투데이 | 스테이블코인 입법 공백…은행권, 컨소시엄 선점 경쟁 격화 | 입법이 표류하는 사이 은행 중심 컨소시엄 가시화 — **시장이 제도보다 앞서가는 상황**. 은행 중심 구조 고착화 시 후발 진입 문턱 상승 우려 |

---

### VASP 라이선스 참고

#### 🇸🇬 싱가포르: MAS (PSA 라이선스)

규제가 매우 깐깐하지만, 한번 취득하면 전 세계 기관 투자자들에게 **'최고 수준의 신뢰'** 확보 가능

- **SPI** (Standard Payment Institution): 월 거래액 300만 SGD 이하 소규모
- **MPI** (Major Payment Institution): 월 거래액 300만 SGD 초과 대규모 (대부분의 플랫폼이 지향)
- **현지 법인:** 싱가포르 내 실제 사무실과 장부 보관 필수
- **인력:** 싱가포르 상임이사(Resident Director) 1명 이상 반드시 필요
- **자본금:** MPI 기준 최소 25만 SGD(약 2.5억 원) + 보증금 20만 SGD
- **기술/보안:** 독립적인 외부 사이버 보안 감사 및 AML 리포트 제출
- **소요 시간:** 약 **12개월~18개월**

#### 🇦🇪 UAE (두바이): VARA 라이선스

세계 최초 가상자산 전담 규제 기구 VARA 설립; 상대적으로 **'Web3 친화적'**이며 승인 속도가 빠르고 거래액 요건이 없어 **지금 시도하기 최적안**

- **현지 법인:** 두바이 본토(Mainland) 또는 프리존(DWTCA 등) 법인 설립
- **인력:** 준법감시인(Compliance Officer) 및 돈세탁방지책임자(MLRO) 상주 필수
- **자본금:** 라이선스 유형별 상이, 보통 수억 원 단위의 자본금 증빙과 연간 감독 수수료
- **규제 준수:** VARA가 요구하는 4단계 규제 매뉴얼 구축
- **소요 시간:** 약 **6개월~10개월**

---

*EmergeFi · RWA Tokenization Platform · Confidential · February 2026*
