qubit.opentag.LibraryTag.define("intentmedia.scahotel.v1.Tag", {
    config: {
        name: "Intent Media - Hotel Search Compare Ads",
        description: "To be placed on any page in the hotel path",
        html: "",
        url: "a.cdn.intentmedia.net/javascripts/v1/intent_media_core.js",
        async: true,
        parameters: [{
            name: "Intent Media Site Name",
            description: "Unique site id provided by Intent Media",
            token: "site_name",
            uv: ""
        }, {
            name: "Intent Media Page ID",
            description: "Unique page id provided by Intent Media",
            token: "page_id",
            uv: ""
        }, {
            name: "Site country",
            description: "2 letter ISO country code of the website version that was loaded",
            token: "site_country",
            uv: ""
        }, {
            name: "Site language",
            description: "2 letter ISO code for the language the website page is rendered in",
            token: "site_language",
            uv: ""
        }, {
            name: "Site currency",
            description: "3 letter ISO currency code for the transaction",
            token: "site_currency",
            uv: ""
        }, {
            name: "Dispay format type",
            description: "Device-specific version of the website that was loaded - DESKTOP or MOBILE",
            token: "display_format_type",
            uv: ""
        }, {
            name: "User member id",
            description: "Unique registered user id to identify logged-in users", 
            token: "user_member_id",
            uv: ""
        }, {
            name: "Visitor id",
            description: "Unique user id persistent at least across the entire booking transaction session",
            token: "visitor id",
            uv: ""
        }, {
            name: "Referrer source",
            description: "Specific site where the user came from - Google/Bing, etc.",
            token: "referrer_source",
            uv: ""
        }, {
            name: "Referrer channel",
            description: "Which marketing channel acquired the user - (SEM/SEO/Meta, etc.)",
            token: "referrer_channel",
            uv: ""
        }, {
            name: "Active member profile",
            description: "Member profile contains data beyond initial account creation default (i.e. loyalty points, preferred airline, written reviews, etc.)",
            token: "active member profile",
            uv: ""
        }, {
            name: "Travel start date",
            description: "Required format YYYYMMDD",
            token: "travel_date_start",
            uv: ""
        }, {
            name: "Travel end date",
            description: "Required format YYYYMMDD", 
            token: "travel_date_end",
            uv: ""
        }, {
            name: "Travelers",
            description: "Total number of travelers (adults+children+seniors)",
            token: "travelers",
            uv: ""
        }, {
            name: "Adults",
            description: "Number of adult travelers", 
            token: "adults",
            uv: ""
        }, {
            name: "Children",
            description: "Number of children travelers",
            token: "children",
            uv: ""
        }, {
            name: "Seniors",
            description: "Number of senior travelers",
            token: "seniors",
            uv: ""
        }, {
            name: "Number of opaque listings",
            description: "Number of opaque listings in search results - list page only, set to 0 if all are retail",
            token: "number_of_opaque_listings",
            uv: ""
        }, {
            name: "Hotel city",
            description: "City of searched, selected or booked hotel property (in English language)", 
            token: "hotel_city",
            uv: ""
        }, {
            name: "Hotel country",
            description: "2 letter ISO country code of searched, selected or booked hotel property",
            token: "hotel_country",
            uv: ""
        }, {
            name: "Hotel state",
            description: "2 letter ISO state code of searched, selected or booked hotel property - US & Canada only",
            token: "hotel_state",
            uv: ""
        }, {
            name: "Hotel rooms",
            description: "Number of hotel rooms booked",
            token: "hotel_rooms",
            uv: ""
        }, {
            name: "Total conversion value",
            description: "Confirmation page only. Total conversion value of the hotel, car, flight or package booking - no currency symbol, 2 decimal places", 
            token: "total_conversion_value",
            uv: ""
        }, {
            name: "Order id",
            description: "Confirmation page only. Order ID of the booking",
            token: "order_id",
            uv: ""
        }, {
            name: "Product category",
            description: "Only needed if conversion tag is deployed on a confirmation page shared across multiple products/paths - HOTEL/FLIGHT/CAR/PACKAGE",
            token: "product_category",
            uv: ""
        }, {
            name: "Conversion type",
            description: "Type of hotel product that was purchased (if applicable) - OPAQUE/RETAIL",
            token: "conversion_type",
            uv: ""
        }, {
            name: "Promotional code",
            description: "Was there a promotion code applied? Y/N",
            token: "promo_code",
            uv: ""
        }, {
            name: "Hotel brand code",
            description: "Chain code for hotel brand in user's search, or of selected/booked property", 
            token: "hotel_brand_code",
            uv: ""
        }]
    },

    script: function () {

    },

    pre: function () {
        window.IntentMediaProperties = {
            site_name: '' + this.valueForToken("site_name"), 
            page_id: '' + this.valueForToken("page_id"), 
            site_country: '' + this.valueForToken("site_country"), 
            site_language: '' + this.valueForToken("site_language"), 
            site_currency: '' + this.valueForToken("site_currency"), 
            display_format_type: '' + this.valueForToken("display_format_type"), 

            user_member_id: '' + this.valueForToken("user_member_id"), 
            visitor_id: '' + this.valueForToken("visitor_id"), 
            referrer_source: '' + this.valueForToken("referrer_source"), 
            referrer_channel: '' + this.valueForToken("referrer_channel"), 
            active_member_profile: '' + this.valueForToken("active_member_profile"), 
            
            travel_date_start: '' + this.valueForToken("travel_date_start"), 
            travel_date_end: '' + this.valueForToken("travel_date_end"), 
            travelers: '' + this.valueForToken("travelers"), 
            adults: '' + this.valueForToken("adults"), 
            children: '' + this.valueForToken("children"), 
            seniors: '' + this.valueForToken("seniors"), 
            number_of_opaque_listings: '' + this.valueForToken("number_of_opaque_listings"), 

            hotel_city: '' + this.valueForToken("hotel_city"), 
            hotel_country: '' + this.valueForToken("hotel_country"), 
            hotel_state: '' + this.valueForToken("hotel_state"), 
            hotel_rooms: '' + this.valueForToken("hotel_rooms"), 

            total_conversion_value: '' + this.valueForToken("total_conversion_value"), 
            order_id: '' + this.valueForToken("order_id"), 
            product_category: '' + this.valueForToken("product_category"), 
            conversion_type: '' + this.valueForToken("conversion_type"), 
            promo_code: '' + this.valueForToken("promo_code"), 
            hotel_brand_code: '' + this.valueForToken("hotel_brand_code") 
        };
    },

    post: function() {

    }
});
