# EPA-PURCHASE-TAG
EPA-PURCHASE-TAG is a tag template for personalized purchases on websites

# OBJETIVES:

- Design a template using a script that searches a term on purchase event based on the items name, categories and brand and design a template that generates a new dataLayer push based on Google Analytics 4 dataLayer structure with all the matching items updating the final ticket price


# REACH:

- Provide trademarks exclusive information for their products ignoring any other trademarks or brands products in order to get a private analytics property


# USAGE:

![image](https://user-images.githubusercontent.com/99297157/204931580-8a71b0b9-08f7-4fb6-ab53-7f1869a0adeb.png)

Tag template consist in 3 fields:

1. A dataLayer variable where tag going to search for value, transaction_id, affiliation, currency, items array, etc., tipycally a dataLayer with "ecommmerce" value is enough

2. An event variable that must be the predefined by Google Tag Manager

3. A Field where you can type the term to be searched on items params


> note: We highly recommed 2 triggers:
> 
> 1. PageView: the one used to any other tag, since we probably want to send those info to another property, is useful to measure pageviews to prevent engagement, campaign or sessions losses
> 
> 2. purchase event: the purchase event must contain the [recommended GA4 structure](https://developers.google.cn/tag-manager/ecommerce-ga4?hl=es#measure_purchases) to get readen by the template


# [LICENSE](https://github.com/epa-datos/epa-purchase-tag/blob/main/LICENSE):

   Copyright 2022 EPA Digital

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

