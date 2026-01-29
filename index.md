---
layout: null
title: "황호성 · 비즈니스를 함께 만드는 개발자"
description: "기획·개발·실험·운영까지 비즈니스 전체 흐름을 설계하는 개발자입니다. 대표 서비스인 단단이(Dandani)를 통해 감정 회복 챌린지를 실제 유저 트래픽과 실험으로 검증해 왔습니다."
---

<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>황호성 · 비즈니스를 함께 만드는 개발자</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-0B1H02T38L"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-0B1H02T38L');
  </script>

  <!-- Inter Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  />

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#f8fafc',
              100: '#eff3f7',
              200: '#dde4ec',
              300: '#c2cfdd',
              400: '#9dacbf',
              500: '#748399',
              600: '#566478',
              700: '#414c5b',
              800: '#2b333b',
              900: '#191f25',
            },
            accent: {
              50: '#fff8ee',
              100: '#ffe9cc',
              200: '#ffd19a',
              300: '#ffb165',
              400: '#ff8c33',
              500: '#f66b0e',
              600: '#d44f04',
              700: '#a53b06',
              800: '#7a2f0b',
              900: '#5e260b',
            },
          },
        }
      }
    }
  </script>
</head>

<body class="bg-[#f5f5f5] text-brand-900 antialiased font-sans">
<div class="min-h-screen flex flex-col">

  <!-- Header -->
  <header class="sticky top-0 z-30 border-b border-gray-200 bg-white/80 backdrop-blur">
    <div class="max-w-6xl mx-auto px-5 md:px-6 py-4 flex items-center justify-between">
      <!-- Logo / Name -->
      <div class="flex items-center gap-3">
        <div class="w-8 h-8 rounded-xl bg-brand-900 text-white flex items-center justify-center text-xs font-semibold tracking-[0.16em]">
          HH
        </div>
        <div class="flex flex-col">
          <span class="text-sm font-semibold tracking-tight">황호성</span>
          <span class="text-[11px] text-gray-500 tracking-[0.16em] uppercase">
            Product-minded Developer
          </span>
        </div>
      </div>

      <!-- Nav -->
      <nav class="hidden md:flex items-center gap-7 text-[11px] font-medium tracking-[0.18em] uppercase text-gray-600">
        <a href="#intro" class="hover:text-black transition">Intro</a>
        <a href="#dandani" class="hover:text-black transition">Dandani</a>
        <a href="#experiments" class="hover:text-black transition">Experiments</a>
        <a href="#projects" class="hover:text-black transition">Projects</a>
      </nav>

      <!-- Right CTA -->
      <div class="hidden md:flex items-center gap-3 text-[11px] tracking-[0.18em] uppercase">
        <a
          href="mailto:amansman77@gmail.com"
          class="px-3 py-1.5 rounded-full border border-brand-900 text-brand-900 hover:bg-brand-900 hover:text-white transition text-[11px] font-medium"
        >
          Contact
        </a>
      </div>

      <!-- Mobile menu (simple text) -->
      <a
        href="mailto:amansman77@gmail.com"
        class="md:hidden text-[11px] tracking-[0.2em] uppercase border px-3 py-1.5 rounded-full"
      >
        Contact
      </a>
    </div>
  </header>

  <!-- Main -->
  <main class="flex-1">
    <div class="max-w-6xl mx-auto px-5 md:px-6 pt-10 pb-16 space-y-14 md:space-y-16">

      <!-- Intro / Hero -->
      <section id="intro" class="grid gap-10 md:grid-cols-[minmax(0,1.5fr)_minmax(0,1fr)] md:items-end">
        <div class="space-y-5 max-w-3xl">
          <p class="text-[11px] font-medium tracking-[0.22em] uppercase text-gray-500">
            비즈니스를 함께 만드는 개발자
          </p>
          <h1 class="text-3xl md:text-[2.6rem] leading-tight font-semibold tracking-tight">
            기획·개발·실험·운영까지<br class="hidden md:block" />
            <span class="bg-accent-100 px-1.5 -mx-1.5 rounded-md">
              비즈니스 전체 흐름을 설계하는 개발자
            </span>
            입니다.
          </h1>
          <p class="text-[15px] md:text-base text-gray-700 leading-relaxed">
            저는 단순히 코드를 전달하는 사람이 아니라,<br class="hidden md:block" />
            <span class="font-medium text-brand-800">
              "문제 정의 → 실험 → 제품화 → 운영"의 전 과정을 스스로 설계하고 실행하는
            </span>
            사람입니다.
            <br />
            <span class="text-gray-600">
              대표 서비스인 <strong>단단이(Dandani)</strong>를 통해,
              감정 회복 챌린지를 실제 유저 트래픽과 실험으로 검증해 왔습니다.
            </span>
          </p>

          <div class="flex flex-wrap gap-3 pt-2">
            <a
              href="https://dandani.yetimates.com/?utm_source=portfolio&utm_medium=owned&utm_campaign=portfolio_main"
              target="_blank"
              class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-brand-900 text-white text-[12px] font-medium tracking-[0.16em] uppercase hover:bg-brand-800 transition"
            >
              단단이 바로 보기
              <span class="text-xs">↗</span>
            </a>
            <a
              href="#projects"
              class="inline-flex items-center gap-2 px-4 py-2 rounded-full border border-gray-300 bg-white text-[12px] font-medium tracking-[0.16em] uppercase hover:border-brand-900 hover:text-brand-900 transition"
            >
              다른 프로젝트 보기
            </a>
          </div>
        </div>

        <!-- Hero Side: Quick Facts -->
        <div class="space-y-4 md:justify-self-end">
          <div class="bg-white border border-gray-200 rounded-2xl p-4 md:p-5 shadow-sm">
            <p class="text-[11px] font-medium tracking-[0.2em] uppercase text-gray-500 mb-3">
              About
            </p>
            <div class="space-y-2 text-[13px] text-gray-700">
              <p><span class="font-semibold text-brand-900">이름</span> · 황호성</p>
              <p><span class="font-semibold text-brand-900">경력</span> · {{ 'now' | date: '%Y' | minus: 2012 | plus: 1 }}년차 풀스택/백엔드 개발자</p>
              <p><span class="font-semibold text-brand-900">현재</span> · 하이파킹 MHP 책임연구원</p>
              <p><span class="font-semibold text-brand-900">관심</span> · 감정 회복, 언어, 실험 기반 제품</p>
            </div>
          </div>

          <div class="bg-white border border-gray-200 rounded-2xl p-4 md:p-5 shadow-sm">
            <p class="text-[11px] font-medium tracking-[0.2em] uppercase text-gray-500 mb-3">
              Links
            </p>
            <div class="space-y-1.5 text-[13px]">
              <a href="https://github.com/amansman77" target="_blank" class="block text-brand-800 hover:underline">
                GitHub · amansman77
              </a>
              <a href="https://yeti.tistory.com" target="_blank" class="block text-brand-800 hover:underline">
                Tech & 기록 블로그
              </a>
              <a href="https://www.linkedin.com/in/hosung-hwang-916046184/" target="_blank" class="block text-brand-800 hover:underline">
                LinkedIn 프로필
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- Dandani: 대표 서비스 -->
      <section id="dandani" class="space-y-6">
        <div class="flex items-center justify-between gap-4">
          <div>
            <p class="text-[11px] font-medium tracking-[0.22em] uppercase text-accent-600 mb-1">
              대표 서비스
            </p>
            <h2 class="text-xl md:text-2xl font-semibold tracking-tight">
              단단이 (Dandani) · 감정 회복 기반 30일 챌린지 서비스
            </h2>
          </div>
          <span class="hidden sm:inline-flex px-3 py-1 rounded-full bg-accent-50 text-[11px] text-accent-700 tracking-[0.16em] uppercase border border-accent-100">
            Experiment-driven Product
          </span>
        </div>

        <div class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm grid gap-6 md:grid-cols-[minmax(0,1.5fr)_minmax(0,1fr)]">
          <!-- Left: Description -->
          <div class="space-y-4 max-w-xl">
            <p class="text-[15px] md:text-base text-gray-800 leading-relaxed">
              <span class="font-semibold text-brand-900">단단이</span>는
              <strong>"상황이 나를 흔들어도, 내가 중심을 잃지 않도록 돕는" 감정 회복 챌린지 서비스</strong>입니다.
              사용자가 감정을 억누르지 않고 바라보며, 작은 실천을 반복할 수 있도록 설계했습니다.
            </p>

            <div class="grid gap-3 text-[13px] text-gray-700">
              <div>
                <p class="font-semibold text-brand-900 mb-1">제가 맡은 역할</p>
                <ul class="list-disc list-inside space-y-1">
                  <li>서비스 기획 · 브랜드 톤 정의 · UX 플로우 설계</li>
                  <li>Cloudflare Workers + D1 기반 서버리스 백엔드 개발</li>
                  <li>React + MUI 기반 프론트엔드 및 인터랙션 구현</li>
                  <li>실험 설계(가설·지표) 및 Instagram 광고를 통한 트래픽 유입 · 분석</li>
                </ul>
              </div>
              <div>
                <p class="font-semibold text-brand-900 mb-1">핵심 기능</p>
                <ul class="list-disc list-inside space-y-1">
                  <li>30일 감정 회복 챌린지 & 실천 기록 캘린더</li>
                  <li>감정 상태(행복/슬픔/화남/불안/보통) 기반 AI 상담</li>
                  <li>30일 후의 나에게 보내는 Timefold 편지(클라이언트 암호화)</li>
                  <li>로그인 없이 사용하는 익명 사용자 구조 + 개인정보 최소 수집</li>
                </ul>
              </div>
            </div>
          </div>

          <!-- Right: Snapshot & Stack -->
          <div class="border border-dashed border-gray-200 rounded-xl p-4 space-y-4 bg-[#fafafa]">
            <div>
              <p class="text-[11px] font-medium tracking-[0.2em] uppercase text-gray-500 mb-1.5">
                Tech Snapshot
              </p>
              <div class="flex flex-wrap gap-2 text-[11px]">
                <span class="px-2.5 py-1 rounded-full bg-white border border-gray-200">Cloudflare Workers · D1</span>
                <span class="px-2.5 py-1 rounded-full bg-white border border-gray-200">React · MUI</span>
                <span class="px-2.5 py-1 rounded-full bg-white border border-gray-200">OpenAI API</span>
                <span class="px-2.5 py-1 rounded-full bg-white border border-gray-200">Serverless / Edge</span>
              </div>
            </div>

            <div class="border-t border-gray-200 pt-3">
              <p class="text-[11px] font-medium tracking-[0.2em] uppercase text-gray-500 mb-1.5">
                실험 기반 개선
              </p>
              <ul class="space-y-1.5 text-[13px] text-gray-700">
                <li>· Retention v1/ v2 실험으로 Day1/Day7 잔존 구조 검증</li>
                <li>· 실패 실험을 기반으로 v3에서 "보상·UX·리마인더" 루프 재설계</li>
                <li>· PM 관점에서 가설 → 실험 → 지표 → 인사이트까지 전 주기 수행</li>
              </ul>
            </div>

            <div class="pt-1">
              <a
                href="#experiments"
                class="inline-flex items-center gap-1 text-[12px] text-brand-800 hover:underline"
              >
                단단이 실험 기록 보기
                <span class="text-xs">↓</span>
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- Experiments -->
      <section id="experiments" class="space-y-5">
        <div class="flex items-center justify-between gap-4">
          <div>
            <p class="text-[11px] font-medium tracking-[0.22em] uppercase text-gray-500 mb-1">
              Experiments
            </p>
            <h2 class="text-xl md:text-2xl font-semibold tracking-tight">
              실험으로 만드는 비즈니스 · Dandani Experiment v1–v3
            </h2>
          </div>
        </div>

        <div class="grid gap-4 md:grid-cols-3">
          <!-- v1 -->
          <article class="bg-white border border-gray-200 rounded-2xl p-4 md:p-5 shadow-sm flex flex-col">
            <div class="flex items-center justify-between mb-3">
              <span class="px-2.5 py-1 rounded-full bg-brand-900 text-white text-[11px] tracking-[0.18em] uppercase">
                v1 · 완료
              </span>
              <span class="text-[11px] text-gray-500">2025.09 ~ 10</span>
            </div>
            <h3 class="text-sm font-semibold mb-2">
              Daily Challenge 기반 리텐션 실험
            </h3>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              "작은 실천 → 기록 → 감정 변화" 루프가 자연스러운 재방문을 만들 수 있는지 검증한 첫 실험입니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1.5 flex-1">
              <li>· DAU 최고 53 → 빠른 하락</li>
              <li>· Day1 / Day7 / Day30 핵심 지표 모두 미달</li>
              <li>· 결론: "루틴 서비스가 아니라 1일 체험 서비스"였음</li>
            </ul>
            <p class="mt-3 text-[12px] text-brand-800 font-medium">
              ❯ 리텐션을 위해선 <strong>"루프와 보상 설계"</strong>가 필요하다는 인사이트 확보
            </p>
          </article>

          <!-- v2 -->
          <article class="bg-white border border-gray-200 rounded-2xl p-4 md:p-5 shadow-sm flex flex-col">
            <div class="flex items-center justify-between mb-3">
              <span class="px-2.5 py-1 rounded-full bg-accent-600 text-white text-[11px] tracking-[0.18em] uppercase">
                v2 · 실패에서 배운 실험
              </span>
              <span class="text-[11px] text-gray-500">2025.11</span>
            </div>
            <h3 class="text-sm font-semibold mb-2">
              7-Day Recovery Loop · 광고 퍼널 실험
            </h3>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              "공감하는 짧은 실천을 직접 선택하면 행동과 잔존으로 이어진다"는 가설을 검증한 실험입니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1.5 flex-1">
              <li>· Instagram CTR 5.03% (광고 퍼포먼스 매우 우수)</li>
              <li>· 하지만 챌린지 선택/실천/재방문 지표는 모두 목표 미달</li>
              <li>· 실천 후 보상, 리마인더, 의미감이 부족했다는 원인 도출</li>
            </ul>
            <p class="mt-3 text-[12px] text-brand-800 font-medium">
              ❯ "공감만으로는 행동이 일어나지 않는다"는 핵심 교훈 확보
            </p>
          </article>

          <!-- v3 -->
          <article class="bg-white border border-dashed border-accent-300 rounded-2xl p-4 md:p-5 flex flex-col bg-accent-50/40">
            <div class="flex items-center justify-between mb-3">
              <span class="px-2.5 py-1 rounded-full bg-white text-accent-700 border border-accent-300 text-[11px] tracking-[0.18em] uppercase">
                v3 · 진행 예정
              </span>
              <span class="text-[11px] text-gray-500">2025.12 ~</span>
            </div>
            <h3 class="text-sm font-semibold mb-2">
              UX & 감정적 보상 구조 검증 실험
            </h3>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              정제된 UI/UX와 감정적 보상 구조가 실천 완료율과 재방문율을 얼마나 끌어올릴 수 있는지 검증합니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1.5 flex-1">
              <li>· Self-dogfooding으로 UX 개선 효과 정성 검증 완료</li>
              <li>· 목표: Day2 Retention ≥ 10%, Day3 ≥ 8%</li>
              <li>· 실험 실패 시 v4(리마인더·습관 루프)로 즉시 전환 계획 포함</li>
            </ul>
            <p class="mt-3 text-[12px] text-accent-700 font-medium">
              ❯ "실험-기록-학습"을 반복하며 비즈니스 코어 루프를 찾아가는 과정입니다.
            </p>
          </article>
        </div>
      </section>

      <!-- Projects -->
      <section id="projects" class="space-y-6">
        <div class="flex items-center justify-between gap-4">
          <div>
            <p class="text-[11px] font-medium tracking-[0.22em] uppercase text-gray-500 mb-1">
              Related Projects
            </p>
            <h2 class="text-xl md:text-2xl font-semibold tracking-tight">
              비즈니스를 함께 만들어갈 수 있는 프로젝트들
            </h2>
          </div>
        </div>

        <div class="grid gap-6 md:grid-cols-2 auto-rows-fr">
          <!-- Mindful Motion -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div class="mb-3 flex items-center justify-between gap-3">
              <h3 class="text-sm font-semibold">
                Mindful Motion · 프리미엄 요가 스튜디오 웹사이트
              </h3>
              <span class="text-[11px] px-2 py-1 rounded-full bg-brand-50 text-brand-700 border border-brand-100">
                Branding · 예약
              </span>
            </div>
            <!-- TAG PILLS -->
            <div class="flex flex-wrap gap-1.5 mb-2">
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Branding</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">예약</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Tailwind</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">UI/UX</span>
            </div>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              오프라인 요가 스튜디오의 브랜드 이미지를 온라인으로 옮기고, 예약/문의까지 한 번에 연결되는
              브랜딩 웹사이트를 설계했습니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1 mb-3 flex-1">
              <li>· Tailwind 기반 디자인 시스템 · 반응형 웹 구현</li>
              <li>· 예약 폼 → Discord Webhook 연동으로 실시간 알림</li>
              <li>· 향후 다른 오프라인 비즈니스에도 재사용 가능한 템플릿 구조</li>
            </ul>
            <a href="https://yoga-class.yetimates.com/" target="_blank" class="text-[12px] text-brand-800 hover:underline">
              사이트 열기 ↗
            </a>
          </article>

          <!-- Church site -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div class="mb-3 flex items-center justify-between gap-3">
              <h3 class="text-sm font-semibold">
                Church Site · 교회 커뮤니티 웹사이트
              </h3>
              <span class="text-[11px] px-2 py-1 rounded-full bg-brand-50 text-brand-700 border border-brand-100">
                커뮤니티 · 정보 구조
              </span>
            </div>
            <!-- TAG PILLS -->
            <div class="flex flex-wrap gap-1.5 mb-2">
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">커뮤니티</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">정보 구조 설계</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Cloudflare Pages</span>
            </div>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              다양한 연령대가 사용하는 교회 웹사이트를, "정보 접근성을 최우선"으로 보는 관점에서 설계했습니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1 mb-3 flex-1">
              <li>· 예배 시간, 설교 아카이브, 공지, 새가족 등록 플로우 설계</li>
              <li>· 고연령층도 읽기 쉬운 타이포/레이아웃 적용</li>
              <li>· Cloudflare Pages 기반 정적 배포 · 빠른 로딩 속도</li>
            </ul>
            <a href="https://church-site-sample.yetimates.com/" target="_blank" class="text-[12px] text-brand-800 hover:underline">
              사이트 열기 ↗
            </a>
          </article>

          <!-- JAYURO -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div class="mb-3 flex items-center justify-between gap-3">
              <h3 class="text-sm font-semibold">
                JAYURO · 교육/강사 매칭 플랫폼(MVP)
              </h3>
              <span class="text-[11px] px-2 py-1 rounded-full bg-brand-50 text-brand-700 border border-brand-100">
                Serverless · Matching
              </span>
            </div>
            <!-- TAG PILLS -->
            <div class="flex flex-wrap gap-1.5 mb-2">
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Serverless</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Matching</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">BFF</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Flutter Web/App</span>
            </div>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              유학·입시·이민 아카데미를 연결하는 교육 매칭 플랫폼으로, MAU 100k를 목표로 한 엣지 기반 아키텍처를 설계했습니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1 mb-3 flex-1">
              <li>· Cloudflare Workers + RDS MySQL + Hyperdrive 기반 BFF 설계</li>
              <li>· Flutter Web/App + React Admin으로 멀티 클라이언트 대응</li>
              <li>· ADR, ERD, API Spec 등 문서 중심의 협업 구조 구축</li>
            </ul>
            <div class="space-y-1 text-[12px]">
              <a href="https://jayuro-app.pages.dev/" target="_blank" class="block text-brand-800 hover:underline">
                사용자 Web 앱 ↗
              </a>
              <a href="https://jayuro-admin.pages.dev/" target="_blank" class="block text-brand-800 hover:underline">
                Admin 대시보드 ↗
              </a>
            </div>
          </article>

          <!-- Shop Mate -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div class="mb-3 flex items-center justify-between gap-3">
              <h3 class="text-sm font-semibold">
                Shop Mate · 영수증 관리 서버리스 웹앱
              </h3>
              <span class="text-[11px] px-2 py-1 rounded-full bg-brand-50 text-brand-700 border border-brand-100">
                OCR · Data Pipeline
              </span>
            </div>
            <!-- TAG PILLS -->
            <div class="flex flex-wrap gap-1.5 mb-2">
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">OCR</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Data Pipeline</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Cloudflare Workers</span>
              <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Edge</span>
            </div>
            <p class="text-[13px] text-gray-700 leading-relaxed mb-3">
              영수증 이미지를 업로드하면, 클라이언트 OCR과 서버 파싱으로 구조화된 지출 데이터로 변환하는 웹앱입니다.
            </p>
            <ul class="text-[12px] text-gray-700 space-y-1 mb-3 flex-1">
              <li>· Tesseract.js 기반 클라이언트 OCR + Cloudflare Workers API</li>
              <li>· 이마트/트레이더스 등 다양한 영수증 포맷 파서 설계</li>
              <li>· D1 + R2 기반 완전 서버리스 데이터 파이프라인 구축</li>
            </ul>
            <a href="https://shop.yetimates.com/" target="_blank" class="text-[12px] text-brand-800 hover:underline">
              사이트 열기 ↗
            </a>
          </article>
        </div>
      </section>

      <!-- Engineering Systems -->
      <section class="space-y-6 mt-16">
        <div class="flex items-baseline justify-between gap-4">
          <div>
            <p class="text-[11px] font-medium tracking-[0.22em] uppercase text-gray-500 mb-1">
              ENGINEERING SYSTEMS
            </p>
            <h2 class="text-xl md:text-2xl font-semibold tracking-tight">
              현업에서 직접 설계·운영해 본 핵심 시스템들
            </h2>
          </div>
          <p class="hidden md:block text-xs text-gray-500 max-w-xs leading-relaxed">
            사이드 프로젝트 외에도, 실제 서비스 환경에서
            <span class="font-semibold">대규모 트래픽과 인프라를 다뤄본 경험</span>을
            짧게 정리했습니다. "어디까지 맡길 수 있는 사람인지"를
            시스템 관점에서 보여주고자 했습니다.
          </p>
        </div>
      
        <div class="grid gap-6 md:grid-cols-2 auto-rows-fr">
          <!-- Card 1: Cyworld Reboot Backend -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div>
              <div class="flex items-center justify-between mb-2">
                <h3 class="text-sm font-semibold text-gray-900">
                  Cyworld Reboot · 소셜 네트워크 백엔드
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-gray-200 px-3 py-1 text-[10px] uppercase tracking-[0.18em] text-gray-600">
                  FXGear · 2021–2023
                </span>
              </div>
              <!-- TAG PILLS -->
              <div class="flex flex-wrap gap-1.5 mb-2">
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">High-Traffic</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Spring Boot</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">JPA</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Kafka</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">CI/CD</span>
              </div>
              <p class="text-xs text-gray-600 mb-3">
                싸이월드 리부트 프로젝트의 백엔드 파트로 합류해,
                회원·인증·결제·도토리·발송 등의 코어 도메인과 인프라를 설계·운영했습니다.
              </p>
      
              <dl class="text-[11px] text-gray-700 space-y-1.5 mb-3">
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">역할</dt>
                  <dd>백엔드 개발자 → 파트 리더</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">Stack</dt>
                  <dd>Spring Boot · JPA · MySQL · Kafka · Jenkins</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">규모</dt>
                  <dd>회원 500만명, 푸시 200만건/6시간 처리</dd>
                </div>
              </dl>
      
              <ul class="text-[11px] text-gray-700 space-y-1.5">
                <li>· 인증/회원/결제/도토리/발송 등 <span class="font-semibold">핵심 도메인 모듈 설계·구현</span></li>
                <li>· CI/CD 파이프라인, APM 연동 등 <span class="font-semibold">운영 편의 인프라</span> 구축</li>
                <li>· 파트 리더로서 일정·이슈 관리 및 코드리뷰/도메인 리뷰 문화 정착</li>
              </ul>
            </div>
          </article>
      
          <!-- Card 2: AI Platform & DataLake -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div>
              <div class="flex items-center justify-between mb-2">
                <h3 class="text-sm font-semibold text-gray-900">
                  AI Platform Suite · DataLake · Edge · MLOps
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-gray-200 px-3 py-1 text-[10px] uppercase tracking-[0.18em] text-gray-600">
                  지어소프트 · 엔키스 · 2020–2021
                </span>
              </div>
              <!-- TAG PILLS -->
              <div class="flex flex-wrap gap-1.5 mb-2">
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Kubernetes</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">DataLake</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Edge AI</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Kafka</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Triton</span>
              </div>
              <p class="text-xs text-gray-600 mb-3">
                자율주행·이미지·센서 데이터를 수집·저장·학습·추론까지 연결하는
                AI 플랫폼 전반을 설계·구현한 경험입니다.
              </p>
      
              <dl class="text-[11px] text-gray-700 space-y-1.5 mb-3">
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">역할</dt>
                  <dd>플랫폼 엔지니어 · 설계/개발 리드</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">Stack</dt>
                  <dd>Kubernetes · Kafka · MongoDB · PostgreSQL · Triton</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">범위</dt>
                  <dd>DataLake · Edge AI · MLOps · 인프라 클러스터</dd>
                </div>
              </dl>
      
              <ul class="text-[11px] text-gray-700 space-y-1.5">
                <li>· Spring Boot + Vue 기반 <span class="font-semibold">DataLake 관리 서비스</span> 개발</li>
                <li>· K8s + Rook-Ceph + Kafka 기반 <span class="font-semibold">고가용 데이터 파이프라인</span> 구성</li>
                <li>· Triton 기반 추론 환경과 Edge(K3s, Jetson) 운영 구조 설계</li>
              </ul>
            </div>
          </article>
      
          <!-- Card 3: Realtime AI Factory Platform -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div>
              <div class="flex items-center justify-between mb-2">
                <h3 class="text-sm font-semibold text-gray-900">
                  Smart Factory · 실시간 AI 추론 플랫폼
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-gray-200 px-3 py-1 text-[10px] uppercase tracking-[0.18em] text-gray-600">
                  엠아이큐브솔루션 · 2019–2020
                </span>
              </div>
              <!-- TAG PILLS -->
              <div class="flex flex-wrap gap-1.5 mb-2">
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Streaming</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">K8s</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Django</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">MongoDB</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">실시간 처리</span>
              </div>
              <p class="text-xs text-gray-600 mb-3">
                공장 센서 데이터를 실시간으로 수집·분석하고,
                이상 징후를 탐지하는 AI 추론 운영 환경을 PoC부터 구축했습니다.
              </p>
      
              <dl class="text-[11px] text-gray-700 space-y-1.5 mb-3">
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">역할</dt>
                  <dd>플랫폼 설계 · 백엔드/데이터 파이프라인 개발</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">Stack</dt>
                  <dd>Kubernetes · Kafka · Spring Boot · Django · MongoDB</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">기능</dt>
                  <dd>센서 수집 · 모델추론 · 알람 · 관리자 웹</dd>
                </div>
              </dl>
      
              <ul class="text-[11px] text-gray-700 space-y-1.5">
                <li>· AI 추론 파이프라인(수집→저장→모델→알람) <span class="font-semibold">엔드투엔드 설계</span></li>
                <li>· Kubernetes + Kafka 기반 <span class="font-semibold">MSA 지향 구조</span> 도입</li>
                <li>· 성능/부하 테스트를 통해 실시간 추론 처리 한계 검증</li>
              </ul>
            </div>
          </article>
      
          <!-- Card 4: High-traffic Marketing & Push Platform -->
          <article class="bg-white border border-gray-200 rounded-2xl p-5 md:p-6 shadow-sm flex flex-col">
            <div>
              <div class="flex items-center justify-between mb-2">
                <h3 class="text-sm font-semibold text-gray-900">
                  Marketing & Messaging · 고트래픽 플랫폼
                </h3>
                <span
                  class="inline-flex items-center rounded-full border border-gray-200 px-3 py-1 text-[10px] uppercase tracking-[0.18em] text-gray-600">
                  인라이플 · 2018–2019
                </span>
              </div>
              <!-- TAG PILLS -->
              <div class="flex flex-wrap gap-1.5 mb-2">
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">L4/L7</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Redis</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">MariaDB</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">ELK</span>
                <span class="inline-flex items-center px-2 py-0.5 rounded-full bg-gray-100 text-gray-600 text-[11px]">Zabbix</span>
              </div>
              <p class="text-xs text-gray-600 mb-3">
                L4/L7, Redis, Chat, Push, MariaDB 기반으로
                다수의 앱·웹을 동시에 지원하는 마케팅 플랫폼을 설계·운영했습니다.
              </p>
      
              <dl class="text-[11px] text-gray-700 space-y-1.5 mb-3">
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">역할</dt>
                  <dd>서버 파트장 · 시스템 아키텍트</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">Stack</dt>
                  <dd>Spring Boot · Redis · MariaDB · ELK · Zabbix</dd>
                </div>
                <div class="flex gap-2">
                  <dt class="w-16 text-gray-400">포커스</dt>
                  <dd>Failover · Scale-out · 모니터링 · CI/CD</dd>
                </div>
              </dl>
      
              <ul class="text-[11px] text-gray-700 space-y-1.5">
                <li>· L4/L7 + Redis + API 서버 구조로 <span class="font-semibold">고가용 아키텍처</span> 설계</li>
                <li>· Zabbix + ELK로 서버·JVM·API 성능 모니터링 환경 도입</li>
                <li>· Jenkins + Git-flow 도입으로 배포 자동화 및 팀 개발 프로세스 개선</li>
              </ul>
            </div>
          </article>
        </div>
      </section>
      
    </div>
  </main>

  <!-- Footer -->
  <footer class="border-t border-gray-200 bg-white">
    <div class="max-w-6xl mx-auto px-5 md:px-6 py-6 text-[11px] text-gray-500 flex flex-col md:flex-row justify-between gap-2">
      <span>© {{ 'now' | date: '%Y' }} Hosung Hwang. All rights reserved.</span>
      <span>Designed & built with Tailwind CSS.</span>
    </div>
  </footer>

</div>
</body>
</html>
