<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-brand-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0 z-0">
                <img src="/generated/image-professional-lawn-care-crew-working-on-a-1765478333701-0.webp" alt="Professional lawn care crew" class="w-full h-full object-cover opacity-20" />
                <div class="absolute inset-0 bg-gradient-to-b from-[var(--color-brand-dark)] via-[var(--color-brand-dark)]/80 to-[var(--color-brand-dark)]"></div>
            </div>
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-brand-primary)]"></span>
                        <span class="text-white text-sm font-medium">Trusted by PE-backed operators</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Unify fragmented lawn care operations.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        The centralized management platform built for lawn care consolidators. Scale from regional operators to 500+ locations with standardized systems, operational playbooks, and real-time visibility across your entire portfolio.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Schedule Demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Case Studies
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Route Schedule -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-900">Today's Routes</div>
                                <div class="h-8 w-24 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">12 Active</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gradient-to-br from-green-50 to-emerald-50 rounded-lg w-full flex items-center justify-center">
                                    <svg class="w-12 h-12 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7"></path></svg>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Dashboard -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-brand-primary)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-bold text-sm">Operations Dashboard</div>
                                    <div class="h-8 w-8 bg-black/10 rounded-full"></div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="grid grid-cols-2 gap-4 mb-4">
                                    <div class="space-y-1">
                                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                                        <div class="h-6 w-full bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-xs font-bold text-gray-900">247</div>
                                    </div>
                                    <div class="space-y-1">
                                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                                        <div class="h-6 w-full bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-xs font-bold text-gray-900">89%</div>
                                    </div>
                                </div>
                                <div class="space-y-2">
                                    <div class="h-2 w-full bg-gray-100 rounded"></div>
                                    <div class="h-2 w-full bg-gray-100 rounded"></div>
                                    <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Crew Management -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-900">Crew Status</div>
                                <div class="h-8 w-24 bg-blue-100 rounded text-blue-700 text-xs flex items-center justify-center font-bold">24 Crews</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gradient-to-br from-blue-50 to-cyan-50 rounded-lg w-full flex items-center justify-center">
                                    <svg class="w-12 h-12 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading lawn care consolidators</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50 grayscale">
                    <!-- Generic PE/Operator Logos -->
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 120 30" fill="currentColor">
                        <text x="10" y="20" font-family="Arial, sans-serif" font-size="18" font-weight="bold">GreenScape</text>
                    </svg>
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 120 30" fill="currentColor">
                        <text x="10" y="20" font-family="Arial, sans-serif" font-size="18" font-weight="bold">LawnPro</text>
                    </svg>
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 120 30" fill="currentColor">
                        <text x="10" y="20" font-family="Arial, sans-serif" font-size="18" font-weight="bold">TurfMaster</text>
                    </svg>
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 120 30" fill="currentColor">
                        <text x="10" y="20" font-family="Arial, sans-serif" font-size="18" font-weight="bold">Verdant</text>
                    </svg>
                    <svg class="h-6 md:h-8 w-auto text-white" viewBox="0 0 120 30" fill="currentColor">
                        <text x="10" y="20" font-family="Arial, sans-serif" font-size="18" font-weight="bold">EcoLawn</text>
                    </svg>
                </div>
            </div>
        </section>

        <!-- Core Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-brand-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">LawnCare Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Operational excellence.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">At enterprise scale.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Feature Card -->
                    <div class="bg-gradient-to-br from-green-600 to-emerald-800 rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Dashboard Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="absolute top-0 right-0 p-6 opacity-30">
                                    <svg class="w-16 h-16 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7"></path>
                                    </svg>
                                </div>
                                <div class="space-y-3 relative z-10">
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/80 text-xs uppercase tracking-wider font-medium">Active Routes</div>
                                        <div class="text-white font-bold text-2xl">247</div>
                                    </div>
                                    <div class="h-2 bg-white/20 rounded-full overflow-hidden">
                                        <div class="h-full bg-white rounded-full" style="width: 89%"></div>
                                    </div>
                                    <div class="text-white/60 text-xs">89% completion rate</div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center text-green-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm9.707 5.707a1 1 0 00-1.414-1.414L9 12.586l-1.293-1.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Route optimization
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-emerald-500/30 flex items-center justify-center text-emerald-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17 6a3 3 0 11-6 0 3 3 0 016 0zM12.93 17c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z"/></svg>
                                    </div>
                                    Crew management
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Scale with confidence.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            From regional operators to national portfolios. LawnCare provides the centralized infrastructure and operational playbooks to consolidate fragmented businesses and scale to 500+ locations seamlessly.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Complete Platform</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to consolidate and scale.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">From day one to 500+ locations.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our platform
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-brand-primary)]"></span>
                                Route Optimization
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Crew Management</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Customer Portal</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Analytics Hub</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Integration Engine</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Compliance Center</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Route Optimization" 
                            description="Maximize efficiency across locations. Intelligent routing algorithms optimize crew schedules, reduce drive time, and increase daily job capacity by up to 30%."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Crew Management" 
                            description="Centralize workforce operations. Track crew performance, manage certifications, schedule training, and monitor equipment across all locations from a single dashboard."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Customer Portal" 
                            description="Deliver consistent service quality. Branded customer portals provide real-time job tracking, automated billing, and self-service options that scale with your growth."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Analytics Hub" 
                            description="Make data-driven decisions. Real-time dashboards track KPIs across all locations, identify underperforming routes, and surface opportunities for operational improvement."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Integration Engine" 
                            description="Connect your tech stack. Seamlessly integrate with QuickBooks, payment processors, GPS tracking, and equipment management systems without custom development."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Compliance Center" 
                            description="Stay audit-ready at scale. Automated compliance tracking, safety protocols, and documentation management ensure consistency across all acquired locations."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- M&A Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-green-100 to-emerald-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-green-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Built for PE-backed consolidators acquiring regional lawn care operators through M&A.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        View acquisition playbook
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by leading lawn care consolidators. Learn from their success stories.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Case Study Card -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <img src="/generated/image-business-executive-reviewing-lawn-care-o-1765478338658-2.webp" alt="Business executive reviewing operations" class="absolute inset-0 w-full h-full object-cover" />
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/70 to-black/30"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">GreenScape</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-brand-primary)] flex items-center justify-center text-black font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z" fill="currentColor"/>
                                            <path d="M7 12l3 3 7-7" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
                                        </svg>
                                        LawnCare
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    <span class="text-green-400">GreenScape</span><br>
                                    How GreenScape scaled from 12 to 150 locations in 18 months
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <img src="/generated/image-lawn-care-crew-leader-coordinating-with--1765478341004-3.webp" alt="Crew coordination" class="absolute inset-0 w-full h-full object-cover opacity-40" />
                                <div class="absolute inset-0 bg-gradient-to-br from-emerald-900/60 to-black/80"></div>
                                <div class="relative z-10">
                                    <h4 class="text-white font-bold text-lg mb-2">TurfMaster</h4>
                                    <p class="text-gray-400 text-sm">85% reduction in admin time</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-emerald-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <img src="/generated/image-aerial-view-of-multiple-lawn-care-trucks-1765478343236-4.webp" alt="Fleet management" class="absolute inset-0 w-full h-full object-cover opacity-40" />
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/60 to-black/80"></div>
                                <div class="relative z-10">
                                    <h4 class="text-white font-bold text-lg mb-2">Verdant</h4>
                                    <p class="text-gray-400 text-sm">300+ locations unified</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-green-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-green-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-emerald-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Consolidate with confidence. <span class="text-[var(--color-brand-primary)]">Scale with speed.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Our proven operational playbook and centralized platform help PE-backed consolidators integrate acquisitions in weeks, not months.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            Integration Playbook
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">↓</kbd>
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        QuickBooks. GPS tracking. Payment processing.<br>
                        <span class="text-gray-400">Whatever tools you use,<br>LawnCare connects seamlessly.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        Explore all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['QuickBooks', 'Stripe', 'GPS Insight', 'ServiceTitan', 'Jobber', 'Aspire', 'LMN', 'Yardbook'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn about lawn care consolidation.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-green-200 to-emerald-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-green-700 transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">M&A Strategy</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-green-600 transition-colors">The $115B opportunity: Why PE is betting on lawn care consolidation</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <img src="/generated/image-happy-homeowner-shaking-hands-with-lawn--1765478345600-5.webp" alt="Customer satisfaction" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Operations</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-green-600 transition-colors">From fragmented to unified: The 90-day integration playbook</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

