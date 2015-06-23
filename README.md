# Fake Facebook API for local development

    FB = {
        api: function(url, cb) {
            var response = {
                error: 1
            };
            console.log('Fake FB.api response', response);
            cb(response);
        },
        ui: function(request, cb) {
            var response = {
                error_code: 1
            };
            console.log('Fake FB.ui response', response);
            cb(response);
        }
    }
