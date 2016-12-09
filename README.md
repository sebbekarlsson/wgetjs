# wget.js
> Probably the most lightweight / simple Javscript GET request library.

## why?
> It does one thing and it does it well.

## Usage:

        //wget(<endpoint>, <callback_function>)

        wget("/api/getusers", function(data) {
            console.log(data);
        });

