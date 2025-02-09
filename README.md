# Proffesional Portfolio
import React from 'react';

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800 p-6">
      <header className="text-center py-6">
        <h1 className="text-4xl font-bold">Agniv Kar</h1>
        <p className="text-lg">Economics Graduate | Aspiring Consultant</p>
        <p className="text-sm text-blue-600">Kolkata, India | agniv.work.id03@gmail.com | <a href="https://www.linkedin.com/in/agniv-kar/" target="_blank" rel="noopener noreferrer" className="underline">LinkedIn</a></p>
      </header>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">About Me</h2>
        <p className="mt-4">
          Economics graduate with a proven track record in leadership, problem-solving, and strategic decision-making. Skilled in conducting impactful research, driving team performance, and enhancing operational efficiency.
        </p>
      </section>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">Projects</h2>
        <ul className="mt-4 space-y-4">
          <li>
            <h3 className="text-xl font-bold">Randomized Control Trial</h3>
            <p>Analyzed the impact of cost-effective psychotherapy on the socio-economic well-being of patients with Major Depressive Disorders in West Bengal using R, STATA, and Python.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">Oil Price Shocks Dissertation</h3>
            <p>Conducted an in-depth analysis of the impact of oil price shocks on sustainability, supported by two scholarly papers.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">Blockchain Growth Strategy at Flint Labs</h3>
            <p>Created blockchain-focused articles, managed website content, and led a team of writers to develop marketing strategies in the financial and health sectors.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">Leadership in Economics & Sports Society</h3>
            <p>Guided cross-functional teams, streamlined event logistics, and drove outreach initiatives to deliver successful university events.</p>
          </li>
          <li>
            <h3 className="text-xl font-bold">Impact of Midday Meal Scheme on Education in India</h3>
            <p>Conducted research at the University of Bristol analyzing the effectiveness of India's Midday Meal Scheme in improving school attendance and learning outcomes. Utilized Difference-in-Differences (DID) and RCT models to assess policy impacts.</p>
          </li>
        </ul>
      </section>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">Experience</h2>
        <ul className="mt-4 space-y-4">
          <li>
            <h3 className="text-xl font-bold">Sales Strategy Consultant</h3>
            <p>Developed and implemented strategic sales plans that increased revenue growth by analyzing customer trends and optimizing sales operations.</p>
          </li>
        </ul>
      </section>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">Skills & Tools</h2>
        <p className="mt-4">MS Excel (Advanced), Power BI (Intermediate), STATA, Python, Policy Analysis, Research & Data Analysis.</p>
      </section>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">Research Reports</h2>
        <ul className="mt-4 space-y-4">
          <li>
            <h3 className="text-xl font-bold">Evaluating the Midday Meal Scheme</h3>
            <p>Investigated the impact of India's Midday Meal Scheme on school enrollment, dropout rates, and nutrition outcomes. Used Difference-in-Differences (DiD) methodology and time-series analysis to assess policy effectiveness.</p>
            <p>Key Findings: While MDM improved attendance, its long-term impact on education quality and nutrition remains uncertain. Proposed alternative strategies like free transport and infrastructure upgrades.</p>
            <p><a href="/midday-meal-report.pdf" className="text-blue-600 underline">Download Full Report</a></p>
          </li>
        </ul>
      </section>

      <section className="my-8">
        <h2 className="text-2xl font-semibold border-b pb-2">Contact</h2>
        <p className="mt-4">Email: <a href="mailto:agniv.work.id03@gmail.com" className="text-blue-600 underline">agniv.work.id03@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/agniv-kar/" target="_blank" rel="noopener noreferrer" className="text-blue-600 underline">linkedin.com/in/agniv-kar</a></p>
      </section>
    </div>
  );
}
