# jk20250206.github.io
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>合同会社D'zero. | 営業×Webのプロフェッショナル</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
        }
        .logo-cube {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #2d3748 0%, #1a202c 100%);
            transform: perspective(100px) rotateX(15deg) rotateY(-15deg);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 24px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .service-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        .process-step {
            position: relative;
        }
        .process-step::after {
            content: '';
            position: absolute;
            top: 50%;
            right: -20px;
            width: 0;
            height: 0;
            border-left: 20px solid #667eea;
            border-top: 10px solid transparent;
            border-bottom: 10px solid transparent;
            transform: translateY(-50%);
        }
        .process-step:last-child::after {
            display: none;
        }
        @media print {
            body { print-color-adjust: exact; }
            .no-print { display: none; }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center space-x-4">
                    <div class="logo-cube">D</div>
                    <div>
                        <h1 class="text-2xl font-bold text-gray-900">合同会社D'zero.</h1>
                        <p class="text-sm text-gray-600">営業×Webのプロフェッショナル</p>
                    </div>
                </div>
                <nav class="hidden md:flex space-x-8">
                    <a href="#services" class="text-gray-700 hover:text-blue-600 transition">サービス</a>
                    <a href="#reasons" class="text-gray-700 hover:text-blue-600 transition">選ばれる理由</a>
                    <a href="#process" class="text-gray-700 hover:text-blue-600 transition">ご利用の流れ</a>
                    <a href="#company" class="text-gray-700 hover:text-blue-600 transition">会社概要</a>
                    <a href="#contact" class="text-gray-700 hover:text-blue-600 transition">お問い合わせ</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-5xl font-bold mb-6">BtoB営業の"成果"をもっと早く、もっと確実に。</h2>
            <p class="text-xl mb-8 max-w-4xl mx-auto">SaaS特化の営業代行とWeb支援で、貴社の売上アップを徹底サポート！</p>
            <p class="text-lg mb-10 opacity-90">営業人材の不足、リード獲得の伸び悩み、オンライン施策の迷走——<br>そんな悩みをD'zero.が伴走型で解決します。</p>
            <a href="#contact" class="bg-white text-blue-600 px-8 py-4 rounded-lg text-lg font-semibold hover:bg-gray-100 transition shadow-lg">
                <i class="fas fa-comments mr-2"></i>今すぐ相談する
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-briefcase mr-3 text-blue-600"></i>提供サービス
                </h2>
                <p class="text-xl text-gray-600">営業とWebの両面から貴社の成長をサポートします</p>
            </div>

            <div class="grid md:grid-cols-2 gap-12">
                <!-- 営業代行 -->
                <div class="service-card bg-white rounded-xl p-8 shadow-lg">
                    <div class="text-center mb-6">
                        <i class="fas fa-phone-alt text-4xl text-blue-600 mb-4"></i>
                        <h3 class="text-2xl font-bold text-gray-900">営業代行（SaaS特化）</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>テレアポ・インサイドセールス</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>商談設定（オンライン・対面）</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>営業スクリプトの設計・改善</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>リードナーチャリング対応</span>
                        </li>
                    </ul>
                </div>

                <!-- Web支援 -->
                <div class="service-card bg-white rounded-xl p-8 shadow-lg">
                    <div class="text-center mb-6">
                        <i class="fas fa-laptop-code text-4xl text-purple-600 mb-4"></i>
                        <h3 class="text-2xl font-bold text-gray-900">Web支援・デジタルサポート</h3>
                    </div>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>ホームページ・LP制作（ペライチ等）</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>SNS運用代行／広告運用（Google広告・Instagram）</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>オウンドメディア運用／SEOライティング</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check-circle text-green-500 mr-3"></i>
                            <span>バナー・LP構成ディレクション</span>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="text-center mt-12">
                <a href="#contact" class="bg-blue-600 text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-blue-700 transition shadow-lg">
                    <i class="fas fa-info-circle mr-2"></i>各サービスの詳細を見る
                </a>
            </div>
        </div>
    </section>

    <!-- Problems Section -->
    <section class="bg-gray-100 py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-8">
                    <i class="fas fa-question-circle mr-3 text-red-500"></i>こんなお悩みありませんか？
                </h2>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <i class="fas fa-user-times text-3xl text-red-500 mb-4"></i>
                    <p class="font-semibold text-gray-800">社内に営業人材がおらず、動けない</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <i class="fas fa-chart-line text-3xl text-red-500 mb-4"></i>
                    <p class="font-semibold text-gray-800">SaaS商材の導入先が広がらない</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <i class="fas fa-globe-asia text-3xl text-red-500 mb-4"></i>
                    <p class="font-semibold text-gray-800">WebやSNSで集客できていない</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <i class="fas fa-random text-3xl text-red-500 mb-4"></i>
                    <p class="font-semibold text-gray-800">営業とWeb施策がバラバラで非効率</p>
                </div>
            </div>

            <div class="text-center">
                <div class="bg-blue-600 text-white p-8 rounded-xl shadow-lg inline-block">
                    <h3 class="text-2xl font-bold mb-4">
                        <i class="fas fa-arrow-right mr-3"></i>そのお悩み、"営業×Webのプロ"が一気通貫で支援します！
                    </h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Reasons Section -->
    <section id="reasons" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-star mr-3 text-yellow-500"></i>D'zero.が選ばれる理由
                </h2>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="bg-blue-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-trophy text-3xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">SaaS営業の実績多数</h3>
                    <p class="text-gray-600">BtoBの新規開拓〜成約まで支援</p>
                </div>
                <div class="text-center">
                    <div class="bg-green-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-cogs text-3xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">柔軟な対応力</h3>
                    <p class="text-gray-600">スクリプト構築・改善もご提案</p>
                </div>
                <div class="text-center">
                    <div class="bg-purple-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-link text-3xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Web連携で営業力強化</h3>
                    <p class="text-gray-600">SNS、SEOもワンストップ</p>
                </div>
                <div class="text-center">
                    <div class="bg-orange-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-network-wired text-3xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">豊富なネットワーク</h3>
                    <p class="text-gray-600">全国5,000社との実績</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section id="process" class="bg-gray-100 py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-route mr-3 text-blue-600"></i>ご利用の流れ
                </h2>
            </div>

            <div class="flex flex-wrap justify-center items-center gap-8 mb-12">
                <div class="process-step bg-white p-6 rounded-lg shadow-lg text-center min-w-48">
                    <div class="bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 font-bold text-lg">1</div>
                    <h3 class="font-bold text-gray-800 mb-2">無料ヒアリング</h3>
                    <p class="text-sm text-gray-600">お悩みをお聞かせください</p>
                </div>
                <div class="process-step bg-white p-6 rounded-lg shadow-lg text-center min-w-48">
                    <div class="bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 font-bold text-lg">2</div>
                    <h3 class="font-bold text-gray-800 mb-2">ご提案・お見積り</h3>
                    <p class="text-sm text-gray-600">最適なプランをご提示</p>
                </div>
                <div class="process-step bg-white p-6 rounded-lg shadow-lg text-center min-w-48">
                    <div class="bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 font-bold text-lg">3</div>
                    <h3 class="font-bold text-gray-800 mb-2">営業支援スタート</h3>
                    <p class="text-sm text-gray-600">実行開始・伴走支援</p>
                </div>
                <div class="process-step bg-white p-6 rounded-lg shadow-lg text-center min-w-48">
                    <div class="bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 font-bold text-lg">4</div>
                    <h3 class="font-bold text-gray-800 mb-2">定期レポート・改善提案</h3>
                    <p class="text-sm text-gray-600">継続的な最適化</p>
                </div>
                <div class="process-step bg-white p-6 rounded-lg shadow-lg text-center min-w-48">
                    <div class="bg-blue-600 text-white w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 font-bold text-lg">5</div>
                    <h3 class="font-bold text-gray-800 mb-2">成果を見ながらスケール支援</h3>
                    <p class="text-sm text-gray-600">さらなる成長をサポート</p>
                </div>
            </div>

            <div class="text-center">
                <a href="#contact" class="bg-blue-600 text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-blue-700 transition shadow-lg">
                    <i class="fas fa-comments mr-2"></i>無料で相談してみる
                </a>
            </div>
        </div>
    </section>

    <!-- Company Section -->
    <section id="company" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-building mr-3 text-gray-600"></i>会社概要
                </h2>
            </div>

            <div class="bg-white rounded-xl shadow-lg p-8 max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="logo-cube mr-4">D</div>
                            <div>
                                <h3 class="text-2xl font-bold text-gray-900">合同会社D'zero.</h3>
                                <p class="text-gray-600">（ディーゼロ）</p>
                            </div>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800 mb-2">事業内容</h4>
                            <p class="text-gray-600">BtoB営業代行（SaaS特化）／Web支援（LP制作・SEO・SNS運用など）</p>
                        </div>
                    </div>
                    
                    <div class="space-y-4">
                        <div class="flex">
                            <span class="font-semibold text-gray-800 w-24">代表者</span>
                            <span class="text-gray-600">倉光 順子</span>
                        </div>
                        <div class="flex">
                            <span class="font-semibold text-gray-800 w-24">設立</span>
                            <span class="text-gray-600">2025年</span>
                        </div>
                        <div class="flex">
                            <span class="font-semibold text-gray-800 w-24">所在地</span>
                            <span class="text-gray-600">福岡県福岡市中央区那の川2-7-3 </span>
                        </div>
                        <div class="flex">
                            <span class="font-semibold text-gray-800 w-24">連絡先</span>
                            <span class="text-gray-600">llc.d.zero726@gmail.com</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gradient-to-br from-blue-600 to-purple-600 py-20">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-white mb-4">
                    <i class="fas fa-envelope mr-3"></i>お問い合わせフォーム
                </h2>
                <p class="text-xl text-white opacity-90">お気軽にご相談ください。2営業日以内に担当よりご連絡いたします。</p>
            </div>

            <div class="bg-white rounded-xl shadow-2xl p-8">
                <form class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block text-sm font-semibold text-gray-700 mb-2">
                                お名前 <span class="text-red-500">*</span>
                            </label>
                            <input type="text" id="name" name="name" required 
                                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition">
                        </div>
                        <div>
                            <label for="company" class="block text-sm font-semibold text-gray-700 mb-2">
                                会社名（任意）
                            </label>
                            <input type="text" id="company" name="company" 
                                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition">
                        </div>
                    </div>
                    
                    <div>
                        <label for="email" class="block text-sm font-semibold text-gray-700 mb-2">
                            メールアドレス <span class="text-red-500">*</span>
                        </label>
                        <input type="email" id="email" name="email" required 
                            class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition">
                    </div>
                    
                    <div>
                        <label for="message" class="block text-sm font-semibold text-gray-700 mb-2">
                            ご相談内容 <span class="text-red-500">*</span>
                        </label>
                        <textarea id="message" name="message" rows="6" required 
                            class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition"
                            placeholder="お困りのことやご相談内容をお聞かせください"></textarea>
                    </div>
                    
                    <div class="text-center">
                        <button type="submit" 
                            class="bg-blue-600 text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-blue-700 transition shadow-lg">
                            <i class="fas fa-paper-plane mr-2"></i>お問い合わせを送信する
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="flex items-center justify-center space-x-4 mb-4">
                <div class="logo-cube">D</div>
                <div>
                    <h3 class="text-xl font-bold">合同会社D'zero.</h3>
                    <p class="text-gray-400">営業×Webのプロフェッショナル</p>
                </div>
            </div>
            <p class="text-gray-400">&copy; 2025 合同会社D'zero. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Form submission handling
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('お問い合わせありがとうございます。2営業日以内にご連絡いたします。');
        });

        // Mobile menu toggle (if needed)
        function toggleMobileMenu() {
            // Mobile menu implementation if needed
        }
    </script>
</body>
</html>

.logo-cube {
    width: auto;
    height: auto;
    padding: 0;
    background: transparent;
    box-shadow: none;
    display: flex;
    align-items: center;
    justify-content: center;
}
