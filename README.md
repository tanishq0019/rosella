# Rosella — Premium Luxury Banqueting Showcase

A premium, high-conversion landing page designed for luxury event properties and grand banqueting management. Built with a focus on minimalist luxury aesthetic layouts, micro-interactions, and flawless cross-device viewports.

## 🚀 Live Demo
👉 **[View the Live Site](https://YOUR_GITHUB_USERNAME.github.io/rosella/)** *(Replace with your live link)*

## 🛠️ Tech Stack & Architecture
- **Markup & Layout:** Semantic HTML5, CSS3, Asymmetrical Flexbox/Grid systems
- **Style Engine:** Tailwind CSS v4 (utilized for lightning-fast atomic CSS utility compilation via CDN)
- **Typography Framework:** Google Fonts (Cinzel for premium Serif header displays & Plus Jakarta Sans for structural, highly readable body prose)

## 📱 Key Mobile Engineering Solutions Included
Standard layouts often break on modern mobile viewports due to dynamic navigation chrome or experimental display boundaries. This project explicitly addresses those issues:

1. **Dynamic Viewport Heights (`min-h-screen` vs. `min-h-fit`):** Overcame mobile Safari and Android Chrome address bar expansion glitches by utilizing fluid parent containers that resize dynamically based on text layout, preventing content truncation.
2. **Safe-Area Layout Bumpers:** Engineered custom layout offsets (`pb-36` + empty padding blocks) at the base of the DOM tree. This guarantees that bottom interactive elements—like the floating communication CTA—never compete with native OS navigation tools (e.g., Apple Home indicator, Fold 4 outer glass aspect ratios).
3. **High-Visibility Context Stacking:** Managed structural layers strictly via `z-index` profiling to prevent user interaction blockages during quick scrolling actions.

## 📈 Future Roadmap
- [ ] Migrate static components into a dynamic **React.js** single-page architecture.
- [ ] Implement a **Spring Boot REST API** microservice backend to handle real-time date reservations and calendar checks.
- [ ] Secure administrative access panels with OAuth2 protocol structures.
