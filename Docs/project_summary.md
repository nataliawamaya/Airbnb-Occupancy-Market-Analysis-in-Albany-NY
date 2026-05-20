## Problem statement

This project analyzes Airbnb listing data to understand what factors are associated with higher estimated occupancy. The goal is to identify which listing characteristics, host attributes, neighborhoods, and amenities are linked to stronger booking performance. These insights can help Airbnb hosts and potential investors understand what may contribute to higher demand in this market.

## Key insights

**1.** Occupancy is highly uneven across listings. The mean occupancy is much higher than the median, suggesting that a smaller group of high-performing listings receives much more demand than the typical listing.

**2.** Superhost status showed one of the strongest relationships with occupancy. Superhost listings had an average occupancy of about 113.69 days compared with 49.65 days for non-superhost listings. The median difference was even larger, with superhosts at 96 days and non-superhosts at 12 days. The Welch’s t-test confirmed that this difference was statistically significant.

**3.** Neighborhood also matters, but it does not fully explain performance. The Fourteenth, Fifteenth, and Second Wards had the highest median occupancy. The Second Ward was especially interesting, because it had strong occupancy and the highest median reviews per month despite having a lower superhost rate than other top-performing wards. This suggests that location-based demand may be especially strong there.

**4.** Property type alone does not explain occupancy differences. Entire-place listings dominate the market and appear in both high- and low-performing neighborhoods. This suggests that simply being an entire-place listing is not enough to explain stronger occupancy.

**5.** Amenity analysis showed that certain listing-level features are associated with higher median occupancy. View or water access had the largest median gap, but only 33 listings had this feature, so that finding should be interpreted carefully. Family-friendly amenities and self check-in also showed strong positive gaps, with self check-in being especially meaningful because it had a larger sample size.

## Recommendations

**1.** Hosts should prioritize becoming or maintaining superhost-level service standards. Superhost status is strongly associated with higher occupancy, so hosts should focus on responsiveness, reliability, cleanliness, accurate listings, and strong guest experiences.

**2.** Hosts should consider adding practical convenience amenities, especially self check-in. Self check-in showed a large positive median occupancy gap and is more realistic for many hosts to add compared with location-based features like water access.

**3.** Family-friendly features may be a valuable opportunity. Listings with family-friendly amenities had higher median occupancy, suggesting that hosts may benefit from serving guests traveling with children.

**4.** Investors should evaluate neighborhood demand carefully. The Fourteenth, Fifteenth, and Second Wards showed stronger typical occupancy, but each area should still be evaluated at the listing level because performance varies within neighborhoods.

**5** Hosts should not rely on property type alone. Since entire-place listings dominate both high- and low-occupancy neighborhoods, success likely depends on a combination of location, host quality, amenities, and overall listing management.

## Limitations

- This analysis shows association, not causation. For example, superhost status is associated with higher occupancy, but the analysis does not prove that superhost status directly causes higher occupancy.

- Some groups have small sample sizes. For example, only 33 listings had view or water access, so that result may be sensitive to a small number of high-performing listings.

- The dataset does not include complete pricing or revenue data, so the project focuses on occupancy and demand rather than profitability.

- The amenities were grouped manually into broader categories. This made the analysis more interpretable, but some amenity classifications may be imperfect.

- The geographic analysis uses latitude and longitude points, but without official ward boundary shapefiles, the ward labels and spatial patterns are approximate.

- Occupancy may also be affected by factors not fully captured in the dataset, such as photos, description quality, cleaning fees, seasonal events, host communication, local regulations, and pricing strategy.

- Lastly, the dataset was missing revenue and pricing information, which would have been key in pinpointing the variables which have the biggest impact on profitability and would lead to a more robust recommendations for hosts and investors.