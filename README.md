// All telemetry for Operation ID: d3c2ceedb9652c345915a06373603448
union *
// Apply filters
| where timestamp > datetime("2022-02-21T14:00:55.632Z") and timestamp < datetime("2022-02-23T14:00:55.632Z")
| where operation_Id == "d3c2ceedb9652c345915a06373603448"
