<script>
  import { onMount } from 'svelte';
</script>

<div class="w-full bg-gradient-to-br from-primary-950 via-primary-900 to-primary-800">
  <!-- Hero Section -->
  <section class="pt-32 pb-20 px-6 md:pt-40 md:pb-32 bg-gradient-to-br from-primary-950 via-primary-900 to-primary-800">
    <div class="max-w-[1200px] mx-auto">
      <div class="text-center max-w-4xl mx-auto mb-16">
        <h1 class="text-5xl md:text-[64px] leading-[1.1] font-medium tracking-tight text-white mb-6">
          Building AI-native<br />product leadership
        </h1>
        <p class="text-xl md:text-[22px] leading-relaxed text-primary-200 max-w-2xl mx-auto">
          The systems, the teams, and the organizational designs<br class="hidden md:block" />that make AI products work at scale.
        </p>
      </div>

      <!-- Hero Image -->
      <div class="rounded-[40px] overflow-hidden border-2 border-primary-700">
        <img src="/generated/image-professional-product-leader-in-a-modern--1766959874356-0.webp" alt="Mirza Besirovic - AI Product Leader" class="w-full h-auto" />
      </div>

      <!-- Quick Stats -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mt-16 max-w-4xl mx-auto">
        <div class="text-center">
          <div class="text-3xl md:text-4xl font-bold text-white mb-2">$100M+</div>
          <div class="text-sm text-primary-300">ARR in AI products</div>
        </div>
        <div class="text-center">
          <div class="text-3xl md:text-4xl font-bold text-white mb-2">10,000+</div>
          <div class="text-sm text-primary-300">AI-enabled customers</div>
        </div>
        <div class="text-center">
          <div class="text-3xl md:text-4xl font-bold text-white mb-2">9</div>
          <div class="text-sm text-primary-300">Product teams led</div>
        </div>
        <div class="text-center">
          <div class="text-3xl md:text-4xl font-bold text-white mb-2">90%</div>
          <div class="text-sm text-primary-300">Automation rate achieved</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Companies Section -->
  <section class="py-20 bg-gradient-to-br from-primary-900 via-primary-800 to-primary-900 border-b border-primary-700">
    <div class="max-w-[1200px] mx-auto px-6">
      <p class="text-center text-sm font-medium text-primary-300 mb-12 uppercase tracking-wide">
        Trusted by product teams at
      </p>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-y-12 gap-x-12 items-center justify-items-center opacity-80 hover:opacity-100 transition-all duration-500">
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-red-300">Netflix</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-orange-300">Reddit</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-blue-300">Vimeo</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-gray-200">Levi's</span></div>
        
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-primary-300">Zendesk</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-gray-200">Dixa</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-green-300">wefox</span></div>
        <div class="h-8 flex items-center"><span class="font-bold text-2xl text-gray-200">Ultimate</span></div>
      </div>
    </div>
  </section>

  <!-- Feature Section 1: AI Systems -->
  <section class="py-24 px-6 bg-gradient-to-br from-primary-800 via-primary-700 to-primary-800" id="work">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-center">
        <!-- Visual -->
        <div class="w-full md:w-1/2 rounded-[32px] overflow-hidden border-2 border-primary-600">
          <img src="/generated/image-diverse-product-team-collaborating-aroun-1766959877472-1.webp" alt="Product team collaboration" class="w-full h-full object-cover" />
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-white max-w-md">
              AI systems that learn and adapt
            </h2>
            <span class="bg-primary-950 text-primary-200 px-3 py-1.5 rounded-full text-xs font-medium border border-primary-600">Products</span>
          </div>
          
          <p class="text-primary-100 text-lg mb-12 leading-relaxed">
            I design and scale agentic platforms that automate up to 90% of customer interactions—turning AI from demos into durable revenue.
          </p>

          <div class="space-y-10">
            <!-- Feature 1 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-300"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4"/><path d="M12 8h.01"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-white mb-2">Multi-agent orchestration</h3>
                <p class="text-primary-200 text-sm leading-relaxed">
                  Build platforms that coordinate multiple AI agents, zero-training engines, and RAG-based knowledge grounding for autonomous customer service.
                </p>
              </div>
            </div>

            <!-- Feature 2 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-300"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" x2="12" y1="15" y2="3"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-white mb-2">From weeks to hours</h3>
                <p class="text-primary-200 text-sm leading-relaxed">
                  Reduce bot deployment times from weeks to hours, powering autonomous customer service for Netflix, Reddit, Vimeo, Levi's, and thousands of enterprises.
                </p>
              </div>
            </div>

            <!-- Feature 3 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-300"><path d="M22 12h-4l-3 9L9 3l-3 9H2"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-white mb-2">Commercial growth driver</h3>
                <p class="text-primary-200 text-sm leading-relaxed">
                  Turn automated resolutions from a metric into a commercial growth driver worth $100M+ ARR, with voice automation and human-in-the-loop workflows.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Impact Section -->
  <section class="py-12 px-6 bg-gradient-to-br from-primary-900 via-primary-800 to-primary-900">
    <div class="max-w-[1200px] mx-auto">
      <div class="bg-gradient-to-br from-primary-950 via-primary-900 to-primary-950 rounded-[32px] p-12 md:p-16 relative border-2 border-primary-700">
        <div class="mb-8 font-bold text-lg text-primary-300">Current Role</div>
        <blockquote class="text-2xl md:text-3xl font-medium leading-tight text-white mb-12 max-w-4xl">
          "Group Product Manager for AI Agents at Zendesk, running product for a platform serving 10,000+ AI-enabled customers and generating $100M+ ARR."
        </blockquote>
        <div class="flex items-center justify-between flex-wrap gap-6">
          <div class="flex items-center gap-4">
            <img src="/generated/image-professional-headshot-of-a-confident-pro-1766959885013-4.webp" alt="Mirza Besirovic" class="w-16 h-16 rounded-full object-cover border-2 border-primary-600" />
            <div>
              <div class="font-medium text-white">Mirza Besirovic</div>
              <div class="text-sm text-primary-300">Group PM for AI Agents, Zendesk</div>
            </div>
          </div>
          <div class="text-right">
            <div class="text-sm text-primary-300 mb-1">Managing</div>
            <div class="font-bold text-2xl text-white">9 Product Teams</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Feature Section 2: Teams & Operating Models -->
  <section class="py-24 px-6 bg-gradient-to-bl from-gray-800 via-gray-900 to-primary-950" id="expertise">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row-reverse gap-16 items-center">
        <!-- Visual -->
        <div class="w-full md:w-1/2 rounded-[32px] overflow-hidden shadow-xl">
          <img src="/generated/image-professional-speaker-presenting-at-a-tec-1766959879967-2.webp" alt="Speaking at conference" class="w-full h-full object-cover" />
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 max-w-md">
              Teams & operating models
            </h2>
            <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Leadership</span>
          </div>
          
          <p class="text-gray-600 text-lg mb-12 leading-relaxed">
            I build the teams, operating models, and strategic roadmaps that allow companies to actually ship AI at scale.
          </p>

          <div class="space-y-10">
            <!-- Feature 1 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-600"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Post-acquisition integration</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Design product org structures for merging 5+ teams across acquisitions (Dixa + Solvemate, Ultimate into Zendesk), navigating complex post-M&A alignment.
                </p>
              </div>
            </div>

            <!-- Feature 2 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-600"><path d="M3 3v18h18"/><path d="m19 9-5 5-4-4-3 3"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Capacity planning & continuous discovery</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Build frameworks that align product ambition with engineering reality, cutting roadmaps from 241% capacity to something teams can actually ship.
                </p>
              </div>
            </div>

            <!-- Feature 3 -->
            <div class="flex gap-4">
              <div class="mt-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-primary-600"><path d="M12 20h9"/><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"/></svg>
              </div>
              <div>
                <h3 class="font-medium text-gray-900 mb-2">Coaching & empowerment</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Coach Group PMs and senior PMs to operate with autonomy, creating environments where product people do their best work through clear direction and ownership.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Feature Section 3: Strategic Frameworks -->
  <section class="py-24 px-6 bg-gradient-to-tr from-primary-100 via-white to-primary-50">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex flex-col md:flex-row gap-16 items-center">
        <!-- Visual -->
        <div class="w-full md:w-1/2 rounded-[32px] overflow-hidden shadow-xl">
          <img src="/generated/image-one-on-one-mentoring-session-between-two-1766959882503-3.webp" alt="Mentoring session" class="w-full h-full object-cover" />
        </div>

        <!-- Content -->
        <div class="w-full md:w-1/2">
          <div class="flex justify-between items-start mb-6">
            <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-gray-900 max-w-md">
              Strategic frameworks
            </h2>
            <span class="bg-primary-600 text-white px-3 py-1.5 rounded-full text-xs font-medium">Strategy</span>
          </div>
          
          <p class="text-gray-600 text-lg mb-12 leading-relaxed">
            I operate as a translator and integrator—connecting AI capabilities, market realities, and organizational constraints into coherent roadmaps.
          </p>

          <div class="space-y-4">
            <!-- Feature 1 (Active) -->
            <div class="bg-gray-50 p-6 rounded-xl border border-gray-100">
              <h3 class="font-medium text-gray-900 mb-2 text-sm">Pricing & packaging for AI</h3>
              <p class="text-gray-600 text-xs leading-relaxed">
                Co-define pricing and packaging strategy for AI automation, establishing automated resolutions as both a product metric and a revenue driver.
              </p>
            </div>

            <!-- Feature 2 -->
            <div class="p-6 rounded-xl border border-gray-200 hover:bg-gray-50 transition-colors">
              <h3 class="font-medium text-gray-900 mb-2 text-sm">Post-M&A roadmap alignment</h3>
              <p class="text-gray-600 text-xs leading-relaxed">
                Navigate the complex alignment of visions and roadmaps after acquisitions, turning competing priorities into unified product strategy.
              </p>
            </div>

            <!-- Feature 3 -->
            <div class="p-6 rounded-xl border border-gray-200 hover:bg-gray-50 transition-colors">
              <h3 class="font-medium text-gray-900 mb-2 text-sm">AI evaluation frameworks</h3>
              <p class="text-gray-600 text-xs leading-relaxed">
                Build instrumentation and evaluation frameworks that allow companies to systematically improve AI performance rather than just ship features.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Speaking & Community Section -->
  <section class="py-24 px-6 bg-gray-900 text-white" id="speaking">
    <div class="max-w-[1200px] mx-auto">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl leading-tight font-medium text-white mb-6">
          Speaking, mentoring & community
        </h2>
        
        <p class="text-gray-400 text-lg leading-relaxed max-w-3xl mx-auto">
          Beyond full-time product leadership, I speak at conferences, mentor product leaders, and build communities that support the next generation of AI product builders.
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Speaking -->
        <div class="bg-gray-800 rounded-2xl p-8 border border-gray-700">
          <div class="w-12 h-12 bg-primary-600 rounded-full flex items-center justify-center mb-6">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2a3 3 0 0 0-3 3v7a3 3 0 0 0 6 0V5a3 3 0 0 0-3-3Z"/><path d="M19 10v2a7 7 0 0 1-14 0v-2"/><line x1="12" x2="12" y1="19" y2="22"/></svg>
          </div>
          <h3 class="text-xl font-semibold text-white mb-3">Conference Speaking</h3>
          <p class="text-primary-200 text-sm mb-4">
            ProductLab Conf Berlin, ProductCamp Europe, Alps GenAI Summit, ADPList BeMore Festival, Kiss the Future AI Summit
          </p>
        </div>

        <!-- Mentoring -->
        <div class="bg-gradient-to-br from-primary-900 to-primary-950 rounded-2xl p-8 border border-primary-800">
          <div class="w-12 h-12 bg-primary-500 rounded-full flex items-center justify-center mb-6">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><line x1="19" x2="19" y1="8" y2="14"/><line x1="22" x2="16" y1="11" y2="11"/></svg>
          </div>
          <h3 class="text-xl font-semibold text-white mb-3">Mentoring</h3>
          <p class="text-gray-400 text-sm mb-4">
            Mentoring product leaders through ADPList and 2hearts, a community supporting young immigrants in tech
          </p>
        </div>

        <!-- Community -->
        <div class="bg-gray-800 rounded-2xl p-8 border border-gray-700">
          <div class="w-12 h-12 bg-primary-600 rounded-full flex items-center justify-center mb-6">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
          </div>
          <h3 class="text-xl font-semibold text-white mb-3">Community Building</h3>
          <p class="text-primary-200 text-sm mb-4">
            Founder of productqties.com, a space for LGBTQ+ professionals in product, and writer of "You Are The Product" on Substack
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Highlights Section -->
  <section class="py-24 px-6 bg-gradient-to-br from-gray-900 via-primary-950 to-gray-900" id="writing">
    <div class="max-w-[1200px] mx-auto">
      <div class="flex justify-between items-end mb-16">
        <div class="max-w-xl">
          <h2 class="text-4xl md:text-[40px] leading-tight font-medium text-white mb-6">
            Experience that drives impact
          </h2>
          <p class="text-primary-200 text-lg leading-relaxed">
            From post-acquisition integration to building AI platforms at scale, I navigate the messy work between demos and $100M ARR.
          </p>
        </div>
        <span class="bg-primary-500 text-white px-3 py-1.5 rounded-full text-xs font-medium mb-2">Key Projects</span>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Card 1: Zendesk -->
        <div class="bg-gradient-to-br from-primary-800 to-primary-900 rounded-2xl p-8 border border-primary-700 hover:border-primary-500 transition-colors">
          <div class="text-primary-300 font-bold text-lg mb-4">Zendesk</div>
          <h3 class="text-xl font-semibold text-white mb-4 leading-snug">
            AI Agents Platform
          </h3>
          <p class="text-primary-200 text-sm mb-6 leading-relaxed">
            Leading 9 product teams across AI platform, automation engine, conversation design, and analytics—serving 10,000+ customers generating $100M+ ARR.
          </p>
          <div class="flex gap-2 flex-wrap">
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">Multi-agent systems</span>
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">Voice automation</span>
          </div>
        </div>

        <!-- Card 2: Post-M&A Integration -->
        <div class="bg-gradient-to-br from-primary-800 to-primary-900 rounded-2xl p-8 border border-primary-700 hover:border-primary-500 transition-colors">
          <div class="text-primary-300 font-bold text-lg mb-4">Dixa + Ultimate</div>
          <h3 class="text-xl font-semibold text-white mb-4 leading-snug">
            Post-Acquisition Integration
          </h3>
          <p class="text-primary-200 text-sm mb-6 leading-relaxed">
            Merged 5+ teams across multiple acquisitions, navigating complex organizational alignment and building unified product roadmaps that teams can execute.
          </p>
          <div class="flex gap-2 flex-wrap">
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">Org design</span>
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">M&A alignment</span>
          </div>
        </div>

        <!-- Card 3: Automation at Scale -->
        <div class="bg-gradient-to-br from-primary-800 to-primary-900 rounded-2xl p-8 border border-primary-700 hover:border-primary-500 transition-colors">
          <div class="text-primary-300 font-bold text-lg mb-4">Enterprise CX</div>
          <h3 class="text-xl font-semibold text-white mb-4 leading-snug">
            90% Automation Rate
          </h3>
          <p class="text-primary-200 text-sm mb-6 leading-relaxed">
            Designed agentic platforms that automate up to 90% of customer interactions for Netflix, Reddit, Vimeo, and Levi's—reducing deployment from weeks to hours.
          </p>
          <div class="flex gap-2 flex-wrap">
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">RAG systems</span>
            <span class="text-xs bg-primary-950 px-3 py-1 rounded-full text-primary-200 border border-primary-700">Zero-training AI</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="py-32 px-6 text-center bg-gradient-to-br from-primary-700 via-primary-600 to-primary-800" id="contact">
    <div class="max-w-[1200px] mx-auto">
      <h2 class="text-4xl md:text-5xl font-medium text-white mb-6 tracking-tight">
        Let's work together
      </h2>
      <p class="text-primary-100 text-lg max-w-2xl mx-auto mb-10">
        Whether you need a speaker for your conference, an advisor for your AI strategy, or a mentor for your product team—I'd love to connect.
      </p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
        <a href="https://www.linkedin.com/in/mirzabesirovic/" target="_blank" class="inline-block bg-white hover:bg-primary-50 text-primary-700 px-8 py-3 rounded-full font-medium transition-colors">
          Connect on LinkedIn
        </a>
        <a href="https://substack.com/@youaretheproduct" target="_blank" class="inline-block bg-primary-800 hover:bg-primary-900 text-white px-8 py-3 rounded-full font-medium border border-primary-600 transition-colors">
          Read my Substack
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-50 pt-20 pb-10 px-6 border-t border-gray-100">
    <div class="max-w-[1200px] mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-20">
        <div class="col-span-1 md:col-span-2">
          <a href="/" class="flex items-center gap-3 text-primary-600 mb-6">
            <svg class="w-7 h-7" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M12.2566 21.954C17.929 21.954 22.5274 17.484 22.5274 11.9699C22.5274 6.45586 17.929 1.98584 12.2566 1.98584C6.58422 1.98584 1.98584 6.45586 1.98584 11.9699C1.98584 17.484 6.58422 21.954 12.2566 21.954ZM15.4608 6.63684C15.6167 6.09831 15.0791 5.77985 14.5881 6.1199L7.73395 10.8665C7.20146 11.2352 7.28522 11.9699 7.85977 11.9699H9.66465V11.9563H13.1823L10.3161 12.9394L9.05251 17.303C8.89655 17.8415 9.43412 18.16 9.92517 17.8199L16.7793 13.0734C17.3118 12.7046 17.228 11.9699 16.6535 11.9699H13.9165L15.4608 6.63684Z"
                fill="currentColor"
              />
            </svg>
            <span class="text-xl tracking-tight font-semibold text-gray-900">Mirza Besirovic</span>
          </a>
          <p class="text-sm text-gray-600 max-w-md mb-6">
            AI Product Leader building the systems, teams, and organizational designs that make AI products work at scale.
          </p>
          <p class="text-xs text-gray-500">
            Group PM for AI Agents at Zendesk
          </p>
        </div>
        
        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Connect</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="https://www.linkedin.com/in/mirzabesirovic/" target="_blank" class="hover:text-gray-900">LinkedIn</a></li>
            <li><a href="https://substack.com/@youaretheproduct" target="_blank" class="hover:text-gray-900">Substack</a></li>
            <li><a href="https://www.adplist.org" target="_blank" class="hover:text-gray-900">ADPList</a></li>
            <li><a href="https://productqties.com" target="_blank" class="hover:text-gray-900">Product Qties</a></li>
          </ul>
        </div>

        <div>
          <h4 class="font-medium text-gray-900 mb-4 text-sm">Services</h4>
          <ul class="space-y-3 text-sm text-gray-600">
            <li><a href="#speaking" class="hover:text-gray-900">Speaking</a></li>
            <li><a href="#expertise" class="hover:text-gray-900">Advisory</a></li>
            <li><a href="#speaking" class="hover:text-gray-900">Mentoring</a></li>
            <li><a href="#writing" class="hover:text-gray-900">Writing</a></li>
          </ul>
        </div>
      </div>

      <div class="flex flex-col md:flex-row justify-between items-center pt-8 border-t border-gray-200">
        <div class="text-xs text-gray-500 mb-4 md:mb-0">
          © 2025 Mirza Besirovic. All rights reserved.
        </div>

        <div class="flex items-center gap-4 text-gray-400">
          <a href="https://www.linkedin.com/in/mirzabesirovic/" target="_blank" class="hover:text-primary-600 transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
          </a>
          <a href="https://substack.com/@youaretheproduct" target="_blank" class="hover:text-primary-600 transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M22.539 8.242H1.46V5.406h21.08v2.836zM1.46 10.812V24L12 18.11 22.54 24V10.812H1.46zM22.54 0H1.46v2.836h21.08V0z"/></svg>
          </a>
        </div>
      </div>
    </div>
  </footer>
</div>



