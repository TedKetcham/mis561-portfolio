# mis561-portfolio
Portfolio for projects in MIS 561 - Data Visualization. This will include the completion of assignments in Excel, Tableau, PowerBI through Datacamp, and various (usually Gemini) AI tools.

Intital E Commerece Profitability Analysis, Develop a basic set of dashboards and explain your design (https://public.tableau.com/app/profile/ted.ketcham/viz/AdvancinginExcelandTableau-Pt_1_17896280066860/ExploratoryDashboard) Not gonna lie, cut it real close with this submission, if I was transported a week back I could of done this way better and less stressful.

Account Profitability and Service Tiers Analysis, developed a basic of dashboards to show how discount tiers were affecting overall profit. (https://public.tableau.com/views/AccountProfitabilityandServiceTiers/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) I think this one is a general upgrade from the one before, looks a fair bit nicer.

MIS 561, 9/28/2026 https://public.tableau.com/views/PowerBITrainingCertifications_17906616560850/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

MIS 561, 10/6/2026 https://public.tableau.com/views/PowerBITrainingCertifications_17906616560850/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
In Flex 4, I calculated Line Price by hand for each individual sales line by dividing Revenue by (1 - Discount %). I would build this in Power BI as a calculated column because the calculation relies on fixed, row-level attributes on a single transaction row and needs to be evaluated independently for every item before any aggregation occurs. If Line Price lives in the Power BI model as a calculated column instead of remaining buried inside my Excel workbook, Marcus and Anita can immediately filter or group sales performance by transaction-level price tiers without waiting for manual workbook updates, giving him a self-service report that refreshes automatically whenever the central dataset updates.

MIS 561, 10/12/2026 https://public.tableau.com/views/PowerBITrainingCertifications_17906616560850/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
Power BI has some advantages compared to Tableau with ease of use for slicers, which are vastly easier to set up and use out of the gate. There is also no equivalent that I know of to the drill-down treemap, which offers a dynamic multi-level exploration. By moving from static workbooks to this interactive model, Marcus and Anita no longer need to rely on manual updates or requests to me. Instead, they get an auto-refreshing, self-service dashboard that lets them slice performance live in meetings.
