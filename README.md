import React from 'react';
import { motion } from 'framer-motion';

export default function PortfolioPage() {
  return (
    <main className="min-h-screen bg-gradient-to-tr from-sky-50 via-emerald-100 to-white text-gray-800 font-sans">
      <section className="text-center py-16">
        <h1 className="text-5xl font-bold text-sky-800">👨‍⚕️ Dr. Sai Kumar Koneti</h1>
        <p className="text-xl text-gray-600 mt-4">Health Informatics • Clinical Research • Data Science</p>

        <div className="mt-6 flex justify-center gap-4 flex-wrap">
          <a href="mailto:konetisaikumar27@gmail.com">
            <img src="https://img.shields.io/badge/Email-grey?style=flat&logo=gmail" />
          </a>
          <a href="https://www.linkedin.com/in/dr-sai-kumar-5142a4226/">
            <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin" />
          </a>
          <img src="https://img.shields.io/badge/Health%20Informatics%20-Masters-green" />
          <img src="https://img.shields.io/badge/Open%20to-Collaborations-purple" />
        </div>
      </section>

      <section className="max-w-6xl mx-auto px-4 py-8">
        <h2 className="text-3xl font-bold text-center text-emerald-700 mb-8">🚀 Featured Projects</h2>
        <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          {[
            {
              title: "Heart Disease Readmission (MIMIC-IV)",
              desc: "ML models predicting 30-day readmission risk; achieved 71.8% accuracy.",
              icon: "🩺"
            },
            {
              title: "Depression Treatment Prediction",
              desc: "LASSO regression model using NIH All of Us data to predict response to Venlafaxine.",
              icon: "🧠"
            },
            {
              title: "FACTORS: AI Tool Evaluation",
              desc: "Framework for evaluating Gen AI tools like Synthesia for public health use.",
              icon: "🧪"
            },
            {
              title: "Brain Tumor Detection",
              desc: "CAD system using MATLAB & PyTorch for MRI tumor analysis.",
              icon: "🧬"
            },
            {
              title: "Dementia Caregiver Education",
              desc: "Created Gen AI videos to educate caregivers on dementia support techniques.",
              icon: "👵"
            },
            {
              title: "Tableau Readmission Dashboards",
              desc: "Built Tableau dashboards to visualize hospital trends and inform decision-making.",
              icon: "📊"
            }
          ].map(({ title, desc, icon }, i) => (
            <motion.div
              whileHover={{ scale: 1.03 }}
              key={i}
              className="rounded-xl border border-gray-200 bg-white p-6 shadow-md hover:shadow-lg"
            >
              <h3 className="text-xl font-semibold text-indigo-700 mb-2">{icon} {title}</h3>
              <p className="text-gray-700 text-sm">{desc}</p>
            </motion.div>
          ))}
        </div>
      </section>

      <section className="py-12 bg-white mt-16">
        <h2 className="text-3xl font-bold text-center text-sky-700 mb-10">📂 Work Areas</h2>
        <div className="flex flex-wrap justify-center gap-8 px-6">
          {[
            {
              title: "Graduate Research Assistant (HAP)",
              desc: "Presented SDOH and nursing home research at AcademyHealth 2025. Created educational content using AI.",
              color: "bg-sky-100"
            },
            {
              title: "MSHI Projects",
              desc: "Predictive analytics with EHR data, clinical modeling, Tableau visualization, and mental health tracking.",
              color: "bg-emerald-100"
            },
            {
              title: "Parexel Internship",
              desc: "RWE insights using TriNetX, Purple Labs. Focused on HFpEF vs. HFrEF treatment outcomes.",
              color: "bg-violet-100"
            },
            {
              title: "Independent Projects",
              desc: "AI-generated videos for caregiver education, brain imaging analysis, and digital tool comparisons.",
              color: "bg-orange-100"
            }
          ].map(({ title, desc, color }, i) => (
            <motion.div
              whileHover={{ scale: 1.05 }}
              key={i}
              className={`rounded-full w-72 h-72 flex flex-col justify-center items-center p-6 text-center shadow-md ${color}`}
            >
              <h3 className="text-lg font-semibold text-gray-800 mb-2">{title}</h3>
              <p className="text-gray-600 text-sm">{desc}</p>
            </motion.div>
          ))}
        </div>
      </section>

      <footer className="text-center py-8 text-sm text-gray-500">
        <p>📫 konetisaikumar27@gmail.com | 💼 <a className="underline" href="https://www.linkedin.com/in/dr-sai-kumar-5142a4226/">LinkedIn</a></p>
        <p>© 2025 Sai Kumar Koneti. All rights reserved.</p>
      </footer>
    </main>
  );
}
