# ShaktiSetu — Visual and Voice-First Order, Quality and Fair-Wage Bridge for Women's Self-Help Groups

- **Hackathon:** Tech4Bharat — Global Accelerator Vision Summit (GAVS) 2026
- **Theme:** Youth and Women
- **Problem Statement:** 8.1 — Women's self-help groups lose orders and members' trust because fulfilment and pay are chaotic

---

## 1. Ground Field Insights: Akkamahadevi's Story (North Karnataka)

Before designing ShaktiSetu, we visited and interviewed **Akkamahadevi**, a home-based garment tailor in North Karnataka who works on bulk orders through local women's Self-Help Groups (SHGs) alongside daily household responsibilities.

<img src="https://github.com/user-attachments/assets/11bff102-e3aa-477f-8dad-3c2b0e79ea70" alt="Field Visit with Akkamahadevi" width="320" />

### Five Real Bottlenecks Observed on the Ground
1. **Unequal Work and Unfair Wage Adjustments:** Bulk orders are divided verbally by the group leader without accounting for each woman's available household hours, and advance deductions for cloth or thread are tracked informally.
2. **Underpricing Bulk Orders by 30 to 40 Percent:** When quoting institutional or local buyers, groups calculate only primary cloth and basic stitching labour—forgetting thread reels, lining, buttons, packaging, transport fares, electricity, 5–8% material wastage, and rework time.
3. **No Deadline Visibility or Time Management:** Working isolated from home, women have no daily pace target or early warning alert when an order deadline is slipping until the final delivery day turns into a panic.
4. **Product Accuracy Issues and Last-Minute Rejections:** Without mid-way quality checks, stitching errors, wrong dimensions, or stains are spotted only when everyone pools finished pieces together on the final day.
5. **Low Literacy and New-Member Onboarding Barrier:** Text-heavy English apps intimidate low-literacy workers, and newly joined SHG members struggle to understand active orders, piece rates, and group rules.

---

## 2. Human-Centered Solution: Visual and Voice-First User Experience

Built specifically for low-budget Android smartphones (Rs. 6,000–Rs. 8,000), low-literacy workers, and patchy 2G/3G rural networks:

- **Phone Number and Unique Group Code Access:** Users sign in with their mobile number and enter a unique **Group Code** with role-based access for **SHG Workers**, **Group Head**, and **Bulk Buyers**. When a new member joins an SHG, entering the Group Code immediately introduces her to ongoing orders, piece rates, and rules through visual cards and Kannada audio.
- **Clutter-Free Worker Dashboard:** Displays only three clear items—her **Assigned Work** visual card, a color-coded **Deadline Alert** bar (Green, Amber, Red), and her **Live Wage and Calculation** card with a **Tap-to-Listen Kannada Speaker icon** next to every rupee figure.
- **One-Tap Kannada Speech-to-Text Reporting:** Workers hold one large mic button and speak naturally in Kannada (for example, reporting stitched blouses or requesting a lighter load due to household work). Speech is converted into clean structured text and sent as an instant alert to the Group Head.
- **One-Tap Work Photo Verification:** Workers snap and submit photos of stitched sub-batches directly from their dashboard for early quality verification before final consolidation.
- **Group Head Operations Cockpit:** Equips the group leader to calculate true order quotes, allocate tasks fairly, view translated voice and text alerts from workers, reassign pending work with one tap, and finalize transparent group payouts.

---

## 3. Multi-Agent AI Architecture

Four autonomous AI agents work continuously behind the scenes around a **deterministic financial accounting ledger** (eliminating AI arithmetic errors on wages and deductions):

1. **Fair-Costing and Margin Guard Agent:** Generates a complete Bill of Materials (cloth, thread, trims, packaging), injects hidden overheads (transport, utilities, 5% wastage buffer), and checks fair hourly labour before the Group Head quotes a buyer—preventing the 30–40% underpricing trap.
2. **Smart Allocation, Deadline Alert and Reassignment Agent:** Splits bulk orders proportionally by daily capacity, sends Kannada voice/visual deadline reminders, parses incoming speech-to-text delay reports, and proactively proposes shifting pending pieces from a delayed worker to an available teammate.
3. **Stitching and Product Accuracy Vision Agent:** Evaluates submitted worker garment photos against order reference specs (stitch alignment, symmetry, stains, dimensions) early in production so defects are fixed at home rather than rejected by the buyer.
4. **Transparent Audio-Ledger and Consensus Payout Agent:** Deterministically computes exact net wages (`Verified Pieces × Piece Rate − Material Advances`) and generates a personal Kannada voice readout explaining every rupee and deduction aloud. Disbursement stays locked until members verify and approve their records.

---

## 4. Frugal Offline-First Engineering & Governance Boundaries

- **Offline-First Progressive Web App (<5 MB):** Compresses Kannada voice notes and batch photos, caches daily entries locally on the phone when network drops, and syncs automatically when 2G/3G connectivity returns.
- **Governance & Human-in-the-Loop Boundaries:** Every member can both **see and hear** her own work count, deductions, and wage calculation in Kannada. AI agents only recommend quotes, task reassignments, and quality flags—the **Group Head and members explicitly approve** every task shift and final payout.

---

## 5. Entrepreneurial Model ("Following the Money")

- **Always Free for Rural Women Workers:** Zero subscription fees or adoption friction for SHG members.
- **B2B Buyer Fulfillment Take-Rate (3 to 5 Percent):** Uniform contractors, corporate gifting companies, and apparel/FMCG brands pay an order-assurance fee for reliable, on-time, quality-verified bulk goods, while tailors like Akkamahadevi earn 25–30% higher net wages by eliminating underpricing.
- **Bank and Federation Credit Enablement (1 to 1.5 Percent Fee):** Verified production ledgers help rural banks and SHG federations (NRLM / Sanjeevini) extend working-capital loans against confirmed Purchase Orders.
- **B2G / CSR Federation SaaS:** Cluster Level Federations (CLFs) license the cluster dashboard to track production capacity and credit health across hundreds of SHGs.
