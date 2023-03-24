# excel-challenge_Crowdfunding

#### Review all data and see which data availability to use for data Analysts:
* Using `Outcome` column to find out Success, Failed, Live and Canceled in the campaigns. I’m using soft & Filter function and use different colour fill in the cell.
* Create `Percent Funded` to made relative to its initial funding goal. The formula is using pledged column / goal column.
* Create `Average Donation` to find how much each project backer paid on average. The formula is using pledged column / backers_count column.
* `Separate category & sub-category` to 2 different columns. It can help to find detail information about which event is good for campaign to get funding. 
* Convert `Unix` timestamps in `launched_at and deadline column` to Date Created Conversion and Date Ended Conversion column for the normal date. I’m using {insert function} “=(((L2/60)/60)/24)+DATE(1970,1,1)” to converted.

#### Analysis:

* Using PivotTable field in name/outcome/country/Parent Category analyzes which Parent Category Success, Failed, Live and Canceled data. Using 2D Column chart to support my result. 
![1](https://user-images.githubusercontent.com/119981450/227587473-5d2430bf-287b-47d2-a550-c01fb3ff4e15.png)
 
* Using PivotTable field in name/outcome/country/Parent Category/sub-category analyzes which Sub-Category Success, Failed, Live and Canceled data. Using 2D Column chart to support my result.
![2](https://user-images.githubusercontent.com/119981450/227587598-0615743a-cb79-49cd-b4ae-418c6130772d.png)

* Using PivotTable field in Date Created Conversion/outcome/Years/Parent Category analyzes which Month is going Success, Failed, Live and Canceled data. Using stacked line chart to support my result.
![3](https://user-images.githubusercontent.com/119981450/227587711-46ce01d9-f127-484d-ae37-39d456c9eaeb.png)

#### Statistical Analysis:
Use campaign backers evaluate the number of backers successful and unsuccessful in campaigns. I’m using data/DataAnalysis/Descriptive Statistics.
![4](https://user-images.githubusercontent.com/119981450/227587907-94f8b2ad-6288-4882-9ddf-e43b8b94ed67.png)


