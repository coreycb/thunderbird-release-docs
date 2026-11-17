# Built-in and System Add-On Release Process

1. Land the new version as a built-in add-on to Thunderbird `main`

2. Release the new version as a system add-on to daily

3. Beta:
   1. Release the new version as a system add-on to beta
   2. Uplift the built-in add-on to Thunderbird beta **only** to resolve
      high-impact issues (fallback for users who don't have access to the system
      add-on)

4. Await go/no-go criteria from beta testing

5. Release/ESR:
   1. Release the new version as a system add-on to release/esr
   2. Uplift the built-in add-on to Thunderbird release/esr **only** to resolve
      high-impact issues (fallback for users who don't have access to the system
      add-on)
