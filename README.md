# RoboSketch-Studio | استوديو روبوسكيتش

## 🤖 Overview | نظرة عامة

**English:**
RoboSketch-Studio is an interactive web app for designing simple robots and geometric shapes. It features a canvas-based editor with snapping, grouping, constraints, and export/import, ideal for students and engineers to prototype mechanisms and layouts.

**العربية:**
RoboSketch-Studio هو تطبيق ويب تفاعلي لتصميم الروبوتات البسيطة والأشكال الهندسية. يوفر محررًا مبنيًا على Canvas مع ميزات الالتقاط، التجميع، القيود، والتصدير/الاستيراد، مناسب للطلاب والمهندسين لنمذجة الآليات والمخططات.

## ✨ Features | الميزات

### English:
- Drag, rotate, and scale shapes (rect, circle, polygon, path)
- Robot blocks: chassis, wheel, caster, arm segment, joint
- Constraints: align, equal length, angle lock, distance
- Grid snap, rulers, guides, multi-select and grouping
- Layers panel with lock/visibility
- Export to SVG/PNG and JSON scene
- Keyboard shortcuts and undo/redo

### العربية:
- سحب، تدوير، وتكبير/تصغير للأشكال (مستطيل، دائرة، مضلع، مسار)
- مكوّنات روبوت: هيكل، عجلة، داعم، ذراع، مفصل
- قيود: محاذاة، أطوال متساوية، تثبيت زاوية، مسافة
- شبكة التقط، مساطر، أدلة، تحديد متعدد وتجميع
- لوحة طبقات مع قفل/إخفاء
- تصدير إلى SVG/PNG وملف JSON للمشهد
- اختصارات لوحة مفاتيح وتراجع/إعادة

## 🛠️ Tech Stack | التقنيات
- TypeScript + Vite
- HTML5 Canvas or SVG (Konva.js / Paper.js)
- Zustand for state management
- ESLint + Prettier + Vitest

## 🚀 Getting Started | البدء
```bash
# Clone
git clone https://github.com/KaizerAE/RoboSketch-Studio.git
cd RoboSketch-Studio

# Install deps
npm install

# Run dev
npm run dev
```
Open the shown localhost URL.

## 📁 Project Structure | هيكل المشروع
```
RoboSketch-Studio/
├── public/
├── src/
│   ├── components/     # UI and panels
│   ├── canvas/         # Rendering and interactions
│   ├── models/         # Shapes and robot parts
│   ├── state/          # Store (Zustand)
│   └── utils/          # Math, geometry helpers
├── assets/
├── package.json
└── README.md
```

## 🧪 Roadmap | خارطة الطريق
- Kinematics preview for 2-link arm
- Import DXF/SVG with constraints detection
- Parametric dimensions and dimensioning tool
- G-code export for plotters

## 📝 License | الترخيص
MIT License.

## 👤 Author | المؤلف
**KaizerAE** — https://github.com/KaizerAE

---
⭐ Star the project if you like it! | ⭐ ادعم المشروع بنجمة!
