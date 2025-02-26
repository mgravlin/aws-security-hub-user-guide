# Viewing finding lists and details in AWS Security Hub<a name="securityhub-findings-viewing"></a>

In the AWS Security Hub navigation pane, **Controls** displays a consolidated list of controls that are available in Security Hub\. See [Viewing and managing security controls](controls-view-manage.md)\.

From **Security standards**, you can navigate to a specific standard and display a list of findings for controls that are currently associated with the standard\. See [Viewing and managing security standards](standards-view-manage.md)\.

From **Insights**, you can display a list of findings for a matching insight result\. See [Viewing and taking action on insight results and findings](securityhub-insights-view-take-action.md)\.

From **Findings**, you can displays a list of findings from enabled product integrations and controls that are associated with one or more standards\.

From **Integrations**, you can display a list of findings generated by an another AWS service or a third\-party integration\. See [Viewing the findings from an integration](securityhub-integrations-managing.md#securityhub-integration-view-findings)\.

You can also use the [https://docs.aws.amazon.com/securityhub/1.0/APIReference/API_GetFindings.html](https://docs.aws.amazon.com/securityhub/1.0/APIReference/API_GetFindings.html) API operation to retrieve a filtered list of findings\.

If you enable cross\-Region aggregation, you can view control statuses, security scores, insights, and findings from across Regions\. In the aggregation Region, the **Controls**, **Security standards**, **Findings**, and **Insights** pages contain data from the aggregation Region and the linked Regions\. In other Regions, these pages only contain findings from that Region\. For information on how to configure cross\-Region aggregation, see [Cross\-Region aggregation](finding-aggregation.md)\.

**Topics**
+ [Filtering and grouping findings \(console\)](findings-filtering-grouping.md)
+ [Viewing finding details](finding-view-details.md)