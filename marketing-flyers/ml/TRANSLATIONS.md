# Malayalam flyer translations

English → Malayalam text for every flyer in `ml/`, for proofreading.
"(unchanged)" means that text stays in English (brand, numbers, SIP/EMI and similar).

## Check these closely (busy backgrounds)

- `too-many-mutual-funds`: Small 'Same Stocks' label sits on the blue Venn lens inside the magnifier illustration; needed tight mask erase and a shorter translation to fit.
- `good-returns-healthy-portfolio`: dark gradient with glow; six-card grid; small labels over a sunset photo
- `portfolio-on-track`: Headline sits on a dark navy background with a blue glow gradient; needed a custom colour mask (white + bright blue glyphs) plus inpaint instead of a box fill.
- `life-changes-portfolio-evolve`: many small labels on photo cards, 6-column grid, and text on two tilted cards (drawn rotated)
- `ganesh-chaturthi`: text sits on a photo sky gradient with clouds; erased with a custom low-red-channel mask + inpaint
- `25k-per-month-25-yrs`: Many small rows with dotted leaders and right-aligned amounts on cards; bottom panel text over gradient/curve illustration.
- `autopilot`: Small labels on cockpit-photo screens (glow, gridlines) need inpainting on a photo background.
- `sip-volatility`: Photo background with palm leaf near the headline, plus many tiny UI labels inside the phone mock-up.
- `child-education-plan`: Milestone labels sit on a faded city/school photo; headline Malayalam much longer than English.
- `daily-sip-example`: Stat blocks next to a night-street photo (man + taxi), multi-colour lines in body and step panel, blue CTA button.
- `small-top-up-bigger-corpus`: Chart with many callouts, a rotated y-axis label, and bordered callout boxes.
- `small-daily-sip-wealth-habit`: Many small labels (calendar weekdays, 5 stat cards, chart legend/tooltip) on a light 3D illustration.
- `volatility-needs-balance`: 'Multi Asset Fund' overlapped the glowing shield border; border segments were rebuilt by cloning the clean segment above.

## 10k-per-month-22-lakhs

**Title:** ₹10,000 per Month = ₹22 Lakhs → പ്രതിമാസം ₹10,000 = ₹22 ലക്ഷം

| Where | English | Malayalam |
|---|---|---|
| tagline top centre y~247-273, ~24px Medium, white #FAFAFC, centred | Start Small. Stay Consistent. | ചെറുതായി തുടങ്ങൂ. സ്ഥിരത പുലർത്തൂ. |
| headline 2 lines y~355-505, ~70px Bold, white; '₹22 Lakhs' green #9AED5D, centred | ₹10,000 every month can grow to ₹22 Lakhs | എല്ലാ മാസവും ₹10,000 / ₹22 ലക്ഷം (green) വരെ വളരാം |
| subtitle y~539-564, ~24px Regular, grey #C6C7CA, centred | In 10 years, at an assumed 12% annual return | 10 വർഷത്തിൽ, 12% വാർഷിക റിട്ടേൺ കണക്കാക്കിയാൽ |
| chart point labels above value pills (x centres 777/533/319/119), ~24px SemiBold, white, centred | Year 10 / Year 7 / Year 4 / Year 1 | വർഷം 10 / വർഷം 7 / വർഷം 4 / വർഷം 1 |
| value pills | ₹22L / ₹12.1L / ₹6.1L / ₹1.3L | (unchanged) |
| legend y~1295-1313, x 316 and 572, ~22px Medium, white, left | Invested / Growth | നിക്ഷേപം / വളർച്ച |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Dark near-uniform background; text erased with inpaint using fixed bg colour.

## 25k-per-month-25-yrs

**Title:** ₹25k per Month in 25 Years → പ്രതിമാസം ₹25K, 25 വർഷത്തിൽ

| Where | English | Malayalam |
|---|---|---|
| headline 3 lines y~140-370, very large ExtraBold, black; '₹25K' and '25 Years' blue #065AE8, centred | What ₹25K a Month Can Build in 25 Years | പ്രതിമാസം ₹25K (blue) / 25 വർഷം (blue) കൊണ്ട് / എന്ത് നേടിത്തരും? |
| subtitle y~404-431, ~24px Medium, dark #1A222D, centred | See What It Can Help You Build | ഇതുകൊണ്ട് എന്തൊക്കെ നേടാമെന്ന് നോക്കൂ |
| left card label x219 y~512-528, ~19px SemiBold, dark, left | Total Invested | ആകെ നിക്ഷേപം |
| left card value | ₹75,00,000 | (unchanged) |
| right card label x597 y~512-528, ~19px SemiBold, dark, left | Potential Value | സാധ്യതയുള്ള മൂല്യം |
| right card value x597 y~551-576, ~30px Bold, green #118E4A, left | ₹4.74 Crore | ₹4.74 കോടി |
| section title between two short decorative lines y~661-679, ~22px in English; ML 20px Medium, dark, centred at x448. Inner ends of both lines trimmed symmetrically (bg rebuilt) to keep a 14px gap | Your Goals. Our Calculation. | നിങ്ങളുടെ ലക്ഷ്യം. ഞങ്ങളുടെ കണക്ക്. |
| goal rows x198, ~19px Medium, dark, left (8 rows) | Dream Car / World Travel / Child's Higher Education / Child's Wedding / Business Ambitions / Child's Future Home / Retirement / Financial Commitments | സ്വപ്ന കാർ / ലോക യാത്ര / കുട്ടിയുടെ ഉന്നത വിദ്യാഭ്യാസം / കുട്ടിയുടെ വിവാഹം / ബിസിനസ് സ്വപ്നങ്ങൾ / കുട്ടിയുടെ ഭാവി വീട് / റിട്ടയർമെന്റ് / സാമ്പത്തിക ബാധ്യതകൾ |
| goal amounts right-aligned at x~786, ~20px SemiBold, blue #1D5CB4 | ₹50 Lakhs / ₹30 Lakhs / ₹30 Lakhs / ₹25 Lakhs / ₹75 Lakhs / ₹1 Crore / ₹1 Crore / ₹65 Lakhs | ₹50 ലക്ഷം / ₹30 ലക്ഷം / ₹30 ലക്ഷം / ₹25 ലക്ഷം / ₹75 ലക്ഷം / ₹1 കോടി / ₹1 കോടി / ₹65 ലക്ഷം |
| bottom panel heading x96 y~1240-1330, 3 lines ~24px SemiBold; line1 black, lines 2-3 blue #1461BF, left | Small SIP Today / Big Possibilities Tomorrow | ഇന്ന് ചെറിയ SIP / നാളെ വലിയ / സാധ്യതകൾ |
| step labels under curve (x centres 250/406/573/739) y~1410-1445, ~15px Medium, grey #383F4C, centred, 2 lines | Start Early / Stay Consistent / Benefit from Compounding / Achieve Your Life Goals | നേരത്തെ തുടങ്ങൂ / സ്ഥിരത പുലർത്തൂ / കോമ്പൗണ്ടിംഗിന്റെ നേട്ടം / ജീവിത ലക്ഷ്യങ്ങൾ നേടൂ |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline area rebuilt with fill_gradient (median-based text mask left blue residue on the huge glyphs). Dotted leaders restored per row by copying the English leader pixels (rows ly-3..ly+3) from Malayalam label end +15px to x660 (where English leaders end); left of the original leader start, pixels come from a phase-matched shift. Section title decorative lines shortened at their inner ends by the same amount each side.

## autopilot

**Title:** Investments on Autopilot → ഓട്ടോപൈലറ്റിൽ നിക്ഷേപം

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~186-255, ~90px Bold, white, centred | Investments on | നിക്ഷേപങ്ങൾ |
| headline line 2 y~280-386, ~120px Bold, blue #007FFF, centred | Autopilot | ഓട്ടോപൈലറ്റിൽ |
| centre screen title x261 y~842-853, ~14px caps, light blue-white, left | SIP JOURNEY | SIP യാത്ര |
| centre screen checklist x555, 3 items x 2 lines, ~12px caps, light, left | DISCIPLINED INVESTING / EXPERT MANAGEMENT / LONG-TERM GROWTH | ചിട്ടയായ നിക്ഷേപം / വിദഗ്ധ മാനേജ്മെന്റ് / ദീർഘകാല വളർച്ച |
| left screen, centre x~125: small grey caption, blue line, white line | ALTITUDE / STEADY / FOCUS | ഉയരം / സ്ഥിരമായ / ശ്രദ്ധ |
| right screen, centre x~774: small grey caption, blue line, white line | HEADING / ON COURSE / TO WEALTH | ദിശ / ശരിയായ ദിശയിൽ / സമ്പത്തിലേക്ക് |
| bottom panel line 1 y~1340-1376, ~32px Bold, white, centred | Experts guide the journey. | വിദഗ്ധർ യാത്രയ്ക്ക് വഴികാട്ടുന്നു. |
| bottom panel line 2 y~1391-1429, ~32px Bold; 'SIP' and 'moving forward.' blue #017EF8, rest white, centred | Your SIP keeps moving forward. | നിങ്ങളുടെ SIP (blue) എന്നും മുന്നോട്ട് നീങ്ങും. (blue) |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Text masks use a fixed background colour on black areas (median-based mask missed the inside of large glyphs).

## child-education-plan

**Title:** Child Education Plan → കുട്ടികളുടെ വിദ്യാഭ്യാസ പ്ലാൻ

| Where | English | Malayalam |
|---|---|---|
| headline 2 lines y~239-397, ~80px Bold, navy #000A2A; 'rise' blue #006AE0, centred | Education costs rise every year | വിദ്യാഭ്യാസ ചെലവ് / വർഷാവർഷം കൂടുന്നു (blue) |
| big number | 8-10% | (unchanged) |
| between two short lines y~625-667, ~40px Medium, near-black, centred | annually | പ്രതിവർഷം |
| body 3 lines y~705-818, ~30px Medium, near-black; 'never limits' blue #0C65C6, centred | Start early, so money never limits your child's dreams. | നേരത്തെ തുടങ്ങൂ, / കുട്ടിയുടെ സ്വപ്നങ്ങൾക്ക് / പണം ഒരിക്കലും തടസ്സമാകില്ല. (last two words blue) |
| milestone labels on photo, ~17px, muted blue #3A659B, centred | School / Higher Education / Bright Future | സ്കൂൾ / ഉന്നത വിദ്യാഭ്യാസം / ശോഭനമായ ഭാവി |
| button line 1 x355 y~1384-1403, ~20px Medium, near-black, left | Build a | ഇപ്പോൾ തന്നെ ഒരുക്കൂ |
| button line 2 x355 y~1414-1438, ~27px Bold, blue #1068C7, left | Child Education Fund | കുട്ടിയുടെ വിദ്യാഭ്യാസ ഫണ്ട് |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline/annually/button areas rebuilt with fill_gradient; body and labels inpainted.

## connect-financial-expert

**Title:** Connect to a Financial Expert → സാമ്പത്തിക വിദഗ്ധനെ ബന്ധപ്പെടൂ

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~226-312, ~85px Medium, navy #092A64, centred | Let Your Money | പണം നിങ്ങൾക്കായി |
| headline line 2 y~321-390, ~85px Medium, blue #0A56C6, centred | Work For You | അധ്വാനിക്കട്ടെ |
| subtitle y~429-469, ~38px Regular, grey #3F444D, centred | Not The Other Way Around. | നിങ്ങൾ പണത്തിനു വേണ്ടിയല്ല. |
| body 2 lines y~1137-1200, ~26px Regular, grey #46494E, centred | Smart investing helps your savings grow with purpose. | ബുദ്ധിപൂർവമായ നിക്ഷേപം നിങ്ങളുടെ സമ്പാദ്യം / ലക്ഷ്യബോധത്തോടെ വളരാൻ സഹായിക്കുന്നു. |
| outlined button 2 lines y~1288-1368, ~32px Medium, blue #10439A, centred | Connect With Your Financial Expert Today | ഇന്നുതന്നെ നിങ്ങളുടെ / സാമ്പത്തിക വിദഗ്ധനെ ബന്ധപ്പെടൂ |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Plain light background.

## daily-sip-example

**Title:** SIP Builds Your Tomorrow → SIP നിങ്ങളുടെ നാളെ ഒരുക്കുന്നു

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~184-244, ~60px Bold, white, centred | Ramesh drives today, | രമേഷ് ഇന്ന് വണ്ടി ഓടിക്കുന്നു, |
| headline line 2 y~259-309, ~60px Bold, blue #0180FE, centred | SIP builds his tomorrow. | SIP അവന്റെ നാളെ ഒരുക്കുന്നു. |
| body 3 lines y~372-470, ~24px Regular, white; amounts blue, centred | Ramesh invests ₹1,000 every day from his cab earnings. In 5 years, it can grow to ₹17.2 lakhs* — a step closer to his dream car. | രമേഷ് ടാക്സി വരുമാനത്തിൽ നിന്ന് ദിവസേന ₹1,000 നിക്ഷേപിക്കുന്നു. / 5 വർഷത്തിൽ ഇത് ₹17.2 ലക്ഷം* വരെ വളരാം — / സ്വപ്ന കാറിലേക്ക് ഒരു ചുവട് കൂടി അടുത്ത്. |
| stat 1 label x174 y~546-571, ~24px, white, left | Daily Investment | ദിവസേനയുള്ള നിക്ഷേപം |
| stat 1 value | ₹1,000 | (unchanged) |
| stat 2 label x174 y~701-722, ~24px, white, left | Investment Duration | നിക്ഷേപ കാലാവധി |
| stat 2 value x174 y~740-771, ~38px Bold, blue #1080EF, left | 5 Years | 5 വർഷം |
| stat 3 label x174 y~843-867, ~24px, white, left | Estimated Value | കണക്കാക്കിയ മൂല്യം |
| stat 3 sub | @ 12% CAGR | (unchanged) |
| stat 3 value x174 y~923-954, ~38px Bold, green #1ED070, left | ₹17.2 Lakhs* | ₹17.2 ലക്ഷം* |
| step 1 (centre x139), ~20px Medium, white; '₹1,000' blue | Invest / ₹1,000 / Every Day | ദിവസേന / ₹1,000 (unchanged pixels) / നിക്ഷേപിക്കൂ |
| step 2 (centre x327), 2 lines; '5 Years' blue | Stay Invested for 5 Years | 5 വർഷം (blue) / നിക്ഷേപം തുടരൂ |
| step 3 (centre x536), 2 lines; 'Compounding' blue | Let Compounding Do the Work | കോമ്പൗണ്ടിംഗ് (blue) / ജോലി ചെയ്യട്ടെ |
| step 4 (centre x751), 2 lines; 'Big Goals' blue | Achieve Big Goals Stress-Free | വലിയ ലക്ഷ്യങ്ങൾ (blue) / ടെൻഷനില്ലാതെ നേടൂ |
| CTA blue filled button y~1393-1426, ~30px Bold, white, centred | Start Your Daily SIP Today | ദിവസേന SIP ഇന്നുതന്നെ തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: '₹1,000' in step 1 left as original pixels.

## direct-vs-regular-mf

**Title:** Direct MF vs Your Distributor → ഡയറക്ട് മ്യൂച്വൽ ഫണ്ട് vs MFD-യോടൊപ്പം

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~198-244, ~56px ExtraBold, white, centred | Direct Mutual Funds | ഡയറക്ട് മ്യൂച്വൽ ഫണ്ടുകൾ |
| blue 'vs' between rules, y~270-302 | vs | (unchanged) |
| headline line 2, y~324-372, ~54px ExtraBold, white, centred | With an MFD | MFD-യോടൊപ്പം |
| subtitle 2 lines y~405-475, ~26px Medium, grey #C8C8C8 with blue #3A83D3 highlight, centred | Choose between doing it all yourself or investing with expert guidance. | തിരഞ്ഞെടുക്കൂ: എല്ലാം സ്വയം ചെയ്യണോ, / അതോ [വിദഗ്ധ മാർഗനിർദേശത്തോടെ] നിക്ഷേപിക്കണോ? |
| left card title, y~687-750, ~30px ExtraBold, white, centred | Direct Mutual Funds | ഡയറക്ട് / മ്യൂച്വൽ ഫണ്ടുകൾ |
| right card title, y~687-755, ~30px ExtraBold, white + blue line 2, centred | With an MFD / Regular Plan | MFD-യോടൊപ്പം / [റെഗുലർ പ്ലാൻ] |
| left row 1, x~214, ~20px Medium, #EEEEEE, left | No personalised roadmap | വ്യക്തിഗത റോഡ്മാപ്പ് ഇല്ല |
| left row 2, same style | You manage research & paperwork | റിസർച്ചും പേപ്പർവർക്കും സ്വയം ചെയ്യണം |
| left row 3, same style | Market swings can feel overwhelming | വിപണിയിലെ ചാഞ്ചാട്ടം ആശങ്കയുണ്ടാക്കാം |
| right row 1, x~636, ~20px Medium, #EEEEEE, left | Goal-based investment guidance | ലക്ഷ്യാധിഷ്ഠിത നിക്ഷേപ മാർഗനിർദേശം |
| right row 2, same style | Research, transactions & paperwork support | റിസർച്ച്, ഇടപാടുകൾ, പേപ്പർവർക്ക് സഹായം |
| right row 3, same style | Regular reviews, rebalancing & updates | പതിവ് റിവ്യൂ, റീബാലൻസിംഗ്, അപ്ഡേറ്റുകൾ |
| centre badge | VS | (unchanged) |
| bottom panel, x~298, 2 lines ~26px Medium, white with blue highlights, left | A small fee for expert guidance can bring long-term peace of mind. | [വിദഗ്ധ മാർഗനിർദേശത്തിനുള്ള] ചെറിയ ഫീസ് / ദീർഘകാല [മനസ്സമാധാനം] നൽകും. |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey ~#7F7F7F, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Black background; headline erased with fixed-black mask (median mask left a blob inside thick letters). 'vs' and 'VS' kept English.

## diversify-mf

**Title:** Invest in Variety — Diversify with MF → വൈവിധ്യമാർന്ന നിക്ഷേപം, മ്യൂച്വൽ ഫണ്ടിലൂടെ

| Where | English | Malayalam |
|---|---|---|
| headline y~240-325, ~50px ExtraBold, navy #020A2C + blue #1060D5 highlight, centred, one line | Invest in Variety | [വൈവിധ്യമാർന്ന] നിക്ഷേപം |
| subtitle 3 lines y~355-490, ~28px Medium, #343546, centred | Mutual funds spread your money across assets, so you don't depend on just one. | മ്യൂച്വൽ ഫണ്ടുകൾ നിങ്ങളുടെ പണം / പല ആസ്തികളിലായി വിഭജിക്കുന്നു, അതിനാൽ / ഒന്നിനെ മാത്രം ആശ്രയിക്കേണ്ടതില്ല. |
| node label top, ~24px Bold navy, centred | Equity | ഇക്വിറ്റി |
| node label left | Global | ഗ്ലോബൽ |
| node label right | Debt | കടം |
| node label bottom-left | Cash | ക്യാഷ് |
| node label bottom-right | Gold | സ്വർണം |
| centre circle, 2 lines ~30px ExtraBold navy, centred | Mutual Funds | മ്യൂച്വൽ / ഫണ്ടുകൾ |
| pill button y~1345-1395, ~26px Bold, blue #1961C4, centred | Diversify with Mutual Funds | മ്യൂച്വൽ ഫണ്ടിലൂടെ വൈവിധ്യം നേടൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey ~#7F7F7F, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline rephrased to a noun phrase so it fits one line at a readable size; 'Invest in Variety' literal was ~1000px wide.

## dream-home-small-sip

**Title:** Dream Home — Small SIP → സ്വപ്ന ഭവനം — ചെറിയ SIP

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~228-271, ~54px ExtraBold white, centred | Your Dream Home | നിങ്ങളുടെ സ്വപ്ന ഭവനം |
| headline line 2 y~297-353, ~54px ExtraBold, blue #1273F4 highlight + white, centred | Starts with a Small Step | [ഒരു ചെറിയ ചുവടിൽ] തുടങ്ങുന്നു |
| subtitle 2 lines y~445-525, ~30px Medium grey #C6C7CC, centred | Plan today. Build your future home step by step. | ഇന്നേ പ്ലാൻ ചെയ്യൂ. നിങ്ങളുടെ ഭാവി വീട് / പടിപടിയായി പണിതുയർത്തൂ. |
| card 1 label ~22px SemiBold white, centred | Start SIP | SIP തുടങ്ങൂ |
| card 2 label 2 lines | Stay Invested | നിക്ഷേപം / തുടരൂ |
| card 3 label 2 lines | Dream Home | സ്വപ്ന / ഭവനം |
| outlined button y~1365-1392, ~28px Medium white, left of arrow | Start Goal-Based SIP | ലക്ഷ്യാധിഷ്ഠിത SIP തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey ~#7F7F7F, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Arrow icon in button untouched.

## early-child-future-plan

**Title:** Early Child Future Plan → കുട്ടിയുടെ ഭാവിക്കായി നേരത്തേ പ്ലാൻ

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~1024-1070, ~40px ExtraBold white + blue #1479E4 highlight, centred, over faded photo | Their Dreams Are Limitless | അവരുടെ സ്വപ്നങ്ങൾക്ക് [അതിരില്ല] |
| headline line 2 y~1096-1154, same style | Plan for Them Early | അവർക്കായി [നേരത്തേ] പ്ലാൻ ചെയ്യൂ |
| subtitle 2 lines y~1186-1256, ~24px Medium white, centred | Start building a child education fund today, so money never limits their future. | കുട്ടിയുടെ വിദ്യാഭ്യാസത്തിനായി ഇന്നുതന്നെ ഒരു ഫണ്ട് തുടങ്ങൂ, / പണം ഒരിക്കലും അവരുടെ ഭാവിക്ക് തടസ്സമാകാതിരിക്കട്ടെ. |
| pill button y~1348-1375, ~27px ExtraBold white, centred | Plan Your Child's Future | കുട്ടിയുടെ ഭാവി പ്ലാൻ ചെയ്യൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey ~#7F7F7F, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline line 1 sits over the faded bottom of the photo; inpainted cleanly.

## emi-vs-sip

**Title:** EMI vs SIP → EMI vs SIP

| Where | English | Malayalam |
|---|---|---|
| headline, top centre (y~170-245), very large bold, red EMI / navy vs / blue SIP | EMI vs SIP | (unchanged, kept in English) |
| subtitle line 1, centre y~330-365, ~32px Medium, near-black, centred | One locks your income. | ഒന്ന് നിങ്ങളുടെ വരുമാനം പൂട്ടിയിടുന്നു. |
| subtitle line 2, centre y~375-410, ~32px Medium, blue #133B96, centred | One builds your future. | മറ്റൊന്ന് നിങ്ങളുടെ ഭാവി പടുത്തുയർത്തുന്നു. |
| card titles, large bold red / blue, centred | EMI / SIP | (unchanged) |
| left card row 1, x~180, ~20px Medium, dark, left-aligned, 2 lines | Fixed monthly repayment | നിശ്ചിത പ്രതിമാസ തിരിച്ചടവ് |
| left card row 2, same style | Built around liability | ബാധ്യതയെ ആശ്രയിച്ചുള്ളത് |
| left card row 3, same style | Limits flexibility | വഴക്കം കുറയ്ക്കുന്നു |
| right card row 1, x~600, ~20px Medium, dark, left-aligned | Disciplined monthly investing | ചിട്ടയായ പ്രതിമാസ നിക്ഷേപം |
| right card row 2, same style | Built around long-term wealth | ദീർഘകാല സമ്പത്തിനെ ആശ്രയിച്ചുള്ളത് |
| right card row 3, same style | Gives you financial control | സാമ്പത്തിക നിയന്ത്രണം നിങ്ങളുടെ കയ്യിൽ |
| centre badge | VS | (unchanged) |
| outlined button y~1330-1375, ~30px SemiBold, blue #2B6BB9, centred | Start Your SIP Journey | നിങ്ങളുടെ SIP യാത്ര തുടങ്ങൂ |
| disclaimer, bottom y~1500-1545, ~17px Regular, grey #7E7F82, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

## equity-investment

**Title:** Equity Investment → ഇക്വിറ്റി നിക്ഷേപം

| Where | English | Malayalam |
|---|---|---|
| headline 2 lines y~232-368, ~50px ExtraBold, white + red #E63E48, centred | Equity Rewards Logic, Not Panic | ഇക്വിറ്റിയിൽ ജയിക്കുന്നത് / യുക്തിയാണ്, [പരിഭ്രാന്തിയല്ല] |
| subtitle 2 lines y~473-536, ~25px Medium, light grey #DADBDE with blue #618ACD highlights, centred | Let facts, discipline, and long-term equity performance guide your decisions. | [വസ്തുതകളും, അച്ചടക്കവും], [ദീർഘകാല] ഇക്വിറ്റി / പ്രകടനവും നിങ്ങളുടെ തീരുമാനങ്ങളെ നയിക്കട്ടെ. |
| outlined button y~1309-1341, ~30px Medium white, centred | Choose Equity With Confidence | ധൈര്യമായി ഇക്വിറ്റി തിരഞ്ഞെടുക്കൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey ~#7F7F7F, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Malayalam headline is longer, so 'യുക്തിയാണ്,' moved to line 2 before the red 'പരിഭ്രാന്തിയല്ല'.

## ganesh-chaturthi

**Title:** Ganesh Chaturthi → ഗണേശ ചതുർത്ഥി

| Where | English | Malayalam |
|---|---|---|
| headline 4 lines x=72, baselines 189/249/309/369, ~46px ExtraBold, navy #00021C (1-2) and blue #0C5AD4 (3-4), left | This Ganesh Chaturthi, start a SIP for your little Ganesh. | ഈ / ഗണേശ ചതുർത്ഥിയിൽ, / കുഞ്ഞു ഗണേശനായി / ഒരു SIP തുടങ്ങൂ. |
| blue short rule under headline |  | (unchanged) |
| para 1, x=72, ~20px Medium #282C38, left, pitch 30 | The biggest things we do for our children often begin very small. | നമ്മുടെ കുട്ടികൾക്കായി നമ്മൾ ചെയ്യുന്ന / വലിയ കാര്യങ്ങൾ പലപ്പോഴും ചെറുതായാണ് തുടങ്ങുന്നത്. |
| para 2, 4 lines, same style | Their first day of school. Their first lesson. Their first ₹1,000 invested for a dream that's still years away. | അവരുടെ ആദ്യ സ്കൂൾ ദിനം. / അവരുടെ ആദ്യ പാഠം. / വർഷങ്ങൾക്കപ്പുറമുള്ള ഒരു സ്വപ്നത്തിനായി / അവരുടെ ആദ്യ ₹1,000 നിക്ഷേപം. |
| para 3, 3 lines, same style, kept left of the child | We may not know today what they will want to become. But we can make sure we start preparing for it. | അവർ നാളെ എന്താകുമെന്ന് / ഇന്ന് നമുക്കറിയില്ല. പക്ഷേ അതിനായി / ഒരുക്കം തുടങ്ങാൻ നമുക്ക് കഴിയും. |
| para 4, 3 lines, same style | This Ganesh Chaturthi, on a day that celebrates auspicious beginnings, make one for their future too. | ശുഭാരംഭങ്ങൾ ആഘോഷിക്കുന്ന ഈ / ഗണേശ ചതുർത്ഥി ദിനത്തിൽ, അവരുടെ / ഭാവിക്കായും ഒരു തുടക്കം കുറിക്കൂ. |
| sign-off baseline 913, ~27px ExtraBold blue, left | Ganpati Bappa Morya. | ഗണപതി ബപ്പാ മോറിയ. |

Notes: No disclaimer in English, none added. Lines drawn at English baselines; paragraph widths limited to stay clear of the child and banana leaves.

## good-returns-healthy-portfolio

**Title:** Good Returns Are Great. Is Your Portfolio Healthy? → നല്ല റിട്ടേൺ മികച്ചതാണ്. നിങ്ങളുടെ പോർട്ട്ഫോളിയോ ആരോഗ്യകരമാണോ?

| Where | English | Malayalam |
|---|---|---|
| headline, top centre y~60-300, 4 lines, ~62px Bold white, line 4 blue #1687F6 | Good Returns / Are Great. / But Is Your Portfolio / Truly Healthy? | നല്ല റിട്ടേൺ / മികച്ചതാണ്. / പക്ഷേ നിങ്ങളുടെ പോർട്ട്ഫോളിയോ / ശരിക്കും ആരോഗ്യകരമാണോ? (ExtraBold, last line blue) |
| subtitle y~335-395, ~24px Regular light grey #D6D8E1, centred, 2 lines | A healthy portfolio is more than just good returns. It should be aligned with your goals, risk profile and future needs. | ആരോഗ്യകരമായ പോർട്ട്ഫോളിയോ എന്നാൽ നല്ല റിട്ടേൺ മാത്രമല്ല. / അത് നിങ്ങളുടെ ലക്ഷ്യങ്ങൾ, റിസ്ക് പ്രൊഫൈൽ, ഭാവി ആവശ്യങ്ങൾ എന്നിവയ്ക്ക് ചേരണം. |
| card grid 3x2, titles ~22px Bold white, desc ~18px Regular grey #C1C4CF, centred | Performance: How your investments have done | പ്രകടനം: നിക്ഷേപങ്ങളുടെ ഇതുവരെയുള്ള പ്രകടനം |
| card 2 | Risk: Are you taking the right level of risk? | റിസ്ക്: ശരിയായ അളവിലാണോ റിസ്ക് എടുക്കുന്നത്? |
| card 3 | Fund Overlap: Are multiple funds doing the same job? | ഫണ്ട് ഓവർലാപ്പ്: പല ഫണ്ടുകളും ഒരേ ജോലിയാണോ ചെയ്യുന്നത്? |
| card 4 | Asset Allocation: Is it well balanced across categories? | അസറ്റ് അലോക്കേഷൻ: എല്ലാ വിഭാഗങ്ങളിലും ശരിയായി സന്തുലിതമാണോ? |
| card 5 | Goal Alignment: Is it still suited to your current goals? | ലക്ഷ്യ പൊരുത്തം: ഇപ്പോഴത്തെ ലക്ഷ്യങ്ങൾക്ക് ഇപ്പോഴും യോജിച്ചതാണോ? |
| card 6 | Actionable Insights: Simple, clear recommendations | പ്രായോഗിക ഉപദേശം: ലളിതവും വ്യക്തവുമായ ശുപാർശകൾ |
| photo timeline labels, ~15px white, centred above milestones | Today / Short Term Goals / Child's Education / Retirement / Financial Freedom | ഇന്ന് / ഹ്രസ്വകാല ലക്ഷ്യങ്ങൾ / കുട്ടിയുടെ വിദ്യാഭ്യാസം / റിട്ടയർമെന്റ് / സാമ്പത്തിക സ്വാതന്ത്ര്യം |
| button y~1250-1316, ~30px Bold, line 1 white, line 2 blue #1E8CF0, centred | Get a complimentary / Portfolio Health Check. | സൗജന്യമായി നേടൂ / പോർട്ട്ഫോളിയോ ഹെൽത്ത് ചെക്ക്. |
| disclaimer, bottom y~1372-1412, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Subtitle drawn smaller than the English (~16px) so it stays on 2 lines; erased with fill_gradient/inpaint.

## inflation-top-up-sip

**Title:** Inflation Leads to Top-Up SIP → പണപ്പെരുപ്പം കൂടുമ്പോൾ ടോപ്പ്-അപ്പ് SIP

| Where | English | Malayalam |
|---|---|---|
| headline y~190-350, ~75px Bold white, 'rise' and 'SIP' blue #0B78F9, centred, 2 lines | As costs rise, / your SIP should too. | ചെലവുകൾ കൂടുമ്പോൾ, / നിങ്ങളുടെ SIP-യും കൂടണം. ('കൂടുമ്പോൾ,' and 'SIP' blue) |
| subtitle y~390-450, ~24px Regular light grey, centred, 2 lines | A Top-Up SIP gradually increases your investment so your future goals stay on track. | ടോപ്പ്-അപ്പ് SIP നിങ്ങളുടെ നിക്ഷേപം പടിപടിയായി കൂട്ടുന്നു, / അങ്ങനെ ഭാവി ലക്ഷ്യങ്ങൾ ശരിയായ വഴിയിൽ തുടരും. |
| tagline y~475-500, ~20px Regular grey #868690, centred | Stay ahead of inflation, one step at a time. | ഓരോ ചുവടിലും പണപ്പെരുപ്പത്തെക്കാൾ മുന്നിൽ നിൽക്കൂ. |
| chart label right y~620-670, left-aligned, line 1 blue, line 2 white | TOP-UP SIP / RISES WITH YOU | ടോപ്പ്-അപ്പ് SIP / കൂടെ ഉയരുന്നു |
| chart label right y~910-962, line 1 red #CC5D62, line 2 white | INFLATION / KEEPS RISING | പണപ്പെരുപ്പം / നിരന്തരം കൂടുന്നു |
| icon captions y~1250-1305, ~22px white, centred | Start with SIP / Increase a little each year / Keep goals realistic | SIP-ൽ തുടങ്ങൂ / ഓരോ വർഷവും അൽപം കൂട്ടൂ / പ്രായോഗിക ലക്ഷ്യങ്ങൾ വെക്കൂ |
| outlined button y~1385-1415, ~28px SemiBold white, centred | Stay Ahead with Top-Up SIP | ടോപ്പ്-അപ്പ് SIP-യുമായി മുന്നേറൂ |
| disclaimer, bottom y~1500-1548, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

## invest-with-confidence

**Title:** Invest with Confidence → ആത്മവിശ്വാസത്തോടെ നിക്ഷേപിക്കൂ

| Where | English | Malayalam |
|---|---|---|
| headline y~240-395, ~72px Bold, line 1 white, line 2 blue #5783D2, centred | A framework for / calmer investing | ഒരു ചട്ടക്കൂട്, / ശാന്തമായ നിക്ഷേപത്തിന് (line 2 blue) |
| subtitle y~415-485, ~24px Regular light grey, centred, 2 lines | Clear goals, steady reviews, tested strategies, and support through market swings. | വ്യക്തമായ ലക്ഷ്യങ്ങൾ, സ്ഥിരമായ അവലോകനം, / പരീക്ഷിച്ച തന്ത്രങ്ങൾ, ചാഞ്ചാട്ടങ്ങളിൽ പിന്തുണ. |
| 4 stacked cards, x~402, ~28px SemiBold white, left-aligned | Goal clarity / Regular updates / Tested strategies / Support in volatility | ലക്ഷ്യ വ്യക്തത / പതിവ് അപ്ഡേറ്റുകൾ / പരീക്ഷിച്ച തന്ത്രങ്ങൾ / ചാഞ്ചാട്ടത്തിലും കൂടെ |
| quote box y~1170-1245, ~26px Regular, centred, 2 lines | Financial progress begins with the right mindset and the right framework. | ശരിയായ മനോഭാവവും ശരിയായ ചട്ടക്കൂടും: / സാമ്പത്തിക പുരോഗതിയുടെ തുടക്കം. |
| outlined button y~1365-1395, ~28px SemiBold white, centred | Invest With Confidence | ആത്മവിശ്വാസത്തോടെ നിക്ഷേപിക്കൂ |
| disclaimer, bottom y~1500-1548, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline erased with a gradient fill applied only under the text mask (avoids a visible box over the top-left glow).

## life-changes-portfolio-evolve

**Title:** Life Changes. Your Portfolio Should Evolve Too. → ജീവിതം മാറുന്നു. പോർട്ട്ഫോളിയോയും മാറണം.

| Where | English | Malayalam |
|---|---|---|
| headline top-left x~77 y~85-280, ~70px Bold navy, line 3 blue, left-aligned | Life Changes. / Your Portfolio / Should Evolve Too. | ജീവിതം മാറുന്നു. / പോർട്ട്ഫോളിയോയും / മാറണം. (line 3 blue) |
| subtitle x~77 y~335-420, ~24px Regular grey #4A4B4F, left-aligned, 3 lines | A portfolio that worked a few years ago may no longer be aligned with your current goals and needs. | കുറച്ച് വർഷം മുമ്പ് നന്നായി ഫലം തന്ന / പോർട്ട്ഫോളിയോ ഇന്നത്തെ ലക്ഷ്യങ്ങൾക്കും / ആവശ്യങ്ങൾക്കും ചേരണമെന്നില്ല. |
| road milestone cards, ~14px SemiBold dark + grey sub, left-aligned | First Job (Savings) / Education (New Goals) / Marriage (Higher Responsibilities) / Home Purchase (Bigger Goals) / Wealth Creation (Long-Term) | ആദ്യ ജോലി (സമ്പാദ്യം) / വിദ്യാഭ്യാസം (പുതിയ ലക്ഷ്യങ്ങൾ) / വിവാഹം (കൂടുതൽ ഉത്തരവാദിത്തം) / വീട് വാങ്ങൽ (വലിയ ലക്ഷ്യങ്ങൾ) / സമ്പത്ത് സൃഷ്ടി (ദീർഘകാലം) |
| section header y~712-740, ~28px Bold navy, centred | A Portfolio Health Check Can Help You Review: | പോർട്ട്ഫോളിയോ ഹെൽത്ത് ചെക്കിലൂടെ ഇവ പരിശോധിക്കാം: |
| 6 columns, titles ~21px Bold navy, desc ~17px grey, centred | Performance: How your investments have done / Fund Overlap: Are multiple funds doing the same job? / Asset Allocation: Is it aligned with your goals? / Risk: Are you taking the right level of risk? / Goal Fit: Does it still suit your current life stage? / Actionable Insights: Simple, clear recommendations | പ്രകടനം: നിക്ഷേപങ്ങളുടെ ഇതുവരെയുള്ള പ്രകടനം / ഫണ്ട് ഓവർലാപ്പ്: പല ഫണ്ടുകൾ ഒരേ ജോലി ചെയ്യുന്നുണ്ടോ? / അസറ്റ് അലോക്കേഷൻ: നിങ്ങളുടെ ലക്ഷ്യങ്ങൾക്ക് ചേരുന്നുണ്ടോ? / റിസ്ക്: ശരിയായ അളവിലാണോ റിസ്ക് എടുക്കുന്നത്? / ലക്ഷ്യ പൊരുത്തം: ഇപ്പോഴത്തെ ജീവിതഘട്ടത്തിന് ചേരുന്നുണ്ടോ? / പ്രായോഗിക ഉപദേശം: ലളിതവും വ്യക്തവുമായ ശുപാർശകൾ |
| THEN card (tilted ~-5deg), header grey bold + items grey | THEN / 3 Funds / ₹5,000 SIP / Single Goal | അന്ന് / 3 ഫണ്ടുകൾ / ₹5,000 SIP (unchanged) / ഒറ്റ ലക്ഷ്യം |
| NOW card (tilted ~+4deg), header blue bold + items dark | NOW / 8+ Funds / Higher SIPs / Multiple Goals / New Responsibilities | ഇന്ന് / 8+ ഫണ്ടുകൾ / ഉയർന്ന SIP-കൾ / പല ലക്ഷ്യങ്ങൾ / പുതിയ കടമകൾ |
| CTA y~1330-1400, ~30px Bold, line 1 navy, line 2 blue, centred | It's time for a complimentary / Portfolio Health Check. | ഇതാണ് ശരിയായ സമയം, ഒരു സൗജന്യ / പോർട്ട്ഫോളിയോ ഹെൽത്ത് ചെക്കിന്. |
| disclaimer, bottom y~1450-1490, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Card/column text is smaller than English (13-15px) because Malayalam is much wider; 'New Responsibilities' shortened to പുതിയ കടമകൾ to stay inside the tilted card.

## multiple-dreams-one-sip

**Title:** Multiple Dreams, One SIP Plan → പല സ്വപ്നങ്ങൾ, ഒരു SIP പ്ലാൻ

| Where | English | Malayalam |
|---|---|---|
| headline y~275-440, ~80px Bold, line 1 navy #041B3C, line 2 blue #1466D6, centred | Multiple Dreams. / One SIP Plan. | പല സ്വപ്നങ്ങൾ. / ഒരു SIP പ്ലാൻ. (line 2 blue) |
| centre badge | ₹ SIP | (unchanged) |
| subtitle y~1185-1265, ~32px Regular navy, centred, 2 lines | Plan different goals with disciplined monthly investing. | ചിട്ടയായ പ്രതിമാസ നിക്ഷേപത്തിലൂടെ / വിവിധ ലക്ഷ്യങ്ങൾ പ്ലാൻ ചെയ്യൂ. |
| button text x~290 y~1357-1392, ~30px Bold blue #2065C1, left-aligned after icon | Start Goal-Based SIP Planning | ലക്ഷ്യാധിഷ്ഠിത SIP തുടങ്ങൂ |
| disclaimer, bottom y~1500-1548, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Button text shortened (no 'planning') to keep a readable size.

## mutual-fund-roadmap

**Title:** Mutual Fund Roadmap → മ്യൂച്വൽ ഫണ്ട് റോഡ്മാപ്പ്

| Where | English | Malayalam |
|---|---|---|
| headline y~165-300, ~60px Bold navy, 'Roadmap' and 'Life Goal' blue #0D59D1, centred, 2 lines | A Mutual Fund Roadmap / For Every Life Goal | മ്യൂച്വൽ ഫണ്ട് റോഡ്മാപ്പ് / ഓരോ ജീവിത ലക്ഷ്യത്തിനും ('റോഡ്മാപ്പ്', 'ജീവിത ലക്ഷ്യത്തിനും' blue) |
| subtitle y~335-360, ~24px Regular dark grey, centred | Match each goal with the right fund category. | ഓരോ ലക്ഷ്യത്തിനും ശരിയായ ഫണ്ട് വിഭാഗം തിരഞ്ഞെടുക്കൂ. |
| 5 roadmap cards, title ~22px Bold near-black, sub ~19px grey, left-aligned | Wealth Creation: Equity Funds / Child Education: Equity / Hybrid Funds / Buying a Home: Debt / Hybrid Funds / Tax Saving: ELSS Funds / Retirement Planning: Index / Equity Funds | സമ്പത്ത് സൃഷ്ടി: ഇക്വിറ്റി ഫണ്ട് / കുട്ടിയുടെ വിദ്യാഭ്യാസം: ഇക്വിറ്റി / ഹൈബ്രിഡ് ഫണ്ട് / വീട് വാങ്ങൽ: ഡെറ്റ് / ഹൈബ്രിഡ് ഫണ്ട് / നികുതി ലാഭം: ELSS ഫണ്ട് / റിട്ടയർമെന്റ് പ്ലാനിംഗ്: ഇൻഡക്സ് / ഇക്വിറ്റി ഫണ്ട് |
| step numbers | 01-05 | (unchanged) |
| pill y~1395-1420, ~24px Bold, navy + blue, left-aligned after icon | Plan smarter. Invest goal-wise. | സ്മാർട്ടായി പ്ലാൻ ചെയ്യൂ. / ലക്ഷ്യം നോക്കി നിക്ഷേപിക്കൂ. (2 lines, second blue) |
| disclaimer, bottom y~1500-1548, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Fund category subtitles use singular ഫണ്ട് to fit the cards; pill text split onto 2 lines.

## need-want-savings

**Title:** Need, Want, Savings → ആവശ്യം, ആഗ്രഹം, സമ്പാദ്യം

| Where | English | Malayalam |
|---|---|---|
| headline line 1, top centre y~150-225, ~70px ExtraBold, navy #08204E, centred | give every rupee | ഓരോ രൂപയ്ക്കും നൽകൂ |
| headline line 2, y~230-290, ~70px ExtraBold, 'a' navy + 'clear role.' blue #0D6BE7, centred | a clear role. | ഒരു (navy) വ്യക്തമായ ലക്ഷ്യം. (blue) |
| subtitle, y~320-377, ~24px Regular, grey #545B6D, centred, 2 lines | a simple 50/30/20 split for needs, wants and future goals. | ആവശ്യങ്ങൾ, ആഗ്രഹങ്ങൾ, ഭാവി ലക്ഷ്യങ്ങൾ — ഇവയ്ക്കായി ലളിതമായ ഒരു 50/30/20 വിഭജനം. |
| percentages 30% / 50% / 20% and donut centre '50/30/20' | 30% / 50% / 20% / 50/30/20 | (unchanged) |
| left label under 30%, x~67, ~24px Bold, blue #2169C8, left | wants | ആഗ്രഹങ്ങൾ |
| right label under 50%, right edge x~830, ~24px Bold, navy #122244, right-aligned | needs | ആവശ്യങ്ങൾ |
| left caption under bag icon, x~65 y~700-750, ~18px Regular, grey #3E4551, left, 2 lines | for the things you enjoy | ഇഷ്ടമുള്ള കാര്യങ്ങൾക്ക് |
| right caption under house icon, right edge x~830 y~750-792, ~18px Regular, grey, right-aligned, 2 lines | for your essentials | അത്യാവശ്യ കാര്യങ്ങൾക്ക് |
| label under 20%, x~82 y~898-952, ~25px Bold, green #418B66, left, 2 lines | savings & investments | സമ്പാദ്യവും നിക്ഷേപവും |
| caption under piggy icon, x~281 y~1007-1050, ~18px Regular, grey, left, 2 lines | for your future and financial goals | നിങ്ങളുടെ ഭാവിക്കും സാമ്പത്തിക ലക്ഷ്യങ്ങൾക്കും |
| donut centre small words above/below 50/30/20, ~18px Medium, dark | the / framework | 'the' removed (as in hi); ഫ്രെയിംവർക്ക് |
| card titles y~1192-1219, ~24px Bold, centred; navy / blue / green | needs / wants / savings | ആവശ്യങ്ങൾ / ആഗ്രഹങ്ങൾ / സമ്പാദ്യം |
| needs card list, x~148, 4 rows y~1262-1368, ~18px Regular, dark grey #3A3F4B, left (bullets kept) | rent / emi; utilities; groceries; insurance | വാടക / EMI; വൈദ്യുതി, വെള്ളം; പലചരക്ക്; ഇൻഷുറൻസ് |
| wants card list, x~393, same style | dining out; entertainment; hobbies; Shopping | പുറത്തെ ഭക്ഷണം; വിനോദം; ഹോബികൾ; ഷോപ്പിംഗ് |
| savings card list, x~635, same style | emergency fund; retirement; mutual funds; fixed deposits | എമർജൻസി ഫണ്ട്; റിട്ടയർമെന്റ്; മ്യൂച്വൽ ഫണ്ടുകൾ; സ്ഥിര നിക്ഷേപം |
| outlined pill button y~1425-1472, ~21px SemiBold, blue #2C61B2, text right of arrow icon | plan your money with clarity | പണം വ്യക്തമായി പ്ലാൻ ചെയ്യൂ |
| disclaimer y~1504-1546, ~19px Regular, grey #727377, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Many small text items; all on near-flat light backgrounds, inpaint is clean. 'fixed deposits' rendered as സ്ഥിര നിക്ഷേപം to fit the card.

## no-lumpsum-only-sip

**Title:** No Lumpsum, Only SIP → ഒറ്റത്തവണ നിക്ഷേപം വേണ്ട, SIP മതി

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~256-316, ~60px Bold, white #F8F8F8, centred | Skip the big investment. | വലിയ നിക്ഷേപം വേണ്ട. |
| headline line 2, y~341-389, ~60px Bold, white with 'SIP.' blue #075EE9, centred | Invest small with an SIP. | ചെറിയ തുകയിൽ SIP തുടങ്ങൂ. (SIP blue) |
| subtitle y~444-504, ~24px Regular, light grey #DEDEDF, centred, 2 lines | Start with what fits your budget and invest consistently over time. | നിങ്ങളുടെ ബജറ്റിന് ഒത്ത തുകയിൽ തുടങ്ങൂ, കാലക്രമേണ സ്ഥിരമായി നിക്ഷേപിക്കൂ. |
| label under money-bag, centre x~248 y~777-797, ~20px Medium, red #AE565D | Big Investment | വലിയ നിക്ഷേപം |
| caption under label, y~809-851, ~17px Regular, grey #AFAFB0, centred, 2 lines | High risk. Hard to time. Not always the best way. | കൂടുതൽ റിസ്ക്. സമയം നോക്കൽ പ്രയാസം. / എപ്പോഴും മികച്ച വഴിയല്ല. |
| three step labels under icons, y~1144-1163, ~18px Regular, light grey #DDDEDF, centred at x 145/398/607 | Start Small / Invest Regularly / Build Future Wealth | ചെറുതായി തുടങ്ങൂ / പതിവായി നിക്ഷേപിക്കൂ / ഭാവി സമ്പത്ത് വളർത്തൂ |
| outlined pill button y~1298-1390, ~34px Medium, white, centred | Start Your SIP Today | ഇന്നുതന്നെ നിങ്ങളുടെ SIP തുടങ്ങൂ |
| disclaimer y~1505-1547, ~19px Regular, grey #858586, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline line 2 reordered for Malayalam, so 'SIP' is re-rendered in the same blue. Flat black areas rebuilt with fill_gradient; text near the glowing curve inpainted.

## one-sip-5-strengths

**Title:** One SIP = 5 Strengths → ഒരു SIP = 5 കരുത്തുകൾ

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~167-231, ~75px Bold, white, centred | One SIP. | ഒരു SIP. |
| headline line 2, y~252-324, ~75px Bold, white + blue #1266EE full stop, centred | Five Strengths. | അഞ്ച് കരുത്തുകൾ. (full stop blue) |
| subtitle y~356-413, ~25px Regular, grey-blue #B9C1D0, centred, 2 lines | Why a Systematic Investment Plan remains a smart wealth-building habit. | സിസ്റ്റമാറ്റിക് ഇൻവെസ്റ്റ്മെന്റ് പ്ലാൻ എന്തുകൊണ്ട് സമ്പത്ത് വളർത്താനുള്ള മികച്ച ശീലമാകുന്നു. |
| card 1 (top centre) title ~24px SemiBold white / body ~19px Regular #D2D7E2, centred | Start Small / Begin with an amount that fits your budget | ചെറുതായി തുടങ്ങൂ / ബജറ്റിന് ഒത്ത തുകയിൽ ആരംഭിക്കാം |
| card 2 (right) title 2 lines / body 2 lines, centred x~736 | Stay Disciplined / Invest regularly with consistency | അച്ചടക്കം പാലിക്കൂ / പതിവായി, മുടങ്ങാതെ നിക്ഷേപിക്കൂ |
| card 3 (bottom right) title / body 3 lines, centred x~632 | Compounding / Let long-term growth build on itself | കോമ്പൗണ്ടിംഗ് / ദീർഘകാല വളർച്ച സ്വയം പെരുകട്ടെ |
| card 4 (bottom left) title / body 2 lines, centred x~258 | Diversify / Spread risk across multiple assets | വൈവിധ്യവൽക്കരണം / റിസ്ക് പല ആസ്തികളിൽ വീതിക്കൂ |
| card 5 (left) title / body 3 lines, centred x~154 | Expert Guidance / Make informed decisions with support | വിദഗ്ധ സഹായം / പിന്തുണയോടെ അറിവോടെ തീരുമാനമെടുക്കൂ |
| centre circle, 3 lines ~40px Bold white caps, centred | SYSTEMATIC INVESTMENT PLAN | സിസ്റ്റമാറ്റിക് ഇൻവെസ്റ്റ്മെന്റ് പ്ലാൻ |
| centre circle below divider, ~24px Medium blue #2A6CB9 | The Power of 5 | 5-ന്റെ കരുത്ത് |
| card numbers 1-5 in orange circles | 1 2 3 4 5 | (unchanged) |
| outlined pill button y~1355-1435, ~30px Medium white, centred | Start Your Child Education Plan Today | കുട്ടിയുടെ വിദ്യാഭ്യാസ പ്ലാൻ ഇന്നുതന്നെ തുടങ്ങൂ |
| disclaimer y~1505-1547, ~19px Regular, grey #82868D, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Big bold headline needed a fixed-bg mask (local-median mask misses thick strokes) plus a small gradient patch under the old 'g' descender. Card titles are a bit smaller than English because Malayalam bold is wide; 'Diversify' title shrinks most. CTA text (child education) is kept faithful to the English even though it doesn't match the flyer topic.

## one-sip-long-term-wealth

**Title:** One SIP — Long-Term Wealth → ഒരു SIP — ദീർഘകാല സമ്പത്ത്

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~211-266, ~62px Bold, navy #061740, centred | One SIP Habit. | ഒരു SIP ശീലം. |
| headline line 2, y~297-364, ~62px Bold, navy + 'Wealth.' blue #0A5FEE, centred | Long-Term Wealth. | ദീർഘകാല (navy) സമ്പത്ത്. (blue) |
| subtitle y~446-505, ~24px SemiBold, black, line 2 partly green #258540, centred | Plant small seeds of savings today, and watch a forest of wealth grow tomorrow | ഇന്ന് സമ്പാദ്യത്തിന്റെ ചെറുവിത്തുകൾ നടൂ, നാളെ (black) സമ്പത്തിന്റെ കാട് വളരുന്നത് കാണൂ (green) |
| 5 step labels under chart, y~1002-1070, ~21px SemiBold, dark navy #11162E (last green #217A3A), centred at x 100/260/420/587/746, 2 lines | Start SIP / Invest Monthly / Stay Consistent / Compounding Works / Financial Freedom | SIP തുടങ്ങൂ / മാസംതോറും നിക്ഷേപിക്കൂ / സ്ഥിരത നിലനിർത്തൂ / കോമ്പൗണ്ടിംഗ് ഫലം തരും / സാമ്പത്തിക സ്വാതന്ത്ര്യം |
| line inside icon panel y~1255-1278, ~22px Medium, dark #1B1B1B + blue #2257B7 second sentence, centred | Good habits grow over time. SIPs work the same way. | നല്ല ശീലങ്ങൾ കാലത്തിനൊപ്പം വളരും. (dark) SIP-യും അങ്ങനെ തന്നെ. (blue) |
| outlined pill button y~1340-1425, ~32px Medium, blue #2E71C8, centred | Start Your SIP Habit | നിങ്ങളുടെ SIP ശീലം തുടങ്ങൂ |
| disclaimer y~1505-1545, ~19px Regular, grey #78797B, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Image is 853x1600. Headline erased with fill_gradient (inpaint left faint streaks on the smooth gradient). 'Start SIP' label set on the same baseline as the other step labels (English sat slightly lower).

## plan-financial-goal-now

**Title:** Plan Financial Goals Now → സാമ്പത്തിക ലക്ഷ്യങ്ങൾ ഇപ്പോൾ പ്ലാൻ ചെയ്യൂ

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~245-305, ~62px Medium, blue #0E46AC, centred | Building wealth? | സമ്പത്ത് വളർത്തണോ? |
| headline line 2, y~330-392, same style | Creating regular income? | സ്ഥിര വരുമാനം വേണോ? |
| headline line 3, y~412-472, same style | Protecting capital? | മൂലധനം സംരക്ഷിക്കണോ? |
| subtitle y~518-574, ~26px Regular, grey #4A505F, centred, 2 lines | We help you invest around your goals with clarity and confidence. | നിങ്ങളുടെ ലക്ഷ്യങ്ങൾക്കനുസരിച്ച് നിക്ഷേപിക്കാൻ / വ്യക്തതയോടെ, ആത്മവിശ്വാസത്തോടെ ഞങ്ങൾ സഹായിക്കും. |
| left pill x~140 y~895-942, ~20px Regular, dark #26293D, left, 2 lines | Wealth creation | സമ്പത്ത് വളർത്തൽ |
| right pill x~728 y~895-942, same style | Regular income | സ്ഥിര വരുമാനം |
| bottom pill x~425 y~1165-1215, same style | Capital protection | മൂലധന സംരക്ഷണം |
| outlined pill button y~1295-1378, text y~1320-1355, ~32px Medium, blue #2F71C9, centred | Plan Your Financial Goal Now | സാമ്പത്തിക ലക്ഷ്യം ഇപ്പോൾ പ്ലാൻ ചെയ്യൂ |
| disclaimer y~1504-1544, ~19px Regular, grey #797979, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline/subtitle/disclaimer erased with fill_gradient on the near-white background; pill and button text inpainted. Subtitle is ~21px (smaller than English) to keep 2 lines.

## portfolio-on-track

**Title:** Is Your Mutual Fund Portfolio on Track? → നിങ്ങളുടെ മ്യൂച്വൽ ഫണ്ട് പോർട്ട്ഫോളിയോ ട്രാക്കിലാണോ?

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~96-155, ~62px Bold, white, centred | Is Your Mutual Fund | നിങ്ങളുടെ മ്യൂച്വൽ ഫണ്ട് |
| headline line 2, y~176-231, ~62px Bold, 'Portfolio' blue #0664F4 + white rest, centred | Portfolio on Track? | പോർട്ട്ഫോളിയോ (blue) ട്രാക്കിലാണോ? (white) |
| subtitle y~287-350, ~25px Regular, light grey #D1D6E3, centred, 2 lines | A quick review can help you understand how well your investments are working together. | ഒരു ചെറിയ റിവ്യൂവിലൂടെ നിങ്ങളുടെ നിക്ഷേപങ്ങൾ ഒരുമിച്ച് എത്ര നന്നായി പ്രവർത്തിക്കുന്നു എന്ന് മനസ്സിലാക്കാം. |
| grid row 1 (cells centred x 190/437/688), title y~896-916 ~20px SemiBold white, body 2 lines ~18px Regular grey | Performance / How your funds have done; Fund Overlap / Are multiple funds owning the same stocks?; Diversification / Is your portfolio well balanced? | പ്രകടനം / നിങ്ങളുടെ ഫണ്ടുകൾ എങ്ങനെ പ്രവർത്തിച്ചു; ഫണ്ട് ഓവർലാപ്പ് / പല ഫണ്ടുകളിലും ഒരേ ഓഹരികളാണോ?; വൈവിധ്യവൽക്കരണം / പോർട്ട്ഫോളിയോ സന്തുലിതമാണോ? |
| grid row 2, title y~1102-1122, body 2 lines, same style | Risk / Is it aligned with your risk profile?; Goal Alignment / Is it still suited to your goals?; Actionable Insights / Simple, clear recommendations | റിസ്ക് / റിസ്ക് പ്രൊഫൈലിന് യോജിച്ചതാണോ?; ലക്ഷ്യവുമായി ചേർച്ച / ഇപ്പോഴും ലക്ഷ്യങ്ങൾക്ക് യോജിച്ചതാണോ?; പ്രായോഗിക നിർദേശം / ലളിതവും വ്യക്തവുമായ ശുപാർശകൾ |
| outlined pill button, text left-aligned x~275 y~1259-1313, ~28px SemiBold white, 2 lines, arrow icon at right kept | Get a Complimentary Portfolio Health Check | സൗജന്യ പോർട്ട്ഫോളിയോ / ഹെൽത്ത് ചെക്ക് നേടൂ |
| disclaimer y~1386-1429, ~19px Regular, grey #B1B4BD, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Image is 873x1458. Headline rendered at ~42px so the longer Malayalam fits the original width.

## retirement-sip

**Title:** Retirement SIP → റിട്ടയർമെന്റ് SIP

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~219-290, ~78px Bold, white, centred | ₹10,000/month SIP | ₹10,000/മാസം SIP |
| headline line 2, y~315-371, ~70px Bold, white + green ₹3 Crore, centred | Can Grow to ₹3 Crore | ₹3 കോടി വരെ വളരാം |
| subtitle 2 lines y~467-527, ~26px SemiBold, white, 'secure retirement.' green, centred | 30 years of steady investing transforms regular savings into a secure retirement. | 30 വർഷത്തെ മുടങ്ങാത്ത നിക്ഷേപം, ചെറിയ സമ്പാദ്യങ്ങളെ സുരക്ഷിതമായ റിട്ടയർമെന്റ് ആക്കി മാറ്റുന്നു. |
| chart label right, centre x~746 y~599-618, ~22px Medium, white | Future You | ഭാവിയിലെ നിങ്ങൾ |
| chart label right, y~639-668, ~32px Bold, green | ₹3 Crore | ₹3 കോടി |
| chart label right, y~684-708, ~21px Regular, white | in 30 years* | 30 വർഷത്തിൽ* |
| chart label middle, centre x~432 y~733-758, ~23px Medium, white | Stay Invested | നിക്ഷേപം തുടരൂ |
| chart label middle, 2 lines y~773-824, ~21px Regular, white | Let compounding do the work | കോമ്പൗണ്ടിംഗ് അതിന്റെ ജോലി ചെയ്യട്ടെ |
| chart label left, centre x~147 y~781-805, ~22px Medium, white | Start Today | ഇന്ന് തുടങ്ങൂ |
| chart label left, y~821-847, blue | ₹10,000 | (unchanged) |
| chart label left, y~858-881, ~21px Regular, white | every month | എല്ലാ മാസവും |
| between divider lines y~1175-1197, ~24px Medium, light blue label + blue amount | Total Invested: ₹36 Lakh | ആകെ നിക്ഷേപം: ₹36 ലക്ഷം |
| outlined pill button y~1297-1330, ~34px Regular, white, centred | Plan Your Retirement via SIP | SIP വഴി റിട്ടയർമെന്റ് പ്ലാൻ ചെയ്യൂ |
| fine print y~1397-1418, ~20px Regular, light grey, centred | Assuming 12% annualised return. For illustration only. | 12% വാർഷിക റിട്ടേൺ കണക്കാക്കി. ഉദാഹരണത്തിന് മാത്രം. |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Dark navy gradient; erased with low-threshold inpaint. ₹10,000 under 'Start Today' kept as original pixels. 'Total Invested' line shrinks to 21px to stay between the divider lines.

## self-care-routine

**Title:** Self Care Routine → സെൽഫ്-കെയർ ദിനചര്യ

| Where | English | Malayalam |
|---|---|---|
| headline y~227-280, ~66px SemiBold, white + blue 'Habit', centred | Add One More Habit | ഒരു ശീലം കൂടി ചേർക്കൂ |
| sub-headline y~311-360, ~48px Light, white, centred | To your self-care routine | സെൽഫ്-കെയർ ദിനചര്യയിലേക്ക് |
| card heading y~529-556, ~27px SemiBold, white, centred | Already part of your routine | ഇതിനകം നിങ്ങളുടെ ദിനചര്യയിൽ |
| card row 1, x=382, ~24px Regular, near-white, left | Skincare | സ്കിൻകെയർ |
| card row 2, same style | Fitness | ഫിറ്റ്നസ് |
| card row 3, same style | Mindfulness | മൈൻഡ്ഫുൾനസ് |
| card row 4, same style | Learning | പഠനം |
| card row 5, same style | Passion projects | ഇഷ്ട പ്രോജക്റ്റുകൾ |
| label above button y~1041-1063, ~27px SemiBold, white, centred | Now add | ഇനി ചേർക്കൂ |
| glowing button, x~403-632 y~1120-1182, ~70px SemiBold, white->light-blue gradient | Investing | നിക്ഷേപം |
| outlined pill y~1349-1374, ~25px Regular, near-white, centred | Take charge of your financial wellness today | സാമ്പത്തിക ആരോഗ്യം ഇന്നുതന്നെ ശ്രദ്ധിക്കൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: 'Investing' redrawn with the same horizontal white-to-blue gradient.

## sip-volatility

**Title:** Beat the Heat — SIP Volatility → ചൂടിനെ തോൽപ്പിക്കൂ, ചാഞ്ചാട്ടത്തിലും പതറാതെ നിൽക്കൂ

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~158-197, ~50px Bold, dark + orange 'Heat.', centred | Beat the Heat. | ചൂടിനെ തോൽപ്പിക്കൂ. |
| headline line 2 y~219-269, ~50px Bold, dark + blue 'Volatility.', centred | Stay steady through Volatility. | ചാഞ്ചാട്ടത്തിലും പതറാതെ നിൽക്കൂ. |
| subtitle line 1 y~343-366, ~24px Regular, dark navy, centred | Summer needs cooling. Markets need discipline. | വേനലിന് തണുപ്പ് വേണം. വിപണിക്ക് അച്ചടക്കം വേണം. |
| subtitle line 2 y~379-402, ~24px Regular, dark navy + blue 'SIP', centred | A SIP helps you stay consistent through ups and downs. | SIP ഉയർച്ച താഴ്ചകളിലും സ്ഥിരത നൽകുന്നു. |
| phone: title x~531 y~537-555, ~20px Bold, navy, left | SIP Active | SIP സജീവം |
| phone: subtitle y~570-583, ~13px Regular, grey, left | Stay invested. Stay confident. | നിക്ഷേപം തുടരൂ. ആത്മവിശ്വാസത്തോടെ. |
| phone card title y~638-673, ~34px Bold, blue, left | SIP Journey | SIP യാത്ര |
| phone card text 2 lines y~687-723, ~13px Regular, grey, left | Small steps today, stronger tomorrow. | ഇന്ന് ചെറിയ ചുവടുകൾ, നാളെ കരുത്തുറ്റ ഭാവി. |
| phone icon label 1, 2 lines ~11px, grey, centred | Disciplined Investing | ചിട്ടയായ നിക്ഷേപം |
| phone icon label 2 | Rupee Cost Averaging | റുപ്പീ കോസ്റ്റ് ആവറേജിംഗ് |
| phone icon label 3 | Wealth Creation | സമ്പത്ത് സൃഷ്ടിക്കൽ |
| phone chart title y~959-967, ~12px SemiBold, navy, left | Market Movement | വിപണിയുടെ നീക്കം |
| phone chart caption 2 lines y~1047-1071, ~11px Regular, grey, left | Ups and downs are normal. Your discipline makes the difference. | ഉയർച്ച താഴ്ചകൾ സ്വാഭാവികം. നിങ്ങളുടെ അച്ചടക്കമാണ് മാറ്റമുണ്ടാക്കുന്നത്. |
| left column title y~1209-1236, ~30px Bold, orange + navy, centred x~221 | HEAT Relief | ചൂടിന് ആശ്വാസം |
| right column title, ~30px Bold, blue + navy, centred x~647 | VOLATILITY Relief | ചാഞ്ചാട്ടത്തിന് ആശ്വാസം |
| left column body 2 lines y~1282-1337, ~22px Regular, navy, centred | Cool down with simple habits. | ലളിതമായ ശീലങ്ങളിലൂടെ തണുപ്പ് നേടൂ. |
| right column body 2 lines, same style | Stay invested with SIP discipline. | SIP അച്ചടക്കത്തോടെ നിക്ഷേപം തുടരൂ. |
| outlined button y~1410-1438, ~28px Medium, blue, centred | Start Your SIP Today | ഇന്നുതന്നെ SIP തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline line 2 is 40px (line 1 45px) to fit the width. Phone labels are 10-13px, as small as the English.

## small-daily-sip-wealth-habit

**Title:** Small Daily SIP = Big Wealth Habit → ദിവസേന ചെറിയ SIP = വലിയ സമ്പാദ്യ ശീലം

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~181-254, ~74px Bold, navy 'Small' + blue 'Daily SIP.', centred | Small Daily SIP. | ദിവസേന ചെറിയ SIP. |
| headline line 2 y~271-344, ~74px Bold, navy 'Big' + blue 'Wealth Habit.', centred | Big Wealth Habit. | വലിയ സമ്പാദ്യ ശീലം. |
| subtitle 2 lines y~388-450, ~27px Regular, near-black, centred | A little invested every day can grow into something meaningful over time. | ദിവസവും നിക്ഷേപിക്കുന്ന ചെറിയ തുക കാലക്രമേണ വലിയ നേട്ടമായി വളരും. |
| calendar header 2 lines y~531-568, ~19px Medium, white on blue, centred | Consistency Today, Wealth Tomorrow | ഇന്ന് സ്ഥിരത, നാളെ സമ്പത്ത് |
| calendar weekdays y~591-600, ~10px Bold, dark grey, centred per column | MON TUE WED THU FRI SAT SUN | തിങ്കൾ ചൊവ്വ ബുധൻ വ്യാഴം വെള്ളി ശനി ഞായർ |
| stat card 1 label / value (~14px Medium dark / ~18px SemiBold blue) | Daily SIP / ₹100/day | ദിവസേന SIP / ₹100/ദിവസം |
| stat card 2 | Market Days / 22 days/month | വിപണി ദിനങ്ങൾ / 22 ദിവസം/മാസം |
| stat card 3 | Time Period / 12 years | കാലയളവ് / 12 വർഷം |
| stat card 4 | Total Invested / ₹3.17 Lakhs | ആകെ നിക്ഷേപം / ₹3.17 ലക്ഷം |
| stat card 5 (green value) | Potential Value / ₹8.48 Lakhs | സാധ്യതാ മൂല്യം / ₹8.48 ലക്ഷം |
| chart legend y~1070-1082, ~16px Medium, dark, left | Total Invested Over Time | കാലക്രമേണ ആകെ നിക്ഷേപം |
| chart tooltip (white on blue) 2 lines | ₹3.17 Lakhs / Total Invested | ₹3.17 ലക്ഷം / ആകെ നിക്ഷേപം |
| chart y-axis labels ₹10L..₹0 and x-axis numbers | ₹10L ₹7.5L ₹5L ₹2.5L ₹0 / 0..12 | (unchanged) |
| x-axis title y~1272-1282, ~13px, grey | Years | വർഷം |
| tagline next to leaf icon y~1338-1356, ~21px Regular, dark, left, between faint dividers | Consistency is where compounding begins. | സ്ഥിരതയിലാണ് കോമ്പൗണ്ടിംഗ് തുടങ്ങുന്നത്. |
| solid blue button y~1423-1450, ~30px SemiBold, white, centred | Start Your Daily SIP | ദിവസേന SIP തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: 'Wealth Habit' is rendered as സമ്പാദ്യ ശീലം (the usual Malayalam phrase), because 'സമ്പത്തിന്റെ ശീലം' reads unnaturally. Weekday labels and two card labels are ~10-12px, as small as the English.

## small-top-up-bigger-corpus

**Title:** Small Top-Up = Bigger Future Corpus → ചെറിയ ടോപ്പ്-അപ്പ് = ഭാവിയിൽ വലിയ സമ്പാദ്യം

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~171-229, ~58px Bold, navy, centred | Small Top-Ups. | ചെറിയ ടോപ്പ്-അപ്പുകൾ. |
| headline line 2 y~248-304, ~58px Bold, blue, centred | Bigger Future Corpus. | ഭാവിയിൽ വലിയ സമ്പാദ്യം. |
| subtitle 2 lines y~345-400, ~23px Regular, dark, centred | Increase your SIP gradually every year and let compounding work harder over time. | എല്ലാ വർഷവും SIP പതിയെ കൂട്ടൂ, കോമ്പൗണ്ടിംഗ് കൂടുതൽ ഫലം നൽകട്ടെ. |
| left card title y~540-564, ~24px SemiBold, navy, centred | Regular SIP | റെഗുലർ SIP |
| right card title, ~24px SemiBold, blue, centred | SIP Top-Up | SIP ടോപ്പ്-അപ്പ് |
| left card rows x=196, ~20px Regular / last Bold | ₹20,000/month · 15 years · ~₹1 Crore | ₹20,000/മാസം · 15 വർഷം · ~₹1 കോടി |
| right card rows x=529, ~18px Regular; last ~28px Bold green | ₹20,000/month · + 10% increase every year · 15 years · ~₹1.74 Crore | ₹20,000/മാസം · + ഓരോ വർഷവും 10% വർധന · 15 വർഷം · ~₹1.74 കോടി |
| chart legend x=246, ~19px Regular, dark, left | SIP Top-Up / Regular SIP | SIP ടോപ്പ്-അപ്പ് / റെഗുലർ SIP |
| y-axis tick labels, x-axis numbers | 2 Cr 1.5 Cr 1 Cr 50L 0 / 0 5 10 15 | (unchanged) |
| callout box top-right: green Bold value + small grey | ~₹1.74 Cr / with Top-Up | ~₹1.74 കോടി / ടോപ്പ്-അപ്പോടെ |
| green annotation by arrow, ~74% kept, then 2 lines ~17px SemiBold green, left | ~74% higher corpus | ~74% (unchanged) കൂടുതൽ സമ്പാദ്യം |
| callout box lower-right: dark Bold value + small grey | ~₹1 Cr / without Top-Up | ~₹1 കോടി / ടോപ്പ്-അപ്പില്ലാതെ |
| x-axis title y~1246-1263, ~18px Regular, grey-navy, centred | Time (Years) | സമയം (വർഷം) |
| rotated y-axis title x~23-42 y~943-1119, ~18px, reads bottom-to-top | Potential Corpus (₹) | സാധ്യതാ സമ്പാദ്യം (₹) |
| solid blue button y~1380-1408, ~28px SemiBold, white, centred | Enable SIP Top-Up | SIP ടോപ്പ്-അപ്പ് തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Callout values use കോടി to follow the Crore glossary; the axis tick labels (Cr/L) stay in English, as the Hindi version does.

## start-automated-sip

**Title:** Start an Automated SIP → ഓട്ടോമേറ്റഡ് SIP തുടങ്ങൂ

| Where | English | Malayalam |
|---|---|---|
| headline line 1 y~250-321, ~95px Medium, white | Automate | നിങ്ങളുടെ SIP (SIP blue) |
| headline line 2 y~354-426, ~95px Medium, white + blue 'SIP' | Your SIP | ഓട്ടോമേറ്റ് ചെയ്യൂ |
| subtitle line 1 y~471-505, ~31px Medium, white, centred | Set it once. Stay consistent. | ഒരിക്കൽ സെറ്റ് ചെയ്യൂ. സ്ഥിരമായി തുടരൂ. |
| subtitle line 2 y~517-550, same | Let your goals keep moving. | നിങ്ങളുടെ ലക്ഷ്യങ്ങൾ മുന്നോട്ട് നീങ്ങട്ടെ. |
| grey body 2 lines y~633-690, ~23px Light, grey-blue, centred | A disciplined SIP can keep working in the background while you focus on life. | നിങ്ങൾ ജീവിതം ആസ്വദിക്കുമ്പോൾ, ചിട്ടയായ SIP പിന്നണിയിൽ പ്രവർത്തിച്ചുകൊണ്ടിരിക്കും. |
| step label under left circle, centre x~190 y~1093-1111, ~21px Regular, white | 1. Set SIP | 1. SIP സെറ്റ് ചെയ്യൂ |
| step label under middle circle, centre x~447 y~1230-1247 | 2. Auto Invest | 2. ഓട്ടോ നിക്ഷേപം |
| step label under right circle, centre x~710 y~1093-1111 | 3. Reach Goals | 3. ലക്ഷ്യങ്ങളിലെത്തൂ |
| outlined pill button y~1362-1386, ~28px Medium, white, centred | Start Automated SIP | ഓട്ടോമേറ്റഡ് SIP തുടങ്ങൂ |
| disclaimer, bottom y~1500-1550, ~17px Regular, grey, centred, 2 lines | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Headline word order is changed to fit Malayalam (Your SIP / Automate), as the Hindi version does. The radial glow behind the headline was rebuilt with fill_gradient, which avoids inpaint blotches.

## start-early-child-education

**Title:** Start Early — Child Education Plan → നേരത്തെ തുടങ്ങൂ — കുട്ടിയുടെ വിദ്യാഭ്യാസ പ്ലാൻ

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~205-270, ~58px Bold, white, centred | Start early, step it up, and | നേരത്തെ തുടങ്ങൂ, പതിയെ കൂട്ടൂ, |
| headline line 2, y~285-350, ~58px Bold, blue #3087FC highlight + white, centred | build your child's tomorrow. | കുട്ടിയുടെ നാളെ (blue) പടുത്തുയർത്തൂ. (white) |
| subtitle 2 lines y~415-495, ~29px Medium, white, centred | A small SIP today builds a massive degree fund tomorrow. | ഇന്നത്തെ ഒരു ചെറിയ SIP നാളെ / വലിയൊരു പഠന ഫണ്ടായി മാറും. |
| card 1/2/3 top line x=388, y~600/828/1057, ~24px Medium, white with blue age, left | If you start at age 3 / 8 / 13 | 3 / 8 / 13 വയസ്സിൽ (blue) തുടങ്ങിയാൽ |
| card amounts | ₹8,500 / ₹18,500 / ₹50,000 | (unchanged) |
| card bottom line x=390, ~24px Medium, white, left | / month | / മാസം |
| note beside shield icon, 2 lines y~1255-1315, ~24px Medium, white, centred between side rules | Starting earlier reduces the monthly investment needed. | നേരത്തെ തുടങ്ങിയാൽ ഓരോ മാസവും / വേണ്ട നിക്ഷേപം കുറയും. |
| outlined button y~1340-1420, ~27px SemiBold, white, centred | Start Your Child Education Plan Today | കുട്ടിയുടെ വിദ്യാഭ്യാസ പ്ലാൻ ഇന്നുതന്നെ തുടങ്ങൂ |
| disclaimer, bottom 2 lines, ~18px Medium, grey #87868C, centred | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: English source is en/start-early-child-education-v2.jpg. Dark smooth background; inpaint removed text cleanly.

## start-early-example

**Title:** Start Early — With Example → നേരത്തെ തുടങ്ങൂ — ഒരു ഉദാഹരണം

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~230-320, ~76px Bold, navy #0A307D, centred | Start Early. | നേരത്തെ തുടങ്ങൂ. |
| headline line 2, y~335-420, ~76px Bold, FIRE red #E23D1E + navy, centred | Reach FIRE Faster. | FIRE (red) വേഗത്തിൽ നേടൂ. (navy) |
| subtitle y~470-510, ~27px Medium, slate #374255, centred | Financial Independence And Retiring Early | സാമ്പത്തിക സ്വാതന്ത്ര്യം, നേരത്തെ റിട്ടയർമെന്റ് |
| table header names, ~31px Bold, navy, centred in columns | Aarav / Vihaan | ആരവ് / വിഹാൻ |
| table row labels x=167, ~23px Medium, slate, left, 1-2 lines | Monthly SIP / Started At Age / Retirement Age / Estimated Corpus | പ്രതിമാസ SIP / തുടങ്ങിയ പ്രായം / റിട്ടയർമെന്റ് പ്രായം / കണക്കാക്കിയ സമ്പാദ്യം |
| table values ₹20,000, 25, 30, 60 | (numbers) | (unchanged) |
| corpus cells, original ₹ number glyphs kept and re-centred, unit ~29px SemiBold navy | ₹12.99 Cr / ₹7.05 Cr | ₹12.99 കോടി / ₹7.05 കോടി |
| bottom headline 2 lines y~1210-1310, ~33px SemiBold, navy, centred | A Five-Year Head Start Can Build Much More Wealth. | അഞ്ച് വർഷം നേരത്തെ തുടങ്ങിയാൽ / ഏറെ കൂടുതൽ സമ്പത്ത് നേടാം. |
| outlined button y~1337-1410, ~28px SemiBold, navy, centred | Start Your FIRE Journey Today | FIRE യാത്ര ഇന്നുതന്നെ തുടങ്ങൂ |
| disclaimer, bottom 2 lines, ~18px Medium, grey #878889, centred | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Light paper-texture background; headline erased with a wide low-threshold mask to avoid ghosting. Names transliterated as in hi.

## timely-portfolio-review

**Title:** Timely Portfolio Review → കൃത്യസമയത്തുള്ള പോർട്ട്ഫോളിയോ റിവ്യൂ

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~215-292, ~60px Bold, blue #347FF7, centred | Timely | കൃത്യസമയത്തുള്ള |
| headline line 2, ~54px Bold, white, centred | portfolio reviews | പോർട്ട്ഫോളിയോ റിവ്യൂ |
| headline line 3, ~54px Bold, white, centred | catch underperformance | മോശം പ്രകടനം |
| headline line 4, ~58px Bold, blue + white, centred | early. | നേരത്തെ (blue) കണ്ടെത്തും. (white) |
| subtitle 2 lines y~560-630, ~25px Medium, light grey #C6CBD7, centred | Regular reviews help you spot weak performers before they affect long-term goals. | പതിവ് റിവ്യൂകളിലൂടെ മോശം ഫണ്ടുകളെ ദീർഘകാല / ലക്ഷ്യങ്ങളെ ബാധിക്കും മുമ്പേ തിരിച്ചറിയാം. |
| tagline y~1258-1295, ~26px Medium, white with blue word, centred | Review early. Stay on track. | നേരത്തെ (blue) റിവ്യൂ ചെയ്യൂ. ശരിയായ വഴിയിൽ തുടരൂ. |
| outlined button y~1340-1420, ~26px SemiBold, white, centred | Review your portfolio on time | പോർട്ട്ഫോളിയോ സമയത്ത് റിവ്യൂ ചെയ്യൂ |
| disclaimer, bottom 2 lines, ~18px Medium, grey #8A909A, centred | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Dark background with faint grid; inpaint clean. Illustration untouched.

## too-many-mutual-funds

**Title:** Do You Have Too Many Mutual Funds? → നിങ്ങൾക്ക് ഒരുപാട് മ്യൂച്വൽ ഫണ്ടുകൾ ഉണ്ടോ?

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~90-155, ~60px Bold, navy #081234, centred | Do you have | നിങ്ങൾക്ക് ഒരുപാട് |
| headline line 2, y~162-230, ~60px Bold, blue #1464D7 + navy, centred | too many mutual funds? | മ്യൂച്വൽ ഫണ്ടുകൾ (blue) ഉണ്ടോ? (navy) |
| subtitle 2 lines y~275-345, ~27px Medium, grey #52555F, centred | Different funds can often own many of the same stocks. | പല ഫണ്ടുകളിലും പലപ്പോഴും / ഒരേ ഓഹരികൾ തന്നെയായിരിക്കും. |
| fund cards (Large Cap Fund, Flexi Cap Fund, ...) | fund category labels | (unchanged, kept English as in hi) |
| Venn centre in magnifier (438,645), ~20px SemiBold, white, centred, 2 lines | Same Stocks | ഒരേ / ഓഹരി |
| column 1 title + body (x 72-293), title ~22px Bold navy, body ~20px Medium grey, centred | Hidden Overlap / Different funds, same stocks | ഒളിഞ്ഞ ഓവർലാപ്പ് / പല ഫണ്ടുകൾ, ഒരേ ഓഹരികൾ |
| column 2 (x 318-560), same style | Over-Concentration / More risk than you realise | അമിത കേന്ദ്രീകരണം / നിങ്ങൾ കരുതുന്നതിലും കൂടുതൽ റിസ്ക് |
| column 3 (x 588-805), 2-line title + 2-line body | Actual Diversification / Are you truly diversified? | യഥാർത്ഥ വൈവിധ്യവൽക്കരണം / നിക്ഷേപം ശരിക്കും വൈവിധ്യമുള്ളതാണോ? |
| closing line 1, y~1210-1252, ~32px Bold, navy, centred | Find out with a | ഇപ്പോൾ തന്നെ കണ്ടെത്തൂ, |
| closing line 2, y~1257-1302, ~28px Bold, blue, centred | complimentary Portfolio Health Check. | സൗജന്യ പോർട്ട്ഫോളിയോ ഹെൽത്ത് ചെക്കിലൂടെ. |
| disclaimer, bottom 2 lines, ~18px Medium, grey #7D7F83, centred | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: Image is 873x1458. Column 3 title shrinks to ~18px to fit 'വൈവിധ്യവൽക്കരണം'.

## volatility-needs-balance

**Title:** Volatility Needs Balance → ചാഞ്ചാട്ടത്തിന് വേണം ബാലൻസ്

| Where | English | Malayalam |
|---|---|---|
| headline line 1, y~195-282, ~64px Bold, white, centred | Volatility Needs | ചാഞ്ചാട്ടത്തിന് വേണം |
| headline line 2, y~292-395, ~92px ExtraBold, blue #0C64EB (flat; English has slight gradient), centred | Balance. | ബാലൻസ്. |
| subtitle 3 lines y~415-530, ~24px Medium, light grey #CDD0D8, centred | Multi Asset Funds spread your money across asset classes, helping smooth the ride when markets turn uncertain. | മൾട്ടി അസറ്റ് ഫണ്ടുകൾ നിങ്ങളുടെ പണം പല / ആസ്തികളിലായി വീതിക്കുന്നു; വിപണി ആടിയുലയുമ്പോഴും / യാത്ര സുഗമമാക്കുന്നു. |
| 4 asset cards, bottom label ~25px SemiBold, white, centred | Equity / Debt / Gold / Cash | ഇക്വിറ്റി / കടം / ഗോൾഡ് / ക്യാഷ് |
| shield centre, 2 lines ~21px Bold, white, centred | Multi Asset Fund | മൾട്ടി അസറ്റ് / ഫണ്ട് |
| tagline y~1270-1305, ~26px Medium, white with blue word, centred | Different assets. Better balance. Less stress. | വ്യത്യസ്ത ആസ്തികൾ. മികച്ച ബാലൻസ് (blue). കുറഞ്ഞ ടെൻഷൻ. |
| outlined button y~1355-1435, ~22px SemiBold, white, centred | Choose Multi Asset Funds for Long-Term Stability | ദീർഘകാല സ്ഥിരതയ്ക്ക് മൾട്ടി അസറ്റ് ഫണ്ടുകൾ തിരഞ്ഞെടുക്കൂ |
| disclaimer, bottom 2 lines, ~18px Medium, grey #87878A, centred | Mutual fund investments are subject to market risks, read all scheme related documents carefully. | മ്യൂച്വൽ ഫണ്ട് നിക്ഷേപങ്ങൾ വിപണിയിലെ നഷ്ടസാധ്യതകൾക്ക് വിധേയമാണ്, സ്കീമുമായി ബന്ധപ്പെട്ട എല്ലാ രേഖകളും ശ്രദ്ധാപൂർവം വായിക്കുക. |

Notes: White text erased with a lightness mask so blue lines/borders survive. Shield label is smaller than English to stay inside the shield.
