# Healthcare Analysis
 Given Datasets provides information on Medicare beneficiaries, including demographic details, chronic conditions, and financial data related to claims

 # SummaryofInsights

ThedatasetconsistsoftwoprimaryfilesBeneficiarySummaryFileandInpatientClaims
File.GivenDatasetsprovidesinformationonMedicarebeneficiaries,includingdemographic
details,chronicconditions,andfinancialdatarelatedtoclaims.Byanalyzingandmergingthese
datasetswecanderivevaluableinsightsintotheUShealthcaresystem.

**BeneficiarySummaryFile** :ID,DateofBirth,Sex,Race,StateCode,DiseaseDetails.
**InpatientClaimsFile** :ID,Claim_ID,ClaimDates(start,end),ClaimAmount,Reimbursement
Amount.

**StepsandInsightsinAnalysis:**
● Cleaningdatabyremovingnullvalueswithmean
● UnderstandingAreasofanalysis(Asmentionedindescriptionpdf)
● Demographic(Age,Race)
● Disease(ChronicConditions)
● Financial(Claim,Reimbursement)
● FinancialclaimbyraceinTexas
● Visitsandclaim

**DemographicInsights:**
● Majorityofbeneficiariesareseniorcitizens,withsignificantnumbersaged75-85.

```
● Racialdistributionshowsthatmostbeneficiariesarewhite.
● Higherproportionofwhitebeneficiariescanbecorrelatedtotheregeneralhigher
population.Eg:White:60.1,Black:12.2,Hispanic:18.7,Other:9.2.
```

**ChronicConditionsInsights:**

```
● MostcommonchronicconditionsareDiabetes,HeartFailure,IschemicHeartDisease,
Alzheimer,Depressionetc.
● Chronicconditionsincreaseswithage,particularlyinthe75-84agegroup.
```
## ●


**FinancialInsights:**

```
● Theaverageclaimamountisapproximately$13,724.41,withatotalofabout$17.
billion.
● Theaveragereimbursementamountisapproximately$11,550.09,withatotalofabout
$14.6billion.
● Thereimbursementratiovariesbyrace,withpotentialdisparitiesindicatinginequitiesin
healthcarecostsandreimbursements.
```
```
● SuddendropinAverageClaimsAmountOverHistoricalPeriodcoincidewithGreat
Recessionof 2007 and 2008 whichcaused“LossofHealthInsurance”duetomajor
Layoffs
● Reducedhealthcarespendingduetoslowdownandpeopleignorednecessarymedical
careduetoconcernsaboutaffordability.
```

```
● Healthcarespending(claims)increaseovertimeindicateincreaseinutilizationof
facilities.
```
**HypothesisTesting** :

```
● NullHypothesis(H0H_0H0 ):Thereisnosignificantdifferenceinthereimbursement
ratiosbetweendifferentracialgroups.
● AlternativeHypothesis(H1H_1H1 ):Thereisasignificantdifferenceinthe
reimbursementratiosbetweendifferentracialgroups.
```
**StatisticalTest** :

```
● UseANOVA(AnalysisofVariance)totestfordifferencesinthemeanreimbursement
ratiosacrossmultipleracialgroups.
● IfANOVAshowssignificantdifferences,followupwithpost-hocteststodeterminewhich
groupsdifferfromeachother.
```
```
● TheF-statistic(0.587337)isrelativelylow,suggestingminimalvariationin
reimbursementratiosexplainedbyracialdifferences.
● Thep-value(0.623238)isgreaterthan0.05(commonlyusedsignificancelevel).This
indicatesthatwefailtorejectthenullhypothesis,whichisthatthere'snostatistically
significantdifferenceinreimbursementratiosbasedonrace.
● Thereisnosignificantdifferenceinthereimbursementratiosbetweendifferentracial
groups.
```

**VisitsandClaimInsights:**

```
● Patientswithchronicconditionsarelikelytohavemorefrequentvisitsandhighertotal
claimamountsduetoongoingmedicalneeds.
● Highvariabilityinclaimamountsandvisitscanindicatedifferencesinhealthcareneeds
andutilizationpatternsamongpatients.
```
```
ActionableInsights:
```
```
● Understandingthedistributionofclaimamountscanhelpinbudgetingand
forecastinghealthcarecosts.
● Identifyingpatientswithexceptionallyhighcostscaninformtargeted
interventionstomanagetheirhealthcareneedsmoreefficiently.
● UnderstandingtheracialdistributionofMedicarebeneficiariesinthecontextof
overallU.S.demographicsprovidesvaluableinsightsintohealthcareaccess,
utilization,anddisparities.
```
