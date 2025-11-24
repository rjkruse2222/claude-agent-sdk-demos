# Restaurant Sales Forecasting: Techniques for Accurate Predictions

Accurate sales forecasting is fundamental to restaurant profitability. It drives labor scheduling, inventory purchasing, cash flow planning, and strategic decisions. Forecast too low and you're understaffed with stockouts; forecast too high and you waste labor and inventory. Developing reliable forecasting techniques improves operational efficiency and financial performance.

This guide covers sales forecasting methods and best practices for restaurants.

## Table of Contents
- Why Sales Forecasting Matters
- Forecasting Fundamentals
- Forecasting Methods
- Building Your Forecast Model
- Improving Forecast Accuracy
- Using Forecasts Operationally
- Key Takeaways

## Why Sales Forecasting Matters

### Impact on Operations

**Labor Scheduling**: Biggest variable cost depends on forecast.
- Under-forecast: Short-staffed, poor service, overtime
- Over-forecast: Excess labor cost, idle staff

**Inventory Management**: Purchase based on expected sales.
- Under-forecast: Stockouts, lost sales, substitutions
- Over-forecast: Waste, spoilage, tied-up capital

**Prep Planning**: Kitchen prep based on anticipated volume.
- Misaligned prep = waste or scrambling

### Impact on Finance

**Cash Flow Planning**: Know when cash comes in.
- Anticipate high and low periods
- Plan for slow periods in advance

**Budgeting**: Annual budget built on forecasts.
- Realistic targets
- Appropriate expense planning

**Decision Making**: Strategic choices depend on projections.
- Staffing levels
- Equipment purchases
- Expansion plans

### Cost of Poor Forecasting

**Example of Under-Forecasting**:
- Forecast: $8,000 Friday night
- Actual: $10,000
- Short two servers
- Result: Long waits, complaints, smaller checks, overtime

**Example of Over-Forecasting**:
- Forecast: $10,000 Monday lunch
- Actual: $6,000
- Over-staffed by three
- Result: $300+ excess labor cost

## Forecasting Fundamentals

### What to Forecast

**Sales Revenue**: Total and by category.
- Food sales
- Beverage sales
- Other revenue

**Guest Count**: Number of customers.
- Useful for labor and prep
- Tied to check average for revenue

**By Daypart**: Breakfast, lunch, dinner.
- Different patterns and staffing needs
- May have different drivers

### Forecast Horizons

**Short-Term** (daily/weekly):
- Labor scheduling
- Daily prep
- Inventory ordering
- Most operational decisions

**Medium-Term** (monthly/quarterly):
- Budget planning
- Staffing levels
- Marketing planning
- Cash flow projection

**Long-Term** (annual+):
- Strategic planning
- Investment decisions
- Growth projections
- Financing needs

### Key Concepts

**Base Forecast**: Expected sales without adjustments.

**Adjustments**: Modifications for known factors.
- Weather
- Events
- Holidays
- Promotions

**Accuracy Measurement**: How close forecast to actual.
- Track and improve over time

## Forecasting Methods

### Historical Average Method

**How It Works**: Use historical data to predict future.

**Simple Average**:
- Same day last year
- Average of same day for multiple years

**Example**:
- November 15 last year: $5,200
- November 15 two years ago: $4,800
- Average: $5,000 forecast

**Pros**: Simple, easy to understand
**Cons**: Doesn't account for trends or changes

### Moving Average Method

**How It Works**: Average recent periods to smooth volatility.

**Example (4-Week Moving Average)**:
- Week 1 Monday: $4,200
- Week 2 Monday: $4,400
- Week 3 Monday: $4,100
- Week 4 Monday: $4,300
- Average: $4,250 forecast for next Monday

**Weighted Moving Average**: Recent weeks weighted more heavily.

**Pros**: Smooths out anomalies
**Cons**: Lags behind trends

### Trend Analysis

**How It Works**: Identify and project growth/decline patterns.

**Example**:
- Year 1 November: $85,000
- Year 2 November: $92,000
- Growth rate: 8.2%
- Year 3 November forecast: $99,500

**Considerations**:
- Linear vs. compound growth
- Sustainability of trends
- Market saturation

**Pros**: Captures growth trajectory
**Cons**: Assumes trends continue

### Same-Store Sales Comparison

**How It Works**: Compare to same period last year with growth adjustment.

**Example**:
- Last November 15: $5,200
- YTD growth rate: 5%
- Adjusted forecast: $5,460

**Pros**: Accounts for seasonality and growth
**Cons**: Assumes consistent patterns

### Regression Analysis

**How It Works**: Statistical relationship between variables.

**Example Variables**:
- Weather and sales correlation
- Local events and traffic
- Economic indicators

**Pros**: Can incorporate multiple factors
**Cons**: Requires statistical knowledge, data

### Causal Forecasting

**How It Works**: Identify factors that drive sales.

**Key Drivers**:
- Weather conditions
- Local events
- Day of week
- Season
- Economic conditions
- Competitive activity

**Build Model**: Estimate impact of each driver.

## Building Your Forecast Model

### Data Collection

**Historical Sales Data**: Foundation of forecasting.
- Daily sales by category
- Guest counts
- Daypart breakdown
- Minimum 1-2 years preferred

**External Data**:
- Weather history
- Event calendar
- Economic data
- Competitive openings/closings

### Identify Patterns

**Weekly Patterns**: Day-of-week variations.
- Typically: Friday/Saturday highest
- Monday/Tuesday often lowest
- Your pattern may differ

**Seasonal Patterns**: Time-of-year variations.
- Summer vs. winter
- Holiday periods
- Local events (sports, festivals)

**Daypart Patterns**: Within-day variations.
- Lunch vs. dinner split
- Brunch on weekends
- Late-night if applicable

### Build Base Forecast

**Start with Historical Base**:
- Same day last year
- OR moving average of recent weeks
- OR trend-adjusted historical

**Apply Growth/Decline Factor**:
- YTD performance vs. last year
- Known changes (menu, prices, hours)

### Add Adjustments

**Weather Adjustment**:
- Rain on Friday night: -15%
- Perfect patio weather: +10%
- Extreme cold: -20%
- Build adjustment factors from history

**Event Adjustment**:
- Major sporting event: +20%
- Concert at nearby venue: +15%
- Competing local festival: -10%

**Holiday Adjustment**:
- Mother's Day: +80%
- Valentine's Day: +100%
- Day after major holiday: -25%

**Promotion Adjustment**:
- New menu launch: +10%
- Marketing campaign: +5%
- Competitor promotion: -5%

### Sample Forecast Worksheet

```
DAILY SALES FORECAST
Date: Friday, November 15, 2024

Base Forecast (same day last year):     $8,500

Adjustments:
  Year-over-year growth (5%):            +$425
  Weather (rain expected):               -$670
  Local event (college football):        +$850
  Promotion (new seasonal menu):         +$400
                                        -------
Adjusted Forecast:                      $9,505

Rounded Forecast:                       $9,500

By Daypart:
  Lunch (20%):                          $1,900
  Dinner (80%):                         $7,600

By Category:
  Food (75%):                           $7,125
  Beverage (25%):                       $2,375
```

## Improving Forecast Accuracy

### Measuring Accuracy

**Forecast Error**: Actual - Forecast

**Percentage Error**: (Actual - Forecast) ÷ Forecast × 100

**Mean Absolute Percentage Error (MAPE)**:
Average of absolute percentage errors over time.

**Example**:
| Day | Forecast | Actual | Error | % Error |
|-----|----------|--------|-------|---------|
| Mon | $4,000 | $4,200 | $200 | 5.0% |
| Tue | $4,500 | $4,300 | -$200 | -4.4% |
| Wed | $5,000 | $5,100 | $100 | 2.0% |
| Thu | $5,500 | $5,200 | -$300 | -5.5% |
| MAPE: | | | | 4.2% |

**Target Accuracy**: MAPE under 5% is excellent; under 10% is good.

### Common Sources of Error

**Systematic Over-Forecasting**: Consistently too optimistic.
- Adjust base down
- Review growth assumptions
- Check for market changes

**Systematic Under-Forecasting**: Consistently too conservative.
- Adjust base up
- May be missing growth
- Opportunity cost (understaffing)

**High Volatility**: Large random errors.
- More adjustment factors needed
- Better data collection
- Shorter forecast horizon

### Improving Over Time

**Track Every Forecast**: Document predictions.

**Compare to Actual**: Calculate errors.

**Analyze Misses**: Why were we wrong?
- What didn't we anticipate?
- What factor was misjudged?
- What data would help?

**Refine Model**: Incorporate learnings.
- Adjust factors
- Add new variables
- Remove unhelpful factors

### Using Technology

**POS Data**: Historical sales readily available.
- Export reports
- Track patterns
- Identify trends

**Forecasting Features**: Many systems include forecasting.
- AI/machine learning models
- Pattern recognition
- Weather integration

**Spreadsheet Models**: Build your own.
- Customizable to your business
- Incorporates local knowledge
- Can be sophisticated

## Using Forecasts Operationally

### Labor Scheduling

**Staff to Forecast**: Match labor to expected volume.

**Sales-to-Labor Ratio**: Target for your operation.
- Example: $40 in sales per labor hour
- $8,000 forecast ÷ $40 = 200 labor hours

**By Position**: Distribute hours appropriately.
- Servers based on cover count
- Kitchen based on food sales
- Support staff as needed

### Inventory Purchasing

**Food Orders**: Based on forecasted food sales.

**Par Levels**: Adjusted for expected volume.
- Higher pars before busy periods
- Lower before slow periods

**Fresh Items**: Order based on short-term forecast.

### Prep Planning

**Prep Lists**: Tied to forecast.
- Proteins: Based on expected covers and mix
- Sauces and bases: Volume dependent
- Produce: Daily forecast guides

**Batch Sizing**: Appropriate to expected need.

### Communication

**Share Forecast**: Team should know expectations.
- Pre-shift meetings
- Posted schedules
- Volume expectations

**Update in Real-Time**: Adjust as information changes.
- Weather changes
- Reservations update
- Early day performance

## Key Takeaways

Accurate sales forecasting drives operational and financial success:

1. **Use historical data**: Past performance is best predictor.

2. **Identify patterns**: Day-of-week, seasonal, and daypart variations.

3. **Adjust for known factors**: Weather, events, holidays, promotions.

4. **Measure accuracy**: Track MAPE and improve over time.

5. **Learn from misses**: Analyze why forecasts were wrong.

6. **Use forecasts operationally**: Drive scheduling, purchasing, and prep.

7. **Leverage technology**: POS data and forecasting features help.

8. **Communicate forecasts**: Team alignment improves execution.

---

*Analyze your last 4 weeks of daily sales data. Identify your day-of-week pattern and any obvious adjustments. Build a simple forecast for next week and compare to actual results.*
