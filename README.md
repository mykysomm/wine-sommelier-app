body {
  margin: 0;
  background:
    radial-gradient(circle at top left, rgba(191, 130, 86, 0.18), transparent 30%),
    linear-gradient(135deg, #0d0b14 0%, #171421 100%);
  color: #f5efe3;
}

button,
input {
  font: inherit;
}

button {
  cursor: pointer;
}

.app-shell {
  max-width: 1500px;
  margin: 0 auto;
  padding: 28px 26px 48px;
}

.topbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
  padding: 10px 8px 24px;
}

.brand-block {
  display: flex;
  align-items: center;
  gap: 14px;
}

.brand-mark {
  width: 42px;
  height: 42px;
  border-radius: 12px;
  display: grid;
  place-items: center;
  background: linear-gradient(135deg, #c79b62, #7f3d2e);
  color: #fff;
  font-weight: 800;
  font-size: 1.3rem;
  box-shadow: 0 15px 30px rgba(198, 153, 98, 0.28);
}

.eyebrow {
  font-size: 0.72rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: #d8c59b;
  margin-bottom: 6px;
}

h1,
h2,
h3,
h4 {
  margin: 0;
  font-weight: 700;
}

h1 {
  font-size: clamp(1.2rem, 2vw, 1.8rem);
  font-family: 'Cormorant Garamond', serif;
  letter-spacing: 0.02em;
}

.topbar-actions {
  display: flex;
  align-items: center;
  gap: 12px;
}

.primary-button,
.ghost-button,
.save-button,
.filter-button {
  border: none;
  border-radius: 999px;
  transition: transform 0.2s ease, opacity 0.2s ease;
}

.primary-button,
.ghost-button {
  padding: 11px 18px;
  font-weight: 600;
}

.primary-button {
  background: linear-gradient(135deg, #d7b378, #a86443);
  color: #1c1718;
}

.ghost-button {
  background: rgba(255, 255, 255, 0.04);
  color: #f2ead8;
  border: 1px solid rgba(255, 255, 255, 0.08);
}

.primary-button:hover,
.ghost-button:hover,
.filter-button:hover,
.save-button:hover,
.wine-card:hover {
  transform: translateY(-1px);
}

.main-layout {
  display: grid;
  grid-template-columns: 390px minmax(0, 1fr);
  gap: 24px;
}

.sidebar,
.timeline-panel,
.insight-panel,
.hero-card {
  background: rgba(20, 18, 29, 0.86);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 28px;
  box-shadow: 0 30px 80px rgba(0, 0, 0, 0.24);
}

.sidebar {
  padding: 20px;
}

.search-box {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-bottom: 20px;
}

.search-box label {
  font-size: 0.78rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #d7cbb1;
}

.search-box input {
  background: rgba(255, 255, 255, 0.04);
  border: 1px solid rgba(255, 255, 255, 0.09);
  border-radius: 14px;
  padding: 14px 15px;
  color: #f3efe5;
  font-size: 0.98rem;
}

.search-box input::placeholder {
  color: rgba(255, 255, 255, 0.45);
}

.results-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 12px;
  color: #d5c7ac;
  font-size: 0.78rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.wine-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.wine-card {
  width: 100%;
  display: grid;
  grid-template-columns: 100px 1fr;
  gap: 12px;
  padding: 10px;
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 20px;
  background: rgba(255,255,255,0.02);
  text-align: left;
  color: inherit;
}

.wine-card.selected {
  background: rgba(184, 136, 96, 0.12);
  border-color: rgba(201, 160, 112, 0.48);
}

.wine-card img {
  width: 100%;
  height: 104px;
  object-fit: cover;
  border-radius: 16px;
}

.wine-card-copy {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.wine-title-row {
  display: flex;
  justify-content: space-between;
  gap: 12px;
}

.wine-card h3 {
  font-size: 1rem;
  line-height: 1.2;
}

.wine-card p,
.wine-card small {
  margin: 0;
  color: #d5ccc0;
}

.wine-card p {
  margin-top: 4px;
}

.wine-card small {
  margin-top: 7px;
  opacity: 0.74;
}

.bookmarked-dot {
  font-size: 1.3rem;
  color: #d9b970;
}

.detail-panel {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.hero-card {
  display: grid;
  grid-template-columns: minmax(250px, 430px) minmax(0, 1fr);
  gap: 24px;
  padding: 18px;
}

.hero-image-wrap {
  min-height: 340px;
}

.hero-image-wrap img,
.mini-visual img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 20px;
}

.hero-copy {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.tag-row {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  margin-bottom: 14px;
}

.tag {
  display: inline-flex;
  align-items: center;
  padding: 7px 10px;
  background: rgba(215, 179, 120, 0.15);
  border: 1px solid rgba(215, 179, 120, 0.35);
  color: #f1d5a6;
  border-radius: 999px;
  font-size: 0.72rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.tag.muted {
  background: rgba(255,255,255,0.04);
  border-color: rgba(255,255,255,0.12);
  color: #d8d0c5;
}

.title-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
  margin-bottom: 14px;
}

.title-row h2 {
  font-size: clamp(2rem, 3vw, 3rem);
  font-family: 'Cormorant Garamond', serif;
  line-height: 0.95;
}

.save-button {
  padding: 11px 16px;
  background: rgba(255,255,255,0.05);
  color: #f5efe3;
  border: 1px solid rgba(255,255,255,0.09);
  font-weight: 600;
}

.save-button.active {
  background: linear-gradient(135deg, #d7b378, #bb8c5d);
  color: #170f18;
}

.subtitle {
  margin: 0 0 20px;
  color: #d2c9b8;
  font-size: 1.02rem;
  line-height: 1.7;
}

.meta-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(180px, 1fr));
  gap: 16px;
}

.meta-grid div {
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(255,255,255,0.06);
  border-radius: 18px;
  padding: 14px 16px;
}

.meta-grid label {
  display: block;
  margin-bottom: 8px;
  color: #c4b49f;
  font-size: 0.72rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.meta-grid strong {
  font-size: 0.96rem;
  color: #fff;
  line-height: 1.4;
}

.content-grid {
  display: grid;
  grid-template-columns: minmax(0, 1.5fr) minmax(260px, 0.8fr);
  gap: 24px;
}

.timeline-panel,
.insight-panel {
  padding: 22px;
}

.panel-header {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 18px;
  margin-bottom: 18px;
}

.panel-header h3 {
  font-size: clamp(1.4rem, 2vw, 2rem);
  font-family: 'Cormorant Garamond', serif;
}

.filter-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  justify-content: flex-end;
}

.filter-button {
  padding: 8px 12px;
  color: #e7e0d0;
  border: 1px solid rgba(255,255,255,0.09);
  background: rgba(255,255,255,0.04);
  font-size: 0.72rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}

.timeline-list {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.timeline-item {
  display: grid;
  grid-template-columns: 14px minmax(0, 1fr);
  gap: 16px;
  padding: 14px 0;
  border-top: 1px solid rgba(255,255,255,0.06);
}

.timeline-item:first-child {
  border-top: none;
  padding-top: 0;
}

.timeline-dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  margin-top: 12px;
  box-shadow: 0 0 18px rgba(255,255,255,0.15);
}

.timeline-content {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.date-badge {
  display: inline-block;
  width: fit-content;
  padding: 5px 10px;
  border-radius: 999px;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
  color: #f3d78e;
  font-size: 0.76rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.event-category {
  color: #d6b78b;
  font-size: 0.72rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.timeline-content h4 {
  font-size: 1.2rem;
  color: #f1ecdf;
}

.timeline-content p {
  margin: 0;
  line-height: 1.7;
  color: #d4cbb7;
}

.timeline-content small {
  color: #b8af9f;
}

.insight-panel {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.compact {
  margin-bottom: 0;
}

.quote-box {
  background: linear-gradient(135deg, rgba(196, 135, 92, 0.12), rgba(114, 85, 147, 0.12));
  border: 1px solid rgba(255,255,255,0.08);
  border-radius: 18px;
  padding: 18px 16px;
  color: #f7ead6;
  line-height: 1.7;
  font-size: 1.02rem;
}

.fact-list {
  margin: 0;
  padding-left: 20px;
  display: flex;
  flex-direction: column;
  gap: 12px;
  color: #d9d0c2;
  line-height: 1.7;
}

.mini-visual {
  overflow: hidden;
  border-radius: 22px;
  min-height: 220px;
  border: 1px solid rgba(255,255,255,0.08);
}

@media (max-width: 1100px) {
  .main-layout {
    grid-template-columns: 1fr;
  }

  .hero-card,
  .content-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 680px) {
  .app-shell {
    padding: 18px 14px 36px;
  }

  .topbar {
    flex-direction: column;
    align-items: flex-start;
  }

  .topbar-actions {
    width: 100%;
    justify-content: flex-start;
    flex-wrap: wrap;
  }

  .title-row {
    flex-direction: column;
    align-items: flex-start;
  }

  .meta-grid {
    grid-template-columns: 1fr;
  }
}



























































































































































































































































































































































"use strict";
