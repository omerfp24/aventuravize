<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aventura Vize Hizmetleri</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8fafc;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .testimonial-card {
            background-color: #ffffff;
            border-radius: 1rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }
        .country-flag {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid white;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <div class="text-3xl font-bold text-blue-800">
                    <span class="text-blue-600">A</span>ventura
                </div>
                <span class="ml-2 text-gray-500 text-sm">Vize Hizmetleri</span>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#anasayfa" class="text-gray-700 hover:text-blue-600 font-medium">Ana Sayfa</a>
                <a href="#hizmetlerimiz" class="text-gray-700 hover:text-blue-600 font-medium">Hizmetlerimiz</a>
                <a href="#ulkeler" class="text-gray-700 hover:text-blue-600 font-medium">Ülkeler</a>
                <a href="#basari" class="text-gray-700 hover:text-blue-600 font-medium">Başarı Oranımız</a>
                <a href="#iletisim" class="text-gray-700 hover:text-blue-600 font-medium">İletişim</a>
            </nav>
            <div class="md:hidden">
                <button id="menu-toggle" class="text-gray-700 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="hidden md:hidden bg-white px-4 py-3 shadow-inner">
            <a href="#anasayfa" class="block py-2 text-gray-700 hover:text-blue-600 font-medium">Ana Sayfa</a>
            <a href="#hizmetlerimiz" class="block py-2 text-gray-700 hover:text-blue-600 font-medium">Hizmetlerimiz</a>
            <a href="#ulkeler" class="block py-2 text-gray-700 hover:text-blue-600 font-medium">Ülkeler</a>
            <a href="#basari" class="block py-2 text-gray-700 hover:text-blue-600 font-medium">Başarı Oranımız</a>
            <a href="#iletisim" class="block py-2 text-gray-700 hover:text-blue-600 font-medium">İletişim</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="anasayfa" class="hero-gradient text-white py-20">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold mb-6">Avrupa Vizesi Almanın En Güvenilir Yolu</h1>
                    <p class="text-xl mb-8">Schengen vizesi başvurularında %100 başarı oranı. Red durumunda ikinci başvuru ücretsiz!</p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#iletisim" class="bg-white text-blue-800 font-semibold px-6 py-3 rounded-lg shadow-lg hover:bg-blue-50 transition duration-300 text-center">Hemen Başvur</a>
                        <a href="#hizmetlerimiz" class="bg-transparent border-2 border-white text-white font-semibold px-6 py-3 rounded-lg hover:bg-white hover:text-blue-800 transition duration-300 text-center">Hizmetlerimiz</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative">
                        <svg class="w-72 h-72 md:w-96 md:h-96" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#FFFFFF" d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-1.5C87,13.3,81.3,26.7,73.6,38.7C65.9,50.7,56.1,61.3,44.1,68.5C32.1,75.8,16.1,79.6,0.7,78.5C-14.6,77.4,-29.3,71.3,-42.2,63.1C-55.1,54.9,-66.3,44.6,-73.9,31.7C-81.5,18.9,-85.5,3.4,-83.8,-11.2C-82.1,-25.8,-74.7,-39.6,-64.4,-50.5C-54.1,-61.5,-40.8,-69.7,-27.4,-77.3C-13.9,-84.9,-0.2,-91.9,13.4,-90.3C27,-88.7,54,-91.5,67.1,-84.3C80.2,-77.1,93.3,-60,94.4,-42.9C95.5,-25.8,84.6,-8.7,81.3,9.3C78,27.3,82.3,46.3,75.6,59.1C68.9,71.9,51.2,78.5,35.2,77.7C19.1,76.9,4.8,68.8,-8.9,63.9C-22.6,59,-35.8,57.3,-47.9,51.5C-60,45.7,-71,35.9,-77.1,23.4C-83.1,10.9,-84.2,-4.3,-81.1,-18.5C-78,-32.7,-70.8,-45.9,-60.3,-56.1C-49.8,-66.3,-36,-73.5,-22,-76.9C-8,-80.3,6.2,-79.9,19.2,-76.7C32.2,-73.5,44,-77.5,44.7,-76.4Z" transform="translate(100 100)" />
                        </svg>
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="bg-white p-4 rounded-full shadow-lg">
                                <svg class="w-24 h-24 md:w-32 md:h-32" viewBox="0 0 512 512" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M256 0C114.6 0 0 114.6 0 256C0 397.4 114.6 512 256 512C397.4 512 512 397.4 512 256C512 114.6 397.4 0 256 0Z" fill="#2563EB"/>
                                    <path d="M256 30C131.1 30 30 131.1 30 256C30 380.9 131.1 482 256 482C380.9 482 482 380.9 482 256C482 131.1 380.9 30 256 30Z" fill="#FFFFFF"/>
                                    <path d="M256 60C147.6 60 60 147.6 60 256C60 364.4 147.6 452 256 452C364.4 452 452 364.4 452 256C452 147.6 364.4 60 256 60Z" fill="#2563EB"/>
                                    <path d="M256 256L256 100" stroke="#FFCD05" stroke-width="10"/>
                                    <path d="M256 256L350 200" stroke="#FFCD05" stroke-width="10"/>
                                    <path d="M256 256L300 350" stroke="#FFCD05" stroke-width="10"/>
                                    <path d="M256 256L150 320" stroke="#FFCD05" stroke-width="10"/>
                                    <path d="M256 256L180 180" stroke="#FFCD05" stroke-width="10"/>
                                    <circle cx="256" cy="256" r="20" fill="#FFCD05"/>
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="bg-blue-50 p-8 rounded-xl shadow-md">
                    <div class="text-5xl font-bold text-blue-600 mb-2">100%</div>
                    <div class="text-gray-600 font-medium">Başarı Oranı</div>
                </div>
                <div class="bg-blue-50 p-8 rounded-xl shadow-md">
                    <div class="text-5xl font-bold text-blue-600 mb-2">0%</div>
                    <div class="text-gray-600 font-medium">Red Oranı</div>
                </div>
                <div class="bg-blue-50 p-8 rounded-xl shadow-md">
                    <div class="text-5xl font-bold text-blue-600 mb-2">Ücretsiz</div>
                    <div class="text-gray-600 font-medium">Red Durumunda İkinci Başvuru</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="hizmetlerimiz" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Vize Hizmetlerimiz</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Avrupa Schengen vizesi başvurularınızda size özel profesyonel hizmetler sunuyoruz.</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h4.586A2 2 0 0112 2.586L15.414 6A2 2 0 0116 7.414V16a2 2 0 01-2 2H6a2 2 0 01-2-2V4zm2 6a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm1 3a1 1 0 100 2h6a1 1 0 100-2H7z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Evrak Hazırlama</h3>
                    <p class="text-gray-600 mb-4">Vize başvurunuz için gerekli tüm belgelerin eksiksiz ve doğru şekilde hazırlanması.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17 6a3 3 0 11-6 0 3 3 0 016 0zM12.93 17c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Randevu Alma</h3>
                    <p class="text-gray-600 mb-4">Konsolosluk ve büyükelçiliklerden hızlı randevu alma ve takip hizmeti.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Başvuru Takibi</h3>
                    <p class="text-gray-600 mb-4">Başvurunuzun her aşamasında profesyonel takip ve bilgilendirme hizmeti.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Garanti Hizmeti</h3>
                    <p class="text-gray-600 mb-4">Red durumunda ikinci başvurunuz tamamen ücretsiz olarak yapılır.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"></path>
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Seyahat Sigortası</h3>
                    <p class="text-gray-600 mb-4">Vize başvurunuz için gerekli seyahat sağlık sigortası hizmeti.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
                <div class="service-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" clip-rule="evenodd"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Danışmanlık</h3>
                    <p class="text-gray-600 mb-4">Vize süreçleri hakkında profesyonel danışmanlık ve bilgilendirme hizmeti.</p>
                    <a href="#iletisim" class="text-blue-600 font-medium hover:text-blue-800 inline-flex items-center">
                        Detaylı Bilgi
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Countries Section -->
    <section id="ulkeler" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Schengen Ülkeleri</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Tüm Schengen ülkeleri için vize başvuru hizmetleri sunuyoruz. Özellikle İspanya vizesi konusunda uzmanız.</p>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-6">
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#FFDA44" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#D80027" d="M0 85.331h512v113.775H0zM0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">İspanya</h3>
                    <span class="text-sm text-blue-600 font-medium">Uzman Olduğumuz Ülke</span>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#D80027" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#000000" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Almanya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#0052B4" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#D80027" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Fransa</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#6DA544" d="M0 85.331h170.663v341.337H0z"/>
                            <path fill="#D80027" d="M341.337 85.331H512v341.337H341.337z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">İtalya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#A2001D" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#0052B4" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Hollanda</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#D80027" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#F0F0F0" d="M215.304 256L0 399.475V112.525z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">İsviçre</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#D80027" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#F0F0F0" d="M256 85.331h256v341.337H256z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Polonya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#FFDA44" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#D80027" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#0052B4" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Romanya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#0052B4" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#D80027" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Lüksemburg</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#FFDA44" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#D80027" d="M512 85.331v166.69L0 256l512 3.979v166.69H0V85.331z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Belçika</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#F0F0F0" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#0052B4" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#D80027" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Slovenya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#FFDA44" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#6DA544" d="M0 85.331h512v113.775H0z"/>
                            <path fill="#D80027" d="M0 312.882h512v113.775H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Litvanya</h3>
                </div>
                <div class="country-card bg-white p-4 rounded-xl shadow-md hover:shadow-lg transition duration-300 flex flex-col items-center">
                    <div class="mb-3 w-16 h-16 rounded-full overflow-hidden border-2 border-blue-100">
                        <svg class="w-full h-full" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                            <path fill="#338AF3" d="M0 85.331h512v341.337H0z"/>
                            <path fill="#FFDA44" d="M0 85.331h512v170.668H0z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold text-gray-800">Ukrayna</h3>
                </div>
            </div>
            <div class="mt-10 text-center">
                <a href="#iletisim" class="inline-block bg-blue-600 text-white font-semibold px-6 py-3 rounded-lg shadow-lg hover:bg-blue-700 transition duration-300">Vize Başvurusu Yap</a>
            </div>
        </div>
    </section>

    <!-- Success Rate Section -->
    <section id="basari" class="py-16 bg-blue-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Başarı Oranımız</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Aventura olarak vize başvurularında %100 başarı oranına sahibiz. Red durumunda ikinci başvurunuz tamamen ücretsiz!</p>
            </div>
            <div class="flex flex-col md:flex-row items-center justify-center gap-8">
                <div class="w-full md:w-1/2 lg:w-1/3">
                    <div class="bg-white p-6 rounded-xl shadow-md">
                        <div class="flex justify-center mb-6">
                            <div class="relative">
                                <svg class="w-48 h-48" viewBox="0 0 100 100">
                                    <circle cx="50" cy="50" r="45" fill="none" stroke="#e6e6e6" stroke-width="5" />
                                    <circle cx="50" cy="50" r="45" fill="none" stroke="#2563eb" stroke-width="5" stroke-dasharray="283" stroke-dashoffset="0" />
                                    <text x="50" y="50" font-family="Arial" font-size="20" font-weight="bold" text-anchor="middle" alignment-baseline="middle" fill="#2563eb">100%</text>
                                </svg>
                            </div>
                        </div>
                        <h3 class="text-xl font-semibold text-center text-gray-800 mb-3">Başarı Oranımız</h3>
                        <p class="text-gray-600 text-center">Bugüne kadar tüm vize başvurularımız başarıyla sonuçlandı.</p>
                    </div>
                </div>
                <div class="w-full md:w-1/2 lg:w-2/3">
                    <div class="bg-white p-6 rounded-xl shadow-md">
                        <h3 class="text-xl font-semibold text-gray-800 mb-4">Neden Bizi Seçmelisiniz?</h3>
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-blue-600 mt-1 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                                </svg>
                                <div>
                                    <span class="font-medium">%100 Başarı Garantisi:</span> 
                                    <span class="text-gray-600">Vize başvurularında %100 başarı oranına sahibiz.</span>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-blue-600 mt-1 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                                </svg>
                                <div>
                                    <span class="font-medium">Ücretsiz İkinci Başvuru:</span> 
                                    <span class="text-gray-600">Red durumunda ikinci başvurunuz tamamen ücretsiz.</span>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-blue-600 mt-1 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                                </svg>
                                <div>
                                    <span class="font-medium">İspanya Vizesi Uzmanlığı:</span> 
                                    <span class="text-gray-600">Özellikle İspanya vizesi konusunda uzmanlaşmış ekip.</span>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-blue-600 mt-1 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                                </svg>
                                <div>
                                    <span class="font-medium">Profesyonel Ekip:</span> 
                                    <span class="text-gray-600">Vize süreçlerinde deneyimli uzman kadro.</span>
                                </div>
                            </li>
                            <li class="flex items-start">
                                <svg class="w-5 h-5 text-blue-600 mt-1 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                                </svg>
                                <div>
                                    <span class="font-medium">Hızlı Süreç:</span> 
                                    <span class="text-gray-600">En kısa sürede vize başvurunuzu tamamlıyoruz.</span>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Müşteri Yorumları</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Müşterilerimizin Aventura vize hizmetleri hakkındaki görüşleri</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="testimonial-card p-6">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold text-lg">AY</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Ahmet Yılmaz</h4>
                            <p class="text-sm text-gray-500">İspanya Vizesi</p>
                        </div>
                    </div>
                    <div class="flex mb-3">
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                    </div>
                    <p class="text-gray-600">"İspanya vizesi için Aventura'ya başvurdum. Tüm süreç çok profesyonelce ilerledi ve hiçbir sorun yaşamadan vizemi aldım. Kesinlikle tavsiye ederim."</p>
                </div>
                <div class="testimonial-card p-6">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold text-lg">MK</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Merve Kaya</h4>
                            <p class="text-sm text-gray-500">Almanya Vizesi</p>
                        </div>
                    </div>
                    <div class="flex mb-3">
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                    </div>
                    <p class="text-gray-600">"Almanya vizesi için evraklarımı hazırlamakta zorlanıyordum. Aventura'nın profesyonel ekibi sayesinde tüm süreç çok kolay ilerledi ve vizemi sorunsuz aldım."</p>
                </div>
                <div class="testimonial-card p-6">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold text-lg">ED</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Emre Demir</h4>
                            <p class="text-sm text-gray-500">İtalya Vizesi</p>
                        </div>
                    </div>
                    <div class="flex mb-3">
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                        <svg class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                        </svg>
                    </div>
                    <p class="text-gray-600">"İtalya vizesi başvurum için Aventura'yı tercih ettim. Çok hızlı ve profesyonel bir hizmet aldım. Teşekkürler Aventura ekibi!"</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="iletisim" class="py-16 bg-blue-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Bize Ulaşın</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Vize başvurunuz için hemen bizimle iletişime geçin.</p>
            </div>
            <div class="flex flex-col md:flex-row gap-8">
                <div class="w-full md:w-1/2 bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-gray-800 mb-6">İletişim Formu</h3>
                    <form id="contactForm" class="space-y-4">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Adınız Soyadınız</label>
                            <input type="text" id="name" name="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">E-posta Adresiniz</label>
                            <input type="email" id="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Telefon Numaranız</label>
                            <input type="tel" id="phone" name="phone" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div>
                            <label for="country" class="block text-sm font-medium text-gray-700 mb-1">Vize Başvurusu Yapacağınız Ülke</label>
                            <select id="country" name="country" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                                <option value="">Seçiniz</option>
                                <option value="İspanya">İspanya</option>
                                <option value="Almanya">Almanya</option>
                                <option value="Fransa">Fransa</option>
                                <option value="İtalya">İtalya</option>
                                <option value="Hollanda">Hollanda</option>
                                <option value="Diğer">Diğer</option>
                            </select>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Mesajınız</label>
                            <textarea id="message" name="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>
                        <div>
                            <button type="submit" class="w-full bg-blue-600 text-white font-semibold px-6 py-3 rounded-lg shadow-lg hover:bg-blue-700 transition duration-300">Gönder</button>
                        </div>
                    </form>
                    <div id="formSuccess" class="hidden mt-4 p-4 bg-green-100 text-green-700 rounded-md">
                        Mesajınız başarıyla gönderildi. En kısa sürede sizinle iletişime geçeceğiz.
                    </div>
                </div>
                <div class="w-full md:w-1/2 bg-white p-8 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-gray-800 mb-6">İletişim Bilgilerimiz</h3>
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-blue-100 rounded-full w-10 h-10 flex items-center justify-center mr-4 mt-1">
                                <svg class="w-5 h-5 text-blue-600" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-medium text-gray-800">Adres</h4>
                                <p class="text-gray-600 mt-1">Bağdat Caddesi No: 123, Kadıköy, İstanbul</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-blue-100 rounded-full w-10 h-10 flex items-center justify-center mr-4 mt-1">
                                <svg class="w-5 ```
