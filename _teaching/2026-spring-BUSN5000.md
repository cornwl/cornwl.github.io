---
title: "BUSN 5000 :: Data Science for Business and Economics"
collection: teaching
type: "Undergraduate Course"
permalink: /teaching/2026-spring-BUSN5000/
venue: "University of Georgia"
date: 2026-01-19
layout: splash
excerpt: "An introduction to the tools and habits of mind that turn data into business and economic insight."
---

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>
/* ===== BUSN 5000 landing page — scoped styles ===== */
.busn5000 { font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; color: #1a1a1a; line-height: 1.65; max-width: none; margin: 0; padding: 0; }
.busn5000 *, .busn5000 *::before, .busn5000 *::after { box-sizing: border-box; }
.busn5000 h1, .busn5000 h2, .busn5000 h3, .busn5000 h4 { font-family: 'Playfair Display', Georgia, serif; font-weight: 700; color: #0f0f0f; letter-spacing: -0.01em; margin: 0; padding: 0; border-bottom: none !important; }
.busn5000 a { color: #BA0C2F; text-decoration: none; border-bottom: 1px solid rgba(186, 12, 47, 0.25); transition: border-color 0.15s ease; }
.busn5000 a:hover { border-bottom-color: #BA0C2F; }
.busn5000 p { margin: 0 0 1em; }

/* --- Hero --- */
.busn5000 .b-hero { background: linear-gradient(135deg, #0a0a0a 0%, #1f1f1f 100%); color: #fafafa; padding: 5rem 1.5rem 7rem; position: relative; overflow: hidden; }
.busn5000 .b-hero::after { content: ''; position: absolute; left: 0; right: 0; bottom: 0; height: 6px; background: #BA0C2F; }
.busn5000 .b-hero__inner { max-width: 880px; margin: 0 auto; }
.busn5000 .b-hero__eyebrow { font-family: 'Inter', sans-serif; font-size: 0.85rem; font-weight: 600; letter-spacing: 0.18em; text-transform: uppercase; color: #BA0C2F; margin: 0 0 1rem; }
.busn5000 .b-hero__title { font-size: clamp(2.1rem, 5vw, 3.6rem); line-height: 1.1; color: #fafafa; margin: 0 0 1.25rem; max-width: 18ch; }
.busn5000 .b-hero__meta { font-size: 1.05rem; color: #c8c8c8; margin: 0; font-weight: 400; }
.busn5000 .b-hero__meta strong { color: #fafafa; font-weight: 600; }

/* --- Facts card (overlaps hero bottom) --- */
.busn5000 .b-facts { max-width: 1040px; margin: -4.5rem auto 4rem; padding: 0 1.5rem; position: relative; z-index: 2; }
.busn5000 .b-facts__grid { background: #fff; border: 1px solid #e5e1da; border-radius: 6px; box-shadow: 0 18px 40px -20px rgba(0,0,0,0.18); display: grid; grid-template-columns: repeat(3, 1fr); gap: 0; overflow: hidden; }
.busn5000 .b-facts__cell { padding: 1.75rem 1.75rem; border-right: 1px solid #ece9e2; }
.busn5000 .b-facts__cell:last-child { border-right: none; }
.busn5000 .b-facts__cell h3 { font-family: 'Inter', sans-serif; font-size: 0.78rem; font-weight: 700; letter-spacing: 0.14em; text-transform: uppercase; color: #BA0C2F; margin: 0 0 0.75rem; }
.busn5000 .b-facts__cell p { font-size: 0.97rem; line-height: 1.6; margin: 0; color: #2a2a2a; }
.busn5000 .b-facts__cell a { font-weight: 500; }

/* --- Body sections --- */
.busn5000 .b-section { max-width: 760px; margin: 0 auto; padding: 0 1.5rem 4.5rem; }
.busn5000 .b-section h2 { font-size: 2rem; margin: 0 0 1.25rem; line-height: 1.2; }
.busn5000 .b-section h2::after { content: ''; display: block; width: 48px; height: 3px; background: #BA0C2F; margin-top: 0.75rem; }
.busn5000 .b-section p { font-size: 1.08rem; color: #2a2a2a; }

/* Placeholder marker styling — visually distinct so Chris can't miss them */
.busn5000 .b-placeholder { background: #fdf6e8; border-left: 3px solid #d4a017; padding: 0.85rem 1rem; font-size: 0.95rem; color: #6b5a1d; border-radius: 0 4px 4px 0; }
.busn5000 .b-placeholder::before { content: '\270E  '; font-weight: 600; }

/* Learning outcomes — custom numbered list */
.busn5000 .b-outcomes { list-style: none; counter-reset: outcome; padding: 0; margin: 1.5rem 0 0; }
.busn5000 .b-outcomes li { counter-increment: outcome; position: relative; padding: 0 0 1.25rem 3.2rem; font-size: 1.05rem; color: #2a2a2a; }
.busn5000 .b-outcomes li::before { content: counter(outcome, decimal-leading-zero); position: absolute; left: 0; top: -0.15rem; font-family: 'Playfair Display', serif; font-size: 1.8rem; font-weight: 700; color: #BA0C2F; line-height: 1; }

/* Semester arc cards */
.busn5000 .b-arcs { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; margin-top: 1.75rem; }
.busn5000 .b-arc { background: #faf7f2; border: 1px solid #ece9e2; border-radius: 4px; padding: 1.4rem 1.25rem; }
.busn5000 .b-arc__weeks { font-family: 'Inter', sans-serif; font-size: 0.72rem; font-weight: 700; letter-spacing: 0.14em; text-transform: uppercase; color: #BA0C2F; }
.busn5000 .b-arc h4 { font-size: 1.15rem; margin: 0.4rem 0 0.5rem; }
.busn5000 .b-arc p { font-size: 0.92rem; color: #4a4a4a; margin: 0; }

/* Grading stacked bar */
.busn5000 .b-grading__bar { display: flex; height: 56px; border-radius: 4px; overflow: hidden; margin: 1.5rem 0 1.25rem; font-family: 'Inter', sans-serif; font-size: 0.78rem; font-weight: 600; color: #fff; }
.busn5000 .b-grading__seg { display: flex; align-items: center; justify-content: center; text-align: center; padding: 0 0.5rem; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }

/* Two-column needs panel */
.busn5000 .b-needs { display: grid; grid-template-columns: 1fr 1fr; gap: 2.5rem; margin-top: 1.5rem; }
.busn5000 .b-needs h4 { font-size: 1.1rem; margin-bottom: 0.6rem; }
.busn5000 .b-needs ul { margin: 0; padding-left: 1.1rem; color: #2a2a2a; font-size: 1rem; }
.busn5000 .b-needs li { margin-bottom: 0.5rem; }

/* CTA footer band */
.busn5000 .b-cta { background: #faf7f2; border-top: 1px solid #ece9e2; padding: 4rem 1.5rem 5rem; text-align: center; margin-top: 2rem; }
.busn5000 .b-cta h2 { font-size: 1.9rem; margin-bottom: 0.75rem; }
.busn5000 .b-cta h2::after { content: ''; display: block; width: 48px; height: 3px; background: #BA0C2F; margin: 0.75rem auto 0; }
.busn5000 .b-cta p { font-size: 1.05rem; color: #3a3a3a; max-width: 580px; margin: 0 auto 1.75rem; }
.busn5000 .b-cta__buttons { display: flex; gap: 0.85rem; justify-content: center; flex-wrap: wrap; }
.busn5000 .b-btn { display: inline-block; padding: 0.85rem 1.65rem; background: #BA0C2F; color: #fff; font-family: 'Inter', sans-serif; font-weight: 600; font-size: 0.97rem; border: 2px solid #BA0C2F; border-radius: 4px; border-bottom: 2px solid #BA0C2F; transition: background 0.15s ease, color 0.15s ease; }
.busn5000 .b-btn:hover { background: #8d0923; border-color: #8d0923; color: #fff; }
.busn5000 .b-btn--ghost { background: transparent; color: #BA0C2F; }
.busn5000 .b-btn--ghost:hover { background: #BA0C2F; color: #fff; }

/* --- Defeat the theme's container padding/margins so hero spans edge-to-edge.
       Uses :has() for clean scoping (Chrome 105+, Safari 15.4+, Firefox 121+). --- */
#main:has(.busn5000), .page__content:has(.busn5000), .splash:has(.busn5000) {
  max-width: none !important; padding: 0 !important; margin: 0 !important;
}
.page__content:has(.busn5000) h2 { padding: 0 !important; border-bottom: none !important; }
/* Fallback for older browsers: pull content out of container with negative margins */
@supports not (selector(:has(*))) {
  .busn5000 { margin-left: -1em; margin-right: -1em; margin-top: -2em; }
}

/* --- Responsive --- */
@media (max-width: 720px) {
  .busn5000 .b-hero { padding: 3.5rem 1.25rem 5.5rem; }
  .busn5000 .b-facts { margin-top: -3.5rem; }
  .busn5000 .b-facts__grid { grid-template-columns: 1fr; }
  .busn5000 .b-facts__cell { border-right: none; border-bottom: 1px solid #ece9e2; }
  .busn5000 .b-facts__cell:last-child { border-bottom: none; }
  .busn5000 .b-arcs { grid-template-columns: 1fr; }
  .busn5000 .b-needs { grid-template-columns: 1fr; gap: 2rem; }
  .busn5000 .b-grading__bar { flex-direction: column; height: auto; }
  .busn5000 .b-grading__seg { padding: 0.65rem; }
}
</style>

<div class="busn5000">

<header class="b-hero">
  <div class="b-hero__inner">
    <p class="b-hero__eyebrow">BUSN 5000 &middot; Spring 2026</p>
    <h1 class="b-hero__title">Data Science for Business and Economics</h1>
    <p class="b-hero__meta"><strong>Mondays &amp; Wednesdays, 9:55 AM</strong> &middot; University of Georgia &middot; Terry College of Business</p>
  </div>
</header>

<aside class="b-facts">
  <div class="b-facts__grid">
    <div class="b-facts__cell">
      <h3>When &amp; where</h3>
      <p>M/W, 9:55 AM<br><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.85rem;">[Building &amp; room]</span></p>
    </div>
    <div class="b-facts__cell">
      <h3>Instructor</h3>
      <p>Prof. Chris Cornwell<br>Office hours: W 2:30&ndash;3:30 PM<br><a href="mailto:cornwl@uga.edu">cornwl@uga.edu</a></p>
    </div>
    <div class="b-facts__cell">
      <h3>Get the PDFs</h3>
      <p><a href="/files/syllabus.busn5000.pdf">Syllabus &rarr;</a><br><a href="/files/schedule.busn5000.weekly.pdf">Weekly schedule &rarr;</a></p>
    </div>
  </div>
</aside>

<section class="b-section">
  <h2>About this course</h2>
  <p class="b-placeholder">[2&ndash;3 sentence course description. Speak to students directly. What is this course, why does it matter for someone going into business or economics, what will they walk away knowing how to do.]</p>
</section>

<section class="b-section">
  <h2>What you'll learn</h2>
  <ol class="b-outcomes">
    <li><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.95rem;">[Learning outcome 1 &mdash; start with a verb: "Translate&hellip;", "Build&hellip;", "Interpret&hellip;"]</span></li>
    <li><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.95rem;">[Learning outcome 2]</span></li>
    <li><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.95rem;">[Learning outcome 3]</span></li>
    <li><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.95rem;">[Learning outcome 4]</span></li>
    <li><span class="b-placeholder" style="display:inline; padding: 0.1rem 0.4rem; font-size: 0.95rem;">[Learning outcome 5 &mdash; aim for 4&ndash;6 total]</span></li>
  </ol>
</section>

<section class="b-section">
  <h2>The arc of the semester</h2>
  <p>The full week-by-week schedule lives in the PDF &mdash; <a href="/files/schedule.busn5000.weekly.pdf">download it here</a>. Here&rsquo;s the big-picture shape:</p>
  <div class="b-arcs">
    <div class="b-arc">
      <span class="b-arc__weeks">Weeks 1&ndash;5</span>
      <h4>[Unit 1 theme]</h4>
      <p>[1&ndash;2 sentence summary of what students are doing in this stretch.]</p>
    </div>
    <div class="b-arc">
      <span class="b-arc__weeks">Weeks 6&ndash;10</span>
      <h4>[Unit 2 theme]</h4>
      <p>[1&ndash;2 sentence summary.]</p>
    </div>
    <div class="b-arc">
      <span class="b-arc__weeks">Weeks 11&ndash;15</span>
      <h4>[Unit 3 theme]</h4>
      <p>[1&ndash;2 sentence summary.]</p>
    </div>
  </div>
</section>

<section class="b-section">
  <h2>Assignments &amp; grading</h2>
  <p>Grades break down as follows. (Hover for labels on narrow screens.)</p>
  <div class="b-grading__bar">
    <span class="b-grading__seg" style="width:30%; background:#BA0C2F" title="Problem sets — 30%">Problem sets &middot; 30%</span>
    <span class="b-grading__seg" style="width:25%; background:#000" title="Midterm — 25%">Midterm &middot; 25%</span>
    <span class="b-grading__seg" style="width:25%; background:#0A4B3E" title="Final project — 25%">Project &middot; 25%</span>
    <span class="b-grading__seg" style="width:20%; background:#6B6B6B" title="Participation — 20%">Participation &middot; 20%</span>
  </div>
  <p class="b-placeholder">[Adjust the segment widths above to match your actual weights, then write a paragraph explaining what each component looks like in practice: how many problem sets, what the project entails, what counts as participation.]</p>
</section>

<section class="b-section">
  <h2>What you'll need</h2>
  <div class="b-needs">
    <div>
      <h4>Software</h4>
      <ul>
        <li>[e.g., R &amp; RStudio]</li>
        <li>[e.g., Python &amp; Jupyter]</li>
        <li>[any course-specific packages or accounts students need to set up]</li>
      </ul>
    </div>
    <div>
      <h4>Readings</h4>
      <ul>
        <li>[Required textbook, with link if available]</li>
        <li>[Recommended supplementary resources]</li>
        <li>[Any course packet or notes you distribute]</li>
      </ul>
    </div>
  </div>
</section>

<footer class="b-cta">
  <h2>Ready to dive in?</h2>
  <p>Pull the syllabus and the weekly schedule below, then come to the first lecture with questions.</p>
  <div class="b-cta__buttons">
    <a class="b-btn" href="/files/syllabus.busn5000.pdf">Download syllabus</a>
    <a class="b-btn b-btn--ghost" href="/files/schedule.busn5000.weekly.pdf">Download schedule</a>
  </div>
</footer>

</div>
