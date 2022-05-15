# gtm-server-tag-ga4-to-piano-analytics
This tag for Google Tag Manager server-side sends GA4 events to Piano Analytics. 
It is designed to work in combination with any GA4 event and the native GA4 client in GTMSS.

1) Client-side: GA4 event tag
2) Server-side: Native GA4 client
3) Server-side: Trigger based on native GA4 client from 2 (condition *Client Name = Google Analytics GA4*)
4) Server-side: GA4 to PA tag based on trigger from 3

Note that this tag is still a beta version. Feedback and suggestions are very much appreciated.
