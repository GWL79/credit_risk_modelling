# credit_risk_modelling

capital requirement -> require bank to hold enough capital that would allow them to absorb losses from defaults

3 pillars of basel II accord:
 - minimum capital requirement
 - supervisory review
 - market discipline
risk - credit risk, operational risk, market risk


credit risk ->  standardised approach/ internal ratings based approach
Standardised approach
- provided by external personnel

Internal ratings based approach
- Foundation Internal Ratings Based approach (F-!RB)
- Advanced Internal Ratings Based approach (A-IRB)

risk based pricing - estimate credit risk

Expected (credit) loss: amount a lender might lose by lending to a borrower
    - Probability of default * Loss given default * Exposure at default

PD: likelihood a borrower would default
LGD: propotion of total exposure that cannot be recovered by lender once default occured
EAD: total value a lender is exposed to when borrower defaults (maximum lender lose if borrower default)

Example:
house cost: 500,000
bank funds 80% of the cost (loan to value)
loan to value = 500,000 * 80% = 400,000
if borrower defaults after paying 40,000, then EAD = 400,000 - 40,000 = 360,000

likelihood that 25% of borrower defaults, PD = 0.25

If borrower defaults, bank can sell house immediately at 342,000, remaining loss = 360,000 - 342,000 = 18,000
Since the bank couldnt recover remaining 18,000, LGD = 18,000/360,000 = 5%

expected loss = 0.25 * 0.05 * 360,000 = 4,500


Capital adequacy: