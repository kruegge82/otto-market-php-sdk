# KeywordReportConfigurationSponsoredProductAdsReportingV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**columns** | [**\kruegge82\otto\Model\KeywordReportAvailableColumnsSponsoredProductAdsReportingV1[]**](KeywordReportAvailableColumnsSponsoredProductAdsReportingV1.md) | List of columns to include in the report. TOTAL_COSTS and TOTAL_SALES are reported in euro cents (EUR cents). |
**group_by** | [**\kruegge82\otto\Model\KeywordReportGroupByColumnsSponsoredProductAdsReportingV1[]**](KeywordReportGroupByColumnsSponsoredProductAdsReportingV1.md) | List of groupBy columns for the kpis in the report. Dimension columns in &#39;columns&#39; are auto-added to GROUP BY. Columns in &#39;groupBy&#39; are auto-added to SELECT. If not specified, KEYWORD is applied and all KPIs are aggregated at this level. | [optional]
**filters** | [**\kruegge82\otto\Model\KeywordReportFilterSponsoredProductAdsReportingV1[]**](KeywordReportFilterSponsoredProductAdsReportingV1.md) | List of filters to apply to the report data. | [optional]
**format** | [**\kruegge82\otto\Model\ReportFormatSponsoredProductAdsReportingV1**](ReportFormatSponsoredProductAdsReportingV1.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
