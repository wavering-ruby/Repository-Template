# Pull Request - How to read

You can use the comments below to sinalize any important message in the documentation, as a possible failure, organization rules / mandatory requisites or, but no excluded by, notes and technical observations.

> [!WARNING]
> Use Warning to any technical possible failure in the code that if not meets some requisites, the product will crash and broke. 

> [!IMPORTANT]
> Use Important to any organization rules or mandatory requisites.

> [!NOTE]
> Any note or technical observation that you want to the dev and products manager needs to see about anything in the code.

# Title [Fix: Order Shippment Bug + New Orders Screen]

## Context

A bug in the screen of CreationOrder was reported by the test team, in the development01 ambient, where a error appears in the console and not a single order appear in the frontend.

And the New Order Screen is a requisite in the document.

## Details

This Pull Request will solve the problems in production based on the report of the bug in the order shippment in the database. Also, will be implement a new screen in the frontend where Axios use the endpoint `order/`, in this page the user will be able to see all the orders grouped by the datecreate that is returned by the timestamp.

> [!WARNING]
> As the bug root cause, do not change the ENDPOINT name without contacting the PM or the frontend architech.

> [!IMPORTANT]
> In that case, the orders only will be seem by the creator, the admin can see everything in that case, but the user with the "creator" profile only can see the created by him. 

## Misc

<details>
    <summary>Closing Issues</summary>

This Pull Request will close these/this issue(s):

Close #1

Close #2

...

Close #N

</details>
