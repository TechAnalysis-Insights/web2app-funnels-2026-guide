# Web2App Funnels 2026: Apple's Commission Rules by Country, Condensed

A web2app funnel moves the purchase decision from the App Store listing to a web page the publisher controls: quiz, paywall, checkout, then a deep link into the app. This doc is the reference version - the numbers and the rule changes, no narrative.

## What the funnel actually is

| Stage | What happens | What to check |
|---|---|---|
| Ad or post | Campaign promise brings the person to a web page | Does the page repeat the ad's promise? |
| Quiz | Visitor answers questions about goals/preferences | Do answers shape the offer, or just add steps? |
| Paywall | Plan and price shown, often with a trial/discount | Which price and trial length convert best? |
| Checkout | Card or wallet payment taken | How many start checkout and drop off? |
| App handoff | Deep link/login opens the app, subscription active | Does the account match across web and app with no extra step? |

## Commission by market (linked-out digital purchases)

| Market | Fee today | Status |
|---|---|---|
| United States | 0% | Court-ordered (contempt ruling, 30 Apr 2025); Apple has proposed 15% standard / 10% partner & renewal / 5% Small Business Program, still to be decided |
| Japan | 15%, or 10% for qualifying developers and renewal-year subscriptions | Announced by Apple, 17 Dec 2025 |

The US timeline: a 30 Apr 2025 district court order found Apple in contempt and barred any commission on external purchases. Apple had been charging 27% before that. On 11 Dec 2025 the Ninth Circuit upheld the contempt finding but also ruled the blanket zero-commission order overbroad - Apple may charge a commission tied to costs that are "genuinely and reasonably necessary," with the rate still to be set by the district court. On 13 Aug 2026, per MacDailyNews, Justice Kagan denied Apple's request to stay that process, so the lower court can keep setting a rate while the Supreme Court considers the case starting its October term. Apple has charged 0% on US link-out purchases since the contempt ruling and has proposed 15% / 10% / 5% depending on app type - proposals Epic says it will contest.


## Fee comparison on $100 of revenue

| Route | Commission | Revenue kept (before processor fees, tax, refunds) |
|---|---|---|
| In-app purchase, standard rate | $30 | $70 |
| In-app purchase, Small Business Program | $15 | $85 |
| US web checkout, link-out, current order | $0 | $100 |
| US web checkout, if Apple's 15% proposal is adopted | $15 | $85 |
| Japan web checkout, link-out | $15 ($10 for qualifying cases) | $85 ($90) |

## Adoption data (RevenueCat, State of Subscription Apps 2026; 115,000+ apps, $16B revenue)
- Web revenue = 3.2% of total subscription revenue globally, 4.9% in North America, 0.8% in India/Southeast Asia.

- - 41% of apps in the top revenue tier report some web revenue, vs. 1.3% in the lowest tier.
  - - An estimated two-thirds of total web revenue comes from the United States.
   
    - ## Risks that sit on the other side of the fee savings
    - - **Payments and refunds move to the publisher.** Japan's rules explicitly state Apple won't refund website-link purchases - chargebacks, failed payments, and refund support all become the publisher's job. Taxes (sales tax/VAT) also shift to the publisher or its payment provider.
      - - **Discovery gap.** Users who find the app via App Store search never see the web funnel; teams that pour energy into paid web traffic can neglect the store listing that still converts organic search.
        - - **Attribution fragmentation.** Tracking differs depending on the mobile measurement partner used, and whether web and app data share a customer identity. Done well, a web funnel improves attribution; done loosely, it fragments it.
         
          - ## When it's worth building one
         
          - The gap is largest for apps above the Small Business Program's $1M threshold that spend heavily on paid acquisition - standard-rate apps have the most commission to recover. For Small Business Program apps the saving is smaller already, and could disappear entirely if Apple's 15% US proposal is adopted. Category matters too: quiz-driven personalization works well for fitness, language learning, and wellness, where the user's stated goal shapes the offer; a one-tap utility app or one that mostly acquires through store search has less to gain.
         
          - Source, methodology, and the full discussion of risk and timing: [Varmeta's full writeup on web2app funnels](https://www.var-meta.com/blog/web2app-funnels?utm_source=github&utm_medium=backlink&utm_campaign=web2app-funnels).
          - 
