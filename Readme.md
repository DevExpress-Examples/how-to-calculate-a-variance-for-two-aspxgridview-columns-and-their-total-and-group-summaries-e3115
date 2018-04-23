# How to calculate a variance for two ASPxGridView columns and their total and group summaries


<p>The example illustrates how to calculate a variance for two ASPxGridView columns and their total and group summaries. Values of the unbound “Variance” column are calculated in the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridViewASPxGridView_CustomUnboundColumnDatatopic"><u>CustomUnboundColumnData</u></a> event handler. Summary custom calculation rules are applied in the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridBase_CustomSummaryCalculatetopic">CustomSummaryCalculate</a>  event handler. The <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebASPxGridBase_CustomSummaryCalculatetopic">CustomSummaryCalculate</a>  event fires for each row involved in summary calculation. When calculating the total summary value, the event is raised for each data row. Additionally, the event is raised before and after processing rows. Values used in the calculation are stored in variables, that are defined outside the handler. The processing rows finalization is used to assign the result to the total summary value via the event's <a href="http://documentation.devexpress.com/#CoreLibraries/DevExpressDataCustomSummaryEventArgs_TotalValuetopic"><u>e.TotalValue</u></a> property.</p>
<p><strong>See Also:</strong><strong><br> </strong><a href="http://documentation.devexpress.com/#AspNet/CustomDocument3762"><u>Custom Aggregate Functions</u></a></p>

<br/>


