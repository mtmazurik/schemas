# schemas
JSON Schema Definitions (JSD)

Schemas in this repository are JSON Schema definitions (JSDs), used to publish (publicly) on our website at www.cloudcomputingassociates.com/schemas.    JSDs are used to validate JSON while in any code in a stack, from UI, to service, to Data Access Layer code logic.    If you care about the format and structure you used JSDs to play the data against, else the data may be corrupt, invalid, or unintelligible at some time in the future.   This is part of the architectural strategy of simply using JSON transport packets, in any aspect of a Microservice build out where any cooperating services can rely on JSDs to both understand the JSON object, and validate it.
