# MRVL optical interconnect industry moat: copper wall, 2026 vendor competition and 2028 LITE M&A
**Date:** 2026-11-15 Asia/Seoul, publicly released source dates cited. **Status:** RESEARCH_ONLY / OPTICAL_SECULAR_TAILWIND_SUPPORTED / MRVL_MONOPOLY_UNPROVEN / LITE_DEAL_NOT_CLOSED / NO_BUY_APPROVAL. This work supplements `MRVL_VS_VRT_AI_OPTICAL_INTERCONNECT_LUMENTUM_20261115.md`; does not replace 5yr risk-adjusted VRT comparison, nor JBTM/PAHC tracks.

## Main thesis
Physical bandwidth and reach constraints of copper, increasing XPU counts, more distributed GPU clusters and scale-out/scale-across traffic support optical links and high-speed Ethernet/coherent transport expansion. Evidence concrete: LightCounting optical transceivers + AOC related products revenue **$26.8B CY2025 +74% YoY**, Q1 2026 ~$10B **>90% YoY**; LightCounting April 2026 **CY2026 Ethernet transceiver market +65% projected**, but **2027–31 conservative** due 2026 laser supply increase/cyclicality; LightCounting Feb report 800G PAM4 chipset shipments almost 3x 2025, 800G ships >2x forecast in 2026 and 1.6T chipset TAM >$2B forecast in 2026. This is **sector revenue not Marvell semiconductor sales or 70% share**.
Copper not universally inefficient: passive short DAC and rack copper can be lower power, cost and latency, optics need lasers and optical/electrical conversion. NVIDIA DGX Vera Rubin NVL72 official **passive copper NVLink cable-cartridge backplane** and NVIDIA GTC 2026 prototype NVL576 multirack **optical** scale-up = complementary length-dependent coexistence. As frequency rises, copper insertion loss, equalization/retiming, energy/heat, weight/mass and reach constraints increase; long-distance/rack-to-rack high-bandwidth optics increasingly economic.
Source NVIDIA hardware https://docs.nvidia.com/dgx/dgxvr-user-guide/hardware.html
GTC prototype https://www.nvidia.com/gtc/session-catalog/sessions/gtc26-s81911/

## Technical stack and market distinctions
### Four distance domains
- Scale-in: intra-chip/package/tray, submeter, often copper for short reaches, optics next gen R&D.
- Scale-up: within rack/multi-rack tightly coupled XPUs, copper existing, optical NPO/CPO fast-evolving for longer ranges.
- Scale-out: between racks/rows/data halls (hundreds of meters–~2km), existing pluggable 800G/1.6T PAM4 modules use MRVL and peer DSPs/TIAs/drivers, lasers/components from LITE/COHR etc.
- Scale-across: between separate facilities/campuses (km–1000+ km), coherent/DWDM 400/800ZR+ optical, MRVL coherent DSP/COLORZ, strong competing Cisco/Acacia and Ciena, coherent DSP different devices from short reach PAM.
Source original company https://www.marvell.com/solutions/data-center/scaling-ai-infrastructure.html ; M&A discussion https://www.sec.gov/Archives/edgar/data/1835632/000119312526443876/d178787d425.htm ; Marvell product https://www.marvell.com/solutions/data-center/optical-dsp.html
### Semiconductor content not entire optical value chain
A representative transceiver includes electrical SerDes/retimer/DSP, analog TIA/laser drivers, photonic modulator/detector/laser, housing/fiber/cooling; signal path is bidirectional and receiver chain differs. Marvell originally strong Inphi high-speed PAM4/coherent DSP/TIA/drivers; FY2026 investor letter **optical interconnect grew ~50% CAGR for five years and accounted for about half data center revenue**, diversified MRVL includes ASIC and switches. **Gartner July 16 2026 picked MRVL as "Company to Beat" in AI datacenter optical connectivity** (DSP pluggables + analog optics + linear receive optics + planned CPO) while **Broadcom** custom AI silicon, **NVIDIA** network fabric. This is quality assessment not certified 70% global optical module market share.
Gartner https://www.gartner.com/en/newsroom/press-releases/2026-07-16-gartner-identifies-the-companies-to-beat-in-the-ai-semiconductor-vendor-race
MRVL FY2026 stockholder letter https://investor.marvell.com/_assets/_da667c3a8a3190ba2b293219dc0fb94d/marvell/db/3848/35416/file/Proxy-Statement-2026-Matt-Letter-Single-Page.pdf (PDF to be screenshot-validated before any web visual evaluation).

### Estimated merchant DSP share cannot extrapolate
In **Nov 2 2026 SEC merger call transcript**, JPMorgan analyst **Harlan Sur asserts his *estimate* MRVL has >70% DSP segment share**; category boundary not defined and independently audited share breakdown unavailable. It is NOT "Marvell owns 70% of all optical modules or optical connectivity revenue." Other independent Gartner makes optical leadership plausible.
SEC transcript https://www.sec.gov/Archives/edgar/data/1633978/000119312526443876/d178787d425.htm

## Secular growth counterweight — the most important hidden investment risk
LightCounting February 2026 **explicitly forecasts PAM4 DSP chip sales growth moderation in 2027–31 caused by *linear-drive photonics LPO and CPO negatively affecting traditional DSP sales***. Market optical ports rising does NOT guarantee merchant DSP dollars/port rise. For selected designs, NVIDIA **Spectrum-X/Quantum-X CPO** integrates photonics in switch package and explicitly **removes some DSP retimers**, benefits 5x power efficiency vs conventional pluggable in NVIDIA-specific comparisons. Distinguish NVIDIA claim from independent product testing; optical light source, photonic IC, modulator drivers, TIA, silicon photonics still have value. MRVL has Celestial AI Photonic Fabric acquired Feb 2026 and LRO/NPO/CPO development—its new content might more than offset old DSP cannibalization, but unproven.
Sources https://mail.lightcounting.com/newsletter/en/february-2026-pam4-and-coherent-dsps-updated-april-2026-381 ; https://www.nvidia.com/en-us/networking/products/silicon-photonics/ ; https://www.marvell.com/blogs/the-evolution-of-ai-interconnects.html

## Strong substitutes and competitors
| Vendor(s) | Actual competing part / complementary distinction | Independent/company evidence |
|---|---|---|
| Broadcom (AVGO) | Direct DSP/SerDes/TIA+laser competitors, **Mar 2026 3nm Taurus 400G/lane optical DSP** enabling 1.6T + 3.2T; next-gen CPO/switch 102T, large engineering platform | https://www.broadcom.com/company/news/apj/product-releases/64016 |
| NVIDIA (NVDA) | Integrated AI networks, **Spectrum-X/Quantum-X Photonics CPO removes some pluggable transceiver DSP**, may vertically integrate silicon and product selection | https://www.nvidia.com/en-us/networking/products/silicon-photonics/ |
| Cisco/Acacia (CSCO) | **800G ZR/ZR+ coherent optical modules** and silicon-photonics engines, especially inter-data-center DWDM; LightCounting June 2026 reports very strong Acacia coherent market growth | https://www.cisco.com/c/en/us/products/collateral/interfaces-modules/transceiver-modules/qsfp-dd-osfp-800g-zr-zr-plus-coherent-optics.html ; https://www.lightcounting.com/newsletter/en/june-2026-quarterly-market-update-375 |
| Coherent (COHR) | Vertically integrated **InP/VCSEL/EML lasers, 800G/1.6T transceiver, optical engine/CPO**; OFC 2026 explicitly supported **three different DSP solutions**, showing replacement/design-choice reality | https://www.coherent.com/news/press-releases/coherent-demonstrates-next-gen-pluggable-transceiver-ofc-2026 |
| InnoLight 300308.SZ & Eoptolink 300502.SZ | Leading **finished module assemblers**, not one-to-one competitors to MRVL DSP but direct competitors to future Lumentum module products, may also be customers of merchant chips/lasers and switch vendor for Broadcom | https://www.lightcounting.com/newsletter/en/june-2026-quarterly-market-update-375 |
| Credo (CRDO) | **Active electrical copper cable** and retimer technology can economically preserve copper at shorter reach, substitutes optical placement and may compete on PHY signal processing, but not fully interchangeable with km optical DWDM | industry-specific official products to validate in follow-up |
| Ciena, Nokia | Coherent transport / data-center interconnect; network systems + pluggables alternative | https://www.lightcounting.com/newsletter/en/june-2026-quarterly-market-update-375 |
**Conclusion competitor mix:** **Broadcom is closest direct semiconductor competitor**; NVIDIA integrated future architecture threat; COHR and Cisco are strong optical ecosystem rivals; Innolight/Eoptolink module customer/partner/downstream competitor, not necessarily replacement for merchant DSP. No MRVL-only industry bottleneck.

## Lumentum acquisition tech and merchant customer conflict
**Signed Nov 1, announced Nov 2 2026. Target CY2028 H1 closing; NOT closed as of Nov15.** 4.5 MRVL shares per LITE share, announced **$115B LITE enterprise value as of Oct28 reference**, future legacy holders MRVL ~67%, LITE ~33%. Future full-stack portfolio **MRVL: high-speed DSP/SerDes/TIA/driver/silicon photonics/Celestial Photonic Fabric + LITE: indium-phosphide InP laser/EML/photodiodes/OCS/optical modules**. Potential hardware optimization, less wasted power and integrated qualification, better control scarce InP chip manufacturing and optical engines; >$1B annual COGS synergy **company forward target**. The claimed **$550B combined TAM in 2030** includes much broader AI silicon and connectivity than current optical transceiver sales; **NOT a predicted merged company revenue or a $550B optical transceiver market**.
**Hidden danger:** MRVL selling *merchant DSP* to Lumentum optical module rivals, while LITE itself builds competing downstream modules. JPMorgan directly questioned on Nov2 whether customers would shift toward **Broadcom/Coherent/alternative suppliers** to hedge, management acknowledged dual merchant/module model and said laser components remain core, but outcome still uncertain. Independent TechTarget Nov2026 highlights merchant silicon partner/channel conflict and adding manufacturing execution/return-on-investment risk. Coupled with significant share issuance and possible CPO retimer bypass, **acquisition strengthening tech doesn't guarantee strengthening MRVL shareholder FCF**.
Official filing https://www.sec.gov/Archives/edgar/data/1835632/000119312526442717/d352474d8k.htm
Merger release https://investor.marvell.com/news-events/press-releases/detail/1040/marvell-and-lumentum-to-combine-creating-a-category-leader-in-ai-connectivity
SEC Q&A https://www.sec.gov/Archives/edgar/data/1633978/000119312526443876/d178787d425.htm
Independent https://www.techtarget.com/news/marvells-115-billion-lumentum-deal-tests-merchant-silicon-business/873486/

## Investment falsification tests next 6–18 months, NOT buy triggers
- MRVL optical merchant DSP-only revenue and **price per port vs shipment rate**; 800G→1.6T design-win market-share and 3.2T Broadcom Taurus early shipments; independent analyst optical DSP market share method and dated sample.
- % ports in retimed conventional PAM4 vs LPO/LRO and CPO; MRVL total *new* silicon photonics/laser/engine content per bit vs lost DSP economics.
- Optical laser manufacturing InP bottleneck relaxation by 2027 and ASP declines; supplier margin and contracted multi-source quality.
- Lumentum shareholder/regulatory approval and merger timing, 67/33 diluted share ownership, post-merger optical business gross profit by customer; guard neutrality with independent modules vs Lumentum downstream modules. Will competitors switch their DSP sourcing?
- Broadcom vs MRVL optical DSP power/bit and port yield matched formfactor; NVIDIA CPO actual production share, Coherent DSP multi-source penetration.
- Company AI DC 2027–2031 CAPEX/recurring inference demand, customer in-sourcing, fleet bandwidth scaling, margin and owner FCF per diluted share after stock-based comp and the LITE deal.
- **Valuation caution:** optical industry revenue and TAM can grow while MRVL fails to capture share, loses $/port from DSP-less CPO, dilutes shareholders or M&A overpays. Research does not assert all optical connection will be Marvell or that copper disappears.

## Key reference index
- [Gartner July 2026 MRVL optical leadership](https://www.gartner.com/en/newsroom/press-releases/2026-07-16-gartner-identifies-the-companies-to-beat-in-the-ai-semiconductor-vendor-race)
- [LightCounting optical 2025 market +74% to $26.8B](https://www.lightcounting.com/newsletter/en/june-2026-quarterly-market-update-375)
- [LightCounting 2026 1.6T chipset >$2B but LPO/CPO hurt PAM DSP](https://mail.lightcounting.com/newsletter/en/february-2026-pam4-and-coherent-dsps-updated-april-2026-381)
- [NVIDIA Rubin passive copper backplane](https://docs.nvidia.com/dgx/dgxvr-user-guide/hardware.html)
- [NVIDIA CPO no retimer/5x advertised power efficiency](https://www.nvidia.com/en-us/networking/products/silicon-photonics/)
- [Marvell original 2026 1.6T DSP portfolio](https://www.marvell.com/solutions/data-center/optical-dsp.html)
- [Broadcom March 2026 Taurus 400G per lane](https://www.broadcom.com/company/news/apj/product-releases/64016)
- [Coherent 2026 optical transceiver with 3 DSP sources](https://www.coherent.com/news/press-releases/coherent-demonstrates-next-gen-pluggable-transceiver-ofc-2026)
- [SEC MRVL–LITE signed agreement](https://www.sec.gov/Archives/edgar/data/1835632/000119312526442717/d352474d8k.htm)
- [SEC 2026-11-02 merger Q&A analyst estimated DSP share 70%+ and merchant customer friction](https://www.sec.gov/Archives/edgar/data/1633978/000119312526443876/d178787d425.htm)
