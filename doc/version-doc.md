FORMAT: X-1A

# Middle-End
Welcome to the our Jobs API documentation.

# Group Admin

The following is a section of resources related to the job offers

## Version [/admin/version]
Get informations about the middle-end

### Get middle-end version [GET]

+ Response 200 (application/json)

    + Body

            {
                "type": "MOBILE APPLICATION VERSION",
                "updated_time": "2013-09-26T18:05:09+02:00",
                "data": {
                    "version": "Viadeo MiddleEnd v0.0.1"
                }
            }
