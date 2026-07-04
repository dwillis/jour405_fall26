# JOUR405: Suggested Final Project Ideas

These project ideas are drawn from successful student work in previous semesters. Each one uses publicly available data, can be completed with the statistical methods taught in class and produces findings with a clear journalistic angle.

You are not limited to these ideas! Use them as inspiration for the scope, complexity and structure of your own project.

---

## Politics & Policy

### Voter Registration Shifts After Major Political Events

Track how voter registration changes by party after elections, inaugurations or policy changes. Maryland's Board of Elections publishes monthly registration data by party and county. Pick a specific event and measure whether registration trends shifted meaningfully afterward.

**Data:** Maryland Board of Elections monthly registration reports (or your state's equivalent)
**Methods:** Percent change calculation, linear regression by party, trend comparison

### Population Growth as a Predictor of Partisan Shift

Do fast-growing counties vote more Democratic over time? Pick a state and compare county-level population change with presidential election margins across several cycles.

**Data:** U.S. Census population estimates, county-level presidential election returns (MIT Election Data + Science Lab)
**Methods:** Linear regression (margin vs. population), county-by-county comparison

### Do College Counties Vote Differently Than Their States?

Compare the Democratic margin in the county containing each state's largest university to the statewide margin. Test whether the gap is growing over time.

**Data:** County and state election results (2000-present), IPEDS enrollment data
**Methods:** Paired t-test, linear regression on margin gap over time

---

## Crime & Public Safety

### Comparing Per Capita Crime Rates Between Neighboring Jurisdictions

Pick two adjacent counties or cities with different demographics and compare crime rates over time using per capita normalization. Are the differences as dramatic as public perception suggests?

**Data:** Local police department or county crime data, U.S. Census population estimates
**Methods:** Per capita rate calculation, monthly/yearly aggregation, linear regression, z-scores

### Campus Crime Trends Before and After COVID

Using federal Clery Act data, compare burglary, assault or other crime categories at a group of peer universities before and after 2020. Did rates bounce back?

**Data:** U.S. Department of Education Campus Safety and Security Survey
**Methods:** Rate per 1,000 students, percent change, t-test (pre/post comparison)

---

## Sports

### Does Spending Predict Winning in College Athletics?

Test whether athletic department expenses correlate with performance rankings (like the Directors' Cup) across a conference or division.

**Data:** EADA (Equity in Athletics Disclosure Act) financial reports, Directors' Cup standings
**Methods:** Correlation analysis, linear regression, scatterplot visualization

### Do Super Bowl Champions See Higher Home Attendance?

Test the assumption that winning a championship boosts the following season's home attendance. Compare defending champions to the league average.

**Data:** NFL stadium attendance data (Pro Football Reference), Super Bowl winners list
**Methods:** T-test (champions vs. non-champions), percent change calculation

### Home Field Advantage Across College Football Conferences

Calculate home win percentages by team and conference over 10-20 years. Is home field advantage real, and does it vary by conference or stadium size?

**Data:** College football game results (Sports Reference), stadium capacity data
**Methods:** Win percentage calculation, grouping by conference, correlation with stadium size

---

## Culture & Entertainment

### Do Critics and Fans Agree on Award-Winning Films?

Compare Rotten Tomatoes critic scores with IMDb audience ratings for Oscar Best Picture winners. Has the gap between critics and fans changed over time?

**Data:** Rotten Tomatoes critic scores, IMDb user ratings, Oscar Best Picture winners list
**Methods:** Paired t-test, linear regression (gap over time), line chart visualization

### Billboard Chart Performance as a Predictor of Grammy Wins

Can a song's peak position or weeks on the Billboard Hot 100 predict whether it wins a Grammy? Test chart metrics against award outcomes.

**Data:** Billboard Hot 100 historical data, Grammy winners database
**Methods:** Spearman correlation, linear regression, decade-by-decade trend analysis

---

## Tips for Scoping Your Project

1. **Start with a yes/no question.** "Does X predict Y?" or "Did Z change after Event W?" encourages clarity.
2. **Find data before falling in love with a topic.** The good question is worthless without accessible data.
3. **Try to get data that is already tabular.** CSVs and structured databases save time compared to scraping or PDF extraction.
4. **A null finding is a finding.** If your hypothesis is wrong, that is a story.
5. **Keep your scope to one main question and a few follow-ups.** Projects that try to answer a lot of questions well usually answer none of them.
