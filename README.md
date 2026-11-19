<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JMG Sneaker Clinic | Cape Town Sneaker Care & Restoration</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Syne:wght@700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Syne', 'sans-serif'],
                    }
                }
            }
        };
    </script>
    <style>
        /* Custom subtle enhancements for smooth visual hierarchy */
        .hero-grid {
            background-image: radial-gradient(circle at top right, rgba(34, 211, 238, 0.14), transparent 45%),
                              radial-gradient(circle at bottom left, rgba(167, 139, 250, 0.14), transparent 45%);
        }
    </style>
</head>
<body id="top" class="bg-slate-950 text-slate-100 font-sans antialiased selection:bg-cyan-400 selection:text-slate-950">
    <!-- Toast notification container for user feedback (replaces native alert/confirm) -->
    <div id="toast-banner" role="status" aria-live="polite" class="fixed bottom-5 right-5 z-50 hidden max-w-sm rounded-2xl border border-cyan-400/40 bg-slate-900/95 px-4 py-3 text-xs sm:text-sm font-medium text-cyan-200 shadow-2xl backdrop-blur">
        <span id="toast-message"></span>
    </div>

    <!-- Top Navigation Bar -->
    <header class="sticky top-0 z-40 border-b border-slate-800/80 bg-slate-950/90 backdrop-blur">
        <div class="mx-auto flex max-w-6xl items-center justify-between px-4 py-3.5 sm:px-6">
            <a href="#top" class="flex items-center gap-2.5">
                <span class="inline-flex h-9 w-9 items-center justify-center rounded-xl bg-cyan-400/15 border border-cyan-400/40 font-display text-sm font-extrabold text-cyan-300">
                    JMG
                </span>
                <div>
                    <span class="block font-display text-sm sm:text-base font-extrabold tracking-tight text-white">JMG Sneaker Clinic</span>
                    <span class="block text-[11px] text-slate-400">Cape Town • Cash Only</span>
                </div>
            </a>

            <nav aria-label="Primary Navigation" class="hidden md:flex items-center gap-6 text-xs font-medium text-slate-300">
                <a href="#packages" class="hover:text-cyan-300 transition">Packages</a>
                <a href="#showcase" class="hover:text-cyan-300 transition">Converse &amp; Care</a>
                <a href="#handover" class="hover:text-cyan-300 transition">Cape Town Handover</a>
                <a href="#faq" class="hover:text-cyan-300 transition">Care &amp; FAQ</a>
                <a href="#quote" class="hover:text-cyan-300 transition">Quote Estimator</a>
            </nav>

            <a href="#quote" class="inline-flex items-center justify-center rounded-xl bg-cyan-400 hover:bg-cyan-300 px-3.5 py-2 text-xs font-display font-extrabold text-slate-950 transition">
                Get Quote
            </a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero-grid border-b border-slate-800/80 py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-7 space-y-5">
                        <div class="inline-flex items-center gap-2 rounded-full border border-cyan-400/30 bg-cyan-400/10 px-3.5 py-1 text-xs font-medium text-cyan-300">
                            <span>Fresh Kicks. Honest Care. Cape Town Local.</span>
                        </div>
                        <h1 class="font-display text-3xl sm:text-5xl font-extrabold tracking-tight text-white leading-tight">
                            Precision sneaker cleaning &amp; restoration built for everyday rotation.
                        </h1>
                        <p class="text-sm sm:text-base text-slate-300 leading-relaxed max-w-2xl">
                            From daily beaters and canvas classics to suede and midsole touch-ups, JMG Sneaker Clinic helps Cape Town sneakerheads keep their rotation crisp with transparent ZAR pricing and direct WhatsApp booking.
                        </p>
                        <div class="flex flex-wrap items-center gap-3 pt-1">
                            <a href="#quote" class="inline-flex items-center justify-center rounded-2xl bg-emerald-400 hover:bg-emerald-300 px-5 py-3 text-sm font-display font-extrabold text-slate-950 shadow-lg shadow-emerald-500/20 transition">
                                Build WhatsApp Quote
                            </a>
                            <a href="#packages" class="inline-flex items-center justify-center rounded-2xl border border-slate-700 hover:border-slate-500 bg-slate-900/80 hover:bg-slate-900 px-5 py-3 text-sm font-display font-bold text-slate-200 transition">
                                View ZAR Packages
                            </a>
                        </div>
                        <div class="grid grid-cols-3 gap-3 pt-3 max-w-lg text-center sm:text-left">
                            <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-3">
                                <span class="block font-display text-base sm:text-lg font-extrabold text-cyan-300">24–48h</span>
                                <span class="block text-[11px] text-slate-400">Typical Turnaround</span>
                            </div>
                            <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-3">
                                <span class="block font-display text-base sm:text-lg font-extrabold text-emerald-300">R120+</span>
                                <span class="block text-[11px] text-slate-400">Starter Care (ZAR)</span>
                            </div>
                            <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-3">
                                <span class="block font-display text-base sm:text-lg font-extrabold text-violet-300">Cash Only</span>
                                <span class="block text-[11px] text-slate-400">At Handover</span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-5">
                        <div class="rounded-3xl border border-slate-800 bg-slate-900/80 p-4 sm:p-5 shadow-2xl space-y-4">
                            <!-- Nike sneaker photography with safe fallback -->
                            <img
                                src="https://images.pexels.com/photos/18202578/pexels-photo-18202578.jpeg?auto=compress&cs=tinysrgb&w=1200"
                                alt="Nike sneakers displayed for care and restoration at JMG Sneaker Clinic"
                                onerror="this.onerror=null;this.src='https://placehold.co/800x520/0f172a/22d3ee?text=Nike+Sneaker+Care';"
                                class="w-full h-56 sm:h-64 object-cover rounded-2xl border border-slate-800 bg-slate-950"
                            >
                            <div class="space-y-1.5 px-1">
                                <p class="font-display text-sm font-bold text-white">Pre-Drop-Off Photo Tip</p>
                                <p class="text-xs text-slate-300 leading-relaxed">
                                    Snap a quick clear photo of any heavy scuffs, suede spots, or lace/sole wear before sending your WhatsApp quote so we can set honest expectations upfront.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Packages Section -->
        <section id="packages" class="border-b border-slate-800/80 py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6 space-y-8">
                <div class="max-w-2xl space-y-2">
                    <span class="text-xs font-display font-bold uppercase tracking-wider text-cyan-300">Transparent ZAR Pricing</span>
                    <h2 class="font-display text-2xl sm:text-4xl font-extrabold text-white">Sneaker Care Packages</h2>
                    <p class="text-sm text-slate-300">
                        Select a package below to load it directly into your live quote estimator. Multi-pair bundles (2+ pairs) are welcome—mention multiple pairs in WhatsApp for combined drop-off or bundle discussion.
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <!-- Express Refresh -->
                    <article class="rounded-3xl border border-slate-800 bg-slate-900/70 p-6 flex flex-col justify-between space-y-6">
                        <div class="space-y-3">
                            <div class="flex items-center justify-between">
                                <h3 class="font-display text-lg font-extrabold text-white">Express Refresh</h3>
                                <span class="font-display text-xl font-extrabold text-cyan-300">R120</span>
                            </div>
                            <p class="text-xs text-slate-400">Per pair • Ideal for light dust, surface marks, and regular rotation maintenance.</p>
                            <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                                <li>• Upper surface &amp; midsole wipe/brush clean</li>
                                <li>• Lace &amp; collar freshening</li>
                                <li>• Quick deodorizing finish</li>
                            </ul>
                        </div>
                        <button type="button" onclick="selectPackageForQuote('Express Refresh', 120)" class="w-full rounded-2xl border border-cyan-500/40 bg-cyan-500/10 hover:bg-cyan-500/20 py-2.5 text-xs sm:text-sm font-display font-bold text-cyan-200 transition">
                            Select Express (R120)
                        </button>
                    </article>

                    <!-- Deep Clinic Treatment -->
                    <article class="rounded-3xl border-2 border-cyan-400/60 bg-slate-900 p-6 flex flex-col justify-between space-y-6 shadow-xl shadow-cyan-500/10">
                        <div class="space-y-3">
                            <div class="flex items-center justify-between">
                                <h3 class="font-display text-lg font-extrabold text-white">Deep Clinic Treatment</h3>
                                <span class="font-display text-xl font-extrabold text-emerald-300">R180</span>
                            </div>
                            <p class="text-xs text-slate-400">Per pair • Our go-to thorough clean for everyday wearers and canvas/mesh pairs.</p>
                            <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                                <li>• Full upper, tongue, eyelet &amp; midsole scrub</li>
                                <li>• Dedicated lace wash &amp; fresh finish</li>
                                <li>• Interior sanitization &amp; odor control</li>
                            </ul>
                        </div>
                        <button type="button" onclick="selectPackageForQuote('Deep Clinic Treatment', 180)" class="w-full rounded-2xl bg-cyan-400 hover:bg-cyan-300 py-2.5 text-xs sm:text-sm font-display font-extrabold text-slate-950 transition">
                            Select Deep Clinic (R180)
                        </button>
                    </article>

                    <!-- Full Restoration & Suede Care -->
                    <article class="rounded-3xl border border-slate-800 bg-slate-900/70 p-6 flex flex-col justify-between space-y-6">
                        <div class="space-y-3">
                            <div class="flex items-center justify-between">
                                <h3 class="font-display text-lg font-extrabold text-white">Restoration &amp; Suede Care</h3>
                                <span class="font-display text-xl font-extrabold text-violet-300">R240</span>
                            </div>
                            <p class="text-xs text-slate-400">Per pair • Targeted care for delicate suede, nubuck, stubborn grime, and detail work.</p>
                            <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                                <li>• Controlled suede/nubuck brushing &amp; spot care</li>
                                <li>• Deep midsole &amp; stitching detail clean</li>
                                <li>• Conditioning &amp; post-clean inspection</li>
                            </ul>
                        </div>
                        <button type="button" onclick="selectPackageForQuote('Restoration & Suede Care', 240)" class="w-full rounded-2xl border border-violet-500/40 bg-violet-500/10 hover:bg-violet-500/20 py-2.5 text-xs sm:text-sm font-display font-bold text-violet-200 transition">
                            Select Restoration (R240)
                        </button>
                    </article>
                </div>
            </div>
        </section>

        <!-- Interactive Showcase & Care Tabs -->
        <section id="showcase" class="border-b border-slate-800/80 py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6 space-y-6">
                <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-4">
                    <div class="space-y-1.5">
                        <span class="text-xs font-display font-bold uppercase tracking-wider text-violet-300">Material &amp; Silhouette Focus</span>
                        <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-white">Nike, New Balance &amp; Converse All Star Care</h2>
                    </div>
                    <div role="tablist" aria-label="Showcase Tabs" class="inline-flex flex-wrap gap-2 rounded-2xl border border-slate-800 bg-slate-900 p-1.5">
                        <button type="button" role="tab" id="tab-btn-converse" aria-selected="true" onclick="switchShowcaseTab('converse')" class="showcase-tab rounded-xl bg-cyan-400 px-3.5 py-2 text-xs font-display font-extrabold text-slate-950 transition">
                            Converse All Star Showcase
                        </button>
                        <button type="button" role="tab" id="tab-btn-suede" aria-selected="false" onclick="switchShowcaseTab('suede')" class="showcase-tab rounded-xl px-3.5 py-2 text-xs font-display font-bold text-slate-300 hover:text-white transition">
                            New Balance &amp; Suede
                        </button>
                        <button type="button" role="tab" id="tab-btn-turnaround" aria-selected="false" onclick="switchShowcaseTab('turnaround')" class="showcase-tab rounded-xl px-3.5 py-2 text-xs font-display font-bold text-slate-300 hover:text-white transition">
                            Turnaround &amp; Slots
                        </button>
                    </div>
                </div>

                <!-- Always-visible Nike, New Balance & Converse photo strip -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
                    <figure class="rounded-2xl border border-slate-800 bg-slate-900/80 p-3.5 space-y-2.5">
                        <img
                            src="https://images.pexels.com/photos/18202578/pexels-photo-18202578.jpeg?auto=compress&cs=tinysrgb&w=900"
                            alt="Nike sneakers leather and midsole care"
                            onerror="this.onerror=null;this.src='https://placehold.co/700x440/0f172a/22d3ee?text=Nike+Sneakers';"
                            class="w-full h-44 object-cover rounded-xl border border-slate-800 bg-slate-950"
                        >
                        <figcaption class="px-1">
                            <span class="block font-display text-sm font-bold text-white">Nike Silhouettes</span>
                            <span class="block text-xs text-slate-400">Leather panels, mesh uppers &amp; midsole detail</span>
                        </figcaption>
                    </figure>

                    <figure class="rounded-2xl border border-slate-800 bg-slate-900/80 p-3.5 space-y-2.5">
                        <img
                            src="https://images.pexels.com/photos/18202638/pexels-photo-18202638.jpeg?auto=compress&cs=tinysrgb&w=900"
                            alt="New Balance running shoe care and suede maintenance"
                            onerror="this.onerror=null;this.src='https://placehold.co/700x440/0f172a/a78bfa?text=New+Balance+Running+Shoe';"
                            class="w-full h-44 object-cover rounded-xl border border-slate-800 bg-slate-950"
                        >
                        <figcaption class="px-1">
                            <span class="block font-display text-sm font-bold text-white">New Balance Runners</span>
                            <span class="block text-xs text-slate-400">Running shoe mesh, suede nap &amp; cushioned soles</span>
                        </figcaption>
                    </figure>

                    <figure class="rounded-2xl border border-slate-800 bg-slate-900/80 p-3.5 space-y-2.5">
                        <img
                            src="https://images.pexels.com/photos/12651117/pexels-photo-12651117.jpeg?auto=compress&cs=tinysrgb&w=900"
                            alt="Converse All Star canvas shoes and rubber foxing"
                            onerror="this.onerror=null;this.src='https://placehold.co/700x440/0f172a/38bdf8?text=Converse+All+Star';"
                            class="w-full h-44 object-cover rounded-xl border border-slate-800 bg-slate-950"
                        >
                        <figcaption class="px-1">
                            <span class="block font-display text-sm font-bold text-white">Converse All Star</span>
                            <span class="block text-xs text-slate-400">Canvas uppers, laces &amp; rubber toe/foxing</span>
                        </figcaption>
                    </figure>
                </div>

                <!-- Tab 1: Converse All Star Showcase -->
                <div id="tab-panel-converse" class="showcase-panel rounded-3xl border border-slate-800 bg-slate-900/70 p-6 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
                    <div class="md:col-span-5">
                        <!-- Original Converse canvas sneaker photography with safe fallback -->
                        <img
                            src="https://images.pexels.com/photos/12651117/pexels-photo-12651117.jpeg?auto=compress&cs=tinysrgb&w=1000"
                            alt="Converse All Star canvas sneakers and rubber foxing"
                            onerror="this.onerror=null;this.src='https://placehold.co/700x460/0f172a/38bdf8?text=Converse+All+Star+Care';"
                            class="w-full h-52 sm:h-60 object-cover rounded-2xl border border-slate-800 bg-slate-950"
                        >
                    </div>
                    <div class="md:col-span-7 space-y-3">
                        <h3 class="font-display text-xl font-extrabold text-white">Converse All Star Canvas &amp; Rubber Foxing</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Chuck Taylors and All Stars are staples across Cape Town. We focus on lifting dirt from woven canvas uppers, brightening rubber toe caps and foxing stripes without harsh bleaching, and restoring clean laces so your everyday pair looks sharp again.
                        </p>
                        <p class="text-xs text-cyan-200 bg-cyan-500/10 border border-cyan-500/30 rounded-xl px-3.5 py-2.5">
                            Tip: Multi-pair Converse or daily beater drop-offs (2+ pairs) are super common—select your pair count in the quote estimator below.
                        </p>
                    </div>
                </div>

                <!-- Tab 2: New Balance & Suede -->
                <div id="tab-panel-suede" class="showcase-panel hidden rounded-3xl border border-slate-800 bg-slate-900/70 p-6 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
                    <div class="md:col-span-5">
                        <!-- New Balance running shoe photography with safe fallback -->
                        <img
                            src="https://images.pexels.com/photos/18202638/pexels-photo-18202638.jpeg?auto=compress&cs=tinysrgb&w=1000"
                            alt="New Balance running shoe prepared for care"
                            onerror="this.onerror=null;this.src='https://placehold.co/700x460/0f172a/a78bfa?text=New+Balance+Running+Shoe';"
                            class="w-full h-52 sm:h-60 object-cover rounded-2xl border border-slate-800 bg-slate-950"
                        >
                    </div>
                    <div class="md:col-span-7 space-y-3">
                        <h3 class="font-display text-xl font-extrabold text-white">New Balance, Suede &amp; Stubborn Stains</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            New Balance runners, suede, and nubuck require gentle dry/low-moisture techniques to preserve nap texture, mesh panels, and dye stability. While most surface dirt, scuffs, and everyday marks lift cleanly, deep oil stains, set-in dye bleed, or worn-through fabric/sole wear may only improve partially rather than vanish 100%.
                        </p>
                        <p class="text-xs text-slate-300 leading-relaxed">
                            Sending a clear photo of trouble spots before drop-off helps us set realistic expectations before you pay cash at handover.
                        </p>
                    </div>
                </div>

                <!-- Tab 3: Turnaround & Slots -->
                <div id="tab-panel-turnaround" class="showcase-panel hidden rounded-3xl border border-slate-800 bg-slate-900/70 p-6 space-y-4">
                    <h3 class="font-display text-xl font-extrabold text-white">Turnaround Times &amp; Daily Handover Slots</h3>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                        Most pairs turn around in <span class="font-semibold text-white">24 to 48 hours</span> once received, allowing proper air/controlled drying so glue lines and suede stay healthy.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                        Drop-off and collection windows are confirmed directly on WhatsApp—weekday evenings and weekend slots are arranged around local Cape Town handover meetups/hubs.
                    </p>
                </div>
            </div>
        </section>

        <!-- Cape Town Handover & Delivery vs Drop-Off -->
        <section id="handover" class="border-b border-slate-800/80 py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6 space-y-6">
                <div class="max-w-2xl space-y-2">
                    <span class="text-xs font-display font-bold uppercase tracking-wider text-emerald-300">Local Handover</span>
                    <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-white">Cape Town Suburbs: Drop-Off &amp; Collection Only</h2>
                    <p class="text-sm text-slate-300">
                        Cape Town suburbs, drop-off and collection only—we are not delivering shoes. We coordinate same-venue drop-off and collection across Cape Town areas by confirmed WhatsApp slot.
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="rounded-3xl border border-slate-800 bg-slate-900/70 p-6 space-y-2.5">
                        <h3 class="font-display text-base font-extrabold text-white">Same-Venue Drop-Off &amp; Collection</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Drop-off and collection happen at the same agreed handover venue—book a time slot via WhatsApp first, then collect back at that same spot once we message you that your sneakers are ready.
                        </p>
                    </div>
                    <div class="rounded-3xl border border-slate-800 bg-slate-900/70 p-6 space-y-2.5">
                        <h3 class="font-display text-base font-extrabold text-white">No Shoe Delivery</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            We are not delivering shoes. All orders across Cape Town suburbs are handled via drop-off and collection at your confirmed handover slot and same agreed venue.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Care Guide & Quick FAQ -->
        <section id="faq" class="border-b border-slate-800/80 py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6 space-y-6">
                <div class="space-y-1.5">
                    <span class="text-xs font-display font-bold uppercase tracking-wider text-cyan-300">Care Guide &amp; FAQ</span>
                    <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-white">Quick Answers Before You Book</h2>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                    <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 space-y-1.5">
                        <h3 class="font-display text-sm font-bold text-white">How does payment work?</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Cash payments only at handover. Please bring exact or close cash where possible and confirm your slot on WhatsApp before heading out.
                        </p>
                    </div>
                    <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 space-y-1.5">
                        <h3 class="font-display text-sm font-bold text-white">Should I remove laces or delicate insoles?</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Mention specialty laces or removable insoles in your notes. We treat laces cleanly and avoid soaking delicate insoles that could warp or unglue.
                        </p>
                    </div>
                    <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 space-y-1.5">
                        <h3 class="font-display text-sm font-bold text-white">Can I bring more than one pair at a time?</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Yes! Set your pair count in the quote estimator to calculate multi-pair totals and ask on WhatsApp if you want bundle options or a combined slot.
                        </p>
                    </div>
                    <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 space-y-1.5">
                        <h3 class="font-display text-sm font-bold text-white">What if I need to change my time slot?</h3>
                        <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                            Just send a quick WhatsApp message if your plans change or you're running late, and collect promptly once your sneakers are ready so handover slots stay open.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Interactive Quote Estimator Section -->
        <section id="quote" class="py-12 sm:py-16">
            <div class="mx-auto max-w-6xl px-4 sm:px-6 space-y-8">
                <div class="max-w-2xl space-y-2">
                    <span class="text-xs font-display font-bold uppercase tracking-wider text-emerald-300">Instant Estimate</span>
                    <h2 class="font-display text-2xl sm:text-4xl font-extrabold text-white">WhatsApp Quote Estimator</h2>
                    <p class="text-sm text-slate-300">
                        Customize your package, pair count, optional add-ons, handover preference, and Cape Town area to generate a ready-to-send WhatsApp quote.
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 items-start">
                    <!-- Quote Form -->
                    <form onsubmit="event.preventDefault(); sendWhatsAppQuote();" class="lg:col-span-6 rounded-3xl border border-slate-800 bg-slate-900/80 p-5 sm:p-7 space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="quote-package" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Care Package</label>
                                <select id="quote-package" onchange="recalculateQuote()" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white">
                                    <option value="Express Refresh|120">Express Refresh — R120 / pair</option>
                                    <option value="Deep Clinic Treatment|180" selected>Deep Clinic Treatment — R180 / pair</option>
                                    <option value="Restoration & Suede Care|240">Restoration &amp; Suede Care — R240 / pair</option>
                                </select>
                            </div>
                            <div>
                                <label for="quote-pairs" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Number of Pairs</label>
                                <input id="quote-pairs" type="number" min="1" max="20" value="1" oninput="recalculateQuote()" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white">
                            </div>
                        </div>

                        <div>
                            <span class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-2">Optional Add-Ons (ZAR)</span>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs sm:text-sm text-slate-200">
                                <label class="flex items-center gap-2.5 rounded-xl border border-slate-800 bg-slate-950/80 px-3.5 py-2.5 cursor-pointer hover:border-slate-700">
                                    <input type="checkbox" value="Midsole Whitening (+R40)" data-price="40" onchange="recalculateQuote()" class="addon-checkbox rounded border-slate-600 bg-slate-900 text-cyan-400 focus:ring-cyan-400">
                                    <span>Midsole Whitening (+R40)</span>
                                </label>
                                <label class="flex items-center gap-2.5 rounded-xl border border-slate-800 bg-slate-950/80 px-3.5 py-2.5 cursor-pointer hover:border-slate-700">
                                    <input type="checkbox" value="Fresh Laces Set (+R35)" data-price="35" onchange="recalculateQuote()" class="addon-checkbox rounded border-slate-600 bg-slate-900 text-cyan-400 focus:ring-cyan-400">
                                    <span>Fresh Laces Set (+R35)</span>
                                </label>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="quote-name" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Your Name (Optional)</label>
                                <input id="quote-name" type="text" oninput="recalculateQuote()" placeholder="e.g. Jordan" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white placeholder-slate-500">
                            </div>
                            <div>
                                <label for="quote-handover" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Handover Option</label>
                                <select id="quote-handover" onchange="recalculateQuote()" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white">
                                    <option value="Same-Venue Drop-Off & Collection" selected>Same-Venue Drop-Off &amp; Collection</option>
                                    <option value="Same-Venue Slot Confirmation">Same-Venue Slot Confirmation</option>
                                    <option value="Multi-Pair Same-Venue Handover">Multi-Pair Same-Venue Handover</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="quote-suburb" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Cape Town Suburb / Area</label>
                                <input id="quote-suburb" type="text" oninput="recalculateQuote()" placeholder="e.g. Claremont, Sea Point, Bellville" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white placeholder-slate-500">
                            </div>
                            <div>
                                <label for="quote-time-slot" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Preferred Time / Slot (Optional)</label>
                                <input id="quote-time-slot" type="text" oninput="recalculateQuote()" placeholder="e.g. Weekday evenings, Sat morning" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white placeholder-slate-500">
                            </div>
                        </div>

                        <div>
                            <label for="quote-fabric-note" class="block text-xs font-display font-bold uppercase tracking-wider text-slate-300 mb-1.5">Shoe &amp; Fabric Notes (Optional)</label>
                            <input id="quote-fabric-note" type="text" oninput="recalculateQuote()" placeholder="e.g. Canvas, suede upper, scuffed toe cap, laces" class="w-full rounded-xl bg-slate-950 border border-slate-700 focus:border-cyan-400 focus:outline-none px-3.5 py-2.5 text-sm text-white placeholder-slate-500">
                        </div>

                        <div class="pt-1 flex flex-wrap items-center justify-between gap-2">
                            <button type="button" onclick="applySampleQuotePreset()" class="inline-flex items-center gap-2 rounded-xl border border-cyan-500/40 hover:border-cyan-400 bg-cyan-500/10 hover:bg-cyan-500/20 px-3.5 py-2 text-xs font-display font-bold text-cyan-300 transition">
                                Try Sample Pair (2x Converse • Claremont)
                            </button>
                            <button type="button" onclick="resetQuoteEstimator()" class="inline-flex items-center gap-2 rounded-xl border border-slate-700 hover:border-slate-500 bg-slate-950/80 hover:bg-slate-900 px-3.5 py-2 text-xs font-display font-bold text-slate-300 hover:text-white transition">
                                Reset Quote
                            </button>
                        </div>
                    </form>

                    <!-- Quote Summary & WhatsApp Actions -->
                    <div class="lg:col-span-6 bg-slate-950/90 border border-slate-800 rounded-3xl p-5 sm:p-7 flex flex-col justify-between space-y-5">
                        <div class="space-y-4">
                            <div class="flex items-center justify-between border-b border-slate-800 pb-3">
                                <span class="text-xs font-display font-bold uppercase tracking-wider text-slate-400">Estimated Total</span>
                                <span id="quote-total-display" class="text-2xl sm:text-3xl font-display font-extrabold text-cyan-300">R180</span>
                            </div>
                            <p id="quote-math-breakdown" class="text-xs text-slate-400">
                                1 pair × R180 base + R0 add-ons (Single-pair estimate)
                            </p>
                            <p id="quote-multibundle-note" class="hidden rounded-xl bg-cyan-500/10 border border-cyan-500/30 px-3.5 py-2 text-xs text-cyan-200">
                                Multi-pair selected (2+ pairs): mention this bundle in WhatsApp if you'd like a multi-pair discount or combined drop-off slot.
                            </p>
                            <div>
                                <p class="text-xs font-display font-bold uppercase tracking-wider text-slate-400 mb-2">WhatsApp Message Preview</p>
                                <pre id="quote-message-preview" class="whitespace-pre-wrap break-words rounded-2xl bg-slate-900 border border-slate-800 p-4 text-xs text-slate-200 font-sans leading-relaxed"></pre>
                            </div>
                            <p class="rounded-xl bg-slate-900/80 border border-slate-800 px-3.5 py-2.5 text-xs text-slate-300">
                                <span class="font-display font-bold text-violet-300">Laces &amp; Insoles Care Tip:</span> Please mention if you have specialty laces or removable insoles—we treat laces cleanly and avoid soaking delicate insoles that could warp or unglue.
                            </p>
                            <p class="rounded-xl bg-slate-900/80 border border-slate-800 px-3.5 py-2.5 text-xs text-slate-300">
                                <span class="font-display font-bold text-emerald-300">Payment &amp; Handover Confirmation:</span> Cash payments only—please confirm your drop-off or collection slot on WhatsApp before heading out and have cash ready at handover.
                            </p>
                            <p class="rounded-xl bg-slate-900/80 border border-slate-800 px-3.5 py-2.5 text-xs text-slate-300">
                                <span class="font-display font-bold text-cyan-300">Exact Cash Tip:</span> Bring exact or close cash where possible at drop-off or collection so handover stays quick and smooth.
                            </p>
                            <p class="rounded-xl bg-slate-900/80 border border-slate-800 px-3.5 py-2.5 text-xs text-slate-300">
                                <span class="font-display font-bold text-rose-300">Slot &amp; Collection Courtesy:</span> Please confirm if your plans change or you're running late for a booked slot, and collect promptly once your sneakers are ready so space stays open for other pairs.
                            </p>
                        </div>

                        <div class="space-y-3">
                            <p class="text-xs text-slate-300 bg-slate-900/70 border border-slate-800/90 rounded-xl px-3.5 py-2">
                                <span class="font-display font-bold text-amber-300">Turnaround Reminder:</span> Standard turnaround is typically 24–48 hours depending on shoe condition, suede drying, and confirmed handover slots.
                            </p>
                            <a id="whatsapp-quote-link" href="https://wa.me/27814094670" target="_blank" rel="noopener noreferrer" class="w-full inline-flex items-center justify-center gap-2 rounded-2xl bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-display font-extrabold text-sm px-5 py-3.5 shadow-lg shadow-emerald-500/20 transition">
                                Send Quote on WhatsApp
                            </a>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5">
                                <button type="button" onclick="copyQuoteMessage()" class="w-full inline-flex items-center justify-center gap-2 rounded-2xl border border-slate-700 hover:border-slate-500 bg-slate-900 hover:bg-slate-800 text-slate-200 font-display font-bold text-xs sm:text-sm px-4 py-3 transition">
                                    Copy Message
                                </button>
                                <button type="button" onclick="copyWhatsAppBookingLink()" class="w-full inline-flex items-center justify-center gap-2 rounded-2xl border border-slate-700 hover:border-slate-500 bg-slate-900 hover:bg-slate-800 text-slate-200 font-display font-bold text-xs sm:text-sm px-4 py-3 transition">
                                    Copy WhatsApp Link
                                </button>
                            </div>
                        </div>

                        <div class="pt-4 border-t border-slate-800/80 text-xs text-slate-400 space-y-1.5">
                            <p class="font-display font-bold text-slate-200">Pre-Launch &amp; Mobile Sharing Check</p>
                            <p>WhatsApp target: <span class="text-cyan-300 font-mono">+27 81 409 4670</span> • Rates: <span class="text-slate-200">R120 / R180 / R240 ZAR</span> • Payment: <span class="text-emerald-300">Cash Only</span></p>
                            <p>Test package buttons, quote copy, WhatsApp link copy, reset, and WhatsApp links on your phone after hosting `index.html` on GitHub Pages, Netlify, or Vercel, then share your live link on WhatsApp Status, Instagram bio, or local community chats.</p>
                            <p>Before going public, swap any preview/fallback images you want to customize with your own real clinic photos and confirm your daily drop-off and collection time slots.</p>
                            <p class="text-slate-300">Ready to share: once verified on mobile, paste your live page URL into your WhatsApp Status, bio, or local Cape Town groups so customers can build quotes in seconds.</p>
                            <p class="text-slate-400">Quick launch check: confirm your WhatsApp number, Cape Town handover areas, and cash-only note read clearly on both portrait and landscape mobile views.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800/80 bg-slate-950 py-10">
        <div class="mx-auto max-w-6xl px-4 sm:px-6 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-6">
            <div class="space-y-1 text-xs text-slate-400">
                <p class="font-display text-sm font-extrabold text-white">JMG Sneaker Clinic</p>
                <p>Cape Town Sneaker Care &amp; Restoration • Cash Payments Only • WhatsApp +27 81 409 4670</p>
            </div>

            <div class="flex flex-wrap items-center gap-4 text-xs font-medium text-slate-300">
                <a href="#packages" class="hover:text-cyan-300 transition">Packages</a>
                <a href="#showcase" class="hover:text-cyan-300 transition">Showcase</a>
                <a href="#handover" class="hover:text-cyan-300 transition">Handover</a>
                <a href="#quote" class="hover:text-cyan-300 transition">Quote</a>
                <a href="#top" class="rounded-xl border border-slate-700 hover:border-cyan-400/60 bg-slate-900 px-3 py-1.5 font-display font-bold text-cyan-300 transition">
                    Back to Top ↑
                </a>
            </div>
        </div>
    </footer>

    <script>
        const WHATSAPP_NUMBER = '27814094670';
        let toastTimer = null;

        /**
         * Displays a subtle non-blocking status toast message.
         */
        function showToast(msg) {
            try {
                const banner = document.getElementById('toast-banner');
                const textEl = document.getElementById('toast-message');
                if (!banner || !textEl) return;

                textEl.textContent = msg;
                banner.classList.remove('hidden');

                if (toastTimer) {
                    clearTimeout(toastTimer);
                }
                toastTimer = setTimeout(() => {
                    banner.classList.add('hidden');
                }, 3200);
            } catch (err) {
                console.error('Toast error:', err);
            }
        }

        /**
         * Copies text using document.execCommand('copy') with clipboard fallback.
         */
        function copyTextSafely(text, successLabel) {
            try {
                const tempInput = document.createElement('textarea');
                tempInput.value = text;
                tempInput.setAttribute('readonly', '');
                tempInput.style.position = 'fixed';
                tempInput.style.left = '-9999px';
                document.body.appendChild(tempInput);
                tempInput.select();
                document.execCommand('copy');
                document.body.removeChild(tempInput);
                showToast(successLabel);
            } catch (err) {
                console.error('Copy failed:', err);
                showToast('Could not copy automatically. You can still copy manually.');
            }
        }

        /**
         * Selects a package from the package cards and scrolls smoothly to the quote estimator.
         */
        function selectPackageForQuote(pkgName, pkgPrice) {
            try {
                const pkgSelect = document.getElementById('quote-package');
                if (pkgSelect) {
                    pkgSelect.value = `${pkgName}|${pkgPrice}`;
                }
                recalculateQuote();
                const quoteSection = document.getElementById('quote');
                if (quoteSection) {
                    quoteSection.scrollIntoView({ behavior: 'smooth' });
                }
                showToast(`Selected ${pkgName} (R${pkgPrice}/pair).`);
            } catch (err) {
                console.error('Error selecting package:', err);
            }
        }

        /**
         * Switches active showcase tab and displays its matching panel.
         */
        function switchShowcaseTab(tabKey) {
            try {
                const tabButtons = {
                    converse: document.getElementById('tab-btn-converse'),
                    suede: document.getElementById('tab-btn-suede'),
                    turnaround: document.getElementById('tab-btn-turnaround')
                };
                const tabPanels = {
                    converse: document.getElementById('tab-panel-converse'),
                    suede: document.getElementById('tab-panel-suede'),
                    turnaround: document.getElementById('tab-panel-turnaround')
                };

                Object.keys(tabPanels).forEach((key) => {
                    const panel = tabPanels[key];
                    const btn = tabButtons[key];
                    const isActive = key === tabKey;

                    if (panel) {
                        panel.classList.toggle('hidden', !isActive);
                    }
                    if (btn) {
                        btn.setAttribute('aria-selected', String(isActive));
                        if (isActive) {
                            btn.className = 'showcase-tab rounded-xl bg-cyan-400 px-3.5 py-2 text-xs font-display font-extrabold text-slate-950 transition';
                        } else {
                            btn.className = 'showcase-tab rounded-xl px-3.5 py-2 text-xs font-display font-bold text-slate-300 hover:text-white transition';
                        }
                    }
                });
            } catch (err) {
                console.error('Error switching tab:', err);
            }
        }

        /**
         * Updates the multi-pair bundle notice when 2 or more pairs are chosen.
         */
        function updateMultiBundleNotice(pairsCount) {
            const bundleNote = document.getElementById('quote-multibundle-note');
            if (!bundleNote) return;
            bundleNote.classList.toggle('hidden', !(pairsCount >= 2));
        }

        /**
         * Recalculates total ZAR estimate, updates breakdown & preview text, and builds WhatsApp URL.
         */
        function recalculateQuote() {
            try {
                const pkgRaw = document.getElementById('quote-package')?.value || 'Deep Clinic Treatment|180';
                const [pkgName, priceStr] = pkgRaw.split('|');
                const pkgPrice = Number.parseInt(priceStr, 10) || 180;

                const rawPairs = Number.parseInt(document.getElementById('quote-pairs')?.value || '1', 10);
                const pairsCount = Number.isNaN(rawPairs) || rawPairs < 1 ? 1 : Math.min(rawPairs, 20);

                let addonPerPairTotal = 0;
                const selectedAddons = [];
                document.querySelectorAll('.addon-checkbox:checked').forEach((cb) => {
                    const addonPrice = Number.parseInt(cb.getAttribute('data-price') || '0', 10) || 0;
                    addonPerPairTotal += addonPrice;
                    selectedAddons.push(cb.value);
                });

                const estimatedTotal = (pkgPrice + addonPerPairTotal) * pairsCount;

                const totalDisplay = document.getElementById('quote-total-display');
                if (totalDisplay) {
                    totalDisplay.textContent = `R${estimatedTotal}`;
                }

                // Auto-sync multi-pair bundle notice
                updateMultiBundleNotice(pairsCount);

                const handover = document.getElementById('quote-handover')?.value || 'Same-Venue Drop-Off & Collection';
                const customerName = (document.getElementById('quote-name')?.value || '').trim();
                const suburb = (document.getElementById('quote-suburb')?.value || '').trim();
                const timeSlot = (document.getElementById('quote-time-slot')?.value || '').trim();
                const fabricNote = (document.getElementById('quote-fabric-note')?.value || '').trim();

                // Update single-pair vs. multi-pair breakdown line when present
                const mathEl = document.getElementById('quote-math-breakdown');
                if (mathEl) {
                    const addonTotal = Math.max(0, estimatedTotal - (pkgPrice * pairsCount));
                    const modeLabel = pairsCount > 1 ? 'Multi-pair estimate' : 'Single-pair estimate';
                    const pairWord = pairsCount === 1 ? 'pair' : 'pairs';
                    mathEl.textContent = `${pairsCount} ${pairWord} × R${pkgPrice} base + R${addonTotal} add-ons (${modeLabel})`;
                }

                const lines = [
                    'Hi JMG Sneaker Clinic! I would like a quote:',
                    customerName ? 'Name: ' + customerName : null,
                    'Package: ' + pkgName + ' (R' + pkgPrice + '/pair)',
                    'Pairs: ' + pairsCount,
                    selectedAddons.length ? 'Add-ons: ' + selectedAddons.join(', ') : 'Add-ons: None',
                    handover ? 'Handover: ' + handover : null,
                    suburb ? 'Cape Town Area/Suburb: ' + suburb : null,
                    timeSlot ? 'Preferred Time/Slot: ' + timeSlot : null,
                    fabricNote ? 'Shoe/Fabric Notes: ' + fabricNote : null,
                    'Payment: Cash only',
                    'Estimated Total: R' + estimatedTotal
                ].filter(Boolean);

                const messageText = lines.join('\n');
                const previewEl = document.getElementById('quote-message-preview');
                if (previewEl) {
                    previewEl.textContent = messageText;
                }

                const waUrl = `https://wa.me/${WHATSAPP_NUMBER}?text=${encodeURIComponent(messageText)}`;
                const waLinkEl = document.getElementById('whatsapp-quote-link');
                if (waLinkEl) {
                    waLinkEl.href = waUrl;
                }

                return { messageText, waUrl };
            } catch (err) {
                console.error('Error recalculating quote:', err);
                return { messageText: '', waUrl: `https://wa.me/${WHATSAPP_NUMBER}` };
            }
        }

        function resetQuoteEstimator() {
            try {
                const pkgSelect = document.getElementById('quote-package');
                const pairsInput = document.getElementById('quote-pairs');
                const handoverSelect = document.getElementById('quote-handover');
                const nameInput = document.getElementById('quote-name');
                const suburbInput = document.getElementById('quote-suburb');
                const timeSlotInput = document.getElementById('quote-time-slot');
                const fabricInput = document.getElementById('quote-fabric-note');

                if (pkgSelect) pkgSelect.value = 'Deep Clinic Treatment|180';
                if (pairsInput) pairsInput.value = '1';
                if (handoverSelect) handoverSelect.value = 'Same-Venue Drop-Off & Collection';
                if (nameInput) nameInput.value = '';
                if (suburbInput) suburbInput.value = '';
                if (timeSlotInput) timeSlotInput.value = '';
                if (fabricInput) fabricInput.value = '';

                document.querySelectorAll('.addon-checkbox').forEach((cb) => {
                    cb.checked = false;
                });

                recalculateQuote();
                showToast('Quote reset to defaults.');
            } catch (err) {
                console.error('Error resetting quote:', err);
            }
        }

        function applySampleQuotePreset() {
            try {
                const pkgSelect = document.getElementById('quote-package');
                const pairsInput = document.getElementById('quote-pairs');
                const handoverSelect = document.getElementById('quote-handover');
                const suburbInput = document.getElementById('quote-suburb');
                const timeSlotInput = document.getElementById('quote-time-slot');
                const fabricInput = document.getElementById('quote-fabric-note');

                if (pkgSelect) pkgSelect.value = 'Deep Clinic Treatment|180';
                if (pairsInput) pairsInput.value = '2';
                if (handoverSelect) handoverSelect.value = 'Same-Venue Drop-Off & Collection';
                if (suburbInput) suburbInput.value = 'Claremont';
                if (timeSlotInput) timeSlotInput.value = 'Saturday morning';
                if (fabricInput) fabricInput.value = '2x Converse All Star canvas & rubber midsole';

                recalculateQuote();
                showToast('Loaded sample quote for 2 pairs in Claremont.');
            } catch (err) {
                console.error('Error applying sample quote preset:', err);
            }
        }

        function copyQuoteMessage() {
            const { messageText } = recalculateQuote();
            copyTextSafely(messageText, 'WhatsApp quote message copied.');
        }

        function copyWhatsAppBookingLink() {
            const { waUrl } = recalculateQuote();
            copyTextSafely(waUrl, 'WhatsApp booking link copied.');
        }

        function sendWhatsAppQuote() {
            const { waUrl } = recalculateQuote();
            window.open(waUrl, '_blank', 'noopener,noreferrer');
        }

        window.addEventListener('DOMContentLoaded', () => {
            recalculateQuote();
        });
    </script>
</body>
</html>
