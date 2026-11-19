# 한국 전력기기 vs 미국/중국 — 미국 AI 데이터센터 공급망 연구 착수 (2026-11-17)

- **Status**: `NEW_THEMATIC_RESEARCH / SCREENING_ONLY / NO_BUY_APPROVAL`
- **Owner 신규 질문**: "우리나라 전력기기가 세계에서 가장 좋나? 미국 데이터센터에 중국 전력기기나 미국 전력기기를 쓸 가능성이 있나?"
- **기존 범위 불변**: JBTM/PAHC 단백질 핵심 트랙, VRT/MRVL AI 인프라 트랙과 구분. 이번 파일은 별도의 전력 인프라 연구 시작점.

## 1. 요약 결론
1. 한국의 고압·초고압 변압기는 수출/납기/공급능력에서 세계 주요 강자. 그러나 **전력기기 세계 1위라는 단일 순위는 정립 불가**. 제품·전압별 실증 reliability, 원가, A/S, 납기, 인증 및 자본수익률로 분류.
2. 미국 기업·미국 현지 생산이 대규모로 사용됨. 데이터센터 *내부* 배전/UPS/PDU 등은 Eaton, Schneider Electric(프랑스지만 미국 현지생산), Vertiv, GE Vernova, ABB, Siemens 등 강력 경쟁사. '미국에서 중국 제품만 배제되면 한국이 시장을 독식한다'는 가설은 기각.
3. 중국산/중국 통제 장비는 보안/규제/관세/고객 조달기준에서 위험이 높으나 **전면 불법 또는 모든 중국산 전력기기의 미국시장 완전 퇴출은 아님**. 데이터센터 내부 장비와 미국 69kV 이상 bulk-power system의 규제 적용이 동일하지 않음.
4. 한국 업체는 미국 현지 생산/서비스를 확장 중: 효성 HICO 멤피스 765kV, HD현대일렉트릭 앨라배마, LS ELECTRIC 유타/텍사스. 수출 경쟁력 + 미국 현지화.
5. 납기 부족은 중요한 단기 가격 결정요인이지만 투자 시 **생산 CAPA 증설 이후 공급과잉/가격 정상화**를 Bear case로 모델링.

## 2. 제품별 비교: 데이터센터 외부~내부
| 장비/시장 | 미국 DC 어디에 쓰나 | 한국 공개 상장사 | 글로벌 경쟁 |
|---|---|---|---|
| 345/765kV 등 대형 변압기 | 발전/송전망~DC 연결 변전소 | HD현대일렉트릭, 효성중공업 | GE Vernova/Prolec, Hitachi Energy, Siemens Energy, WEG |
| 배전변압기/중압 차단·스위치기어 | 캠퍼스 13.8/38kV 등 배전 | LS ELECTRIC, HD현대일렉트릭 | Eaton, Schneider, Siemens, ABB, Powell 등 |
| 저압 switchgear, busway, UPS/PDU | 서버동 내부 및 랙 전력 | LS ELECTRIC(일부), 기타 | Eaton, Schneider, Vertiv, Legrand, nVent, ABB |
| 초고압 제어/보호/디지털 계전 | 계통 안정성·원격제어·보안 | 한국 업체별 확인 | 글로벌 보호계전/그리드 솔루션 공급사 |

- 개별 현장 조달/실제 설치에서 각사가 차지하는 매출을 공개 EPC·공급계약과 연결하기 전에는 혼합하지 않음.
- 전기적 적합성(전압·주파수), ANSI/IEEE/NEMA/UL/IEC 인증, 신뢰성/사후서비스, 배터리/UPS 운영·사이버보안, 미국 설비 기준·설치사 선호가 복합 진입장벽.

## 3. 수요와 수입 구조: 확인된 1차 근거
- [USITC 2026 working paper](https://www.usitc.gov/publications/332/working_papers/behind_the_trade.pdf): 미국 *액체유전체 변압기* 수입의 주요 공급국은 멕시코와 한국. 두 국가는 2022~24 합계 수입의 50% 이상. **이 세부 품목 수입 데이터**를 미국 전력기기 전체 점유율로 확대해석 금지. 연구진 서술은 해당 대형 변압기 생산부족으로 일부 국내 공급이 수요 20% 수준. 원문 그림 6.1 참조.
- [CRS 2026-04 distribution transformer](https://www.everycrsreport.com/reports/R48933.html): *배전변압기*의 미국 수입의존은 약 25~30%; 주 수입처 대만/캐나다/멕시코 등으로 대형 변압기 수입 통계와 다른 분모. 약 34개 OEM(2024 DOE 기준).
- [Reuters 2026-05-11](https://www.reuters.com/business/energy/us-power-transformer-buyers-scramble-imports-factory-slots--reeii-2026-05-11/): 데이터센터+그리드 증설/제조업으로 대형 변압기 리드타임 일부 4년, 공급 증설 경쟁; 2019~25 기간 GSU 변압기 수요 증가, 공급 병목은 5년 이상 지속될 수 있다는 전문가 의견(예측).
- [Eaton 공식 2026Q3](https://www.eaton.com/us/en-us/company/news-insights/news-releases/2026/eaton-reports-record-third-quarter-2026-results.html): Electrical Americas 매출 $4.2B(+22% organic), 영업이익 $1.2B/마진29.8%, 전기부문 수주잔고 강함. **미국 자체의 강력한 경쟁 증거**.
- [GE Vernova Prolec 2026-02](https://www.gevernova.com/news/press-releases/ge-vernova-completes-prolec-ge-acquisition): GE Vernova는 Prolec GE 잔여 50% 인수, 북미 미/멕시코 변압기 제조 7개 공장(미국 내 5개). 미국산 공급 채널 확장.

## 4. 중국·외산 장비의 미국 보안 규제: 과대해석 금지
- [White House EO 14421, 2026-08-26](https://www.whitehouse.gov/presidential-actions/2026/08/declaring-a-national-emergency-to-secure-the-united-states-bulk-power-system/):
  - 미국 *bulk-power system* 69kV 이상 송전망 및 관련 발전/변전/제어 설비 중심. 로컬 배전 설비 전체에 자동 적용되는 것은 아님.
  - Covered Foreign Entity(미국의 특정 무기금수·제재 대상국 또는 위험 지정 주체) 연계·위험 판단을 충족하는 외산 거래에 제한. **중국산 모든 장비 일괄 금지 아님**, 한국산 모든 장비 자동 허용도 아님.
  - 디지털 소프트웨어/펌웨어/원격관리 등 보안 민감도 높음. 향후 규정 및 사전승인·조달 우선순위 변동 가능; 2026-11-17 현재 개별 고객 조달정책 및 적용 규칙은 `UNKNOWN`.
  - 정책 방향과 구매사 정책을 분리. 미국 조달에서 현지생산업체(미국계 또는 한국계) 프리미엄 가능.
- [DOE 2020 중국 조달 제한](https://www.energy.gov/articles/secretary-energy-signs-order-mitigate-security-risks-nations-electric-grid)은 당시 특정 국방 핵심 시설 전력망에 적용; [DOE 후속 설명](https://www.energy.gov/ceser/securing-critical-electric-infrastructure)은 2020 조달 금지 조치 철회 명시. 이를 2026년 현재 전면 금지로 인용하는 것은 잘못.

## 5. 한국 업체의 실제 2026 경쟁실적
- **HD현대일렉트릭 (267260)**: 2026Q3 매출 1조1,799억원, 영업이익 2,845억원, 마진 24.1%, 북미 전력 변압기 수요 확대; 2026-09 말 전체 수주잔고 약 $8.84B. [연합뉴스 2026-10-27](https://en.yna.co.kr/view/AEN20261027006451320); 1회성 환율과 변압기/배전 믹스 반영 검증 요.
- **효성중공업 (298040)**: 2026Q3 영업이익 약 2,435억원(외부 기사 기준, 주력 전력/건설 분리 필요). 2026-09 미국 빅테크 2곳에 765kV·345kV 변압기 약 $287M 수주 [효성 공식](https://www.hyosung.com/en/newsroom/view/19333). 테네시州 공식 2025-11 [멤피스 $157M 확장 계획/765kV 미국 내 전용 생산](https://www.tn.gov/ecd/news/2025/11/12/hyosung-hico--ltd--expands-u-s--manufacturing-headquarters-for-second-time-in-six-months.html).
- **LS ELECTRIC (010120)**: 2026Q3 매출 약 1조8,780억원, 영업이익 약 2,335억원, 마진12.4%, 연간 3Q 기준 실적 [KB증권 2026-10](https://rdata.kbsec.com/pdf_data/20261021102459960K.pdf). 2026-10-19 미국 AI DC 38kV 스위치기어 약 1,700억원 계약 [연합뉴스](https://en.yna.co.kr/view/AEN20261019002700320), 2026-11-16 **추가** DC 38kV+저압 배전 ~$93.83M 계약 [연합뉴스](https://en.yna.co.kr/view/AEN20261116002700320); 계약 간 중복/프레임 조건 확인 전 합산 금지. [LS 미국 유타 공장 증설](https://nahp.ls-electric.com/company/press/3427/ls-electric-accelerates-north-american-growth-with-ls-electric-utah-expansion) 2030년까지 약 $168M 투자·스위치기어 생산능력 3배 계획; 미래 CAPEX/실현 가정.
- **Schneider** 2026Q3 NA Energy Management organic +20.3% [공식 2026Q3 공개자료](https://docs.publicnow.com/viewDoc?filename=23116%5CEXT%5C9793FE51F899E54DDF5AF288EB6AE12FECF561A9_78DF8C1484BC09DD3983BA3CFA0E3B5DE5FD4683.PDF). 비교 경쟁사 규모 확인; 미국 기업이 아니라 프랑스 본사.

## 6. 투자 스크리닝과 미확정 쟁점
- **Direct DC electrical fit**: LS ELECTRIC/ETN/Schneider/VRT — 실제 현장 배전·전력품질/PDU/UPS 노출.
- **Grid transformer fit**: HD현대일렉트릭/효성중공업/GEV/Hitachi/Siemens — DC·일반 그리드·노후 변압기 교체 수요.
- 회사별 주가/PER/PFCF/2027~30 GAAP EPS와 영업현금흐름, 미국 DC **직접** 매출 비중, 내부공급/현지 생산, 신규 CAPA 가동시점, 전력기기별 이익률, 최대고객 집중도, 신용/환위험, Section 232/301 관세 적용은 **아직 계산·판정하지 않음**.
- 기술 최고 기업에 대한 엄밀한 실측 비교(고장률·손실률·납기·IEEE 인증·TCO·서비스 네트워크)와 hyperscaler 물량/공급계약 검증이 필수.
- **Bear case**: 2028 이후 공급 CAPA 확대/미국 내재화/수요 지연/수입규제, 해외 경쟁사 역공, 수주잔고의 마진 정상화, 데이터센터의 전력 공급접속 규제로 발주 지연.
- **다음 연구 과제**: 한국 3개사 + 미국 ETN/GEV를 **동일 기준**으로 DC 직접 매출·고압 변압기 사업·전기 사업 GAAP EBIT/FCF/시총·EPS·추정 2028 생산능력을 비교. 중국산 설치·조달의 실제 사례는 프로젝트 단위로 확인(모든 업체 중국산 제품 배제/채택 임의 단정 금지).
- **최종 상태**: `POWER_EQUIPMENT_INITIAL_SCREEN_COMPLETE / NO_SINGLE_GLOBAL_BEST / KOREAN_TRANSFORMER_GLOBAL_LEADERS / US_IN_HOUSE_EQUIPMENT_STRONG / CHINA_GRID_RISK_MATERIAL / NO_BUY_APPROVAL`.

## 2026-11-19 추가 대화 보존·후속 정량 비교 (기존 11/17 1차 조사 유지)

- [전체 원문 851–1368행](SOURCE_TRANSCRIPT_20261119_USER_SUPPLIED.txt#L851-L1368)에서 미국 LS 현지제조와 한국 전력 3사·미국/중국 경쟁에 관한 후속 질의/과거 PM 답변 추가 확인.
- [LS ELECTRIC Utah/Texas 공장 별도 경제성](LS_ELECTRIC_US_MANUFACTURING_PROFITABILITY_20261119.md): 2026Q3 연결 영업률과 **미국 현지 공장 이익률은 별개**, Utah $168M/2030 CAPA3x, ROIC/제품별 현지 제조 실제 부가가치 검증.
- [한국 3사 2026Q3 수치·2027E 선행 PER·순위 변경·EO 14421](KOREA_POWER_EQUIPMENT_TOP3_VALUATION_EO_CHINA_US_20261119.md): HD현대일렉트릭>LS>효성 잠정 사업/밸류에이션 연구 선호, AI DC 내부 직접성은 LS 우선, 이후 **동일 분모 owner FCF 재계산 전 원픽 보류**의 세 구분. 과거 시세·추정 EPS는 최신 재조회 필요.
- 중국 2024 저압 변압기 수입비중 54%라는 이전 답변은 `PREVIOUS_CHAT`으로 분리, 고압 수입 한국/멕시코 비중과 다른 세부 시장. 미국 안보명령 모든 중국 장비 자동 금지 금지.
- 당일 기존 결론은 매매/비중 변경 없음, 기존 JBTM·PAHC 투자 Core 2 자동 교체 없음.
