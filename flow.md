# Flow

* create an external website in creator:

1)

![Example](../images/create-external-1.png)

2)

![Example](../images/create-external-2.png)

* create a provider in creator (and pixel)
* get pixel and send it to the advertiser

![Example](../images/create-provider-pixel.png)

* create a pixel(s) in the network side (e.g traficjunky)

* integrate network pixel in creator

![Example](../images/integrate-network-pixel-in-creator.png)


* use redirect link api in the network side to redirect to the advertiser landing page

Example:
`https://cd4dtmohdk.execute-api.eu-west-2.amazonaws.com/dev/redirect?utm_source=trafficjunky&aclid={ACLID}&utm_campaign=vipOffer.com&target=http%3A%2F%2Finstasxt.securesaferoute.com%2F%3Fin%3Dinstsxt1a%3Abest%26x_source%3Dvip63885%3A--`


* utm_source(required) - from supported [external networks](supported-external-networks.md)

* aclid(requird) - network click id
* utm_campaign(required): the domain of the campaign external website
* target(required) : url encoded string of the landing page url