Business Case Review: Riverty Consumer Card (Germany)
What the numbers imply
Funnel: 5% convert × 85% approved × 70% activate ≈ 3% of existing users end up with an active card.
Implied user base (my inference): 31,238 ÷ ~3% suggests roughly 1.05m existing German users. Finance should confirm.
Year 1 volume reconciles: 31,238 × EUR 4,000 ≈ EUR 125m.
Year 5 doesn’t fully reconcile. EUR 1.02bn ÷ 164,365 cards ≈ EUR 6,200 per card, below the EUR 7,000 cap. That could be a cohort-mix effect, but I can’t reproduce 164,365 cards from the stated assumptions alone (a single 5% conversion, 5% churn). Ask the model owner how card growth is generated after Year 1.
1. The three most fragile assumptions to test first

1. The 5% conversion (and 70% activation) of existing users.

Everything scales linearly from this, so halving it halves every downstream figure.
The brief says Lena knows Riverty but doesn’t prefer it and rarely seeks it out. Nothing in it shows existing users want a Riverty card.
It’s also the cheapest to test (waitlist or fake-door within the user base).

2. Spend per user: EUR 4,000 rising to EUR 7,000.

EUR 4,000 is about EUR 333 a month on a card Lena would be adding beside a debit card, Klarna and PayPal.
Reaching that, then growing 75%, requires Riverty to become a top-of-wallet habit. That is the least proven behaviour in the case.
“Active” also needs a definition. One transaction and EUR 333 a month are very different bars.

3. Volume is not revenue, and it may not be incremental.

The case shows card volume only. Revenue depends on interchange plus interest on revolving balances.
My understanding is that EU rules cap consumer card interchange very low (roughly 0.2% debit, 0.3% credit). Please verify with Finance. If so, EUR 125m of volume yields only a few hundred thousand euros of interchange, so the business case rests on revolving interest, credit losses and the pool already held by instalment card banks.
If card spend merely moves from Riverty checkout (where merchants pay fees) to the card, net revenue could fall and the merchant-first strategy takes a hit. This links the financial risk to the strategic one.
2. Three primary KPIs for the Friends & Family MVP

F&F users are not representative of the market, so this test validates operations and early behaviour, not the 5% conversion. Thresholds below are illustrative and should be set with Finance and Risk.

KPI	What it measures	Benchmark to test against
Activation rate: approved users who make a first transaction within 30 days	Whether the card gets used at all	Model assumes 70%
Repeat active use: share of activated users with 2+ transactions in the first 60 days, plus monthly spend per active user and the share of spend off-partner or in-store	Habit formation and whether the card fills the coverage gap	Annualised spend path toward EUR 4,000 (about EUR 333 a month)
Merchant incrementality: change in Riverty checkout volume at partner merchants among cardholders vs. a matched non-cardholder group	Whether the card adds volume or cannibalises it	No decline in partner checkout volume

Guardrail (not a headline KPI): early repayment and arrears behaviour, since interest income depends on it.

3. Product hypothesis

Based on the brief’s observations that Lena uses BNPL on most non-trivial purchases, prefers money to leave her account only after she has decided to keep the item, takes whichever provider appears at checkout, and cannot use Riverty at non-partner merchants or in stores,

we believe that giving her a Riverty card that carries this “decide first, pay later” behaviour to non-partner online shops and physical stores

will result in her using it repeatedly for purchases she would otherwise make with a debit card, Klarna or PayPal, without reducing her Riverty usage at partner merchants,

as measured by at least X% of activated cardholders making 2 or more off-partner or in-store transactions within 60 days (X to be calibrated with Finance and Risk), with no decline in partner-merchant checkout volume versus a matched control group.

What would make us change course: if activation or repeat use falls well short of the benchmarks, or if partner checkout volume drops, we narrow the proposition or pause before scaling rather than investing further.
