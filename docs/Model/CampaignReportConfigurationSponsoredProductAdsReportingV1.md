# CampaignReportConfigurationSponsoredProductAdsReportingV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**columns** | [**\kruegge82\otto\Model\CampaignReportAvailableColumnsSponsoredProductAdsReportingV1[]**](CampaignReportAvailableColumnsSponsoredProductAdsReportingV1.md) | List of columns to include in the report. TOTAL_COSTS and TOTAL_SALES are reported in euro cents (EUR cents). |
**group_by** | [**\kruegge82\otto\Model\CampaignReportGroupByColumnsSponsoredProductAdsReportingV1[]**](CampaignReportGroupByColumnsSponsoredProductAdsReportingV1.md) | List of groupBy columns for the kpis in the report. Dimension columns in &#39;columns&#39; are auto-added to GROUP BY. Columns in &#39;groupBy&#39; are auto-added to SELECT. If not specified, defaults to grouping by CAMPAIGN_ID for campaign reports. | [optional]
**filters** | [**\kruegge82\otto\Model\ReportFilterSponsoredProductAdsReportingV1[]**](ReportFilterSponsoredProductAdsReportingV1.md) | List of filters to apply to the report data. | [optional]
**format** | [**\kruegge82\otto\Model\ReportFormatSponsoredProductAdsReportingV1**](ReportFormatSponsoredProductAdsReportingV1.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
