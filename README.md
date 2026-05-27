<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>助成金対応リスキリングLP | 株式会社VC</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts (Noto Sans JP) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Noto Sans JP', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            light: '#e0fcf6',
                            DEFAULT: '#10b981', // ターコイズグリーン系
                            dark: '#0f172a',    // 濃紺
                            accent: '#14b8a6',  // アクセントの明るいターコイズ
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            overflow-x: hidden;
        }
        .hero-gradient {
            background: radial-gradient(circle at 80% 20%, #e6faf6 0%, #ffffff 60%);
        }
    </style>
</head>
<body class="text-slate-800 bg-slate-50 antialiased">

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-100 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <div class="flex items-center gap-3">
                    <div class="flex items-center justify-center w-12 h-12 rounded-xl bg-teal-500 text-white font-black text-xl shadow-lg shadow-teal-500/20">
                        VC
                    </div>
                    <div>
                        <p class="text-[10px] text-teal-600 font-bold tracking-wider leading-none">弊社で解決可能なサービス</p>
                        <h1 class="text-lg font-black text-slate-800 leading-tight">株式会社VC</h1>
                    </div>
                </div>

                <!-- Navigation Deskop -->
                <nav class="hidden md:flex items-center gap-8">
                    <a href="#features" class="text-sm font-medium text-slate-600 hover:text-teal-600 transition-colors">特長・機能</a>
                    <a href="#requirements" class="text-sm font-medium text-slate-600 hover:text-teal-600 transition-colors">助成金要件</a>
                    <a href="#flow" class="text-sm font-medium text-slate-600 hover:text-teal-600 transition-colors">申請の流れ</a>
                    <a href="#simulator" class="text-sm font-medium text-slate-600 hover:text-teal-600 transition-colors">簡単適応診断</a>
                </nav>

                <!-- CTA Button -->
                <div class="hidden sm:block">
                    <a href="#contact" class="inline-flex items-center gap-2 px-5 py-3 rounded-full bg-teal-500 hover:bg-teal-600 text-white font-bold text-sm shadow-md hover:shadow-lg hover:shadow-teal-500/20 transition-all transform hover:-translate-y-0.5">
                        <i class="fa-solid fa-envelope"></i>
                        <span>無料相談・お問合せ</span>
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" class="md:hidden flex items-center p-2 text-slate-600 hover:text-teal-600 focus:outline-none">
                    <i class="fa-solid fa-bars text-2xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 px-4 py-4 space-y-3 shadow-inner">
            <a href="#features" class="block py-2 text-slate-600 hover:text-teal-600 font-medium text-sm">特長・機能</a>
            <a href="#requirements" class="block py-2 text-slate-600 hover:text-teal-600 font-medium text-sm">助成金要件</a>
            <a href="#flow" class="block py-2 text-slate-600 hover:text-teal-600 font-medium text-sm">申請の流れ</a>
            <a href="#simulator" class="block py-2 text-slate-600 hover:text-teal-600 font-medium text-sm">簡単適応診断</a>
            <a href="#contact" class="block w-full text-center py-3 rounded-xl bg-teal-500 text-white font-bold text-sm">
                <i class="fa-solid fa-envelope mr-2"></i>無料相談・お問合せ
            </a>
        </div>
    </header>

    <!-- Main Content wrapper to push down content from fixed header -->
    <main class="pt-20">

        <!-- Hero Section -->
        <section class="hero-gradient py-12 md:py-24 relative overflow-hidden">
            <!-- Background Blob -->
            <div class="absolute top-1/4 -right-24 w-96 h-96 bg-teal-200/40 rounded-full blur-3xl -z-10"></div>
            <div class="absolute -bottom-12 -left-24 w-80 h-80 bg-emerald-200/30 rounded-full blur-3xl -z-10"></div>

            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    
                    <!-- Left side: Text & Badges -->
                    <div class="lg:col-span-7 space-y-8">
                        <!-- Tiny Tag -->
                        <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-teal-50 border border-teal-200 text-teal-700 text-xs font-bold tracking-wide">
                            <span class="w-2 h-2 rounded-full bg-teal-500 animate-pulse"></span>
                            人材開発支援助成金（リスキリング）対応
                        </div>

                        <!-- Main Catchphrase -->
                        <h2 class="text-3xl sm:text-4xl lg:text-5xl font-black text-slate-900 leading-tight tracking-tight">
                            国庫助成を活用して、<br class="hidden sm:inline">
                            <span class="text-transparent bg-clip-text bg-gradient-to-r from-teal-600 to-emerald-600">自社主導のDX人材</span>を<br class="hidden sm:inline">完全内製化する。
                        </h2>

                        <!-- Description -->
                        <p class="text-slate-600 text-base sm:text-lg leading-relaxed max-w-2xl">
                            最大75%の経費助成（事業展開等リスキリング支援コース）の厳しい労働局審査要件をあらかじめクリアした、株式会社VCの「実務直結型eラーニング・ハイブリッド研修」。
                        </p>

                        <!-- Highlight Statistics Cards -->
                        <div class="grid grid-cols-3 gap-3 sm:gap-4 max-w-xl">
                            <div class="bg-white/80 backdrop-blur border border-teal-100 rounded-2xl p-4 text-center shadow-sm hover:shadow-md transition-shadow">
                                <p class="text-xs text-slate-500 font-medium mb-1">経費助成率</p>
                                <p class="text-xl sm:text-2xl font-black text-teal-600">最大75%</p>
                            </div>
                            <div class="bg-white/80 backdrop-blur border border-teal-100 rounded-2xl p-4 text-center shadow-sm hover:shadow-md transition-shadow">
                                <p class="text-xs text-slate-500 font-medium mb-1">審査基準準拠</p>
                                <p class="text-xl sm:text-2xl font-black text-teal-600">100%</p>
                            </div>
                            <div class="bg-white/80 backdrop-blur border border-teal-100 rounded-2xl p-4 text-center shadow-sm hover:shadow-md transition-shadow">
                                <p class="text-xs text-slate-500 font-medium mb-1">受講ログ・勤怠</p>
                                <p class="text-xl sm:text-2xl font-black text-teal-600">完全同期</p>
                            </div>
                        </div>

                        <!-- Action Buttons -->
                        <div class="flex flex-col sm:flex-row gap-4">
                            <a href="#simulator" class="inline-flex items-center justify-center px-8 py-4 rounded-xl bg-slate-900 text-white font-bold text-base shadow-xl hover:bg-slate-800 transition-all transform hover:-translate-y-0.5 text-center">
                                国の助成金適応を確認する（無料）
                            </a>
                            <a href="#requirements" class="inline-flex items-center justify-center px-8 py-4 rounded-xl bg-white text-slate-700 border border-slate-300 font-bold text-base shadow-sm hover:bg-slate-50 transition-all text-center">
                                助成金要件を見る
                            </a>
                        </div>
                    </div>

                    <!-- Right side: Requirements Panel -->
                    <div class="lg:col-span-5">
                        <div class="bg-white rounded-3xl p-6 sm:p-8 shadow-xl shadow-slate-200/80 border border-slate-100 relative">
                            <!-- Premium badge indicator -->
                            <div class="absolute -top-4 right-6 bg-emerald-500 text-white text-[10px] uppercase tracking-wider font-extrabold px-3 py-1 rounded-full shadow-md shadow-emerald-500/20">
                                COMPLIANCE
                            </div>

                            <div class="flex items-start gap-4 mb-6">
                                <div class="flex-shrink-0 w-10 h-10 rounded-full bg-teal-50 flex items-center justify-center text-teal-600">
                                    <i class="fa-solid fa-circle-check text-xl"></i>
                                </div>
                                <div>
                                    <h3 class="text-lg font-bold text-slate-900">審査突破を保証する4大前提</h3>
                                    <p class="text-xs text-slate-500 font-medium mt-0.5">厚生労働省の最新指導要領に準拠</p>
                                </div>
                            </div>

                            <!-- List Items -->
                            <div class="space-y-6">
                                <div class="flex gap-4">
                                    <span class="flex-shrink-0 w-6 h-6 rounded-full bg-teal-50 text-teal-600 flex items-center justify-center text-xs font-bold border border-teal-200 mt-1">1</span>
                                    <div>
                                        <h4 class="font-bold text-sm text-slate-800">実稼働15時間以上の訓練</h4>
                                        <p class="text-xs text-slate-500 mt-1 leading-relaxed">移動・休憩を除く正味学習時間をシステム上で厳密に計測・立証。</p>
                                    </div>
                                </div>

                                <div class="flex gap-4">
                                    <span class="flex-shrink-0 w-6 h-6 rounded-full bg-teal-50 text-teal-600 flex items-center justify-center text-xs font-bold border border-teal-200 mt-1">2</span>
                                    <div>
                                        <h4 class="font-bold text-sm text-slate-800">勤怠と学習ログの完全一致</h4>
                                        <p class="text-xs text-slate-500 mt-1 leading-relaxed">勤務時間外受講による不支給リスクを「受講可能時間制御」で完全排除。</p>
                                    </div>
                                </div>

                                <div class="flex gap-4">
                                    <span class="flex-shrink-0 w-6 h-6 rounded-full bg-teal-50 text-teal-600 flex items-center justify-center text-xs font-bold border border-teal-200 mt-1">3</span>
                                    <div>
                                        <h4 class="font-bold text-sm text-slate-800">スキップ・早送り制限</h4>
                                        <p class="text-xs text-slate-500 mt-1 leading-relaxed">動画のスキップ再生を防ぎ、全カリキュラム修了の実態を厳格にログ保存。</p>
                                    </div>
                                </div>

                                <div class="flex gap-4">
                                    <span class="flex-shrink-0 w-6 h-6 rounded-full bg-teal-50 text-teal-600 flex items-center justify-center text-xs font-bold border border-teal-200 mt-1">4</span>
                                    <div>
                                        <h4 class="font-bold text-sm text-slate-800">公認受講証明書の自動出力</h4>
                                        <p class="text-xs text-slate-500 mt-1 leading-relaxed">支給申請時に添付が義務付けられるログ・修了証をワンクリックで生成。</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Interactive Simulator Section -->
        <section id="simulator" class="py-16 bg-slate-900 text-white relative">
            <div class="absolute top-0 right-0 w-1/3 h-full bg-teal-950/20 -skew-x-12 -z-0"></div>
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
                <div class="text-center mb-10">
                    <span class="text-teal-400 text-xs font-bold tracking-widest uppercase">30-Second Diagnosis</span>
                    <h2 class="text-2xl sm:text-3xl font-black mt-2">助成金適応セルフチェックシミュレーター</h2>
                    <p class="text-slate-400 text-sm mt-2">いくつかの質問に回答するだけで、想定される助成金額を瞬時にシミュレーションします。</p>
                </div>

                <!-- Simulation Interactive Card -->
                <div class="bg-slate-800 border border-slate-700 rounded-3xl p-6 sm:p-10 shadow-2xl">
                    <div id="sim-question-flow" class="space-y-8">
                        <!-- Step 1 -->
                        <div class="sim-step" data-step="1">
                            <span class="text-xs font-bold text-teal-400">STEP 1 / 4</span>
                            <h3 class="text-lg sm:text-xl font-bold mt-1">貴社の雇用形態について教えてください。</h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-6">
                                <button onclick="nextStep(1, 'regular')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">雇用保険に加入している正社員がいる</div>
                                    <p class="text-xs text-slate-400 mt-1">一般的な厚生労働省の助成金の基本対象です</p>
                                </button>
                                <button onclick="nextStep(1, 'non-regular')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">契約社員・パート雇用がメイン</div>
                                    <p class="text-xs text-slate-400 mt-1">別途非正規向けの助成金が適応できる可能性があります</p>
                                </button>
                            </div>
                        </div>

                        <!-- Step 2 -->
                        <div class="sim-step hidden" data-step="2">
                            <span class="text-xs font-bold text-teal-400">STEP 2 / 4</span>
                            <h3 class="text-lg sm:text-xl font-bold mt-1">研修を受講させたい予定人数は？</h3>
                            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 mt-6">
                                <button onclick="nextStep(2, 5)" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-center transition-all">
                                    <div class="font-bold text-lg">1〜5名</div>
                                </button>
                                <button onclick="nextStep(2, 15)" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-center transition-all">
                                    <div class="font-bold text-lg">6〜20名</div>
                                </button>
                                <button onclick="nextStep(2, 50)" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-center transition-all">
                                    <div class="font-bold text-lg">21名以上</div>
                                </button>
                            </div>
                        </div>

                        <!-- Step 3 -->
                        <div class="sim-step hidden" data-step="3">
                            <span class="text-xs font-bold text-teal-400">STEP 3 / 4</span>
                            <h3 class="text-lg sm:text-xl font-bold mt-1">貴社の資本金または従業員規模は？</h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-6">
                                <button onclick="nextStep(3, 'small')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">中小企業（例: 小売で従業員50人以下など）</div>
                                    <p class="text-xs text-slate-400 mt-1">助成率が一番高い優遇枠（最大75%）が適用されます</p>
                                </button>
                                <button onclick="nextStep(3, 'large')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">大企業</div>
                                    <p class="text-xs text-slate-400 mt-1">大企業向けの助成率（最大60%）が適用されます</p>
                                </button>
                            </div>
                        </div>

                        <!-- Step 4 -->
                        <div class="sim-step hidden" data-step="4">
                            <span class="text-xs font-bold text-teal-400">STEP 4 / 4</span>
                            <h3 class="text-lg sm:text-xl font-bold mt-1">ご検討中の研修分野はどちらですか？</h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-6">
                                <button onclick="calculateResult('dx')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">IT・DX人材育成・リスキリング</div>
                                    <p class="text-xs text-slate-400 mt-1">事業展開等リスキリング支援コースの対象です</p>
                                </button>
                                <button onclick="calculateResult('general')" class="p-4 rounded-2xl border border-slate-600 hover:border-teal-400 bg-slate-800 hover:bg-slate-700/50 text-left transition-all">
                                    <div class="font-bold">その他一般実務・専門研修</div>
                                    <p class="text-xs text-slate-400 mt-1">通常の人材開発支援コースなどが適応となります</p>
                                </button>
                            </div>
                        </div>

                        <!-- Result Section -->
                        <div id="sim-result" class="hidden space-y-6">
                            <div class="bg-gradient-to-br from-teal-950 to-slate-900 border border-teal-500/30 rounded-2xl p-6 sm:p-8 text-center">
                                <span class="px-3 py-1 bg-teal-500/10 text-teal-400 border border-teal-500/20 rounded-full text-xs font-bold uppercase">Diagnosis Result</span>
                                <h4 class="text-xl sm:text-2xl font-black mt-4">貴社は助成金の「支給対象」である可能性が高いです！</h4>
                                
                                <div class="my-8 grid grid-cols-1 sm:grid-cols-2 gap-6 items-center">
                                    <div class="bg-slate-800/80 border border-slate-700 rounded-xl p-4">
                                        <p class="text-xs text-slate-400">想定最大 経費助成率</p>
                                        <p id="res-rate" class="text-3xl font-black text-teal-400 mt-1">最大75%</p>
                                    </div>
                                    <div class="bg-slate-800/80 border border-slate-700 rounded-xl p-4">
                                        <p class="text-xs text-slate-400">対象おすすめコース</p>
                                        <p id="res-course" class="text-lg font-black text-white mt-1">事業展開等リスキリング支援コース</p>
                                    </div>
                                </div>

                                <p class="text-xs text-slate-400 leading-relaxed max-w-xl mx-auto">
                                    ※上記のシミュレーションは目安であり、個別の審査状況や計画届の提出時期によって変動します。正確な受講費用や具体的な申請要件は個別相談（無料）にてご案内いたします。
                                </p>
                            </div>

                            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                                <button onclick="resetSimulator()" class="px-6 py-4 rounded-xl border border-slate-700 hover:bg-slate-800 text-sm font-bold transition-all">
                                    もう一度診断する
                                </button>
                                <a href="#contact" class="px-8 py-4 rounded-xl bg-teal-500 hover:bg-teal-600 text-slate-950 font-black text-sm shadow-xl transition-all text-center">
                                    この内容で無料相談・申請サポートを受ける
                                </a>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="py-20 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-teal-600 text-xs font-bold tracking-widest uppercase">Features & Strengths</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-slate-900 mt-2">株式会社VCの実務直結ハイブリッド研修</h2>
                    <p class="text-slate-500 text-sm mt-3">単なる「受講して終わり」ではなく、助成金の厳格な受講ログ管理基準を満たしながら、自社で動ける確かなDX実務力を身につけるプログラムを提供しています。</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Feature 1 -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-8 hover:shadow-xl transition-all">
                        <div class="w-12 h-12 rounded-2xl bg-teal-500/10 text-teal-600 flex items-center justify-center mb-6">
                            <i class="fa-solid fa-graduation-cap text-xl"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-3">実務から逆算したカリキュラム</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            座学にとどまらない、実際のビジネス課題をベースにした演習・プロジェクト課題を設計。自社主導でDXプロジェクトを動かせる即戦力へと引き上げます。
                        </p>
                    </div>

                    <!-- Feature 2 -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-8 hover:shadow-xl transition-all">
                        <div class="w-12 h-12 rounded-2xl bg-emerald-500/10 text-emerald-600 flex items-center justify-center mb-6">
                            <i class="fa-solid fa-clock text-xl"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-3">100%支給準拠の受講ログ管理</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            労働局の監査で指摘を受けやすい「受講時間の齟齬」「動画の早送り」を防止し、システム側で公認の勤怠同期・進捗レポートをいつでも自動出力。
                        </p>
                    </div>

                    <!-- Feature 3 -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-8 hover:shadow-xl transition-all">
                        <div class="w-12 h-12 rounded-2xl bg-sky-500/10 text-sky-600 flex items-center justify-center mb-6">
                            <i class="fa-solid fa-handshake-angle text-xl"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-3">安心の申請完全サポート体制</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            初めての助成金申請でも安心。複雑な訓練実施計画届、必要となる書類整備の案内から、不備のないログ作成までプロがしっかりと伴走します。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Requirements Detail Section -->
        <section id="requirements" class="py-20 bg-slate-50">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-teal-600 text-xs font-bold tracking-widest uppercase">Subsidy Requirements</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-slate-900 mt-2">助成金の対象要件と支給限度額</h2>
                    <p class="text-slate-500 text-sm mt-3">人材開発支援助成金「事業展開等リスキリング支援コース」の基本的な対象範囲は以下の通りです。</p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-stretch">
                    <!-- Requiments Summary Left -->
                    <div class="bg-white rounded-3xl p-6 sm:p-8 border border-slate-200/60 shadow-sm flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-6 flex items-center gap-3">
                                <span class="w-1.5 h-6 bg-teal-500 rounded-full"></span>
                                助成の対象となる主な条件
                            </h3>
                            <ul class="space-y-4">
                                <li class="flex items-start gap-3">
                                    <i class="fa-regular fa-square-check text-teal-600 mt-1"></i>
                                    <div>
                                        <span class="font-bold text-slate-800 text-sm">雇用保険適用事業所の事業主</span>
                                        <p class="text-xs text-slate-500 mt-0.5">雇用保険を正しく適用し、対象の従業員が雇用保険の被保険者であること。</p>
                                    </div>
                                </li>
                                <li class="flex items-start gap-3">
                                    <i class="fa-regular fa-square-check text-teal-600 mt-1"></i>
                                    <div>
                                        <span class="font-bold text-slate-800 text-sm">計画届の事前提出</span>
                                        <p class="text-xs text-slate-500 mt-0.5">訓練（研修）開始日の少なくとも1ヶ月前までに訓練実施計画届を提出していること。</p>
                                    </div>
                                </li>
                                <li class="flex items-start gap-3">
                                    <i class="fa-regular fa-square-check text-teal-600 mt-1"></i>
                                    <div>
                                        <span class="font-bold text-slate-800 text-sm">OFF-JT（訓練時間15時間以上）</span>
                                        <p class="text-xs text-slate-500 mt-0.5">研修全体の所要カリキュラムが実学習時間で15時間以上を満たしていること。</p>
                                    </div>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-8 pt-6 border-t border-slate-100">
                            <p class="text-xs text-slate-400">※詳しい最新の指導要領や改正情報は、無料相談時に詳しくお伝えさせていただきます。</p>
                        </div>
                    </div>

                    <!-- Limits and rates Right -->
                    <div class="bg-teal-500 text-slate-950 rounded-3xl p-6 sm:p-8 shadow-lg shadow-teal-500/10 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-black mb-6 flex items-center gap-3">
                                <span class="w-1.5 h-6 bg-slate-950 rounded-full"></span>
                                中小企業における支給イメージ
                            </h3>
                            <div class="space-y-6">
                                <div class="bg-white/95 rounded-2xl p-5 shadow-sm">
                                    <div class="flex justify-between items-center mb-1">
                                        <span class="text-xs font-bold text-slate-500">経費助成（研修費用等）</span>
                                        <span class="text-xs font-bold text-teal-600 bg-teal-50 px-2.5 py-0.5 rounded-full">中小企業</span>
                                    </div>
                                    <p class="text-2xl font-black text-slate-900">経費の75% を国庫が負担</p>
                                    <p class="text-xs text-slate-500 mt-1">※大企業の場合は60%助成。上限は受講生1人あたり最大30万円〜50万円となります。</p>
                                </div>

                                <div class="bg-white/95 rounded-2xl p-5 shadow-sm">
                                    <div class="flex justify-between items-center mb-1">
                                        <span class="text-xs font-bold text-slate-500">賃金助成（訓練時間分）</span>
                                        <span class="text-xs font-bold text-teal-600 bg-teal-50 px-2.5 py-0.5 rounded-full">1人1時間あたり</span>
                                    </div>
                                    <p class="text-2xl font-black text-slate-900">960円 / 1時間 助成</p>
                                    <p class="text-xs text-slate-500 mt-1">※研修を受講させている間の従業員の時給分として、国から支払われます（大企業は480円）。</p>
                                </div>
                            </div>
                        </div>
                        <div class="mt-8 pt-6 border-t border-slate-950/10 text-xs text-slate-900 font-semibold leading-relaxed">
                            <i class="fa-solid fa-circle-info mr-1"></i> 受講費用の立て替え（一時負担）が発生しますが、修了後に支給申請を行うことで、最大75%相当額が還付（支給）されます。
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Process Flow Section -->
        <section id="flow" class="py-20 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-teal-600 text-xs font-bold tracking-widest uppercase">Implementation Flow</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-slate-900 mt-2">申請から受講・支給までの流れ</h2>
                    <p class="text-slate-500 text-sm mt-3">複雑な助成金申請ステップを、株式会社VCがフルサポートします。初めての企業様も安心です。</p>
                </div>

                <!-- Process Steps Cards -->
                <div class="grid grid-cols-1 md:grid-cols-4 gap-6 relative">
                    <!-- Step 1 Card -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-6 relative">
                        <span class="absolute -top-4 left-6 bg-slate-900 text-teal-400 text-xs font-black px-3.5 py-1.5 rounded-full">01</span>
                        <h3 class="text-base font-bold text-slate-900 mt-4 mb-2">個別相談・研修プラン設計</h3>
                        <p class="text-slate-500 text-xs leading-relaxed">
                            受講を予定する従業員の人数や、育成したいスキルに応じて、対象要件に合致する「実務直結eラーニング・ハイブリッド研修」のカリキュラムを設計します。
                        </p>
                    </div>

                    <!-- Step 2 Card -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-6 relative">
                        <span class="absolute -top-4 left-6 bg-slate-900 text-teal-400 text-xs font-black px-3.5 py-1.5 rounded-full">02</span>
                        <h3 class="text-base font-bold text-slate-900 mt-4 mb-2">訓練実施計画届の提出</h3>
                        <p class="text-slate-500 text-xs leading-relaxed">
                            研修開始の<strong>1ヶ月前までに</strong>、労働局へ必要書類（実施計画届など）を提出します。必要な書類や記入事項は弊社が分かりやすくご案内します。
                        </p>
                    </div>

                    <!-- Step 3 Card -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-6 relative">
                        <span class="absolute -top-4 left-6 bg-slate-900 text-teal-400 text-xs font-black px-3.5 py-1.5 rounded-full">03</span>
                        <h3 class="text-base font-bold text-slate-900 mt-4 mb-2">研修の受講（学習＆ログ同期）</h3>
                        <p class="text-slate-500 text-xs leading-relaxed">
                            eラーニングプラットフォームを使い、計画されたスケジュールで訓練を進めます。実稼働の15時間以上のログと勤怠情報を自動同期します。
                        </p>
                    </div>

                    <!-- Step 4 Card -->
                    <div class="bg-slate-50 border border-slate-100 rounded-3xl p-6 relative">
                        <span class="absolute -top-4 left-6 bg-teal-500 text-white text-xs font-black px-3.5 py-1.5 rounded-full">04</span>
                        <h3 class="text-base font-bold text-slate-900 mt-4 mb-2">受講完了・支給申請</h3>
                        <p class="text-slate-500 text-xs leading-relaxed">
                            研修を無事修了した後、システムから自動出力された受講証明書・ログ添付書類を添えて、助成金支給申請をおこない、経費還付を受け取ります。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-slate-50 border-t border-slate-200/50">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-12">
                    <span class="text-teal-600 text-xs font-bold tracking-widest uppercase">Contact & Consultation</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-slate-900 mt-2">助成金適応のご相談（無料）</h2>
                    <p class="text-slate-500 text-sm mt-3">自社で助成金が使えるか、どのような研修プログラムが適切か、お気軽にお問い合わせください。</p>
                </div>

                <!-- Form Card -->
                <div class="bg-white rounded-3xl p-6 sm:p-10 shadow-lg border border-slate-200/60">
                    <form id="contact-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">会社名 <span class="text-rose-500">*</span></label>
                                <input type="text" required name="company" placeholder="株式会社〇〇" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">ご担当者名 <span class="text-rose-500">*</span></label>
                                <input type="text" required name="name" placeholder="山田 太郎" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">メールアドレス <span class="text-rose-500">*</span></label>
                                <input type="email" required name="email" placeholder="example@company.com" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">お電話番号</label>
                                <input type="tel" name="tel" placeholder="03-1234-5678" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">検討している受講規模（想定人数）</label>
                            <select name="scale" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none bg-white">
                                <option value="未定">選択してください</option>
                                <option value="1〜5名">1〜5名</option>
                                <option value="6〜20名">6〜20名</option>
                                <option value="21名以上">21名以上</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">お問い合わせ内容 <span class="text-rose-500">*</span></label>
                            <textarea required name="message" rows="5" placeholder="研修内容について詳しく知りたい、助成金のシミュレーション詳細をお願いしたい等..." class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-teal-500 focus:border-teal-500 text-sm transition-all outline-none"></textarea>
                        </div>

                        <div class="flex items-start gap-3 mt-4">
                            <input type="checkbox" required id="privacy" class="mt-1 h-4 w-4 text-teal-600 focus:ring-teal-500 border-slate-300 rounded">
                            <label for="privacy" class="text-xs text-slate-500 leading-normal">
                                個人情報の取り扱いについて（プライバシーポリシー）に同意する。
                            </label>
                        </div>

                        <div class="pt-4">
                            <button type="submit" class="w-full py-4 rounded-xl bg-teal-500 hover:bg-teal-600 text-white font-black text-base shadow-xl shadow-teal-500/20 hover:shadow-teal-500/30 transition-all text-center">
                                無料相談・お問合せを送信する
                            </button>
                        </div>

                    </form>

                    <!-- Successful Sent message (Hidden by default) -->
                    <div id="contact-success" class="hidden text-center py-12 space-y-6">
                        <div class="w-16 h-16 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center mx-auto text-2xl">
                            <i class="fa-solid fa-check"></i>
                        </div>
                        <div class="space-y-2">
                            <h3 class="text-2xl font-bold text-slate-900">お問合せを送信いたしました</h3>
                            <p class="text-slate-500 text-sm leading-relaxed max-w-md mx-auto">
                                ご登録いただいたメールアドレス宛に、自動返信メールを送信いたしました。<br>
                                助成金申請のご案内について、担当者より1〜2営業日以内にご連絡いたします。
                            </p>
                        </div>
                        <button onclick="resetContactForm()" class="text-teal-600 font-bold text-sm hover:underline">
                            フォームに戻る
                        </button>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-white border-t border-slate-800 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 items-center border-b border-slate-800 pb-8 mb-8">
                <!-- Left -->
                <div class="flex items-center gap-3">
                    <div class="flex items-center justify-center w-10 h-10 rounded-xl bg-teal-500 text-white font-black text-lg">
                        VC
                    </div>
                    <div>
                        <p class="text-[9px] text-teal-400 font-bold">弊社で解決可能なサービス</p>
                        <h4 class="text-base font-black text-white">株式会社VC</h4>
                    </div>
                </div>
                <!-- Middle Links -->
                <div class="flex flex-wrap gap-x-6 gap-y-2 text-xs text-slate-400">
                    <a href="#features" class="hover:text-teal-400">特長・機能</a>
                    <a href="#requirements" class="hover:text-teal-400">助成金要件</a>
                    <a href="#flow" class="hover:text-teal-400">申請の流れ</a>
                    <a href="#simulator" class="hover:text-teal-400">簡単診断</a>
                </div>
                <!-- Right Info -->
                <div class="text-right text-xs text-slate-400">
                    <p>〒104-0061 東京都中央区銀座（ダミー住所）</p>
                    <p class="mt-1">TEL: 03-1234-5678</p>
                </div>
            </div>
            <div class="flex flex-col sm:flex-row justify-between items-center gap-4 text-xs text-slate-500">
                <p>&copy; 2026 株式会社VC. All rights reserved.</p>
                <p>※本ページの内容は最新の指導要領をもとに掲載しておりますが、個々の状況に応じて内容が変わる場合がございます。</p>
            </div>
        </div>
    </footer>

    <!-- Interactive JS logic -->
    <script>
        // Mobile Navigation Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Hide mobile menu when clicking any link in it
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Active Simulator State
        let simData = {
            step1: '',
            step2: 0,
            step3: '',
            step4: ''
        };

        function nextStep(currentStep, answer) {
            // Save state data
            if (currentStep === 1) simData.step1 = answer;
            if (currentStep === 2) simData.step2 = answer;
            if (currentStep === 3) simData.step3 = answer;

            // Hide current step, show next
            document.querySelector(`.sim-step[data-step="${currentStep}"]`).classList.add('hidden');
            document.querySelector(`.sim-step[data-step="${currentStep + 1}"]`).classList.remove('hidden');
        }

        function calculateResult(answer) {
            simData.step4 = answer;

            // Hide step 4
            document.querySelector('.sim-step[data-step="4"]').classList.add('hidden');

            // Logic to calculate appropriate rate and recommendations
            let rateText = '最大75%';
            let courseText = '事業展開等リスキリング支援コース';

            // If large company (Step 3)
            if (simData.step3 === 'large') {
                rateText = '最大60%';
            }

            // If not regular workers (Step 1)
            if (simData.step1 === 'non-regular') {
                courseText = 'キャリアアップ助成金（人材育成支援）';
                rateText = '最大60%';
            }

            // If not digital focus (Step 4)
            if (simData.step4 === 'general') {
                courseText = '人材開発支援助成金（通常訓練）';
                rateText = '最大45% (中小企業)';
            }

            // Set result text
            document.getElementById('res-rate').textContent = rateText;
            document.getElementById('res-course').textContent = courseText;

            // Show result block
            document.getElementById('sim-result').classList.remove('hidden');
        }

        function resetSimulator() {
            // Clear data
            simData = { step1: '', step2: 0, step3: '', step4: '' };

            // Hide result, show step 1
            document.getElementById('sim-result').classList.add('hidden');
            document.querySelectorAll('.sim-step').forEach((step, idx) => {
                if (idx === 0) {
                    step.classList.remove('hidden');
                } else {
                    step.classList.add('hidden');
                }
            });
        }

        // Contact Form Handlers
        function handleFormSubmit(event) {
            event.preventDefault();
            // In a real application, you would post details to your database/server here.
            
            // Toggle view to success
            document.getElementById('contact-form').classList.add('hidden');
            document.getElementById('contact-success').classList.remove('hidden');
        }

        function resetContactForm() {
            document.getElementById('contact-form').reset();
            document.getElementById('contact-form').classList.remove('hidden');
            document.getElementById('contact-success').classList.add('hidden');
        }
    </script>

</body>
</html>
