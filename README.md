<h1>Preprocessing</h1>
- Drop useless columns like host_id, host_name, id, name and columns that contains large missing values like last_review and reviews_per_month.
- KMeans is a clustering algorithm, so qualitative columns will be transformed to quatitative values using one-hot-encoding method with neighbourhood_group, neighbourhood, room_type
<h1>KMeans</h1>
- Using Heatmap to find out correlations attributes.
<img src="https://asset.cloudinary.com/dxhsadna0/de82e65a4ac3c4b731e4aaf32b0f58cf"/>
- Using 

<h1>Report</h1>
1. Statistical analysis of apartments by neighborhood groups with the most recent review in October 2018 (Roll up by district, evenly distributed by month).</br>
2. Statistical analysis of apartments with a minimum stay of 1 or 3 nights, rental price below $50, and located in the Stalen Island neighborhood. (Slice and dice).</br>
3. Statistical analysis of apartments with "Private Room" type in the Bronx neighborhoods. (Drill down).</br>
4. Statistical analysis of information about apartments owned by hosts named Aron or John, with an average monthly review count greater than 1. (Slice and dice).</br>
5. Statistical analysis of information about apartments with the last review count in each month of 2019, categorized by Queens neighborhoods. (Pivot).</br>
6. Statistical analysis of host names in Brooklyn by districts where they own more than 10 apartments. (Drill down with slicing).</br>
7. Statistical analysis of apartment information in Queens or Manhattan neighborhoods with a rental price of $100. (Slice and dice).</br>
8. Statistical analysis of the monthly review count for apartments owned by hosts named John in Queens neighborhoods, categorized by districts (Drill down by neighborhood). </br>
9. Statistical analysis of the number of apartments with a minimum stay of 3 or 4 nights, belonging to the "Shared Room" type, and having a monthly review count greater than 1. (Slice and dice).</br> 
10. Statistical analysis of apartments in the Manhattan area with a price of $50, a review count above 100, and availability for more than 200 days in a year.</br>
11. Statistical analysis of the top 5 highest-priced apartments in the "Astoria" district of Queens.</br>
12. Statistical analysis of hosts in Midtown, Manhattan area, who own more than 5 apartments.</br>
