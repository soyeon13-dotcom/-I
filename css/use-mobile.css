/* ============================================================
   USE — Mobile-First Override
   대상: @media (max-width: 768px)
   지시 원칙:
     · 전체 재작성 없이 추가/수정 스타일만 선언
     · 모든 인터랙션 요소 min-height 56px 이상
     · 기본 본문 폰트 16px 이상
     · Fat Finger 방지 (중장년층 타겟)
   ============================================================ */

@media (max-width: 768px) {

  /* ----------------------------------------------------------
     DESIGN TOKENS — 모바일 재정의
     ---------------------------------------------------------- */
  :root {
    --grid-gutter: 18px;          /* 데스크톱: 100vw*3/16 → 모바일: 18px 고정 */
    --header-h:    60px;          /* 헤더 높이 소폭 축소 */
    --sidebar-w:   0px;           /* 사이드바 없음 (이미 0이지만 명시) */
  }

  /* ----------------------------------------------------------
     RESET 보완 — 모바일 기본 폰트
     ---------------------------------------------------------- */
  body {
    font-size: 16px;
  }

  /* ----------------------------------------------------------
     ONBOARDING SHELL
     ---------------------------------------------------------- */
  .ob-page {
    padding: 28px var(--grid-gutter) 40px;
    align-items: flex-start;
  }

  .ob-card {
    max-width: 100%;
    padding: 24px 0 0;
  }

  /* 로그인/회원가입 배경 카드 */
  .auth-bg .ob-card {
    padding: 32px 24px 28px;
    border-radius: 16px;
  }

  .ob-h2  { font-size: 24px; }
  .ob-sub { font-size: 16px; margin-bottom: 20px; }

  .ob-skip {
    top: 20px;
    right: 20px;
    font-size: 15px;
  }

  .ob-back {
    font-size: 16px;
    margin-bottom: 20px;
  }

  /* ----------------------------------------------------------
     BUTTONS — Fat Finger 보장
     ---------------------------------------------------------- */
  .btn-primary,
  .btn-accent {
    min-height: 56px;
    font-size: 17px;
  }

  .btn-secondary,
  .btn-outline {
    min-height: 56px;
    font-size: 16px;
  }

  .btn-ghost { min-height: 52px; font-size: 16px; }

  .det-dl-btn,
  .det-share-btn { min-height: 56px; font-size: 16px; }

  .btn-save { height: 56px; font-size: 17px; }
  .btn-app  { height: 56px; font-size: 16px; }
  .btn-danger { height: 56px; }
  .use-btn  { height: 52px; font-size: 15px; }

  .hero-use-btn    { height: 56px; font-size: 17px; }
  .hero-detail-btn { height: 56px; font-size: 15px; }

  .dl-btn {
    height: 52px;
    font-size: 15px;
  }

  /* Pill download 버튼 */
  .pill-dl-btn {
    height: 52px;
    font-size: 15px;
  }

  /* 사회 로그인 버튼 */
  .social-btn { min-height: 56px; font-size: 16px; }

  /* ----------------------------------------------------------
     INPUT FIELDS
     ---------------------------------------------------------- */
  .field-wrap {
    min-height: 56px;
    padding: 0 16px;
    margin-bottom: 12px;
  }

  .field-wrap input { font-size: 17px; }
  .field-prefix     { font-size: 16px; }

  /* 성별 버튼 */
  .gender-btn { min-height: 56px; font-size: 16px; }

  /* SMS 발송 버튼 */
  .btn-sms-send,
  .btn-sms-resend { min-height: 56px; font-size: 15px; }

  /* 생년월일 */
  .birth-input { min-height: 52px; font-size: 16px; }

  /* 이메일 도메인 */
  .email-domain-wrap { min-height: 56px; }
  .email-domain-wrap select { font-size: 16px; }

  /* OTP */
  .otp-big-wrap .field-wrap { min-height: 56px; }

  /* ----------------------------------------------------------
     OPTION CARDS (온보딩 선택)
     ---------------------------------------------------------- */
  /* 3열 → 2열 */
  .opt-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
    margin-bottom: 20px;
  }

  .opt-card { padding: 22px 14px; min-height: 88px; }
  .opt-card .opt-title { font-size: 16px; }
  .opt-card .opt-sub   { font-size: 13px; }

  /* 카테고리 칩: 6열 → 3열 */
  .cat-grid {
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-bottom: 20px;
  }

  .cat-chip { padding: 18px 8px; font-size: 14px; min-height: 64px; }

  /* 브랜드 칩: 8열 → 4열 */
  .brand-grid {
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    margin-bottom: 20px;
  }

  .brand-chip { padding: 14px 6px; font-size: 13px; min-height: 56px; }

  /* 서비스 연동 리스트: 3열 → 1열 */
  .svc-grid {
    grid-template-columns: 1fr;
    gap: 10px;
  }

  .svc-card { padding: 14px 16px; }

  .conn-btn {
    padding: 10px 16px;
    font-size: 14px;
    min-height: 44px;
  }

  /* 빠른선택 칩 */
  .quick-sel-chip {
    padding: 10px 18px;
    font-size: 14px;
    min-height: 44px;
  }

  /* ----------------------------------------------------------
     SIGNUP SPLIT LAYOUT → 단일 열 (우측 폼만 표시)
     ---------------------------------------------------------- */
  .su-split {
    grid-template-columns: 1fr;
    max-width: 100%;
    min-height: auto;
    border-radius: 0;
    box-shadow: none;
  }

  /* 데스크톱 왼쪽 브랜드 패널은 모바일에서 최소화 */
  .su-left {
    padding: 28px var(--grid-gutter) 20px;
    min-height: auto;
  }
  .su-left h1 { font-size: 26px; margin-bottom: 10px; }
  .su-left p  { font-size: 15px; margin-bottom: 20px; }
  .su-left-benefits { gap: 10px; }
  .b-txt { font-size: 15px; }

  .su-right {
    padding: 24px var(--grid-gutter) 32px;
  }
  .su-right h2 { font-size: 22px; }

  /* ----------------------------------------------------------
     APP HEADER — 모바일 단순화
     ---------------------------------------------------------- */
  .app-header {
    padding: 0 var(--grid-gutter);
    gap: 10px;
  }

  .hdr-logo { font-size: 20px; }

  /* 상단 네비게이션 숨김 — 하단 탭바로 대체 예정 */
  .hdr-nav { display: none; }

  /* 헤더 우측 버튼 축소 */
  .hdr-bell-btn,
  .hdr-mypage-btn {
    height: 40px;
    padding: 0 12px;
    font-size: 13px;
  }

  /* 알림 드롭다운 → 전체 폭 bottom sheet 스타일 */
  .noti-dropdown {
    position: fixed;
    top: auto;
    bottom: 0;
    left: 0;
    right: 0;
    width: 100%;
    border-radius: 20px 20px 0 0;
    max-height: 80vh;
    transform: translateY(8px) scale(1); /* scale 제거 */
  }

  .noti-dropdown.open {
    transform: translateY(0) scale(1);
  }

  .noti-drop-body { max-height: 60vh; }
  .noti-item-title { font-size: 15px; }
  .noti-item-sub   { font-size: 13px; }

  /* ----------------------------------------------------------
     MAIN CONTENT — 사이드바 제거, 패딩 조정
     ---------------------------------------------------------- */
  .app-body {
    padding-top: var(--header-h);
    height: 100dvh; /* Dynamic Viewport Height (iOS Safari 대응) */
  }

  .main-content {
    margin-left: 0;
    padding: 20px var(--grid-gutter) 80px; /* 하단 탭바 공간 확보 80px */
  }

  .page-title { font-size: 22px; margin-bottom: 4px; }
  .page-sub   { font-size: 15px; margin-bottom: 20px; }

  /* ----------------------------------------------------------
     하단 탭바 예약 클래스 — JS로 동적 생성 시 즉시 적용
     ---------------------------------------------------------- */
  .bottom-tab-bar {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    height: 64px;
    background: white;
    border-top: 2px solid var(--gray-200);
    display: flex;
    align-items: stretch;
    z-index: 200;
    box-shadow: 0 -4px 16px rgba(0, 0, 0, .08);
  }

  .tab-bar-item {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 4px;
    font-size: 11px;
    font-weight: 700;
    color: var(--gray-400);
    cursor: pointer;
    min-height: 64px;
    transition: color .15s;
  }

  .tab-bar-item.on   { color: var(--primary); }
  .tab-bar-item-icon { font-size: 22px; }

  /* ----------------------------------------------------------
     HOME LAYOUT — 2열 그리드 → 단일 열
     ---------------------------------------------------------- */
  .home-layout {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  /* 우측 패널을 하단에 배치 */
  .right-panel {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  /* 패널 카드 */
  .panel-card { padding: 16px; }
  .panel-title { font-size: 15px; margin-bottom: 12px; }
  .stat-val { font-size: 20px; }

  /* ----------------------------------------------------------
     HOME: 쿠폰 캐러셀 (만료 임박)
     ---------------------------------------------------------- */
  .carousel-wrap { margin-bottom: 20px; }

  /* 카드 폭: 1장이 뷰포트의 ~78%로 노출, 옆 카드 살짝 보임 */
  .carousel-slide {
    flex: 0 0 78vw;
    max-width: 320px;
    padding: 22px 20px;
  }

  .carousel-slide .cs-title { font-size: 18px; }
  .carousel-slide .cs-disc  { font-size: 30px; }

  .carousel-track { gap: 14px; }

  .c-btn {
    padding: 10px 18px;
    font-size: 14px;
    min-height: 44px;
  }

  /* ----------------------------------------------------------
     HOME: 추천 쿠폰 캐러셀 (Center Focus)
     ---------------------------------------------------------- */
  /* 카드 폭 vw 기반으로 전환 — 화면 밖 잘림 방지 */
  .home-rec-card {
    width: 72vw;
    max-width: 280px;
    min-height: 200px;
    padding: 22px 18px 20px;
    border-radius: 22px;
  }

  /* 트랙 패딩: 첫 카드가 중앙에 오도록 */
  .home-rec-track {
    padding: 0 calc(50% - 36vw);
    gap: 12px;
  }

  .hrc-disc  { font-size: 40px; }
  .hrc-title { font-size: 15px; }
  .hrc-brand { font-size: 13px; }

  /* 캐러셀 네비 버튼 */
  .hrn-btn {
    width: 40px;
    height: 40px;
    font-size: 22px;
  }

  /* ----------------------------------------------------------
     HOME: 쿠폰 그리드 — 3열 → 2열 (카드 가독성 확보)
     ---------------------------------------------------------- */
  .cpn-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  .cpn-visual { height: 120px; }
  .cpn-vis-disc  { font-size: 32px; }
  .cpn-vis-brand { font-size: 11px; }
  .cpn-title     { font-size: 13px; }
  .cpn-info      { padding: 12px 14px 14px; }

  /* ----------------------------------------------------------
     HOME: Hero 쿠폰 카드
     ---------------------------------------------------------- */
  .hero-cpn-card { padding: 22px 20px 18px; border-radius: 16px; margin-bottom: 16px; }
  .hero-disc  { font-size: 44px; }
  .hero-title { font-size: 16px; }
  .hero-btns  { gap: 8px; }
  .hero-use-btn    { flex: 2; }
  .hero-detail-btn { flex: 1; }

  /* 조건 노출 칩 */
  .auto-apply-chip { font-size: 11px; padding: 6px 10px; }

  /* ----------------------------------------------------------
     HOME: 카테고리 / 브랜드 칩
     ---------------------------------------------------------- */
  .home-cat-chip {
    padding: 10px 16px;
    font-size: 14px;
    min-height: 44px;
  }

  .home-brand-chip {
    padding: 9px 14px;
    font-size: 14px;
    min-height: 44px;
  }

  .home-filter-chip,
  .home-loc-chip {
    padding: 9px 14px;
    font-size: 14px;
    min-height: 44px;
  }

  /* 해시태그 */
  .home-hashtag-chip {
    padding: 9px 14px;
    font-size: 14px;
    min-height: 44px;
  }

  /* 채널 탭 세그먼트 */
  .home-channel-tabs { width: 100%; }
  .hct-btn {
    flex: 1;
    min-width: 0;
    padding: 10px 8px;
    font-size: 13px;
    min-height: 44px;
  }

  /* ----------------------------------------------------------
     HOME: GPS 알림 배너
     ---------------------------------------------------------- */
  .gps-noti-bar {
    padding: 14px 16px;
    border-radius: 12px;
  }
  .gps-noti-title { font-size: 14px; }
  .gps-noti-sub   { font-size: 12px; }

  /* ----------------------------------------------------------
     HOME: 검색바
     ---------------------------------------------------------- */
  .hsb-bar  { padding: 4px 6px 4px 4px; }
  .hsb-input { font-size: 15px; }
  .hsb-search-btn { width: 42px; height: 42px; }

  .home-big-search { padding: 10px 12px 10px 16px; }
  .hbs-input { font-size: 15px; }
  .hbs-btn   { width: 42px; height: 42px; }

  /* ----------------------------------------------------------
     WALLET
     ---------------------------------------------------------- */
  /* 지갑 쿠폰 그리드: 3열 → 2열 */
  .wallet-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  /* 필터 바 */
  .wlt-filter-bar { gap: 8px; }
  .wlt-cat-tabs   { gap: 6px; overflow-x: auto; scrollbar-width: none; flex-wrap: nowrap; padding-bottom: 4px; }
  .wlt-cat-tabs::-webkit-scrollbar { display: none; }

  .wlt-cat-btn {
    flex: 0 0 auto;
    padding: 10px 14px;
    min-height: 44px;
    font-size: 14px;
  }

  .wlt-sort-select {
    height: 44px;
    font-size: 14px;
  }

  /* 곧 만료 스트립 카드 */
  .expire-soon-card { width: 80vw; max-width: 280px; padding: 18px; }
  .esc-title { font-size: 15px; }
  .esc-disc  { font-size: 24px; }

  /* ----------------------------------------------------------
     DETAIL PAGE — 2열 → 단일 열
     ---------------------------------------------------------- */
  .det-layout {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  .det-hero-card { padding: 28px 24px; }
  .det-hero-disc { font-size: 52px; }

  .det-price-val { font-size: 32px; }

  .det-urgency,
  .det-price-box { min-height: auto; }

  .det-dl-btn,
  .det-share-btn { min-height: 56px; }

  /* 바코드 확대 모달 */
  .brc-zoom-box {
    width: 92vw;
    padding: 28px 20px;
    border-radius: 20px;
  }
  .brc-zoom-num { font-size: 18px; letter-spacing: 3px; }

  /* ----------------------------------------------------------
     BARCODE PAGE
     ---------------------------------------------------------- */
  .brc-center { gap: 16px; }
  .brc-card   { padding: 28px 20px; }
  .brc-card h3 { font-size: 20px; }
  .brc-num { font-size: 20px; letter-spacing: 3px; }

  /* 바코드 전체화면 카드 */
  .brc-fullscreen-card { padding: 28px 20px; }
  .brc-cpn-name  { font-size: 18px; }
  .brc-num-large { font-size: 20px; letter-spacing: 4px; }

  /* 바코드 bottom sheet 팝업 */
  .brc-popup-body { padding: 16px 20px 0; }
  .brc-popup-title { font-size: 17px; }
  .brc-popup-name  { font-size: 18px; }
  .brc-popup-num   { font-size: 19px; letter-spacing: 4px; }

  /* ----------------------------------------------------------
     POINTS HUB — 2열 → 단일 열
     ---------------------------------------------------------- */
  .pts-layout {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  /* 포인트 그리드: 3열 → 2열 */
  .pts-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  .pts-svc-card { padding: 16px; }
  .pts-brand    { font-size: 17px; }
  .pts-bal      { font-size: 26px; }

  .pts-hero { padding: 22px 20px; }
  .pts-total { font-size: 32px; }
  .pts-unit  { font-size: 16px; }

  /* 서비스 상세 레이아웃: 2열 → 단일 열 */
  .pts-det-layout {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  .pts-det-hero { padding: 24px 20px; }
  .pts-det-bal  { font-size: 42px; }
  .pts-det-unit { font-size: 18px; }

  /* 카테고리 탭 */
  .cat-tab {
    padding: 10px 16px;
    font-size: 14px;
    min-height: 44px;
  }

  /* ----------------------------------------------------------
     MYPAGE — 2열 → 단일 열
     ---------------------------------------------------------- */
  .mypage-layout {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  .user-card { padding: 24px 20px; border-radius: 14px; }
  .user-greeting { font-size: 18px; }
  .user-avatar { width: 56px; height: 56px; font-size: 22px; }

  .asset-item { padding: 14px 10px; }
  .asset-val  { font-size: 18px; }
  .asset-lbl  { font-size: 12px; }

  .mypage-menu-item {
    padding: 18px 18px;
    font-size: 16px;
    min-height: 60px;
  }

  .mypage-menu-arrow { font-size: 16px; }

  /* 마이페이지 서브 탭 */
  .mps-tab {
    padding: 12px 16px;
    font-size: 14px;
    min-height: 48px;
  }

  /* 마이페이지 카드 */
  .mps-card { padding: 20px 16px; }
  .mps-title { font-size: 20px; margin-bottom: 18px; }

  /* 설정 rows */
  .settings-row { font-size: 15px; padding: 16px 0; }
  .info-row      { font-size: 15px; padding: 16px 0; }
  .toggle-row    { padding: 16px 0; }
  .toggle-lbl    { font-size: 16px; }

  /* 라디오/체크박스 */
  .radio-opt {
    padding: 16px;
    font-size: 16px;
    min-height: 56px;
  }

  .check-opt {
    padding: 12px 16px;
    font-size: 14px;
    min-height: 48px;
  }

  /* 알림 마스터 카드: 2열 유지 (터치 타겟 충분) */
  .noti-master-card { padding: 18px 14px; }
  .nm-title { font-size: 16px; }
  .nm-desc  { font-size: 12px; }

  /* 브랜드 알림 방식 테이블 → 모바일 단순화 */
  .noti-brand-method-header,
  .noti-brand-method-row {
    grid-template-columns: 80px 1fr;
    font-size: 12px;
  }

  /* 알림 카테고리 칩 */
  .noti-cat-chip {
    padding: 10px 16px;
    font-size: 14px;
    min-height: 44px;
  }

  /* 브랜드 알림 칩 */
  .noti-brand-chip {
    padding: 10px 12px;
    min-width: 56px;
    min-height: 72px;
  }

  /* ----------------------------------------------------------
     CONNECT SCREENS
     ---------------------------------------------------------- */
  .connect-body { max-width: 100%; }

  /* 연동 방식 카드: 2열 → 단일 열 */
  .connect-type-grid {
    grid-template-columns: 1fr;
    gap: 14px;
    margin-bottom: 20px;
  }

  .connect-type-card { padding: 24px 20px; }
  .connect-type-label { font-size: 18px; }
  .connect-type-desc  { font-size: 14px; }

  /* 서비스 선택 그리드 */
  .svc-sel-grid {
    grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
    gap: 10px;
  }

  /* 체크리스트 아이템 */
  .svc-check-item {
    padding: 16px 18px;
    font-size: 16px;
    min-height: 60px;
  }

  /* 인증 방식 카드 */
  .auth-method-card {
    padding: 18px 18px;
    font-size: 16px;
    min-height: 64px;
  }

  /* 연동 완료 배너 */
  .connect-success-banner { padding: 28px 20px; }
  .success-count { font-size: 44px; }
  .success-msg   { font-size: 15px; }

  /* ----------------------------------------------------------
     DOWNLOAD PAGE
     ---------------------------------------------------------- */
  .dl-hero { padding: 24px 20px; border-radius: 14px; }
  .dl-hero h2 { font-size: 22px; }
  .dl-hero p  { font-size: 15px; }
  .dl-hero-count { font-size: 36px; }

  /* 다운로드 쿠폰 그리드: 2열 → 1열 */
  .dl-cpn-grid {
    grid-template-columns: 1fr;
    gap: 12px;
  }

  .dl-cpn-card .dc-title { font-size: 16px; }
  .dl-cpn-card .dc-disc  { font-size: 24px; }

  /* ----------------------------------------------------------
     GPS/NEARBY MAP — 좌우 분할 → 상하 스택
     ---------------------------------------------------------- */
  .nearby-split {
    flex-direction: column;
    height: auto;
    min-height: 0;
  }

  .nearby-split-list {
    max-width: 100%;
    min-width: 0;
    border-right: none;
    border-bottom: 1.5px solid var(--gray-200);
    max-height: 40vh;
    overflow-y: auto;
  }

  .nearby-split-map {
    min-height: 300px;
    height: 50vh;
  }

  /* ----------------------------------------------------------
     SEARCH RESULTS
     ---------------------------------------------------------- */
  .search-kw-badge { font-size: 15px; padding: 8px 14px; }
  .search-count    { font-size: 14px; }

  /* 검색 결과 쿠폰 그리드 */
  #searchResultList .cpn-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  /* ----------------------------------------------------------
     NOTIFICATIONS
     ---------------------------------------------------------- */
  .noti-cpn-card { padding: 24px 20px; border-radius: 16px; }
  .noti-cpn-disc { font-size: 52px; }

  /* 사용처 카드: 2열 유지 */
  .noti-use-card { padding: 18px 12px; }
  .noti-use-title { font-size: 15px; }

  /* ----------------------------------------------------------
     PAGE NAV — 뒤로가기/홈 버튼
     ---------------------------------------------------------- */
  .pnav-back,
  .pnav-home {
    height: 48px;
    padding: 0 16px;
    font-size: 15px;
    min-width: 64px;
  }

  .pnav-title { font-size: 16px; }

  /* ----------------------------------------------------------
     SPLASH
     ---------------------------------------------------------- */
  .sp-title  { font-size: 32px; }
  .sp-sub    { font-size: 17px; }
  .sp-logo   { width: 100px; height: 100px; border-radius: 20px; }
  .sp-logo-txt { font-size: 30px; }

  /* ----------------------------------------------------------
     TOAST — 모바일 하단 탭바 위로 올림
     ---------------------------------------------------------- */
  .toast {
    bottom: 80px; /* 탭바(64px) + 여백 16px */
    font-size: 15px;
    padding: 14px 24px;
    white-space: normal;
    text-align: center;
    max-width: calc(100vw - 40px);
  }

  /* ----------------------------------------------------------
     LOADING STEPS
     ---------------------------------------------------------- */
  .ld-steps { max-width: 100%; }
  .ld-step  { padding: 14px 16px; gap: 12px; }
  .step-txt { font-size: 16px; }
  .step-sub { font-size: 13px; }

  /* ----------------------------------------------------------
     DISCOUNT SLIDER
     ---------------------------------------------------------- */
  .disc-slider-val { font-size: 60px; }
  .disc-slider-val .disc-pct { font-size: 26px; }

  /* ----------------------------------------------------------
     NEARBY DETAIL
     ---------------------------------------------------------- */
  .nearby-search-input { height: 52px; font-size: 15px; }
  .nearby-search-btn   { height: 52px; padding: 0 16px; font-size: 15px; }

  .nearby-name { font-size: 15px; }
  .nearby-addr { font-size: 12px; }

} /* end @media (max-width: 768px) */


/* ============================================================
   추가: @media (max-width: 480px)
   소형 폰 (se, 갤럭시 A 시리즈 등)에서 쿠폰 그리드 1열 전환
   ============================================================ */
@media (max-width: 480px) {

  /* 쿠폰 그리드 2열 → 1열 (좁은 화면에서 가독성 극대화) */
  .cpn-grid,
  .wallet-grid,
  #searchResultList .cpn-grid {
    grid-template-columns: 1fr;
    gap: 12px;
  }

  /* 포인트 그리드 유지 2열 (숫자 위주라 가독 가능) */

  /* 홈 카드 좌우 패딩 최소화 */
  .main-content { padding: 16px 14px 80px; }

  /* 옵션카드 1열 */
  .opt-grid {
    grid-template-columns: repeat(2, 1fr); /* 480px 이하도 2열 유지 */
  }

  /* 브랜드 칩 3열 */
  .brand-grid { grid-template-columns: repeat(3, 1fr); }

  /* 카테고리 칩 3열 유지 */
  .cat-grid { grid-template-columns: repeat(3, 1fr); }

  /* 연동 서비스 선택 */
  .svc-sel-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  /* 폰트 소폭 조정 */
  .ob-h2 { font-size: 22px; }
  .hero-disc { font-size: 38px; }
  .det-hero-disc { font-size: 44px; }

  /* 홈 추천 캐러셀 카드 폭 — 더 넓게 */
  .home-rec-card {
    width: 80vw;
    max-width: 300px;
  }
  .home-rec-track {
    padding: 0 calc(50% - 40vw);
  }

  /* 만료 임박 캐러셀 카드 */
  .carousel-slide {
    flex: 0 0 86vw;
    max-width: 300px;
  }

} /* end @media (max-width: 480px) */
