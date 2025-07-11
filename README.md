# DWTA-daily-wage-tracking-app-
DWTA is a tech solution for India’s 400M+ informal workers, offering secure wage tracking, biometric check-in, blockchain proof, and emergency aid. It reduces wage fraud, supports microloans, and builds financial identity—enabling credit, insurance, and welfare access.

DWTA (Daily Wage Tracking App) is an innovative, inclusive digital platform designed to uplift and protect India’s vast informal workforce by addressing their most critical financial vulnerabilities. With over 400 million daily-wage workers in the country—many facing issues like wage theft, lack of emergency support, and zero access to credit due to the absence of financial history—DWTA offers a powerful solution through secure wage tracking, face or fingerprint-based attendance logging, and blockchain-backed wage proof to ensure transparency and trust. The app enables workers to digitally record their daily labor and receive instant support in times of crisis via integrated NGO and government channels. With a clean, user-friendly interface built using Flutter and Firebase, DWTA supports UPI integration, offline access, and regional languages to ensure maximum usability and reach. Beyond real-time benefits, DWPA helps build a digital financial footprint that unlocks access to loans, insurance, and future government entitlements, bridging the gap between unorganized labor and formal financial systems. Its scalable design, future-ready tech stack, and potential for integration with labor welfare boards, pensions, and AI-powered voice assistants make DWTA a transformative step toward inclusive economic resilience in India.
*Problem Statement
      “Millions of daily wage workers lose income due to wage theft, non-payment, or emergencies.”
	•	Shocking fact or stat:
         India has 400+ million informal workers. 50% face wage disputes , No wage tracking, No emergency help, No financial history = no credit
 * Motive
        Our goal is to empower unorganized workers with a simple, transparent, and secure way to track wages and get financial support.
	•	Record work + attendance proof (face/biometric),	•	Track daily income,	•	Get instant microloans/food tokens during crisis,	•	Build digital history for credit eligibility
* UI Screenshots
	•	Worker check-in screen
	•	Wage history dashboard
	•	Emergency help button
	•	Admin dashboard (optional)

* Impact
  Explain how DWTA improves stability:
	  •	Reduces wage fraud
	  •	Gives workers emergency fallback
	  •	Helps NGOs/governments track economic risk zones
	  •	Generates credit score for financial access

Graph idea: Before vs After DWTA adoption (wage lost, support received)

* Future Scope
	  •	Link to insurance, pension, PF
	  •	Advanced credit scoring
	  •	Link to labor unions or government
* Technical Feasibility
   existing tools and tech:
	  •	Face recognition: Can use lightweight models (e.g., Mediapipe, OpenCV).
  	•	Wage tracking: Use Firebase or any real-time database.
  	•	Blockchain proof: Platforms like Polygon, Hyperledger, or IPFS make data immutable without high cost.
    •	UPI integration: Through Razorpay or Bharat Interface APIs.
* Operational Feasibility
	  •	Daily wage workers already use smartphones for YouTube, UPI, WhatsApp.
	  •	Biometric or facial check-in is simple and quick.
	  •	NGOs, local employers, or labor hubs can onboard users.
 3. Financial Feasibility
	•	Initial development cost: Low (open-source tools, student devs)
	•	Hosting: Use free tiers (Firebase, GitHub, Vercel)
	•	Maintenance cost: Minimal for pilot stage

Revenue or Support Models:
	•	Partner with NGOs, state governments, labor unions
	•	CSR funds from companies
	•	Add freemium services for advanced features (credit score, loans)
* Social Feasibility
	•	Need is massive: Millions of workers lose wages due to lack of documentation
	•	Can be piloted in construction, farming, street vendors
	•	Workers trust local apps if presented through unions or community leaders

 Culturally and socially acceptable if localized
 Ethical Implications of AI

Use this section to show that you’re thinking responsibly.
	•	Privacy & Consent: Facial data used only with consent, stored securely, not shared.
	•	 Bias & Fairness: AI models must be trained on diverse datasets to avoid biaacross skin tones, gender, etc.
	•	Transparency: Workers should understand how the AI makes decisions (like risk scoring or alerts).
	• Explainability: Wage alerts or emergency flags should include a clear reason.

* Responsible AI Practices

How DWPA ensures AI is used ethically and effectively:
	•	 Uses on-device face verification when possible to reduce cloud dependency
	• Facial data encrypted + not shared across employers
	•	No black-box decision-making – alerts include clear reasons
	•	 Offers manual override or verification by human agents
	  •	AI voice assistant in regional language

