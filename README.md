<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TONIR Financial Readiness Command Center - Documentation</title>
    <!-- Tailwind CSS for modern executive UI -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen font-sans antialiased p-6 sm:p-12">
    <main class="max-w-4xl mx-auto space-y-8 bg-slate-900 border border-slate-800 rounded-2xl p-8 shadow-2xl">
        
        <!-- Header -->
        <div class="border-b border-slate-800 pb-6 flex items-center justify-between flex-wrap gap-4">
            <div class="flex items-center space-x-3">
                <div class="bg-blue-600 text-white font-black px-3 py-1.5 rounded-lg text-lg tracking-wider">TONIR</div>
                <div>
                    <h1 class="text-2xl font-bold tracking-tight">Financial Readiness Command Center</h1>
                    <p class="text-xs text-slate-400">Total Obligations to Net Income Ratio (TONIR) Engine</p>
                </div>
            </div>
            <a href="tonir_command_center_v7.html" class="bg-blue-600 hover:bg-blue-500 text-white text-xs font-medium px-4 py-2 rounded-lg transition shadow-lg shadow-blue-900/50">Launch Command Center</a>
        </div>

        <!-- Copyright & License Section -->
        <div class="bg-slate-950 border border-slate-800 rounded-xl p-6 space-y-3">
            <h2 class="text-sm font-bold uppercase tracking-wider text-amber-400">Copyright & License</h2>
            <p class="text-xs text-slate-300"><strong>Proprietary Software & Non-Commercial License</strong> — Copyright &copy; 2026 Stefan T Falls. All Rights Reserved.</p>
            <div class="bg-slate-900 border border-slate-800 rounded-lg p-4 text-xs text-slate-400 space-y-2">
                <p><strong class="text-white">Notice:</strong> This software and its underlying architecture, formulas, and operational design represent extensive proprietary development and refinement.</p>
                <p><strong class="text-amber-400">Strict Non-Commercial Use License:</strong> You are granted a limited, personal, non-exclusive right to use this tool for individual financial tracking and readiness evaluations. Redistribution, reverse engineering, modification, or commercial exploitation—including incorporation into paid services, corporate consulting tools, SaaS products, or monetization in any form—is <strong class="text-white underline">strictly prohibited</strong> without explicit written authorization from the author.</p>
            </div>
        </div>

        <!-- Overview & Philosophy -->
        <div class="space-y-4">
            <h2 class="text-lg font-semibold text-slate-200">Overview & Philosophy</h2>
            <p class="text-sm text-slate-300 leading-relaxed">
                TONIR runs entirely on the honor system with zero required external bank feeds or automated cloud syncs, ensuring absolute personal privacy. By focusing heavily on your fixed obligations relative to your recurring net income, TONIR cuts through the noise of daily spending to reveal your true financial stability zone.
            </p>

            <h3 class="text-xs font-bold uppercase tracking-wider text-slate-400 pt-2">The TONIR Stability Scale</h3>
            <div class="grid grid-cols-1 sm:grid-cols-5 gap-2 text-xs">
                <div class="p-3 rounded border border-emerald-600 bg-emerald-950/40"><span class="font-bold text-emerald-400 block">0-39%</span> Zone 1: Elite</div>
                <div class="p-3 rounded border border-yellow-600 bg-yellow-950/40"><span class="font-bold text-yellow-400 block">40-59%</span> Zone 2: Healthy</div>
                <div class="p-3 rounded border border-orange-600 bg-orange-950/40"><span class="font-bold text-orange-400 block">60-79%</span> Zone 3: Paycheck</div>
                <div class="p-3 rounded border border-red-600 bg-red-950/40"><span class="font-bold text-red-400 block">80-99%</span> Zone 4: Fragile</div>
                <div class="p-3 rounded border border-purple-600 bg-purple-950/40"><span class="font-bold text-purple-400 block">100%+</span> Zone 5: Survival</div>
            </div>
        </div>

        <!-- Core Architecture & 12 Independent Sections -->
        <div class="space-y-4">
            <h2 class="text-lg font-semibold text-slate-200">Core Architecture & 12 Independent Sections</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs text-slate-300">
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">TONIR Dashboard</strong> Aggregates net cash flow, traditional DTI, net financial position, and visualizes obligation category breakdowns.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">1. Income</strong> Tracks recurring vs. one-time inflows (net and gross).</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">2. Assets & Liabilities</strong> Monitors investable assets and formal debts for a true net worth baseline.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">3. Credit Cards</strong> Captures revolving balances where monthly payments apply.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">4. Food & Shopping</strong> Granular variable expense logging.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">5. Fuel</strong> Vehicle-specific trip and fuel cost monitoring.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">6. Investments</strong> Tracks committed outflows like Roth IRAs and 401(k) contributions.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">7. Insurance</strong> Itemizes monthly premiums across auto, health, renters, and life policies.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">8. Legal</strong> Non-negotiable obligations (e.g., child support, childcare).</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">9. Loans</strong> Formal debt service and Buy Now Pay Later (BNPL) liabilities.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">10. Mortgage or Rent</strong> Housing cost segregation with configurable DTI toggles.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg"><strong class="text-white block mb-1">11. Subscriptions</strong> Recurring digital and software memberships.</div>
                <div class="bg-slate-950 border border-slate-800 p-3.5 rounded-lg sm:col-span-2"><strong class="text-white block mb-1">12. Utilities</strong> Essential home services tracked down to the cent.</div>
            </div>
        </div>

        <!-- Getting Started -->
        <div class="space-y-3 pt-2">
            <h2 class="text-lg font-semibold text-slate-200">Getting Started</h2>
            <ol class="list-decimal list-inside text-xs sm:text-sm text-slate-300 space-y-1.5">
                <li>Download or clone the repository containing your files.</li>
                <li>Open <code class="text-blue-400 bg-slate-950 px-1.5 py-0.5 rounded">tonir_command_center_v7.html</code> in any modern web browser.</li>
                <li>Accept the Non-Commercial License agreement modal.</li>
                <li>Click <strong>Load Example Template</strong> to review sample data or begin entering your own personal metrics.</li>
            </ol>
        </div>

    </main>
</body>
</html>
