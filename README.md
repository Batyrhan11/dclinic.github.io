<!DOCTYPE html>
<html lang="ru" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D'CLINIC — Стоматология в Шымкенте</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0f172a',
                            teal: '#0e7490',
                            light: '#f8fafc',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-brand-light text-brand-dark font-sans antialiased selection:bg-brand-teal selection:text-white">

    <!-- Шапка сайта -->
    <header class="fixed top-0 left-0 right-0 bg-white/80 backdrop-blur-md z-50 border-b border-slate-100">
        <div class="max-w-5xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <span class="text-xl font-bold tracking-tight text-brand-dark">D'CLINIC</span>
                <span class="text-xs text-slate-400 hidden sm:inline">Dr. Jafari Jafar</span>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-600">
                <a href="#services" class="hover:text-brand-teal transition">Услуги</a>
                <a href="#about" class="hover:text-brand-teal transition">О нас</a>
                <a href="#contacts" class="hover:text-brand-teal transition">Контакты</a>
            </nav>
            <a href="https://wa.me/77713209995" target="_blank" class="bg-brand-dark text-white text-sm font-medium px-5 py-2.5 rounded-full hover:bg-brand-teal transition shadow-sm">
                WhatsApp
            </a>
        </div>
    </header>

    <!-- Первый экран (Hero) -->
    <section class="pt-32 pb-20 md:pt-44 md:pb-32 px-6">
        <div class="max-w-3xl mx-auto text-center">
            <div class="inline-block bg-brand-teal/10 text-brand-teal text-xs font-semibold px-3 py-1 rounded-full mb-6">
                Шымкент • Ул. Айбергенова, 1а
            </div>
            <h1 class="text-4xl md:text-6xl font-light tracking-tight text-brand-dark mb-6 leading-tight">
                Здоровая улыбка <br><span class="font-semibold">без компромиссов</span>
            </h1>
            <p class="text-lg text-slate-600 mb-10 max-w-xl mx-auto font-light">
                Более 5000 счастливых пациентов доверили нам свои улыбки. Опытные врачи, передовые технологии и комфортное лечение.
            </p>
            <div class="flex justify-center">
                <a href="https://wa.me/77713209995" target="_blank" class="bg-brand-teal text-white font-medium px-8 py-4 rounded-full hover:bg-cyan-800 transition shadow-lg shadow-brand-teal/20 text-center">
                    Записаться в WhatsApp
                </a>
            </div>
        </div>
    </section>

    <!-- Услуги -->
    <section id="services" class="py-24 bg-white border-t border-slate-100 px-6">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-light text-brand-dark mb-3">Наши направления</h2>
                <p class="text-slate-500 text-sm">Полный спектр стоматологических услуг для всей семьи</p>
            </div>
            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-brand-light p-8 rounded-2xl border border-slate-100 hover:border-brand-teal/30 transition">
                    <h3 class="text-lg font-medium mb-2">Брекеты и ортодонтия</h3>
                    <p class="text-slate-500 text-sm font-light">Исправление прикуса любой сложности для взрослых и подростков.</p>
                </div>
                <div class="bg-brand-light p-8 rounded-2xl border border-slate-100 hover:border-brand-teal/30 transition">
                    <h3 class="text-lg font-medium mb-2">Имплантация и Виниры</h3>
                    <p class="text-slate-500 text-sm font-light">Надежное восстановление зубов и эстетика Emax премиум-качества.</p>
                </div>
                <div class="bg-brand-light p-8 rounded-2xl border border-slate-100 hover:border-brand-teal/30 transition">
                    <h3 class="text-lg font-medium mb-2">Лечение и Удаление</h3>
                    <p class="text-slate-500 text-sm font-light">Безболезненное лечение кариеса и бережное удаление зубов.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- О клинике -->
    <section id="about" class="py-20 bg-brand-light border-t border-slate-100 px-6">
        <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-3xl font-light mb-6">D'CLINIC в Шымкенте</h2>
                <p class="text-slate-600 font-light text-sm leading-relaxed mb-6">
                    Мы создаем условия, в которых каждый пациент чувствует себя в безопасности. Работаем с передовыми материалами, гарантируем стерильность и индивидуальный подход.
                </p>
                <div class="flex items-center space-x-6 text-sm">
                    <div>
                        <span class="block text-2xl font-semibold text-brand-dark">5000+</span>
                        <span class="text-slate-400 text-xs">Улыбок</span>
                    </div>
                    <div class="w-px h-8 bg-slate-200"></div>
                    <div>
                        <span class="block text-2xl font-semibold text-brand-dark">24/7</span>
                        <span class="text-slate-400 text-xs">Забота о вас</span>
                    </div>
                </div>
            </div>
            <div class="bg-white p-8 rounded-3xl border border-slate-100">
                <h3 class="font-medium mb-4 text-brand-dark">Как нас найти:</h3>
                <p class="text-sm text-slate-600 font-light mb-2">📍 Г. Шымкент, ул. Айбергенова, 1а (1 этаж)</p>
                <p class="text-sm text-slate-600 font-light mb-6">⏰ Двери клиники всегда открыты для вас</p>
                <a href="https://wa.me/77713209995" target="_blank" class="block w-full bg-brand-dark text-white text-center py-3 rounded-xl text-sm font-medium hover:bg-brand-teal transition">
                    Задать вопрос в WhatsApp
                </a>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer id="contacts" class="py-12 bg-slate-900 text-white px-6">
        <div class="max-w-5xl mx-auto flex flex-col md:flex-row justify-between items-center text-sm font-light text-slate-400">
            <div class="mb-4 md:mb-0">
                <span class="text-white font-medium">D'CLINIC</span> Dr. Jafari Jafar © 2026
            </div>
            <div class="flex space-x-6">
                <a href="https://wa.me/77713209995" target="_blank" class="hover:text-white transition">WhatsApp: +7 (771) 320-99-95</a>
                <a href="https://instagram.com/dzhafar.clinic" target="_blank" class="hover:text-white transition">Instagram @dzhafar.clinic</a>
            </div>
        </div>
    </footer>

</body>
</html>
