---
layout: bidder
title: FutureAds
description: Prebid FutureAds Bidder Adaptor
pbjs: true
pbs: true
biddercode: futureads
aliasCode: admixer
media_types: banner, video, native
gdpr_supported: true
usp_supported: true
schain_supported: true
gvl_id: 511
userIds: AdmixerID
prebid_member: true
sidebarType: 1
---

### Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description                                                                                                    | Example                                | Type     |
|---------------|----------|----------------------------------------------------------------------------------------------------------------|----------------------------------------|----------|
| `zone`        | required | The unique identifier of the ad placement. Could be obtained from the FutureAds UI or from your account manager. | "e5ff8e48-4bd0-4a2c-9236-55530ab8981d" | `string` |
| `kvTargeting` | optional | Key/Value - a pair of the unique values that will be used for the custom targeting option.                     | {key1: value2, key2: value2}           | `object` |
