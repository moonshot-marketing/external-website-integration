# Supported External Networks


| Network Name       |     utm_source       | click id macro                                                                                                                         | Notes
|--------------------|----------------------|----------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| Traffic Junky      |     trafficjunky     | [{ACLID}](https://www.trafficjunky.com/blog/2016/09/22/using-url-tokens/)                                                              |
| EPOM               |                      |                                                                                                                                        | use this string in the url: `-EPOM`
| Outbrain           |      outbrain        | [{{ob_click_id}}](https://www.outbrain.com/help/advertisers/server-app-integrations/#postback)                                         |
| Taboola            |      taboola         | [{click_id}](https://help.taboola.com/hc/en-us/articles/115006850567-How-to-Track-Conversions-Using-Server-to-Server-Integration-S2S-) |


# External Source Id


| Network Name       |                                         |  Example                                |
|--------------------|-----------------------------------------|-----------------------------------------|
| Traffic Junky      |        {{member_id}}&#124;{{a}}         |  1000989181|1000160561                  |
| EPOM               |                  pixel id               |  b079fe295df09f1b25ccd091498e57c8-20-0  |
| Outbrain           |                 event name              |            saleoutbrain                 |
| Taboola            |                 event name              |            examplename                  |
| BING               |                 pixel id                |            B011RPQW                     |
| Google             |                 pixel id                |            927-311-8892                 |

