<script>
  import SectionWrapper from '$lib/components/SectionWrapper.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import FeatureCard from '$lib/components/FeatureCard.svelte';
  import PricingCard from '$lib/components/PricingCard.svelte';
</script>

<svelte:head>
  <title>Stonewall Mind Academy</title>
  <meta name="description" content="Elevate your mental game and dominate between the pipes with our elite 12-week goaltender program." />
  <link rel="icon" type="image/png" href="/black_icon_transparent_background.png" />
</svelte:head>

<main class="min-h-screen bg-black">

  <SectionWrapper theme="dark">
    <Hero />
  </SectionWrapper>

  <SectionWrapper theme="gray">
    <div class="text-center max-w-3xl mx-auto space-y-4 px-4">
      <h2 class="text-2xl md:text-3xl font-bold">If goaltending is 90% mental, why aren't you training your mind?</h2>
      <p class="text-base md:text-xl text-gray-700">If you are struggling with consistency, letting bad goals ruin your momentum, or feeling the overwhelming pressure of the crease, you are in the right place.</p>
      <p class="text-base md:text-xl text-gray-700">You don't need more ice time, more drills working on your RVH. You need a plan to train your mind and your game, so you can be the best, most consistent version of you on and off the ice.</p>
    </div>
  </SectionWrapper>

  <SectionWrapper theme="light">
    <div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center px-4">
      <div class="md:col-span-5 bg-gray-200 rounded-lg aspect-[3/4] flex items-center justify-center overflow-hidden">
         <img src="/coachteddy.png" alt="Coach Teddy" class="w-full h-full object-cover">
      </div>
      <div class="md:col-span-7 space-y-4 md:space-y-6">
        <h2 class="text-2xl md:text-4xl font-bold text-black">Meet Your Coach</h2>
        <div class="prose max-w-none text-gray-800 space-y-3 md:space-y-4 text-base md:text-lg">
           <p>I'm Coach Teddy. Former goalie, mental performance coach, Gold Level USA Hockey Coach, and Director of Goaltending for the Vegas Jr. Golden Knights.</p>
           <p> I've dedicated my career to helping goalies reach their full potential across the country and have had the privilege of working with goalies from age 6, up to NCAA Division 1.</p>
           <p>After years of analyzing elite goaltending mechanics and studying sport psychology, I've distilled a set of easy to use tools that actually works and is used by the top Olympic and NHL athletes</p>
           <p>At Stonewall Mind Academy, I believe that having a 1% edge on your mental game can make the all the difference between losing and winning in high-pressure situations.</p>
        </div>
      </div>
    </div>
  </SectionWrapper>

  <SectionWrapper theme="dark">
    <div class="text-center mb-12 md:mb-16 px-4">
      <h2 class="text-2xl md:text-4xl font-bold mb-4">The Pillars of Elite Goaltending</h2>
      <p class="text-gray-400 max-w-2xl mx-auto font-bold text-sm md:text-base">Master these core mental frameworks to transform your game.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 md:gap-8 px-4">
      <FeatureCard
        title="Crease Confidence"
        description="Develop an unshakable belief in your positioning and reaction time, eliminating second-guessing during high-pressure plays."
        icon='<img src="/Untitled design.svg" alt="Superhero" class="w-16 h-16" />'
      />
      <FeatureCard
        title="Resilience & Reset"
        description="Learn advanced cognitive techniques to instantly bounce back after allowing a goal. Maintain elite performance with a short memory."
        icon='<svg class="w-16 h-16" viewBox="0 0 24 24" fill="none"><path d="M12 2.5L4 6v6c0 6 3.5 10.5 8 12 4.5-1.5 8-6 8-12V6l-8-3.5z" fill="black" stroke="black" stroke-width="1"/><path d="M12 2.5L4 6v6c0 6 3.5 10.5 8 12V2.5z" fill="white"/></svg>'
      />
      <FeatureCard
        title="Pre-Game Priming"
        description="Establish rigorous routines that lock in your focus and prime your nervous system before the puck even drops."
        icon='<svg class="w-16 h-16 text-black" viewBox="0 0 24 24" fill="none" stroke="black" stroke-width="1.5"><path d="M13 10V3L4 14h7v7l9-11h-7z" stroke-linecap="round" stroke-linejoin="round"/></svg>'
      />
    </div>
  </SectionWrapper>

  <SectionWrapper theme="gray">
    <div class="text-center mb-12 px-4">
      <h2 class="text-2xl md:text-4xl font-bold mb-4 text-black">Ready To Be The Best, Most Consistent Version Of You On & Off The Ice?</h2>
      <p class="text-gray-600 max-w-2xl mx-auto font-bold text-sm md:text-base">Start your journey to elite mental training today.</p>
    </div>

    <div class="max-w-md mx-auto px-4">
      <div class="bg-white text-black border-2 border-black rounded-lg shadow-2xl p-6 md:p-8">
        <h3 class="text-2xl md:text-3xl font-bold mb-6 text-center">Stonewall Mind Academy</h3>

        <div class="space-y-4 mb-8">
          <div class="border border-gray-300 rounded-lg p-3 md:p-4 hover:border-black transition-colors">
            <div class="flex justify-between items-center">
              <div>
                <div class="font-bold text-base md:text-lg">Monthly</div>
                <div class="text-gray-600 text-xs md:text-sm">Billed monthly</div>
              </div>
              <div class="text-2xl md:text-3xl font-bold">$5<span class="text-base md:text-lg text-gray-600">/mo</span></div>
            </div>
          </div>

          <div class="border-2 border-black rounded-lg p-3 md:p-4 bg-gray-50">
            <div class="flex justify-between items-center">
              <div>
                <div class="font-bold text-base md:text-lg">Annual</div>
                <div class="text-gray-600 text-xs md:text-sm">Save 20%</div>
              </div>
              <div class="text-2xl md:text-3xl font-bold">$47.99<span class="text-base md:text-lg text-gray-600">/yr</span></div>
            </div>
          </div>
        </div>

        <div class="border-t border-gray-300 pt-6 mb-8">
          <h4 class="font-bold text-lg mb-4 text-center">What's Included:</h4>
          <ul class="space-y-3">
            <li class="flex items-start">
              <svg class="w-5 h-5 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="black" viewBox="0 0 24 24" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-sm">Access to the complete course all year long</span>
            </li>
            <li class="flex items-start">
              <svg class="w-5 h-5 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="black" viewBox="0 0 24 24" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-sm">Any updates to the course material</span>
            </li>
            <li class="flex items-start">
              <svg class="w-5 h-5 mr-3 mt-0.5 flex-shrink-0" fill="none" stroke="black" viewBox="0 0 24 24" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"></path>
              </svg>
              <span class="text-sm">Direct access to me for questions or coaching calls</span>
            </li>
          </ul>
        </div>

        <a href="https://app.stonewallmind.academy/courses/9805" class="w-full bg-black text-white font-bold py-4 px-8 rounded-lg shadow-lg hover:bg-gray-800 transition-all transform hover:scale-105 cursor-pointer inline-block text-center">
          GET STARTED
        </a>
      </div>
    </div>
  </SectionWrapper>

  <SectionWrapper theme="light">
    <div class="max-w-4xl mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-2xl md:text-4xl font-bold mb-4 text-black">Course Curriculum</h2>
        <p class="text-gray-600 font-bold text-sm md:text-base">14 Lessons To Help Add. More Tools To Your Toolbox</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-3 md:gap-4">
        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">1.</span>
            <span>Why Do I Need To Learn Mental Toughness?</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">2.</span>
            <span>Foundations For Being Mentally Strong</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">3.</span>
            <span>Build Your Elite Mindset</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">4.</span>
            <span>Understanding Motivation & Commitment</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">5.</span>
            <span>A Better Way in Setting Goals</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">6.</span>
            <span>Focus On The Process Over The Outcome</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">7.</span>
            <span>Spheres of Influence</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">8.</span>
            <span>Building Focus, Awareness & Confidence</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">9.</span>
            <span>Mental Imagery</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">10.</span>
            <span>Signal Light Protocol</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">11.</span>
            <span>Hockey Success Checklist</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">12.</span>
            <span>Flipping The Switch: Pre-Game Process</span>
          </h3>
        </div>

        <div class="bg-black border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-white flex items-start gap-2 md:gap-3">
            <span class="shrink-0">13.</span>
            <span>Do More In Less Time</span>
          </h3>
        </div>

        <div class="bg-white border-2 border-black rounded-lg p-4 md:p-6 hover:shadow-lg transition-shadow">
          <h3 class="text-sm md:text-base font-bold text-black flex items-start gap-2 md:gap-3">
            <span class="shrink-0">14.</span>
            <span>Embrace The Anxiety</span>
          </h3>
        </div>
      </div>
    </div>
  </SectionWrapper>

  <SectionWrapper theme="dark">
    <div class="max-w-4xl mx-auto text-center space-y-6 px-4">
      <h2 class="text-2xl md:text-4xl font-bold leading-tight">
        For Only 13 Cents a Day
      </h2>
      <p class="text-base md:text-lg font-bold leading-relaxed">
        Get access to the same proven mental performance strategies used by NHL and Olympic athletes to perform at their very best.
      </p>
      <p class="text-base md:text-lg font-bold">
        Easy to use. Takes only minutes a day. Results that last a lifetime.
      </p>
      <a href="https://app.stonewallmind.academy/courses/9805" class="mt-8 bg-white text-black font-bold py-3 md:py-4 px-8 md:px-12 text-sm md:text-base rounded-lg shadow-lg hover:bg-gray-200 transition-all transform hover:scale-105 cursor-pointer inline-block">
        GET STARTED
      </a>
    </div>
  </SectionWrapper>

  <SectionWrapper theme="gray">
    <div class="max-w-2xl mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-2xl md:text-4xl font-bold mb-4 text-black">Have Questions?</h2>
        <p class="text-gray-600 font-bold text-sm md:text-base">Fill out the form and let's schedule a call about your goals and how I can help.</p>
      </div>

      <form action="https://formspree.io/f/mojowdpv" method="POST" class="bg-white border-2 border-black rounded-lg p-6 md:p-8 shadow-lg space-y-6">
        <div>
          <label for="name" class="block text-sm font-bold text-black mb-2">Name *</label>
          <input
            type="text"
            id="name"
            name="name"
            required
            minlength="2"
            maxlength="100"
            class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:border-black focus:outline-none transition-colors"
            placeholder="Your name"
          />
        </div>

        <div>
          <label for="email" class="block text-sm font-bold text-black mb-2">Email *</label>
          <input
            type="email"
            id="email"
            name="email"
            required
            class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:border-black focus:outline-none transition-colors"
            placeholder="your@email.com"
          />
        </div>

        <div>
          <label for="phone" class="block text-sm font-bold text-black mb-2">Phone Number *</label>
          <input
            type="tel"
            id="phone"
            name="phone"
            required
            pattern="[0-9\s\-\(\)\+]+"
            minlength="10"
            maxlength="20"
            class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:border-black focus:outline-none transition-colors"
            placeholder="(555) 123-4567"
          />
        </div>

        <div>
          <label for="message" class="block text-sm font-bold text-black mb-2">Message *</label>
          <textarea
            id="message"
            name="message"
            required
            minlength="10"
            maxlength="1000"
            rows="5"
            class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg focus:border-black focus:outline-none transition-colors resize-none"
            placeholder="Tell me what questions you have..."
          ></textarea>
        </div>

        <button
          type="submit"
          class="w-full bg-black text-white font-bold py-4 px-8 rounded-lg shadow-lg hover:bg-gray-800 transition-all transform hover:scale-105 cursor-pointer"
        >
          SEND MESSAGE
        </button>
      </form>
    </div>
  </SectionWrapper>

  <footer class="bg-black text-center py-8 border-t border-gray-800 text-sm text-gray-500">
    <p>&copy; {new Date().getFullYear()} Stonewall Mind Academy. All rights reserved.</p>
  </footer>

</main>
