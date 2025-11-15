# Training Answers

## 1. the warehouse that causes revenue drops
- **Warehouse:** Warehouse 3 (`w_warehouse_sk` = 3)
- **Most impacted category:** Electronics
- **Revenue impact:** -$17,958.17
- **Notes:** Store 5 relies on Warehouse 3 for Q4 electronics replenishment. Warehouse 3’s inventory for the overlapping SKUs collapsed between the October and November 2022 inventory snapshots (and triggered a cluster of `out_of_stock` tickets), which corresponded to a ~$17.9K gap in Store 5’s November electronics revenue.

## 2. the state that has return spikes
- **State with spike:** CA
- **Category:** Jewelry (largest January 2023 return bucket)
- **Return volume/value:** 2,500 items totaling $691,182.47
- **December baseline:** Company-wide December 2022 Jewelry revenue across store, web, and catalog channels summed to $5,200,865.89, so the January spike means **13.29%** of that revenue must be discounted ($691,182.47 ÷ $5,200,865.89).

## 3. the item that loses revenue
- **Item:** Brand #433 Sports 1 (`item_sk` = 2)
- **Issue:** The BF2022-ELEC promo code was mistakenly enabled on this sports SKU for several weeks, so shoppers received aggressive “electronics” discounts on the wrong item.
- **Lost revenue:** $45,770.69 in under-collected sales.

## 4. the product that sells most
- **Answer:** Brand #887 Jewelry 887 sold 661 units in 2019, the highest quantity for any product that year.

## 5. the profit that increases year over year
- **Answer:** Net profit increased by $7,934,200.86 from 2021 ($53.54M) to 2022 ($61.47M).

## 6. the category that sells most
- **Answer:** Shoes led 2023 with 38,840 units sold across channels.

## 7. the year that needs validation
- **Answer:** 2021 delivered the lowest net profit, so that’s the year requiring re-validation.

## 8. the store that has highest profit in 2022
- **Answer:** Store 3 generated the top 2022 net profit at roughly $11.31M.

## 9. the city that sells most items in 2022
- **Answer:** Homestead (Store 3’s city) sold 133,797 items in 2022, the highest of any city.

## 10. the product that sells most in 2022 holidays
- **Answer:** Brand #912 Home 433 (`item_sk` = 3434) was the best-selling product during the 2022 holiday period.
